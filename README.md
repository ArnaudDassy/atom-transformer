# Transformer package

Transformer is package that allow you to execute small modifications on words on numbers.

## 1. Upper Case

  Shortcut : ``` ctrl-alt-shift-u ```

  >Make all letter of a word or a sentence in upper case mode

  ```javascript
var s = "JavaScript syntax highlighting";
// Upper Case
// s =  "JAVASCRIPT SYNTAX HIGHLIGHTING"
```

## 2. Word Invert

  Shortcut :   ``` ctrl-alt-shift-i ```

  >Inverse the position of two selected words

  ```javascript
var s = "JavaScript syntax highlighting";
// Word Invert
// s =  "highlighting syntax JavaScript"
```

## 3. Word Reverse

  Shortcut :   ``` ctrl-alt-shift-r ```

  >Reverse the order of a word's letters

  ```javascript
var s = "JavaScript syntax highlighting";
// Word Reverse
// s =  "tpircSavaJ syntax highlighting"
```

## 4. Word Wave

  Shortcut :   ``` ctrl-alt-shift-w ```

  >Switch a letter on two on upper case

  ```javascript
var s = "JavaScript syntax highlighting";
// Word Wave
// s =  "jAvAsCrIpT sYnTaX hIgHlIgHtInG"
```

## 5. Word Shuffle

  Shortcut :   ``` ctrl-alt-shift-s ```

  >Shuffle randomly the letter of a word

  ```javascript
var s = "JavaScript syntax highlighting";
// Word Shuffle
// s =  "crapivtSaJ syntax highlighting"
```

## 6. Calculate
  Shortcut :  ``` ctrl-alt-shift-e ```

  >Calculate the selected operation(s)

  ```javascript
var s = "The result is equal to 8+8/3*9+9*5";
// Calculate
// s =  "The result is equal to 285"
```

  > NB : The tools clean unwanted spaces or letters, for example 6a 89+7e4/   2, will be evaluate as  689+74/2 and result 381.5

## 7. Camel Case Mode

  Shortcut :   ``` ctrl-alt-shift-c ```

  >Combine several following and selected words, deleting spaces and put the first letter of each word in upper case mode

  ```javascript
var s = "JavaScript syntax highlighting";
// Camel Case
// s =  "javascriptSyntaxHighlighting"
```

## 8 Underscore Case Mode

  Shortcut :   ``` ctrl-alt-shift-v ```

  >Combine several following and selected words, deleting spaces and separate each word with and underscore

  ```javascript
var s = "JavaScript syntax highlighting";
// Underscore Case
// s =  "javascript_syntax_highlighting"
```
