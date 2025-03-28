 Two ﬁnite, strictly increasing, integer sequences are given. Any common integer between the two sequences constitute an intersection point. Take for example the following two sequences where intersection points are
printed in bold:

    First= 3 5 7 9 20 25 30 40 55 56 57 60 62
    Second= 1 4 7 11 14 25 44 47 55 57 100

You can ‘walk” over these two sequences in the following way:

    You may start at the beginning of any of the two sequences. Now start moving forward.
    At each intersection point, you have the choice of either continuing with the same sequence you’re currently on, or switching to the other sequence.

The objective is ﬁnding a path that produces the maximum sum of data you walked over. In the above example, the largest possible sum is 450, which is the result of adding 3, 5, 7, 9, 20, 25, 44, 47, 55, 56, 57, 60, and 62
