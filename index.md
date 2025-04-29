# Katelin Huynh's CPSC 120 Portfolio

### About me: 
I am a Computer Engineering student at California State University, Fullerton, and expect to graduate in Spring of 2028.

## Favorite CPSC 120 Labs ##
### Patterns With Loops
* #### [Lab 08, Part 2:](https://github.com/cpsc-spring-2025/cpsc-120-lab-08-katelin_isaiah/tree/main/part-2)
I really enjoyed coding this lab! It used loops to create a knitting pattern up to a total of 22 lines. On each line, there’ll always be a total of 22 bar ( | ) and dash ( - ) characters with an asterisk ( * ) between the dash and bar characters, and then create a new line afterward to continue the pattern as the line number increases. Overall, I found this lab not that difficult, but it was fun and visually appealing to do!

> Lab Output
```
$ ./pattern 
*||||||||||||||||||||||
-*|||||||||||||||||||||
--*||||||||||||||||||||
---*|||||||||||||||||||
----*||||||||||||||||||
-----*|||||||||||||||||
------*||||||||||||||||
-------*|||||||||||||||
--------*||||||||||||||
---------*|||||||||||||
----------*||||||||||||
-----------*|||||||||||
------------*||||||||||
-------------*|||||||||
--------------*||||||||
---------------*|||||||
----------------*||||||
-----------------*|||||
------------------*||||
-------------------*|||
--------------------*||
---------------------*|
```

### Object-Oriented Hi-Lo Game
* #### [Lab 11, Part 2:](https://github.com/cpsc-spring-2025/cpsc-120-lab-11-ethan_kate/tree/main/part-2)
This lab was the more advanced version of lab 04, part 2 HiLo game. The difference was that in lab 04 we gave the guesser two tries to get the secret number, while in lab 11, we allowed the guesser to have 4 attempts to get the secret number. We used bool functions that used if statements to determine if the guess of either correct, too big, or too small. I enjoyed creating this lab as it was a step up from lab 04, it was challenging, but it felt rewarding to see the result of the game.

> Lab Output(s)

*When finding out the secret number:*
```
$ ./hilo 5
You have 4 guesses left.
Enter a guess 1-10: 8
Too big!
You have 3 guesses left.
Enter a guess 1-10: 2
Too small!
You have 2 guesses left.
Enter a guess 1-10: 5
You won!
```

*When unsuccessfully finding the secret number:*
```
$ ./hilo 9
You have 4 guesses left.
Enter a guess 1-10: 1
Too small!
You have 3 guesses left.
Enter a guess 1-10: 2
Too small!
You have 2 guesses left.
Enter a guess 1-10: 3
Too small!
You have 1 guesses left.
Enter a guess 1-10: 4
Too small!
You lost!
```

*When given a random secret number and finding the secret number:*
```
$ ./hilo
You have 4 guesses left.
Enter a guess 1-10: 5
Too big!
You have 3 guesses left.
Enter a guess 1-10: 3
Too big!
You have 2 guesses left.
Enter a guess 1-10: 2
Too big!
You have 1 guesses left.
Enter a guess 1-10: 1
You won!
```


### Animated Gradient & Making Messages
* #### [Lab 12:](https://github.com/cpsc-spring-2025/cpsc-120-lab-12-kate_cody/tree/main)
This lab was my favorite lab **OVERALL**, it utilized RBG and RNG along with creating images with a .gif format. It was challenging at first but was rewarding to see the end result. I was able to learn how to use rng to randomly change the intensity of red, green, and blue, to create that static effect in the .gif. Learning to adjust the message’s font, size, color and placement was super useful for anyone who’s into digital media!


> Animated Gradient GIF:

![alt text](https://github.com/cpsc-spring-2025/cpsc-120-lab-12-kate_cody/blob/main/part-1/sample_images/sample_image.gif "Animated Gradient")

> Making Messages GIF:

![alt text](https://github.com/cpsc-spring-2025/cpsc-120-lab-12-kate_cody/blob/main/part-2/sample_images/sample_image.gif "Making Messages")
