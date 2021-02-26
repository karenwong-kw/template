---
layout: essay
type: essay
title: Brick By Brick
# All dates must be YYYY-MM-DD format!
date: 2021-02-25
labels:
  - UI Framework
  - HTML
  - CSS
  - UI Design
---

As a person coming from a background of primarily coding in languages such as Java and C/C++, coding in HTML and CSS is a completely different experience. This entire experience has been very hands on and visually responsive. Every little change implemented can be seen within a couple of seconds. It made me realize how detailed you can get with this. Any option you can think of is possible as long as you know which switches to flip. That being said, it is incredibly tedious to compose ideas you have in your head with raw HTML and CSS. It’s like building your own home but you’re building it brick by brick with nothing but your hands. Sure, building everything one at a time is impressive however the amount of time and effort being put in may not fully satisfy you.

<img class="ui medium left floated image" src="../images/without.png">
<br>
Take a look at this web page. It has its basic structure of text, images, links, and paragraphs but it doesn’t look clean or appealing. The navigation bar is undistinguishable and there are barely any visual cues to where you are supposed to look at. It looks more like a sketch outline of what the final product should look like.

<img class="ui medium left floated image" src="../images/with.png">
<br>

Now here we add Semantic UI, a UI Framework. The navigation bar is clean and distinguishable. Users will know where to look without having to scan the whole page. Not only was this page friendlier to look at, it was easier to code too.

In this example, we are creating a Title for the History on Chrome paragraph column. This code is just raw html.

## <h2><a name="Chrome">A brief history on Chrome</a></h2>


However we can use semantic UI vocabulary that just flows better. It’s more difficult to understand code that doesn’t flow like how english does. If we were to change the sizing of the column, we would have to figure out the size ourselves and change it in our style sheet.

## <div class="ui column"><h2 id="Chrome">A brief history of Chrome</h2>


In this same line of code, we implemented semantic UI. Using the div class ui column, we clearly stated what this line is for so it is easier to understand what it does. If we wanted to change the size, we simply would just say “ui ten wide column” or however wide you wanted it to be. It will automatically change the sizing for you without worrying about the details too much.

In a way using UI frameworks feels like buying pre-built parts of the house and being the interior designer. You select what parts you want and make the changes to your liking. However, learning a UI framework takes some time and commitment. Because some of these elements are pre-built for you, in order to alter and understand them you would need to read through the documentation. It can be super frustrating at first because it feels like you have to work around these rules. But I would say the investment is worth it. Those several hours you spend looking over documentation is still better than the much longer hours you would take trying to fix in raw HTML and CSS.

