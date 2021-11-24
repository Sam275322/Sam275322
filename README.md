- 👋 Hi, I’m @Sam275322
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Sam275322/Sam275322 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
1
from random import randint
2
guesses = 0
3
randomNum = (randint(0,100))
4
numPlayer = 0
5
while (​numPlayer​!=​randomNum​):
6
    numPlayer = int(input("Guess the number(0-100)"))
7
    if (​numPlayer​>​randomNum​) : 
8	        print "It's -"  
9
    elif (​numPlayer​<​randomNum​) : print("It's +")
10
    guesses=guesses+1
11
