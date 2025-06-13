# opossum-nets

## opp-006
Generated as of https://github.com/liamt19/AwesomeOpossum/pull/14, after adding higher root PST which likely improved visit distributions.
```
datagen 18t 16d 25000n dfrc
   games     positions          nodes        nps       fill
  770174    94,755,123  2,426,310,501     39,742        141

Elo   | 34.98 +- 13.13 (95%)
SPRT  | 8.0+0.08s Threads=1 Hash=32MB
LLR   | 2.91 (-2.25, 2.89) [0.00, 5.00]
Games | N: 1694 W: 653 L: 483 D: 558
Penta | [59, 158, 298, 218, 114]
https://somelizard.pythonanywhere.com/test/2651/
```

## opp-005-pw
Used the same data as opp-005, but with crelu + pairwise-mul instead of screlu.
```
Elo   | 17.36 +- 9.05 (95%)
SPRT  | 8.0+0.08s Threads=1 Hash=32MB
LLR   | 2.93 (-2.25, 2.89) [0.00, 5.00]
Games | N: 3766 W: 1419 L: 1231 D: 1116
Penta | [182, 364, 668, 422, 247]
https://somelizard.pythonanywhere.com/test/2645/
```


## opp-005
Data generated after fixing [dfrc datagen](https://github.com/liamt19/AwesomeOpossum/commit/1df342ee0dd7e41bf4f3b912f0193722596641c8)
```
datagen 16t 16d 25000n dfrc
   games     positions          nodes        nps       fill
  870235   108,700,645  2,778,829,486     41,685        137

Elo   | 110.58 +- 25.48 (95%)
SPRT  | 8.0+0.08s Threads=1 Hash=32MB
LLR   | 2.91 (-2.25, 2.89) [0.00, 5.00]
Games | N: 630 W: 341 L: 147 D: 142
Penta | [18, 28, 107, 66, 96]
https://somelizard.pythonanywhere.com/test/2640/
```

## opp-003 

Data generated as of https://github.com/liamt19/AwesomeOpossum/pull/9, before fixing the exploration scaling logarithm base. 512 HL.
```
Node limit:   35,000
Depth limit:  14

Variant:      Standard
   games     positions          nodes        nps       fill
  243646    44,894,709  1,178,345,928     35,254        141

Variant:      DFRC
   games     positions          nodes        nps       fill
  144848    26,670,454    700,228,058     35,537        141

Elo   | -19.30 +- 12.20 (95%)
SPRT  | 8.0+0.08s Threads=1 Hash=32MB
LLR   | -2.26 (-2.25, 2.89) [0.00, 5.00]
Games | N: 2090 W: 709 L: 825 D: 556
Penta | [146, 220, 381, 200, 98]
https://somelizard.pythonanywhere.com/test/2632/
```
