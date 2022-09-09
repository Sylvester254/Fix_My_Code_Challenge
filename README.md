# Fix my code
```Debugging```
> Fix my code is a new type of project, where we’ll jump into an existing code base and fix it!

## Tasks 
- [0-fizzbuzz.py](./0-fizzbuzz.py)
Something is going wrong...
```
$ ./0-fizzbuzz.py 50
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 Fizz 16 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz 26 Fizz 28 29 Fizz 31 32 Fizz 34 Buzz Fizz 37 38 Fizz Buzz 41 Fizz 43 44 Fizz 46 47 Fizz 49 Buzz
$
```
- [1-print_square.js](./1-print_square.js)
Something is going wrong…
```
$ ./1-print_square.js 4
####
####
####
####
$ ./1-print_square.js 10
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
```./1-print_square.js``` 10 should print a square of size 10…
- [2-sort.rb](./2-sort.rb)
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
- [3-user.py](./3-user.py)
Something is going wrong….
```
$ ./3-user.py 
Test User
is_valid_password should return True if it's the right password
$
```
My tests should not print any error…
- [4-delete_dnodeint](./4-delete_dnodeint/)
-Double linked list 
Something is going wrong….
```
$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 main.c free_dlistint.c print_dlistint.c add_dnodeint_end.c delete_dnodeint_at_index.c -o delete_dnodeint
$ ./delete_dnodeint 
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