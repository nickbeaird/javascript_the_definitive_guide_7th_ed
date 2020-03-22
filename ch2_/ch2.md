# Ch2 - Lexical Structure

## Ch2.1  - Text of a JS Program
- JS is case sensitive
- JS recongnizes spaces and tabs

# Ch2.2 - Comments
```javascript
// Single line comment
/* Mult0 - 
   line 
   comment

*/ 

/* Also
 * Multi
 * Line
 * Comment
*/
```

## Ch2.4 - Identifiers and Reserved Words
- Identifiers must start with a letter, _ (underscore), or $

## Ch2.5
- JS is written in Unicod.e 
- For backwards compatibility, it is best to use ASCII characters for identifiers.

## Ch2.5.1 - Unicode Escape Sequesnces
- You can use unicode for an identifier and you may have to access it via a code. Example taken from book. 

```javascript
let café = 1; // Define a variable using a Unicode character
caf\u00e9     // => 1; access the variable using an escape sequence
caf\u{E9}     // => 1; another form of the same escape sequence
```
