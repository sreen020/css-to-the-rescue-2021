# CSS to The Rescue

## View the menu
https://sreen020.github.io/css-to-the-rescue-2021/

## Assignment
When we received this assignment I did not know in witch direction I would go. I did a little research about CSS Zen Garden. This is a website where everyone can style **the same** HTML. The outcome of each person is very different. 
<br>
I chose to work on the menu assignment. Like the CSS Zen Garden, the HTML is already made. My duty is to create the styling with as many new methods I could find.
<br>
## What do I want to use?
I often use the same css stuff. It works, so why try new ones right? Well in this assignment I learned a **LOT** of new css tricks.<br>

**Grid**<br>
Before this assignment I only used flexbox. I knew grid existed but I’ve never working with it. To get familiar with grid I used https://cssgridgarden.com/<br>
<br>
**Darkmode**<br>
Whaaaaaaat?? Is there a darkmode function in CSS?<br>
<br>
**Transform**<br>
I know I can rotate something with this!<br>
<br>
**Animate**<br>
When I see all those keyframes and percentages I’ll get scared.<br>
<br>
**Checkbox hack**<br>
How can you make working buttons using CSS only?<br>
<br>
**Print stylesheets**<br>
I’ve honestly never tough about this.<br>


## Final results

**Grid**<br>
Let’s try display grid. After watching some video’s and playing around for a while I started to understand grid. My vision was clear, I want to have a 3 column full responsive grid. The amount of rows can variate. I used “fr” for this.<br>

```
grid-template-columns: repeat(auto-fit, minmax(600px, 1fr));

```
<br>
This wasn’t enough so I took it a step further. After doing some research I found something named: “named grid”. This means that you can make a grid and tell the grid where something need to be placed. <br>

```
  grid-template-areas:
    "header header header"
    "a b c"
    "d e f"
    "g h i";

```

I couldn’t get this working with the minmax responsive function… So I did use one media query. <br>

<br><br>
**Darkmode**<br>
Like I said before, i’ve had never heard about darkmode in css. This was a WHOAW moment for me. I’m sure that I’ll use this more from now on. 

https://css-tricks.com/a-complete-guide-to-dark-mode-on-the-web/
<br>
To use the darkmode mediatype you can just use:
```
@media (prefers-color-scheme: dark)
```
<br>
I thought about changing my whole website but in the end I just changed the colors. Here is the code I did this with:

```
@media (prefers-color-scheme: dark) {
  :root {
    --main-color: #2d3134;
    --accent-color: #f3510a;
    --bg-color: #202124;
    --text-color: #fefefd;
    --header-color: #f3510a;

    --header-text: #202020;
    --price-color: #f3510a;
    --heart-color: #f3510a;
    --toggle-button: #f3510a;
  }

  body > header p {
    text-shadow: -1px -1px 1px #111, 2px 2px 1px #363636;
  }
}
```
<br><br>
**Transform**<br>

**Animate**<br>
**Checkbox hack**<br>
**Print stylesheets**<br>


##weeks

### Week 1

### Week 2

### Week 3

### Week 4
