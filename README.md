# WEB102 Prework - *The Kraken of the Trench*

Submitted by: **Christine Grimadeau**

**The Kraken of the Trench** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **20** hours spent in total

## Required Features

The following **required** functionality is completed:

* [✅] The introduction section explains the background of the company and how many games remain unfunded.
* [✅] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [✅] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [✅] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented features:
<img width="1425" height="669" alt="SeaMonster" src="https://github.com/user-attachments/assets/4dc183a5-1fc1-436a-acb9-aa3f8e8c2e67" />


GIF created with LICEcap and converted from EZgif 
<br>
(using it on mac converts it into frames only so I had to also use EZgif)


## Notes

One challange that I encountered was using the template literalls correcly. In several places in my code, I would often accidentely use the single quotes instead of the backticks which would cause the JavaScript expressions such as ${variable} to render as plain text on the page rather than evaluating to their actual values. It would affect the stats cards, the description string, and the top funded game displays. Debugging that required a lot careful reviewing of each line where the literalls were used. 

Another challange I faced was definetely understanding how reduce() worked. Building up an accumulator to sum values across an array was a new concept, and it took some practice to get the arrow function syntax right. I also ran into a Git issue where my local branch was behind the remote, causing a rejected push. I resolved this by running git pull origin main --rebase before pushing again.

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
