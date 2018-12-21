---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of Norway by Sakura Klein

## Describe your program

Norway i choose this flag because i been there and it is a cool place so i thought it would be cool to code a flag that i have some type of prior knowledge for what the country is like. 

I think i should get a apprentice of practioner because i completed the code and the out put is the norway flag but i got some help on it.

## Current output



* * *
![Flag](/images/flagv2.png)
* * *

## Describe your process.
-   This week was pretty good week for because i sucessfully coded the flag that i choose surprisingly. While coding the Norweign flag i did not do it completely by my self but for most part i did. While coding the flag i first forcused on making the rectangles based on the color and length which is the first half of the code. After i got all the rectangles right i had to combine it in a way that will make the norweign flag. I always kept in consideration that the whole rectangle is 300 to 500 keeping that in mind helped me firgure out the exact location of where i want the rectangele. The hard part about making the flag for me was the second part of the code because you have to combine a lot of rectangles to make a flag. I hope next week i can do what is assigned and understand it. What helped me the most is thinking about the area of the rectangle also how there is 2 different sets of code. One for to create the rectangles just by itself and the other set is to connect them. 




## Explain your code.
 After i got all my numbers set and right i replaced the numbers with words which is the code right below include image. I started with 500 since that is the width after i had numbers like 300 so to get that i wrote width * 3/5 which would get me 300. For 100 i did width * 1/5 since that would get 100. For 150 i was confused at first since no perfect number that is a multiple for 500.

* * *

```
width = 500
height = width * 3/5
stripe-width = width * 1/5
fo = width * 3/10

bg=rectangle(width,height,"solid","red")
vw=rectangle(stripe-width,300,"solid","white")
hw=rectangle(width,stripe-width,"solid","white")
hb=rectangle(width,50,"solid","dark-blue")
vb=rectangle(50,height,"solid","dark-blue")

```

* * *


## Program code

```
include image

width = 500
height = width * 3/5
stripe-width = width * 1/5
fo = width * 3/10

bg=rectangle(width,height,"solid","red")
vw=rectangle(stripe-width,300,"solid","white")
hw=rectangle(width,stripe-width,"solid","white")
hb=rectangle(width,50,"solid","dark-blue")
vb=rectangle(50,height,"solid","dark-blue")

f1=place-image(hw,250,fo,bg)
f2=place-image(vw,fo,fo,f1)
f3=place-image(hb,250,fo,f2)
f4=place-image(vb,150,fo,f3)

```
