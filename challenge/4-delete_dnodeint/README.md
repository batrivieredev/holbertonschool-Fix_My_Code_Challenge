## Requirements

### General

*   Allowed editors: `vi`, `vim`, `emacs`
*   All your files will be compiled on Ubuntu 20.04 LTS
*   All your files should end with a new line
*   A `README.md` file, at the root of the folder of the project is mandatory

## Tasks

### 1.

Please take a look at my implementation of FizzBuzz in Python: [source code](https://github.com/hs-hq/0x00-Fix_My_Code_Challenge/blob/main/0-fizzbuzz.py "source code")

Something is going wrong….
```
$ ./0-fizzbuzz.py 50
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 Fizz 16 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz 26 Fizz 28 29 Fizz 31 32 Fizz 34 Buzz Fizz 37 38 Fizz Buzz 41 Fizz 43 44 Fizz 46 47 Fizz 49 Buzz
$
```
`15` should print `FizzBuzz` not `Fizz`



### 2.

Please take a look at my implementation of printing a square in Javascript: [source code](/rltoken/lPV5IG2ZGg1phTLaGqXWlA "source code")

Something is going wrong….
```
$ ./1-print\_square.js 4
####
####
####
####
$ ./1-print\_square.js 10
################
################
################
################
################
################
################
################
################
################
################
################
################
################
################
################
$
```
`./1-print_square.js 10` should print a square of size 10…



### 3.

Please find here my implementation of sorting arguments in Ruby: [source code](/rltoken/ajP4dKdGc1c4GC8mFBr2RQ "source code")

Something is going wrong….
```
$ ruby 2-sort.rb 12 41 2 C 9 -9 31 fun -1 32
31
32
12
41
2
9
-9
-1
$
```


### 4.

Please find here my implementation of a User class in Python: [source code](https://github.com/hs-hq/0x00-Fix_My_Code_Challenge/blob/main/3-user.py "source code")

Something is going wrong….
```
$ ./3-user.py
Test User
is\_valid\_password should return True if it's the right password
$
```
My tests should not print any error…



### 5.

Please find here my implementation of a Double linked list in C: [source code](/rltoken/-Zr7inxNUNe0vnyv3SIjMg "source code")

Something is going wrong….
```
$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 main.c free\_dlistint.c print\_dlistint.c add\_dnodeint\_end.c delete\_dnodeint\_at\_index.c -o delete\_dnodeint
$ ./delete\_dnodeint
0
1
2
3
4
98
402
1024
-----------------
0
1
2
3
4
0
402
1024
-----------------
1
2
3
4
0
402
1024
-----------------
2
3
4
0
402
1024
-----------------
3
4
0
402
1024
-----------------
4
0
402
1024
-----------------
0
402
1024
-----------------
402
1024
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
$
```
It doesn’t look right…
