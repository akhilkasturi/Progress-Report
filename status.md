# Status Report

#### Your name

Akhil Kasturi

#### Your section leader's name

Xinwen (Ellen) Zhang

#### Project title

SMITE Competitive Toolkit

***

Short answers for the below questions suffice. If you want to alter your plan for your project (and obtain approval for the same), be sure to email your section leader directly!

#### What have you done for your project so far?

So far, I have created a few functions. One allows you to input the time that a buff is killed, and it will return the time that the buff will respawn, for every buff in the game. I have also created a 'damage calculator' which allows you to input various different variables, (power, penetration, protections, mitigations, ability level), and it will accurately return how much damage you will deal in game.

#### What have you not done for your project yet?

I have created a damage calculator for one character, and I aim to create one for another character.

#### What problems, if any, have you encountered?

When doing the buff respawn timer, I had some trouble with accurately returning the seconds part of the timer. A few errors occurred: times such as 1:50 or 1:05 would not display the zeros, which made the timer incorrect. I was able to fix this using % 60 and converting the seconds to a string, and then creating an if statement that would add a zero to the string either before or after the digit that was displayed alone.
