# Javascript & Jquery - Jon Duckett

## Object Literals

Object literals are pretty freakin cool, imo.
I'm gonna try to write one out here, just to keep in my mind sort of how they work.
```
let myHouse = {
  name: 'Stanwood House'
  bedrooms: 4
  bathrooms: 3
  sqft: 2800
  occupants: 4
  spacePerPerson: function () {
    return this.sqft / this.occupants;
  }
};
```

## Document Object Model

Alright, well to start with, I didn't know that a web browser keeps an HTML document in memory. I guess that makes sense, but I had no idea. 

DOM, I also learned, is what I am more used to hearing called API.

This section is pretty dense, so I'm going to try and summarize, just so I can have written some stuff down to hopefully keep in my brain. The first thing is some of (maybe all of?) the ways you can call an element with JS

```getElementsBy```
* id
* tag
* class

Also you can apparently loop through all of the elements that you've selected, which is kinda neat. 

Also, you can replace the text of a particular node by using ```.replace ``` which could come in handy later to remember. You can additionally append or remove elements to the DOM with ```.append``` or ```.remove```

Honestly there is a ton more in that text that I just can't really wrap my head around in written form, but I'll try and catch a vide on Youtube or something to understand the rest.
