# Introduction

# Objectives

- get the kids excited about programming
- introduce the kids to the following concepts:
    - data (strings, numbers)
    - functions
    - operations (+)
    - comparators (===)
    - conditonals (if, else)
- teach the kids how to make a number guessing game using real code, not something like scratch.
- build a connection to technology by thinking of code as the kids "robot friend"
- encourage kids to experiment rather than dictate what they learn.
- encourage kids to explore further

# Requirements

open your browser to https://replit.com/languages/javascript

this is a website that lets you write javascript and run it without needing to download any tools or go through any complicated setup.

all code written on the left side can be "run" using the big green run button. The result of the code can be seen on the right side of the page.

# Lesson plan

## Run your first program
When you open https://replit.com/languages/javascript you will see some text on the left side of the page. It should look like

```
console.log("Hello World")
```

and you'll see on the right side when you hit the run button you should see "Hello World"

Congrats! you just ran your first ever program.


## Teach the computer how to talk
Now can you make it say anything else? go ahead and try to make it say anything that you want.

If you're looking for something to try, why not make it say your name? that would look like

```
console.log("Hello Brooklin")
```

except you would replace "Brooklin" with your own name.

make sure you remember to use the quotes "" around anything that is a word or sentence.

for example what happens if you try

console.log(Hello World)

the red text might not make any sense yet, but that's ok. you can know that if you see any red text that usually means there's something not working with your code.

## Partner Excercise: Teach the computer how to greet others

Now you've learned how to make the computer "talk" using console.log.
Let's see if you can teach it how to greet someone else in the class.

```js
let name = "Brooklin"
console.warn("Hello " + name)
```

This is great, but what if we want to greet a lot of people?
whenever we want to do something over and over again in programming, we often use a `function`

```js

function greet(name) {
    console.warn("Hello" + name)
}

// we can run functions like so
greet("Brooklin")
```




## Partner Excercise: Make a number guessing game


