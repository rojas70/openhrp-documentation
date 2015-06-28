
There are two files corresponding two sets of results. 

7classes.mat divide the exp- and FC- data into seven classes. The list is
1. x
2. y
3. theta
4. xy
5. xtheta
6. ytheta
7. xytheta
regardless of signs of plus and minus.


12classes.mat The same as 7classes.mat. 
1. +x
2. +y
3. -y
4. +theta
5. -theta
6. x + y
7. x - y
8. x + theta
9. x - theta
10. +y + theta
11. -y + theta
12. x + y + theta

There is an array  in the .mat file containing structures. The structs have two elements: classes and comparison. Any corresponding classes and comparison in one struct shows the prediction under some specific classes and the comparison between the classes of training cases and their prediction under predictFunc. 

