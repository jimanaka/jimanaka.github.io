---
layout: essay
type: essay
title: Coding in Style
# All dates must be YYYY-MM-DD format!
date: 2020-02-13
labels:
  - Software Engineering
  - Learning
  - ICS314
  - Coding Standards
  - ESLint
---
# Coding in Style
## The ESLint Dilemma

<img class="ui medium right floated image" src="/images/ESLint.png">
I’m going to be honest; I hate coding standards and the tools we use to check them.  Whenever there comes a time where I am required to install specific coding standard tools, they always find a way to mess with me.  False errors, tab and spacing issues, or the worst of the worst, false positives.  Whether it be back in ICS 211 or now, I don’t think I’ve ever had a positive experience with tools like ESLint or CheckStyle.  Despite this, I do see the necessity and the advantages of using code standards.  They can reveal small quirks about the language you are using and make your code readable to everyone.  For these reasons, my feeling towards ESLint and coding standards are mixed and it turns out to be quite the dilemma.

## Man vs. Machine
<img class="ui medium left floated image" src="/images/boxing.jpg">
 Installing style tools has always been an uphill battle for me.  Just recently, I was trying to install ESLint and spent over 2 hours trying to get it to work on my desktop.  These tools never have a simple installation process and every IDE comes with a bunch of style tools automatically enabled which can mess with you even more.  To install ESLint I had to download and install a style XML, enable it in 3 different areas of the IDE preferences, install npm, install NodeJS, download a provided eslint file for my project, and disable all other enabled style checkers just so I could start my homework.  There is probably a good reason for this, but I feel like everything could be solved if someone just made an ESLint XML file or IDE installer that can automatically configure ESLint for you.  Maybe it’s just my gross incompetence with installing code style tools, but right now, its me vs my machine.
 
## A Silver Lining
Even though I've had all these negative experiences, I still see the benefit from using coding standards.  One of the biggest positives of using coding standards is everyone can read your code efficiently.  If every programmer was coding in their own specialized style, reading code requires you to adapt to each individual programmer.  With coding standards, everyone is coding with the same semantics which means you can process code more efficiently.  Another. less recognized, benefit from coding standards is that it can actually help people learn about different languages.  I’ve experienced this first hand.  Before I used ESLint, I used to initialize my array variables like:

```let arry = []```

Little did I know that if I was only pushing or shifting the array, the array is still considered to be constant.  This means that when using arrays in this way, it should be initialized like:

```const arry = []```

With just ESLint alone, I gained a bit of insight of how JavaScript handles arrays during runtime.
## Reluctant Defeat
<img class="ui medium right floated image" src="/images/man_machine.jpg">
ESLint and other style tools are a blessing and a curse.  On one hand they can provide hidden insights about the language you are using, but on the other, they can be a pain to install and adapt to.  Even though I do hate it, I do feel like it is a necessity to be a productive and efficient programmer.


