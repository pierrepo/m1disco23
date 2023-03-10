
# Hello
## is it *me* you're looking for?
:heartpulse: :heartpulse: :heartpulse:

```
{
  "firstName": "Lelia",
  "lastName": "Erscoi",
  "age": 23
}
```



`print("Hello,world!")`

| Language | Level        | "Hello, world!"      |
|----------|--------------|----------------------|
| Romanian | Native       | "Buna, lume!"        |
| English  | Bilingual    | "Hello, world!"      |
| French   | Intermediate | "Bonjour, le monde!" |
| Japanese | Intermediate | "こんにちは世界!"    |
| Dutch    | Beginner     | "Hallo, Wereld"      |

I really like  **good coffee**.

<ul> Date Ideas-
    <li>Beach picnics. </li>
    <li>Volleyball in the parc. </li>
    <li>Drunk geocaching. </li>
</ul>    

### _I have a tattoo of Bayes Formula_
$P(A|B)= \frac{P(B|A) \dot P(A)}{P(B)}$


### ~~I think sparkles are very pretty~~
![Alt Text](https://media.giphy.com/media/ySvZaRKnzCdvG/giphy.gif)


_My favorite game is Mass Effect._

Click [here](https://www.youtube.com/watch?v=rh8ayPFB-3E).


``` python 
class Singer:
    def __init__(self, name):
        self.name = name
        
    def sing_verse(self, verse_num):
        if verse_num == 1:
            lyrics = "We're no strangers to love\nYou know the rules and so do I\nA full commitment's what I'm thinking of\nYou wouldn't get this from any other guy"
        elif verse_num == 2:
            lyrics = "We've known each other for so long\nYour heart's been aching but you're too shy to say it\nInside we both know what's been going on\nWe know the game and we're gonna play it"
        else:
            raise ValueError("Invalid verse number")
        print(f"{self.name}: {lyrics}")
        
    def sing_chorus(self):
        lyrics = "Never gonna give you up\nNever gonna let you down\nNever gonna run around and desert you\nNever gonna make you cry\nNever gonna say goodbye\nNever gonna tell a lie and hurt you"
        print(f"{self.name}: {lyrics}")
        
    def sing_bridge(self):
        lyrics = "And if you ask me how I'm feeling\nDon't tell me you're too blind to see"
        print(f"{self.name}: {lyrics}")



# Create two singers
singer1 = Singer("Rick Astley")
singer2 = Singer("Lelia")

# Sing the song
singer1.sing_verse(1)
singer2.sing_chorus()
singer1.sing_verse(2)
singer2.sing_chorus()
singer1.sing_bridge()
singer2.sing_chorus()
```
## I'm the lovely delegate of the class
