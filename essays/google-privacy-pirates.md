---
layout: essay
type: essay
title: Google: Privacy Pirates
# All dates must be YYYY-MM-DD format!
date: 2020-04-24
labels:
  - Software Engineering
  - Learning
  - ICS314
  - Ethics
---
# Google: Privacy Pirates
## What are Ethics?

Ethics are morals and guidelines that govern our thoughts and actions.  It can be influenced by our surrounding environment or our inner thoughts.  In terms of software engineering, ethics can be whether you do something that can harm another person.  This could mean compromising someone's privacy, creating malicious code, etc.  As software engineering is a relatively new field, there have been many instances where individuals have done unethical things.  One such event was when google first launched their StreetView feature, compromising the privacy of many unsuspecting citizens.

## All Seeing Eyes
We've all heard this story before, a big tech company like Google or Facebook farming user data and invading the privacy of millions, but do you know the full extent of their capabilities?  Well in the late 2000's, the world found out what Google was capable of.  In 2007, Google revealed their StreetView technology.  Just like the current StreetView implemented in google maps, it allowed people to have a street-level perspective of the worlds streets and cities.  To gather this monstrous database of pictures, Google drove around neighborhoods and cities manually taking pictures.  While collecting data, Google violated the privacy of ordinary citizens in two ways.  First, they did not blur any personal information or identifying aspects of pictures.  This meant that your actions recorded by the Google StreetView database can be traced back to you.  People ended up being identified leaving adult stores, ditching work, or being in other inappropriate situations.  The second way that google violated the public's privacy is by collecting personal data from unencrypted wifi as the camera trucks drove by.  They collected information such as emails, passwords, and financial/medical records.  And that is not the end of it.  After these actions came into the public eye, Google tried to cover it up by outright denying it.  When that was proven wrong, Google then tried to put the blame on a single low-level worker.  Of course, that was also proven wrong and Google was forced to face the consequences of their actions.
 
## A Silver Lining
Even though I've had all these negative experiences, I still see the benefit from using coding standards.  One of the biggest positives of using coding standards is everyone can read your code efficiently.  If every programmer was coding in their own specialized style, reading code requires you to adapt to each individual programmer.  With coding standards, everyone is coding with the same semantics which means you can process code more efficiently.  Another. less recognized, benefit from coding standards is that it can actually help people learn about different languages.  I’ve experienced this first hand.  Before I used ESLint, I used to initialize my array variables like:

```let arry = []```

Little did I know that if I was only pushing or shifting the array, the array is still considered to be constant.  This means that when using arrays in this way, it should be initialized like:

```const arry = []```

With just ESLint alone, I gained a bit of insight of how JavaScript handles arrays during runtime.
## Reluctant Defeat
<img class="ui medium right floated image" src="/images/man_machine.jpg">
ESLint and other style tools are a blessing and a curse.  On one hand they can provide hidden insights about the language you are using, but on the other, they can be a pain to install and adapt to.  Even though I do hate it, I do feel like it is a necessity to be a productive and efficient programmer.


