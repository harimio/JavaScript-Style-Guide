# JavaScript Style Guide
Conventions and rules for use in JavaScript programming.

## Content
  1. [Authors](#authors)
  1. [Indentation](#indentation)


## Authors.

[José De Ita]

[Harimio]

[José De Ita]: <https://github.com/josedeita>
[Harimio]: <https://github.com/harimio>

## 1. Indentation.
The unit of indentation is fours spaces.

## 2. Line Length.

Avoid lines longer than 80 characters. When a statement will not fit on a single line, it should be break it after an dot (.) or a comma (,) in these cases the next line should be indented with 8 spaces.

**Reason:** This generate more clean and readable code.

## 3. Variables.

3.1 All variables should be declared before used and should be declared with “var” sentence.

    var foo = ‘Hello World!’;

**Reason:** When you fail in the declaration with var sentence, this variable gets placed in the global context (window). Remember, we want to avoid polluting the global namespace.

 ---
3.2 Declare only one variable per line and should be listed alphabetical order if possible.
    
    var bar = ‘Hasta la vista baby!’;
    var foo = ‘Hello World!’;

**Reason:** This is helpful when others read the code.

---
3.3 All variables should be declared with the convention lowerCamelCase.

    var someVariable = ‘Hello World!’;

**Reason:** This is helpful when others read the code.

:D

1. ## Item 1
  1. A corollary to the above item.
  2. Yet another point to consider.
2. Item 2
  * A corollary that does not need to be ordered.
    * This is indented four spaces, because it's two spaces further than the item above.
    * You might want to consider making a new list.
3. Item 3
