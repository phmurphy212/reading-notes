# HTML & CSS - Jon Duckett

## Text

In this section of the text, Duckett talks about several ways to manipulate text elements using HTML.

Several of these elements seem to serve a very similar function, so let's look at those

#### Bold and Strong
```<b> <strong>
- Both of these tags create a bolded element

#### Italics and Emphasis
```<i> <em>
- These two tags italicize text

#### Strikethrough and delete
```<s> <del>
- Strikes through the text between these tags

The text also discusses some additional ways to manipulate text. 

There is also a group of tags that just do what their name implies, such as:
- ```<cite>```
- ```<address>```
- ```<abbr>```
- ```<dfn>```

We also learn about headings, of which there are six, which are written as
```
<h1> Thing you want as a heading </h1>
```
Subscript and superscript are also taught as ```<sup> & <sub>```
Finally we learn about line breaks (```<br >) and horizontal rule, which is just a line across the page (```<hr \>) 

## Introducting CSS

Okay, let me just say, I didn't know much about CSS, but reading up on it a little today, it seems really cool. 

This chapter starts out talking about sort of how to set up your CSS document. You'll need to specify:
- <link> (expect a CSS file)
    - href (location of CSS file)
    - type (always text/css for CSS)
    - rel (always styleshet for CSS)

Then it gets into a bunchof CSS selectors, which I will honestly probably look up frequently until I have them memorized.
The part that I really want to commit to memory is the rules for host CSS cascades. 

> 1. Last Rule: will take the last rule, if two rules are set for a single selector
  2. Specificity: A more specific rule will take precedence
  3. Important: A rule you set as important explicitly

Finally it talks about how inheritance works in CSS where things like font-family are passed to child elements. 

# Javascript & Jquery - Jon Duckett

## Basic Javascript Instructions

This chapter was an ![absolute unit](https://miro.medium.com/max/2160/0*lTk9nVcJheFq-Q4B.jpg)

It covers setting variables and assigning them a value, and while they use var, we're using let. 
Ducket also shows how to set a number as a variable, as well as a boolean.
```
var firstName = 'Phillip';
let firstName = 'Phil';
let myAge = 32; 
let readsSlowly = true; 
```
It also goes over some ways to change the values of a variable, and shows some different formatting for how you can set variables in the first place.

Then it gets to the part that I'm going to need to study a bit more, arrays. 

```
let kidsNames = {'Nina',
                'Ellie'
                'Undecided'
                }
```

After that, we get into the first instance of ientifying whether JS is 0 or 1 indexed, when Duckett talks about how to access/change the values of a variable within an array
* this is done using ```kidsNames[2]```

Then to close things out, it gets into arithmatic operators and string operators. The math operators function like math, mostly, and the string operators we have been using pretty frequently in class thus far.

## Decisions and Loops

This one wasn't too bad, since we'd just gone over most of it in class tonight. 

Essentially it reiterated on how to make, and what goes into a loop, or an if/then statement.

I'll include an example here:

```
let remainingEnergy = 2;
if (remainingEnergy >= 25){
  alert('Seems like you\'re running out of steam')
} else {
  alert('Oh no, you're going to die from exhaustion, hurry to bed!!!!')
}
```
