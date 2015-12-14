# JavaScript Style Guide
Conventions and rules for use in JavaScript programming.

## Content
  1. [Authors](#authors)
  1. [Indentation](#indentation)
  1. [Statement Rules](#statement-rules)
  1. [Variables](#variables) 


## Authors.

![José De Ita](https://avatars3.githubusercontent.com/u/12465470?v=3&s=30) [José De Ita]

![Harimio](https://avatars3.githubusercontent.com/u/12465425?v=3&u=d0d7b2461c31cb2bc17a44e2dd64d18439e0bca0&s=30) [Harimio]

[José De Ita]: <https://github.com/josedeita>
[Harimio]: <https://github.com/harimio>

## Indentation.
- The unit of indentation is fours spaces.

## Statement Rules.

- Avoid lines longer than 80 characters. When a statement will not fit on a single line, it should be break it after an dot `.` or a comma `,` in these cases the next line should be indented with 8 spaces.

- All sentences in JavaScript should be terminated with semicolon `;`.

- All sentences: `if` / `else` / `for` / `while` / `try`  Should have braces `{ }` and always go on multiples lines.

## Variables.

- All variables should be declared before used and should be declared with `var` sentence.

 ```
 var foo = 'Hello World!'; 
 ```

  **Reason:** When you fail in the declaration with var sentence, this variable gets placed in the global context (window). Remember, we want to avoid polluting the global namespace.

- Declare only one variable per line and should be listed alphabetical order if possible.
 ```
 var foo = 'Hello World!'; 
 var bar = 'Hasta la vista Baby!'
 ```

  **Reason:** This is helpful when others read the code.

- All variables should be declared with the convention lowerCamelCase.

 ```
 var someVariable = 'A content here'; 
 var otherVariableName = 'Namaste;'
 ```

  **Reason:** This is helpful when others read the code.

