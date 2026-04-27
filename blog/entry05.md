# Entry 5
##### 4/20/26
## Content
As we slowly approach making our Freedom Project, we continue to learn our tools (In my case [Bulma](https://bulma.io/documentation/start/overview/)) in order to give us an easier time making said project. As I continued to learn, I found out many different things about Bulma and learned many new ways to use it. Some of these includes, Panels, Hero Layouts and Tags which I used the website to learn because it came with information, a breadkdown as well as examples of what does what.
### [Tags](https://bulma.io/documentation/elements/tag/).
Tags are like a nametag, it allows you to write text within a premade box that is more noticable and appealing then normal text. I learned tags and most of the other parts of Bulma mainly thought the website. It gives us information about the different elements used as well as an example of what it looks like plus the code. A `tag` looks like:<br>
<img width="88" height="39" alt="image" src="https://github.com/user-attachments/assets/5387f95f-ecae-4515-b3f5-861290b4eedf" />
The code itself isn't that crazy mainly using a class div with the text you want inside. <br>
``` html
<div class="tag">
  <span class="tag">Hello</span>
</div>
```
You can change the tag around with other built in Bulma classes like size, hover and color. For instance, adding the class "are-large", "is-danger" and "is-hover would make the tag bigger, red and also hoverable. 
### [Panel](https://bulma.io/documentation/components/panel/)
Panels are very cool, they replace navbar in a sense as they are use to navigate around your website but looks very different from a navbar. An example of what a panel looks like:<br>
<img width="411" height="54" alt="image" src="https://github.com/user-attachments/assets/e12991b1-c87c-4fb4-b23c-834c8c6c34d1" />
The example above has very minimal components yet still looks complicated regardless. The code is similair to that of a table, having a main  element that initiates the process and many stuff inside that makes up the core. The code for it is:
``` html
    <nav class="panel">
      <p class='panel-heading'> Wow</p>
      <p class="panel-tabs">
        <a> Amazing</a>
      </p>
      <p class='panel-block'> Never</p>
    </nav>
```
To further explain the code, it has four main classes that it needs: "panel", "panel-heading", "panel-tabs" and "panel-blocks". Panel is used as the core structure of the code and is needed for everything else to work, the nav element the class is nested in is similair to a div where it acts as an container but is better suited for a panel while the div is more universal. Next, panel-heading is the text at the very top used to explain what the panel is about and what topic it would explain. Panel Tabs are where it differs from a navbar, it acts like a dropdown that opens up the actual links.
### [Hero Layouts](https://bulma.io/documentation/layout/hero/)
The term Hero Layouts comes from the fact that Bulma gives you a layout/format for your "Hero" the title that explains what your website is about. In Bulma, it is shown as a giant banner that lets you display your Header in a flashier way. Bulma lets you change its size,color and even add subheaders. Me personally believe that it is way better than your casual h1. Here's an example of what a hero looks like:
<img width="1901" height="643" alt="image" src="https://github.com/user-attachments/assets/494d9477-8903-4e45-8690-0b5264b1925e" />
The code is quite simple:
``` html
<section class='hero is-info is-large'>
  <div class='hero-body'>
    <p class='title'> Icecream Sandwhich</p>
    <p class='subtitle'> Vanilla flavored</p>
  </div>
</section>
```
For better clarification, class `Hero` is used to initialize the Hero Layout, `is-info` changes the color to a lightblue, `is-large` , you guessed it, changes its size. The `hero-body` is the place where the actual text goes where you can place `<p>` or even `<h1>` if you wanted to. The class `hero-body` is actually quite important because it determines the location of the text: in the middle. Using `hero-head` and `hero-foot` can align the text at the top or bottom respectively.

### Skills
1. How to Learn, I do believe that I have bettered myself in this field because of what im able to understand about bulma. Usually, just using the website is ver ineffective as way to learn but ive been able to make it work by using the examples, information and code snippet to better understand the code and its many properties.
2. Growth Mindset, this is too another skill I believe I developed because of the process it took to learn my tool. While learning the panel, it was a lot harder to understand because of the many lines of code the examples gave (the one I gave is much more simple). The examples tend to give an actual example of its use but I was still able to understand it even if it took some time.
### Going Forward
By the time in writing this, we are only a few days away from starting to code our project, compared to before, i'm very excited to try the many new things I learned and how it would affect my website if I didn't have a tool. Use your tool, don't let it use you.
[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
