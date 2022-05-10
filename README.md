# Mastermind Game
Clone the repository to access the game in your computer. Open your terminal and type the following:
<ul>
  <li> mkdir "FOLDER NAME" </li>
  <li> cd "FOLDER NAME"</li>
  <li> git clone https://github.com/jacyespinosa/mastermind.git</li>
  <li> cd mastermind</liv>
  <li> pip3 install flask</li>
  <li> pip3 install flask-sqlalchemy</li>
  <li> pip3 install requests</li>
  <li> python3 main.py</liv>
  <li> Open http://192.168.1.175:8080/ to view it in the browser.</li>
</ul>

# About Mastermind
This is a game where a player tries to guess the number combinations. At the end of each attempt to guess the 4 number combinations, the computer will provide feedback whether the player had guess a number correctly, or/and position correctly. A player must guess the right number combinations within 10 attempts to win the game.

# Tech Used
<li>Python</li>
<li>Flask</li>
<li>HTML/CSS</li>
<li>SqlAlchemy/Sqlite</li>

# Implementation
<ul>
  <li>
    Used Random generator API (https://www.random.org/clients/http/api/) to randomly select 4 numbers from 0 ~ 7 (Duplicate numbers are allowed)
  </li>
  <ul>
    <li>The generated numbers are the 4 number combination that the user will try to guess.</li>
  </ul>
</ul>


# Rules
<ul>
<li>
    Player must select a number <b><u>between 0-7</u></b>.
    <ul>
        <li>
            You have an option to change this to make it more challenging.
        </li>
        <p>
            <b>**Note that duplicate numbers could exist in the Mastermind's code.</b>
        </p>
    </ul>
</li>
<li>
    User must click 'CHECK' at the end of each attempt to guess
    the 4 number combinations, the computer will provide feedback whether the player had guess a number
    correctly, or/and position correctly.
    <ul style="margin-left: 40px;">
        <li>
           '1' -> Number is in the combination and in the CORRECT position.
        </li>
        <li>
           '2' -> Number is in the combination but in the WRONG position.
        </li>
        <p>
            <b>**Note that the computer’s feedback does <u>NOT</u> reveal which number the player guessed correctly.</b>
        </p>
    </ul>
</li>
<li>
    A player must guess the right number combinations within
    10 attempts to win the game.

</li>  
</ul>


# Extensions
<li>Users have the option to adjust the choices of numbers that are used</li>
  <ul>
    <li>
      Numbers between 0-7 (Default)
    </li>
    <li>
    Numbers between 0-10
    </li>
    <li>
    Numbers between 0-15
    </li>
  </ul>
<li>Score is displayed when the game has won.</li>
  <ul><li>The lower the score, the better. If a user scores 1, then that means it only took them ONE try to get the correct Mastermind code.</li></ul>
  
# Game Screenshots
![Screen Shot 2022-05-09 at 1 35 11 PM](https://user-images.githubusercontent.com/80412098/167493280-6ef10af5-2e65-4945-9bad-740014f0696e.png)

![Screen Shot 2022-05-09 at 1 29 27 PM](https://user-images.githubusercontent.com/80412098/167493063-b38c7d74-6499-44c0-8fd8-0f1ae2b04e74.png)
