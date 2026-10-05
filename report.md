The program calculates the factorial of a number. It gets input from register X and stores the result in register Z.

Set Z to 0. While X is not zero, multiply Z by X, subtract 1 from X.

Trace table for X = 5:

Pass | X at entry | action (line 6-7)    | Z after | X after (line 10)
1    | 5          | Z = 1 * 5            | 5       | 4
2    | 4          | Z = 5 * 4            | 20      | 3
3    | 3          | Z = 20 * 3           | 60      | 2
4    | 2          | Z = 60 * 2           | 120     | 1
5    | 1          | Z = 120 * 1          | 120     | 0
6    | 0          | JMZ 12 fires -> exit | 120     | 0

AI was not used during this exercise.