# Used brainjs to make math (wow such smart)

### Training notes
Training finishes when errorThresh is below 0.03, which from my experience takes about 200-500 iterations to do so.

When running with errorThresh being 0.01, the machine took exactly 20,000 iterations to complete it's training, but it still got 16% of the equations wrong because brainjs is bad when taking in tens of thousands of numbers. Those 20,000 iterations also took somewhere around 5-10 mins to complete.


Each iteration takes exactly 5 miliseconds (0.73 big macs eaten for americans), so go figure how long it takes to run through 20,000 iterations.


### Training example (errorThresh: 0.03)
```
iterations: 0, training error: 3.8730483429157276
iterations: 10, training error: 0.05590719120980839
iterations: 20, training error: 0.05305782187084092
iterations: 30, training error: 0.05100329661260197
iterations: 40, training error: 0.0504750375631016
iterations: 50, training error: 0.049005858335446045
iterations: 60, training error: 0.046432070215201814
iterations: 70, training error: 0.04314793979815115
iterations: 80, training error: 0.039140101912440155
iterations: 90, training error: 0.03745928651442208
iterations: 100, training error: 0.03618286819793762
iterations: 110, training error: 0.03970159404121808
iterations: 120, training error: 0.03518720029138027
iterations: 130, training error: 0.03206654362006774
iterations: 140, training error: 0.04740865061656987
iterations: 150, training error: 0.03142031067627467
iterations: 160, training error: 0.03356578992930726
iterations: 170, training error: 0.034528651601683655
iterations: 180, training error: 0.03231827362409479
iterations: 190, training error: 0.035969394988233636
iterations: 200, training error: 0.031305225108426774
0+0=0
0+1=1
1+0=1
0+2=2
2+0=2
0+3=3
3+0=3
0+4=4
4+0=4
0+5=5
5+0=5
0+6=6
6+0=6
0+7=7
7+0=7
0+8=8
8+0=8
0+9=9
9+0=9
1+1=2
1+2=3
2+1=3
1+3=4
3+1=4
1+4=5
4+1=5
1+5=6
5+1=6
1+6=7
6+1=7
1+7=8
7+1=8
1+8=9
8+1=9
1+9=10
9+1=10
2+2=4
2+3=5
3+2=5
2+4=6
4+2=6
2+5=7
5+2=7
2+6=8
6+2=8
2+7=9
7+2=9
2+8=10
8+2=10
2+9=11
9+2=11
3+3=6
3+4=7
4+3=7
3+5=8
5+3=8
3+6=9
6+3=9
3+7=10
7+3=10
3+8=11
8+3=11
3+9=12
9+3=12
4+4=8
4+5=9
5+4=9
4+6=10
6+4=10
4+7=11
7+4=11
4+8=12
8+4=12
4+9=13
9+4=13
5+5=10
5+6=11
6+5=11
5+7=12
7+5=12
5+8=13
8+5=13
5+9=14
9+5=14
6+6=12
6+7=13
7+6=13
6+8=14
8+6=14
6+9=15
9+6=15
7+7=14
7+8=15
8+7=15
7+9=16
9+7=16
8+8=16
8+9=16 - error
9+8=17
9+9=18
Errors: 0.01
```
