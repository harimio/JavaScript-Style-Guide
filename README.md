# JavaScript Style Guide
Conventions and rules for use in JavaScript programming.

##Authors.

> [José De Ita]
> 
> [Harimio]

[José De Ita]: <https://github.com/josedeita>
[Harimio]: <https://github.com/harimio>

## Indentation.
The unit of indentation is fours spaces.

## Line Length.

Avoid lines longer than 80 characters. When a statement will not fit on a single line, it should be break it after an dot (.) or a comma (,) in these cases the next line should be indented with 8 spaces.

> **Reason:** This generate more clean and readable code.

## Variables.

All variables should be declared before used and should be declared with “var” sentence.

> **Example:**
> 
>     var foo = ‘Hello World!’;
> 
> **Reason:** When you fail in the declaration with var sentence, this variable gets placed in the global context (window). Remember, we want to avoid polluting the global namespace.
 
Declare only one variable per line and should be listed alphabetical order if possible.
> 
> **Example:**
> 
>     var foo = ‘Hello World!’;
>     var bar = ‘Hasta la vista baby!’;
> 
> **Reason:** This is helpful when others read the code.

