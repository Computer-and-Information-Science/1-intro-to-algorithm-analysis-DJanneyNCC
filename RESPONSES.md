# CISC230 - David Janney

## factorial2.cpp

- input/parameter impacting number of calls: n
- 3 specific examples of input/parameter and number of calls: n=0, 1 call; n=1, 2 calls; n=5, 6 calls
- number of recursive calls when input/parameter is *n*: n+1

## ireverse2.cpp

- input/parameter impacting number of calls: n
- 3 specific examples of input/parameter and number of calls: n=3, 1 call; n=9, 1 call; n=347, 3 calls
- number of recursive calls when input/parameter is *n*: log(n) rounded up, for n = input value

## sreverse2.cpp

- input/parameter impacting number of calls: s
- 3 specific examples of input/parameter and number of calls: s=star, 4 calls; s=among, 5 calls; s=us, 2 calls
- number of recursive calls when input/parameter is *n*: n

## permute.cpp

- input/parameter impacting number of calls: string length
- 3 specific examples of input/parameter and number of calls: s=abc, 16 calls; s=abcd, 65 calls; s=abcde, 326 calls
- number of recursive calls when input/parameter is *n*: sum from 0 to string length of 2n!-1 (for context, I had to use a graph for this, and it's still off by a bit)

## tower.cpp

- input/parameter impacting number of calls: n
- 3 specific examples of input/parameter and number of calls: n=2, 7 calls; n=3, 15 calls; n=5, 63 calls
- number of recursive calls when input/parameter is *n*: 2<sup>(n+1)</sup>-1

## fibonacci2.cpp (presented in video lesson)

- input/parameter impacting number of calls: N
- 3 specific examples of input/parameter and number of calls: N=2, 2 calls; N=5, 11 calls; N=20, 56 calls
- number of recursive calls when input/parameter is *n*: 3n-4 (doesn't work for the first case)
