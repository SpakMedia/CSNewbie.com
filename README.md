# CSNewbie.com
### An Open Source Resource Website for Computer Science

# Resources
**Books**

# Notes With Examples

[Harvard CS50](https://www.youtube.com/playlist?list=PL2SOU6wwxB0uVbmox-s0PCssse5VKGkWh)

**Linear**

+ Most problems in CS problems are linear.
+ The larger the dataset or problem to solve, the longer it will take.
+ 'n' is the variable used to represent a value.

**Logarithmic**

+ Logarithmic algorithms - such as binary search - "narrows down the search by repeatedly halving the dataset until you find the target value." -[src](https://towardsdatascience.com/linear-time-vs-logarithmic-time-big-o-notation-6ef4227051fb)

![algorithms](https://cs50.harvard.edu/2018/fall/weeks/0/notes/running_time.png)

**What's an algorithm?**

+ A set of instructions to solve a problem, step-by-step.

[Ted Ed Explainer Video](https://youtu.be/6hfOvs8pY1k)

**What is Pseudocode?**

+ English-like syntax that resembles a programming language.

Example:
```
let N = 0
for each person in room
  set N = N +1
```

+ Line 1: declares a variable `N` and initalizes it's value of `0`.
+ Line 2: is a loop.
+ Line 3: how we will go about counting. The indentation implies this is a line that will be repeated.

In other words:<br>
For each person in the room we will increase our count `N` by 1.

**Optimization of the above algorithm**

```
let N = 0
for each pair (2) of people in the room
  set N = N + 1
```

+ The above sudocode is buggy, if there is an odd number of people in the room. However, we can catch this exception by updating our logic.

```
let N = 0
for each pair of people in room
  set N = N + 2
if 1 person remains then
  set N = N + 1
```

+ A `condition` is also known as a `branch`.
+ An `edge Case` is also known as a `corner case`.

**To-to-date CS50 Resources**
[cs50.net](http://cs50.net)
---

## FAQ
**Q:** How do you want the content placed on the site? Links to PDFs, PDFs themselves, or links to where to buy the books? I have a ton of PDFs but not sure how you feel about posting free material online that authors would probably prefer be acquired through regular purchase

**A:** I think links to where to buy the books would be wise -- maybe a sentence or two as to why you liked it. As much as I love free info, I don't want to piss off people who worked hard on a product.

## Contributors
[https://github.com/SpakMedia/CSNewbie.com/graphs/contributors](https://github.com/SpakMedia/CSNewbie.com/graphs/contributors)

## Contribute
[https://github.com/SpakMedia/CSNewbie.com](https://github.com/SpakMedia/CSNewbie.com)

## Affiliate Links & Advertising Disclaimer
In an effort to make Spak Media profitable we will occasionally convert resource links shared to affiliate links. <br>
<br>
Why? We want to grow the network via PPC advertising. Also, at scale we will need to invest more time into managing & organizing all Spak Media projects. Eventually we'd like to have a small dedicated team (5 - 10 people) of content editors & programmers that are paid to help us stay organized & moving forward. 
