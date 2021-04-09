# Shola`s Website

I have build a profile singe web-page using HTML and CSS. I have outlined below the steps I took, research and things I have learned while working at my first project:

## Planning and objective settings

We enjoyed working as a team and had a lot zoom meetings along the way.  On our first meetings we researched together a couple of personal websites and decided on a prefered **layout**. 

I have askes Shola to pick out a favourite color pallete using [color hunt](https://colorhunt.co/). 

I have also designed a **wireframe** that I had him look at before starting the code. 

We held regular meeting to get to know each other and gather content info about the site. I used [this survey](https://docs.google.com/forms/d/e/1FAIpQLSd44GjndruKlptEGBUEwI3A_lH5NEoUwROSDSVhooreAC7V9A/viewform?usp=sf_link) to collect more information to help me put together the content of the website.

Pair programmin and team work was the core focus in our meetings

## Things I have learned while working on the website

### CSS flexbox 

This is what helped buld the main structure of the website. I have started out by using `row` and `column` layout to create a **3 column** layout. I realised that this was not suitable for what I wanted to do as I wanted to style my content as 3 separate boxes with a specific design. Flexbox was my solution. I have used this to create `float` `flexible boxes` with guidance from [this](https://www.w3schools.com/css/css_float_examples.asp?fbclid=IwAR11xs-tgzTMXYnLEL6yfzQsH9tRhaRto8Rax7DVnNBWAvJqAFR1IliWxJ0) to move my first paragraph next to the image. Used `flexbox` layout for my 3 main boxes with research from [this](https://www.w3schools.com/css/css3_flexbox.asp?fbclid=IwAR3z_xf7YCo00DtCxSfQsEHDnJfsLwM0CRICEhRFQ1xUYkrmhuJ445U2A-8). I think this is a really usefull tool for the future. 

### Fixed header and navbar

I struggled to keep my `header` and `navbar` fixed. Here is where I learned the importance of **HTML structure**. Having the `header` and `main` into 2 separate `div` allowed me to use 

```CSS

.navbar{
    position:fixed;
    width: 100%
}
```
The `width` set to 100% allowed me to set the `header` to be the size of the page. 

I have added a :

```CSS
.menu{
    padding: 16px;
    margin-top: 30px;
}

``` 
to avoid content overlay. 

My source of reasearch was [this](https://www.w3schools.com/howto/howto_css_fixed_menu.asp?fbclid=IwAR11dcQ71l3epkHmJXl0g8-wKWZGbf2Ec4IC5LEwURYAuZb3nbE3w2KKjqQ).

### HTML structure - link navbar with sections of the page

At forst that was difficult to figure out but I google it and manage to fixed it by creatin a `section=id` to the `section` of the page I wanted to link. The specific `id` was linked in the `href` of the navbar. 

### CSS float and box-sizing

I know you can do this using `flexbox` but I wanted to try and use the `float` method this time. I like that you can do things in many different ways.  I have used a `grid` of boxes to keep images side by side with the `clearfix` hack. 

The only problem with this is adding something that adding something that is too large could cause the box to break. To solve this `box-sizing` property was used. 

```CSS
   *{
      box-sizing: border-box;
    }
```

### Media Query 

I think this is what I ned to research more about. but basically I have added this 
```CSS
@media (max-width: 800px) {
    .flex-container {
      flex-direction: column;
    }
  }
  ```

 into my CSS for my `flexcontainer` to make my website repossive on other screensized. When you switch to a different screensize, the 2 or 3 column layout will change to 1.  

 All in all _The Client_ was very happy with the final version and I hope you are too! I had a lot of fun working on this and enjoyed the team coding the most. 






## Overview

For your first project on the bootcamp, I have discussed with Shola and sent him 

## Outcome

- a single web page created with HTML and CSS
- a profile describing your client
- a short 1-page README.md file alongside it which describes how you went about the project (your thoughts, research, plans, and justification for decisions)

## Extra

This is not only a chance for you to practice the core skills of HTML and CSS, but also a chance to invest time in thinking about how to build a website for a client, and have a user-centric approach - a key learning objective of the course. You will need to actively communicate with the client to find out everything you need in order to design and build a website which represents them to the rest of the cohort.

Although you will each have an individual repository in which to make the website, there is nothing stopping you pair programming with your partner on the project. Organise your time so that you can spend an equal amount of time on each project. For example, if you spend three hours coding together on Sunday, you would spend 1.5 hours pair programming on one site, before moving over to the other site.

This project will span the first two weeks of the bootcamp, and you will be given time in live evening sessions to work on it as well.
