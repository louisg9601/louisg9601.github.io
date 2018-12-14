- - -
layout: post
title: "flag project-in progress
date:2018-12-14
- - -

This week i finished my V2 flag on the first day,and then during a one on one i had i defined all the numbers so now every thing looks like this
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
I'm supposed to only be about half way done,but i was working so fast that i finished the flag in the 30 minutes on the first day then defined the numbers in 20 minutes during the one on one. It wasn't that hard once I started to remember a lot of the things like put-image,which seems easy to use now that it was one month ago,altough it was still tedious,having to find out the perfect measurements so it could look nice or having to layer the different stripes. 
![My Flag](/images/LGFlagV2.png)
I didn't really have any questions when making the flag execpt when i asked to scedual the the one on one,which really help my grade after I fixed my website and showed my teacher so the 1s i had for blog posts could be 3s.50
