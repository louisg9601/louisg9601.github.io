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

I didn't really need any help with this project, I got a time boost when I did a one on one to see what was wrong with my blog,i fixed my blog and that what was bringing my grade down so I had the rest of the period to work on my flag and define all of my functions.


## Explain your code.

This is the my flag program and some of the definitions i made for said functions,

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
                                             (put-image (rectangle WIDTH LEGNTH3 "solid" "white")  LEGNTH/position2 POSITION3 (rectangle WIDTH LEGNTH/position1 "solid" "red"))))))


```

* * *

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 
<!--- Delete this comment and add your writing -->


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
