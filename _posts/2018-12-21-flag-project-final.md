---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of _Puerto Rico_ by _Louis Gonzalez_

## Describe your program
I did the Flag of Puerto Rico because that is where both sides of my family are from and feels like a part of me, I'll probably get a practitioner because of the flag I chose,i don't know what I'm going to get though because i never got the paper that shows what flags qualify for what grades.



## Current output

![my flag](/images/LG_FlagV2.png)

## Describe your process.

I didn't really need any help with this project,And any problems that i had i solved by myself using my own knowledge,i even went as far as actually helping others too. I got a time boost when I did a one on one to see what was wrong with my blog,i fixed my blog and that what was bringing my grade down so I had the rest of the period to work on my flag and define all of my functions.


## Explain your code.

This is the my flag program and some of the definitions i made for said functions,I ​

* * *
```
(define TRIANGLE/STAR-POSITION 60)
(define TRIANGLE-X 86)
(define TRIANGLE-Y 100)
(define STAR-X 60)
(define STAR-Y 102)
(define POSITION3 140)
(define FLAG (put-image (star STAR-SIZE "solid" "white") 
                        STAR-X STAR-Y 
                        (put-image (rotate TRIANGLE-ROTATION(triangle LEGNTH/position1 "solid" "blue")
                                           ) 
                                   TRIANGLE-X TRIANGLE-Y 
                                   (put-image (rectangle WIDTH LEGNTH3 "solid" "white") 
                                             LEGNTH/position2 TRIANGLE/STAR-POSITION


```

* * *

 This is the entire program for my flag,I've completed my flag and yes,this is all the Puerto Rico flag needs to be made in WeScheme,including definitions for any numbers.from left to right this is the order of the shapes:STAR,TRIANGLE,WHITE STRIPES,and RED BACKGROUND LAYER,the triangle being blue,the stripes and star are white,and the background layer is red acting as the red stripes. When I started,I had acidentally made the background white and the stripes red,leaving the colors inverted,the triangle was actually worked on first because it only needed to be rotated,the star was worked on last and was the hardest part of this project since there aren't any measurments of where the star needs to be on the triangle and how big the star is,I just looked up a picture of the flag,and this is where I realised that the stripe colors we're inverted,which I fixed easily by swapping the colors and strings,after this I just decided on centering the star on the smae point as the triangle and making the star a reasonable size. After this was all the definitions,which was easy to do,all i needed to do was define all of the numbers as what measurement they would be,like the length of the base rectangle being 300 and the length 200,most have two jobs,as a position or a measurement,like length/position 2 being the x coordinate  for the stripes,but at the same time being the y coordinate for the triangle. What I need to do next for this flag project is to make a function that changes said flag into differnent sizes,which I might have trouble with.

## Program code

```
(define WIDTH 300)
(define LEGNTH/position1 200)
(define LEGNTH/position2 150)
(define LEGNTH3 40)
(define STAR-SIZE 47)
(define TRIANGLE-ROTATION -90)
(define TRIANGLE/STAR-POSITION 60)
(define TRIANGLE-X 86)
(define TRIANGLE-Y 100)
(define STAR-X 60)
(define STAR-Y 102)
(define POSITION3 140)
(define FLAG (put-image (star STAR-SIZE "solid" "white") 
                        STAR-X STAR-Y 
                        (put-image (rotate TRIANGLE-ROTATION(triangle LEGNTH/position1 "solid" "blue")
                                           ) 
                                   TRIANGLE-X TRIANGLE-Y 
                                   (put-image (rectangle WIDTH LEGNTH3 "solid" "white") 
                                             LEGNTH/position2 TRIANGLE/STAR-POSITION 
                                             (put-image (rectangle WIDTH LEGNTH3 "solid" "white")  LEGNTH/position2 POSITION3 (rectangle WIDTH LEGNTH/position1 "solid" "red"))))))



```
