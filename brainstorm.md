``I think that it's extraordinarily important that we in computer science keep fun in computing. When it started out, it was an awful lot of fun. Of course, the paying customers got shafted every now and then, and after a while we began to take their complaints seriously. We began to feel as if we really were responsible for the successful, error-free perfect use of these machines. I don't think we are. I think we're responsible for stretching them, setting them off in new directions, and keeping fun in the house. I hope the field of computer science never loses its sense of fun. Above all, I hope we don't become missionaries. Don't feel as if you're Bible salesmen. The world has too many of those already. What you know about computing other people will learn. Don't feel as if the key to successful computing is only in your hands. What's in your hands, I think and hope, is intelligence: the ability to see the machine as more than when you were first led up to it, that you can make it more.''

Alan J. Perlis (April 1, 1922-February 7, 1990)

In my family, I started more serious attempts to introduce coding when my kids were ages 12 and 14. Although I spend most of my work time with Microsoft technologies, I didn’t introduce my kids to .NET or the legendary but increasingly marginalized Visual Basic language. Instead, I introduced my kids to JavaScript, a universally important language with no barriers to code sharing. That means they could write their own single-page meme-powered example and share it with their friends, no installation or deployment required (just a free JavaScript playground like CodePen).

## Resources
- flow chart for young learners https://medium.com/young-coder/a-programming-flow-chart-for-kids-983cbaff8038
- young coder https://medium.com/young-coder
- free javascript beginner book https://medium.com/young-coder/a-free-javascript-beginner-book-4f11404679a0
- first steps for electronics for kids https://medium.com/young-coder/first-steps-in-electronics-for-kids-37107265cc8d
- learn to code by hacking minecraft https://medium.com/young-coder/learning-to-code-by-hacking-minecraft-8c3da41e741a
- sicp https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html
- codepen https://codepen.io/pen/
- repl js: https://replit.com/languages/javascript
- How to Invent Everything, A Survival Guide for the Stranded Time Traveler

## Why learn code
- What is "coding"?

When I was younger I wanted nothing more than to be a wizard. I got spellbooks, I had talismans of power, and I even read about the magical history of the world and the fantastic creatures like dragons that exist within it.

So as I grew older I found out there was a magical language that only a few diligent sorcerers knew, that allows you to predict the future, to control robots and machines, to speak with others accross large distances, and even travel to space.

that language was code.

...

## Well how did it all start?

In the early days of humans about two hundred and 2 thousand years ago there were no smartphones, no tvs, no cars. Infact humans hadn't even figured out how to talk yet. which made it pretty hard to do anything at all. The early computer programmers of this age had to content themselves 

Somewhat embarassingly it took us about one hundred and fifty thousand more years before people decided they had enough silence and figured out how to talk to eachother. This was when humans realized that in a way - they could program eachother. By given one person instructions, they could get them to act the way they wanted (more or less - there were still a lot of bugs).

Another 43000-45000 thousand years or so later after enough talking we figured out we could convince plants where to grow. One could say this was the first programming language ever invented. we realized that if we put plants into the ground we could convince them to grow where we wanted, and even to grow bigger and better than before. Things started to really pick up the pace after this.

Only a few thousand years later and we'd had so many good ideas that we realized we needed a place to keep them all, so we invented writing. This was the worlds very first true database. Of course we had dabled with songs, stories, and structures but all of those proved to a volatile memory that didn't have much of a guarantee of lasting stability.

With the ability to remember and share everyone's good ideas the programmers of that time experienced a new information explosion and over the next few thousand years we would learn to harness the power of those ideas to make peoples lives a lot better.

However admittedly we also had a lot of bad ideas along the way. So many bad ideas that people started to question how we were coming up with all of these ideas in the first place.

So we started to make rules for ideas. Those rules became the "Scientific Method". A lot of people complained, people liked the old way of doing things where we could come up with any idea that we wanted and no one could prove if it was right or not. This continues to be true to this day.

However thanks to this we had better and better ideas and only a few hundred years later humans learned how to make computers.

At first only a few people knew how to use computers, and it was very difficult to tell them to do much. However in 1969 despite this, we managed to use these computers to send people to the moon.

It would only be a few decades before everyone had access to these computers. and it would only be within the last 30 years (1990s) that we all realized we love computers so much we even want to carry a little one with us. It got so easy to use computers that in the past few years we even figured out how to let an actual monkey use a computer (this is real, it played ping pong.)

However, while many can use a computer, only the dedicated few can truly command them.

The good news is, that anyone can do it. and you can to.

## So what is "coding" really?

Well if I wanted to be boring, coding is simply the ability to tell computers to do what you want them to.

however I prefer to think of it differently. In a way, coding is the ability to cast magical spells, in an arcane language that few people can read, that with enough practice can enable you to do nearly anything you can imagine.

so let's learn how to cast our first magic spell.
let's learn how to talk to our computer.

## Hello Wor-... RISE MY LOYAL SERVANT AND DO MY BIDDING!

- enter the javascript repl (read-eval-print loop) at https://replit.com/languages/javascript

Your first "Magic Spell" is called "console.log"
It's a strange name, and not nearly as descriptive as something like "fireball" but we can think of this kind of like a "messaging" spell.

```js
console.log("RISE MY LOYAL SERVANT AND DO MY BIDDING!!!")
```

now we have commanded our loyal computer servant to rise. However, much like humans 200 000 years ago our computer friend has not learned how to speak yet. to do that, we need to tell them how. or in other words we need to give them the "function" to speak.

```js
function speak() {
    console.log("Computer: Yes Master")
}
```

we've told our computer friend how to speak, but we haven't actually told them to speak yet.

```
speak()
```

alltogether your program should look like 

```
console.log("RISE MY LOYAL SERVANT AND DO MY BIDDING!!!")

function speak() {
    console.warn("Computer: Yes Master")
}

speak()
```

Now we're going to learn how to tell the computer to "do our bidding".

```
console.log("DO MY BIDDING! tell me, what is 5 * 12?")

speak()
```

you should see 

// DO MY BIDDING! tell me, what is 5 * 12?

// From here, I plan to teach how to get the robot to respond with a new value.

// Then I plan to teach how to train the robot how to play rock paper scissors.