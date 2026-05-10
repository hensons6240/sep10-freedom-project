# Entry 6
##### 5/4
## Content
At this time, we've already started and "finished" our freedom project to some extent, having completed our MVP. I used what I already knew about html and css, to get all my existing content which we've already gotten earlier on in the year to prepare for this. I also used my tool, Bulma to help apply some components and color to my project including the grid system. Below is a preview of my project:<br>
<img width="1000" height="500" alt="image" src="https://github.com/user-attachments/assets/cbec5ab7-e607-4459-a025-e89e6bf3e009" />
MVP: The least I had to do in order to recieve a score of 100 on the project. (Ex. following the rubric properly).
## Challenges
Applying Bulma was most definetly the most difficult part when working on my project, although I have practiced and tinkered around with the many components I was going to use, actually applying them together, efficiently was no easy task, there was many problems especially within the code preventing me to just copy and paste.

1. Navbar. On paper, this seemed pretty simple, copy and paste the code, change the linking and text, voila, a working navbar. However, the way I came about implementing my navbar was very different, instead opting for a hero layout with a built in navbar meaning the code was significantly different from the normal one, additionally, I had no experience with Bulma's navbar, previosly only using the one in bootstrap which was a lot more managable. For the actual problem, I wanted for my navbar, when minimized or used on a smaller layout (ex. phone) to use a burger-button, meaning it went from:
<img width="273" height="73" alt="image" src="https://github.com/user-attachments/assets/ec5e6476-40c0-4141-9149-114e6441bacc" />

My big screen desktop, to a burger:
<img width="174" height="51" alt="image" src="https://github.com/user-attachments/assets/322de432-c19f-45d3-a19b-8424cae4fd23" />
The code that was given to me that I ended up copy and pasting, had the burger nonfunctionable and had me completly lost for some time, I tried searching through the internet and bulma's website to no avial ultimately leading me to using AI. The issue with the code was there wasn't an implemented ```data-target``` connecting the popup navbar and burger.
<img width="869" height="152" alt="image" src="https://github.com/user-attachments/assets/4801fc3e-c4e4-490f-9106-75ad9e48568e" />

Because the navbar had an id of: "navbarMenuHero" , the burger too neeeded to have their data-target to have the id so it knew what to actually open up. This ended up beiung a nuisance to fix because I have been relying on the bulma website for my problems.

2. Formatting. This most likely ended up being my fault but I was unsure how to use the grid system not because I didn't know how to use the bootstrap grid system but more that I didn't know I could (I actually ended up using nothing from bootstrap because of this). Bulma, like bootstrap is a CSS Framework meaning it shares a lot of similarities with bootstrap including that both having the grid-system. Bulma's grid system was not something I tinkered with and looked a lot more advanced then boostraps having multiple options:
<img width="224" height="135" alt="image" src="https://github.com/user-attachments/assets/0f39fb12-b47c-47d1-b1f5-2a5c9c6b5c5f" />
It took me awhile to figure out which one to use (I could've used any of them, some just needed more tinkering) but I was able to find the proper grid I wanted for both mobile and desktop. Looking back, I do believe using the bootstrap grid system, something I had actual experience with would've been a lot simplier to use then whatever bulma had.

## Engineering Design Progress
Finishing the MVP officially puts us on step .7, Test and evaluate the prototype, having to test our created prototype to see for improvement as needed also known as going beyong the MVP where we go beyong the minimum aiming to make our project better than it currently is despite it being usable.



[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
