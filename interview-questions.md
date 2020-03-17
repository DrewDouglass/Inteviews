# General Knowledge Questions:

Please write your answers in the code blocks.

**NOTICE:** Some (but not all) questions may be easier to answer with code or pseudocode. As an example, all of these are an acceptable answer to the question "How do you iterate a variable in PHP?"

```
$number++;
```

```
num = num + 1
```

```
variable "num" now equals "num" + 1
```

---

## Section: PHP

1. How do you get information from a form that is submitted using the "get" method?

```
Use the $_GET super global and the array of the param $_GET['CH']
Would be prudent to filter any and all incoming input from users.
```

2. What is the correct way to create a function in PHP?

```
<?php
    function college_hunks($arg=true) {
        if($arg) {
            return "Hi team!";
        }
        return "Hey.";
    }
?>
```

Can also create anonymous functions in later versions of PHP.

3. Name a method to output an array?

```
var_dump() or print_r(), you could also loop through it and echo what is needed or encode it in something human readbale like JSON and dump that. Or just use a php debugger/inspector.
```

4. Which operator is used to check if two values are equal and of same data type?

```
triple equals, strict check comparison. "Drew" === "Drew" //true
```

5. Which superglobal variable holds information about headers, paths, and script locations?

```
$_SERVER and it's array values.
```

6. Explain how `static function` works in PHP class methods.

```
A static function is a method of a class you can call, ie, class::CollegeTest() without initiating an object of the class. Basically, it allows a convienent way to call a certain method without needing the object first (like so -> $obj->CollegeTest())
```

7. What is the commonly used library for database connections?

```
mysqli, PDO, or one of many 3rd party ORMs
```

8. What is the commonly used library for making requests?

```
cURL, for extremely simple requests, file_get_contents()
```

9. What is PHP function strlen?

```
It stands for string length and well, it gets the length of a string. Not zero based. The manual suggests caution when dealing with non english characters and mb_strlen may be better suited.
```

## Section: SQL

For the below questions, assume you are using this table (named `Persons`):

| Id  | FirstName | LastName  |
| --- | --------- | --------- |
| 1   | Peter     | Jackson   |
| 2   | Adam      | Savage    |
| 3   | Linus     | Sebastian |
| 4   | Brent     | Spiner    |
| 5   | Doom      | Guy       |

1. How would you select just the first record and only the column `FirstName`?

```
(Code off the top of my head, semi-pseudo)
FROM Persons SELECT FirstName WHERE Id = 1
```

2. How would you select all the records where the `FirstName` is "Peter" and the `LastName` is "Jackson"?

```
(Code off the top of my head, semi-pseudo)
FROM Persons SELECT * WHERE FirstName = Peter and LastName = Jackson
```

3. How would you select all the records where the `LastName` starts with an "s"?

```
[Put Your Answer Here]
```

4. How would you select all the records where the `FirstName` is alphabetically between "Brent" and "Linus"?

```
[Put Your Answer Here]
```

5. How would you insert the name "David Tennant"?

```
[Put Your Answer Here]
```

6. How would you change all the records where the `FirstName` is equal to "Peter" into "Samuel"?

```
[Put Your Answer Here]
```

7. How would you delete the records where the `LastName` is "Sebastian"?

```
[Put Your Answer Here]
```

8. How would you get the number of records in the `Persons` table?

```
[Put Your Answer Here]
```

9. Give an example of how would you join 2 related tables together?

```
[Put Your Answer Here]
```

## Section: Vanilla Javascript

1. How do you create a function in JavaScript?

```
[Put Your Answer Here]
```

2. How do you call a function named "myFunction"?

```
[Put Your Answer Here]
```

4. How to write an IF statement for executing some code if "i" is NOT equal to 5?

```
[Put Your Answer Here]
```

5. How does a WHILE loop start?

```
[Put Your Answer Here]
```

6. How does a FOR loop start?

```
[Put Your Answer Here]
```

7. How do you round the number 7.25, to the nearest integer?

```
[Put Your Answer Here]
```

8. What will the following code return: Boolean(10 > 9)

## Section: jQuery

1. Can jQuery animate() method can be used to animate ANY CSS property?

```
[Put Your Answer Here]
```

2. Which jQuery method is used to hide selected elements?

```
[Put Your Answer Here]
```

3. Which jQuery method is used to perform an asynchronous HTTP request?

```
[Put Your Answer Here]
```

4. Look at the following selector: \$("div p"). What does it select?

```
[Put Your Answer Here]
```

## Section: React

1. What is JSX?

```
[Put Your Answer Here]
```

2. What triggers a render cycle?

```
[Put Your Answer Here]
```

3. What is a React Hook?

```
[Put Your Answer Here]
```

4. Which method in a React Component should you override to stop the component from updating?

```
[Put Your Answer Here]
```

5. Which method in a React Component is called after the component is rendered for the first time?

```
[Put Your Answer Here]
```

6. What happens when you call setState() inside render() method?

```
[Put Your Answer Here]
```
