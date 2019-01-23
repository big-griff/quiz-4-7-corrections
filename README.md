# quiz-4-7-corrections
totally corrections


# Quiz 4
1. correct answer:
```let hours = prompt("Enter the number of hours worked this week.", 40);```
This answer is correct because the question asked how to have somebody input the hours worked that week, but otherwise default to 40.

7. wrong answer: -1
-1 is not a falsey value because only nil, null, and false pointers are falsey. Anything else is truthy.

9. wrong answers: floating point, character, integer
These are not valid data points in Javascript.

10. correct answer: const PI = 3.14;
while const pi is correct, const PI is more correctly formatted according to Javascript convention.

# Quiz 5
1. wrong answers: =, !=, >, !==, >=, ==, <, <=
The above are RELATIONAL operators, not LOGICAL operators.

2. correct answer: false, true
"!!" can be taken to mean "not not" which would return "true".

3. wrong answers: ||, &&
I seem to have gotten my logical and relational operators mixed up somewhere.

4. correct answer: a < b && a < c
c > a || c > b
The results are not definite, so an "or" operator is more appropriate than an "and" operator.

5. correct answer: x === y
x !== y
I used the wrong form of equals operator.

7. It is correct syntax to include a "break;" after declaring a case.

9. A switch statement not the simplest way to solve this problem. Rather, if-statements get the job done quicker and easier.

10. Brackets can also go below the statement.

12. There is no need to repeat the setup phase.

13. I forgot the opening bracket.

15. Both -- and ++ accomplish the task.

# Quiz 6
2. There is no reason for a error to occur unless one of the parameters is actually buggy and will make the code break. Otherwise, they are just ignored.

4. The problem doesn't ask for input, only that it accepts the values being divided as parameters.

5. subtract requires parameters, simply calling the function doesn't work.

6. prompt and Math.random return values, alert and console.log only display them.

8. I still can't figure this one out

10. There is no stop condition for either snippet of code, so they will run indefinitely.

14. If d is undefined, that will be shown in the console.

15. Still can't brain this one out

# Quiz 7
1. Can't remember

3. A for...of loop iterates over iterable objects like arrays, while for...each does not.

5. ```cars.indexOf(car) !== -1``` and ```cars.lastIndexOf(car) !== -1``` are also correct.

7. 0 and 1 were correct because an index[0] and so forth is how you display the referenced objects.

9. i=0, so it will display from zero up.

11. ```for (let item of list) {
   ``` console.log(item);```
   } also works.
   
12. Referencing an index can be thought of as referencing x+1 within the index.

13. ```numbers.push``` is incorrect, ```numbers.add``` is correct.

14. can't figure this one out

15. ```a,b,c``` and ```1,2,3``` are also valid.



