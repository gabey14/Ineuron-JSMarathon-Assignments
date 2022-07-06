<p align="center"><img height = "150px" width= "500px" src="https://bit.ly/3nIMsKt"/></p>
<h1 align="center">JavaScript Marathon Assignment</h1>

## Day-3

<details>
<summary>List all the Escape Sequences characters in javascript.</summary><b>

→ Escape sequence characters are used to encode special characters in a strings.

#### Escape sequences characters are:

    - \' :- Used to denote single quotes in the string.
    - \" :- Used to denote double quotes in the string.
    - \n :- Used to escape to new line.
    - \t :- Use to denote a TAB space.
    - \v :- Vertical TAB
    - \r :- carriage return
    - \b :- backspace
    - \f :- form feed

</b></details>
<br>

<details>
<summary>Explain with example length and substring methods in javascript.</summary><b>
    
### length
    
`length` is a property of the String. A prototype object which reflects the `length` of the string.
    
```bash
    let message = 'Hello my name is Abey George.';
    console.log(message.length);
```
    
     Output: 29

### substring()

`substring()` method returns the string between start and end indexes.

- Note - first index(indexStart) is `inclusive` while the last index(indexLast) is exclusive`.

```bash
    const str = 'Hitesh';

    console.log(str.substring(1, 3));

    console.log(str.substring(2));

```

    OutPut: it
            tesh

</b></details>
<br>

<details>
<summary>What are padStart and padEnd in javascript, explain with an example.</summary><b>
    
### padStart()
    
`padStart()` pads/adds the given string from start to other string until it reaches its given length.

## Syntax

    padStart(targetLength)
    padStart(targetLength, padString)

```bash

'Abey'.padStart(10);         // "      Abey"
'Abey'.padStart(10, "foo");  // "foofooAbey"
'Abey'.padStart(6,"123465"); // "12Abey"
'Abey'.padStart(8, "0");     // "0000Abey"
'Abey'.padStart(1);          // "Abey"
```

NOTE: if the given length is less than the given string then the original string is returned.

### padEnd()

`padEnd()` pads/adds the given string from end to other string until it reaches its given length.

## Syntax

    padEnd(targetLength)
    padEnd(targetLength, padString)

```bash

'Abey'.padEnd(10);         // "Abey      "
'Abey'.padEnd(10, "foo");  // "Abeyfoofoo"
'Abey'.padEnd(6,"123465"); // "Abey12"
'Abey'.padEnd(8, "0");     // "Abey0000"
'Abey'.padEnd(1);          // "Abey"

```

NOTE: if the given length is less than the given string then the original string is returned.

</b></details>
<br>

<details>
<summary>Define Global Object in javascript along with the global scope.</summary><b>

### Global Object:-

→ Global objects are the objects which provide functions and variables that can be used anywhere in the environment. In browsers, the global object is known as a `window` while in the `Node` environment it is 'global'. This global object came inbuilt into the languages/environments. Any variables or functions declared using `var` becomes a property of the `Global object`.<br>
`gobalThis` is the standard name for the global object and is supported by almost every environment.

### Global Scope:-

- The scope is accessible from everywhere in the `global scope`.
- variables that are declared globally have global scope.
- variables declared using `var` has global scope.
  </b></details>
  <br>

<details>
<summary>List all the names of Javascript engines present currently. </summary><b>

→ Some of the notable JavaScript engines are:

- V8 - Used and developed by `Chrome Browser`.
- Spider Monkey - Used in `firefox Browser` and developed by `Mozilla`.
- JavaScriptCore - It is `Apple's` engine for its `Safari browser`.
- Chakra - It is the engine of the `Internet Explorer browser`.
  </b></details>
