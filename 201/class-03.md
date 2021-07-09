# HTML & CSS - Jon Duckett

## Lists

*Most* of this section was a bit of review, but I did learn a new thing!

There are actually **3** types of lists, I only knew about 2.

The 2 that I already knew were ordered, and unordered lists.

```
<ul>
  <li>list element</li>
  <li>another</li>
  <li>and another</li>
</ul>

<ol>
  <li>list element</li>
  <li>another</li>
  <li>and another</li>
</ol>
```
The type that I didn't know about though, is a definition list. 
It is constructed the same, but uses the tag ```<dl></dl>```. 

I also discovered that you can do nested lists, with one list inside of another!

## Boxes

This section is going to be a bit of a challenge for me. 
*I do not have an eye for visual design at all...*

However, the things covered in this secion of the book will make it a bit easier to pretend that I do.

The first things that Duckett talks about are:
* min-height
* max-height
* min-width
* max-width

There are several ways in which you can set these (pixels, percents, ems) but their function is the part that I'm most excited about. 
If used properly, these settings can help prevent the elements on your page from being stretched too wide or made too narrow.
Similarly, it can prevent being shrunk down from the top of bottom of the page. This is very useful, because nothing is worse than a website that wasn't properly designed for mobile.

He also talks about borders, their properties, and how to set them. This is another way to effectively control the layout of your page.

Another thing I didn't know well was the difference between padding and margins. 

* margins: spacing between elements of a page
* padding: spacing fromt he edges of the current element

The chapter finishes out talking about some things I didn't find particularly useful, but I did find the way to change the style of your lists pretty interesting. 

To do this, you'll need to set the ```display``` parameter to ```inline```, ```block```, etc in CSS

# Javascript & Jquery - Jon Duckett

## Basic Javascript Instructions

These few pages here talk about arrays. Specifically, how they look, and how they're accessed.

As a simple example to give me something to remember by:
```
let familyMembers = ['Ai', 'Nina', 'Ellie']
familyMembers[2] 
```
 Because JavaScript is a 0 indexed language, 2 will return the third element in that array, which should be Ellie *(I think)*

 More to learn here, definitely not perfected my understanding yet.

## Decisions and Loops

So in this chapter, Duckett starts out taling about if/else statements. I think we've already demonstarted a bit of how to to that in code that has been written to far: 
```
if(firstAnswer === 'yes' || firstAnswer === 'y'){
  alert('I am! Hard to believe right?');
  correctResponse ++;
} else if (firstAnswer === 'no' || firstAnswer === 'n'){
  alert('I\'ve been married for almost 10 years, my wife\'s name is Aileen (eye-lean)');
  incorrectResponse ++;
} else {
  invalidResponse ++;
  alert('Please answer only with yes or no');
}
```

After that it pretty much gets into content that I don't fully understand at this point. 
He talks about ```switch``` statements, which I think basically just allow you to return a different value, based on how far into a task you've gotten.

The last topic in this section talks about all of the different types of loops. Since I don't actually understand them very throughly, I'm just going to break them down into their parts, for the sake of memory.

##### loop components?
```for (i = 0;```: **starting value of variable**
```i < 8;```: **until no longer true** 
```i++)```: **action to take**

I think that the loops are all pretty similar, and don't really know why you'd use one over anothers
