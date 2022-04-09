# If Statement

## **Challenges**

### Challenge 1
```
The given number is positive or not?.
```
### Challenge 2
```
Program to find the greatest of Two numbers.
```
### Challenge 3
```
Program to find the greatest of Three numbers.
```
### Challenge 4
```
The Program to check which number is even or odd?
```
### Challenge 5
```
A Program to check letter whether it is a vowel or not? 
using else if statement.
```
### Challenge 6
```
get the exact day of the week with the else if statement.
using Date() function.
expected out put is:- "this is a Sunday", "this is a Monday" etc.
```
## **Key Notes**

<details>
  <summary>Hint</summary>

## **If Statement**

`if` statement is used to execute the code whether condition is true

Syntax
  ```js
    
    if(expression)//true block  in single line

    if(expression){  
        // true block  
        // multi line
        // ...
    }  

    if(expression){  
        // true block  
        // ...
        if(expression){  
         // true block  
        }  
        // ...
    }  
  ```
  
  Strategy - 1
  ```js
    const result = 10 > 6;
    if(result)//content to be evaluated  single line
  ```

  Strategy - 2
  ```js
    const result = 10 > 6;
    if(result){
        // content to be evaluated...
        // multi line...
        // ...
    }
  ```
 Strategy - 3
  ```js
    if(10 > 6){
        // content to be evaluated...
        // multi line...
        // ...
    }
  ```
  ## **If Else If Statement**

  `if-else` statement is used to execute the code whether condition is true or false.
  Syntax
  ```js
    if(expression){  
        // true block
        // ...
    } else {
        // false block
        // ...
    } 
  ```
  ## **If Else Statement**

  `if-else-if` evaluates the content only if expression is true from several expressions.
  Syntax
  ```js
    if(expression1){  
        //content to be evaluated if expression1 is true  
    }  
    else if(expression2){  
        //content to be evaluated if expression2 is true  
    }  
    else if(expression3){  
        //content to be evaluated if expression3 is true  
    }  
    else{  
        //content to be evaluated if expression is false  
    }  
  ```

</details>

## **NB**
consider all `edge` cases.
## **References**

[variables](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics#variables)

[operators](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics#operators)

[Conditional Statements](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling#conditional_statements)

[Date()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/getDate)