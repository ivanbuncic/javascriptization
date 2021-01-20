---
title: What on earth is a variable in JavaScript?
description: I'll try to explain to myself what is a variable.
date: 2021-01-07
tags: variables
layout: layouts/post.njk
---

### Drawer or something else?

``` js
// Creating a variable with var keyword

var number = 5;
var func = function() {
	return number;
}
var stringy = 'Hi I\'m stringy';

var stringy2 = "Hy I'm stringy2";

var stringy3 = `String that has special powers, I could 
dinamically embed whatever I want, I could write multi rows,  
number from above ${number} or stringy "${stringy}". I could 
even calculate inside of it, like number * 2 = ${ number * 2 }`;
console.log(stringy3);
// Creating a varibale with let keyword

// Creating a variable with const keyword


```
