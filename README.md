# Return all elements of the matrix in diagonal order using Python 3
Given a matrix of M x N elements (M rows, N columns), return all elements of the matrix in diagonal order as shown.

## Case

Given a matrix of M x N elements (M rows, N columns), return all elements of the matrix in diagonal order as shown.

Input:
```
[
[ 1, 2, 3 ],
[ 4, 5, 6 ],
[ 7, 8, 9 ]
]
```
Output: [1,2,4,7,5,3,6,8,9]

so initially it goes to diagonal right up {1}.
then from 2 it goes diagonal left bottom, so {2,4}
then it goes diagonal right up, so {7,5,3}
then it goes diagonal left bottom so {6,8}
then it goes diagonal right up so {9}

Input:
```
[
[  1,  2,  3,  4,  5,  6,  7 ],
[  8,  9, 10, 11, 12, 13, 14 ],
[ 15, 16, 17, 18, 19, 20, 21 ]
]
```

Output: [ 1, 2, 8, 15, 9, 3, 4, 10, 16, …, 21 ]

Or I will describe it in image :

![](https://www.geeksforgeeks.org/wp-content/uploads/matrix_zag-zag.png)

## Usage

* If the Input like this:
```
[
[ 1, 2, 3 ],
[ 4, 5, 6 ],
[ 7, 8, 9 ]
]
```
Use this -> `solution1.py` Or use this from command prompt -> `python solution1.py`

* If the Input like this:
```
[
[  1,  2,  3,  4,  5,  6,  7 ],
[  8,  9, 10, 11, 12, 13, 14 ],
[ 15, 16, 17, 18, 19, 20, 21 ]
]
```
Use this -> `solution2.py` Or use this from command prompt -> `python solution2.py`

## Output

* If the Input like this:
```
[
[ 1, 2, 3 ],
[ 4, 5, 6 ],
[ 7, 8, 9 ]
]
```

Then Output should be like this -> `1 2 4 7 5 3 6 8 9`

* If the Input like this:
```
[
[  1,  2,  3,  4,  5,  6,  7 ],
[  8,  9, 10, 11, 12, 13, 14 ],
[ 15, 16, 17, 18, 19, 20, 21 ]
]
```
Then Output should be like this -> `1 2 8 15 9 3 4 10 16 17 11 5 6 12 18 19 13 7 14 20 21`

***Love Python? Hell Yeah!***
