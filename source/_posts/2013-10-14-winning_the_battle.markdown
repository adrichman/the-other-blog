---
layout: post
title: "winning the battle but..."
date: 2013-10-14 20:51
categories: 
---
##battled for an embarrasingly long time with this problem for coderbyte:

>Using the JavaScript language, have the function PermutationStep(num) take the num parameter 
>being passed and return the next number greater than num using the same digits. For example: 
>if num is 123 return 132, if it's 12453 return 12534. If a number has no greater permutations, 
>return -1 (ie. 999). 
>
>Input = 11121 Output = 11211
>Input = 41352 Output = 41523


My original solution didn't take too terribly long, and it was able to pass all my test cases, but then coderbyte's response informed me that it failed for a really exhaustive case such as 897654321. I was exceeding my stack limit on that case, so I rethought ways to keep the permutations to the minimum. Really happy I that I pulled through it because the result also runs much faster.

[Github::PermutationStep.not_exhaustive.js](https://github.com/adrichman/coderbyte/blob/master/PermutationStep.not_exhaustive.js)

