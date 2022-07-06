<p align="center"><img height = "150px" width= "500px" src="https://bit.ly/3nIMsKt"/></p>
<h1 align="center">JavaScript Marathon Assignment</h1>

## Day-2

<details>
<summary>What is lexical structure?</summary><b>
→ Lexical structure is the basic syntax for writing any programming language. It is also considered as the lowest level syntactical structure which needs to be follwed.
Some lexical structure rules in JavaScript are:

1.  JS is written in UNICODE(it is an international standard for character encoding).
2.  JS is a case-sensitive language.
3.  Using semicolons is optional in JS, as it adds semicolons behind the scenes by `Automatic Semicolon Insertion` technique.
4.  There are two types of comments present in JS:
    - Single Line Comment(// THis is a comment)
    - Multi-Line Comment(/_ This is a comment _/)
5.  Whitespaces, Line breaks, and Comments are ignored whit executing.
6.  A variable name can only start with a letter, the dollar sign($), or an underscore \_.
7.  There are reserved keywords and future reserved keywords which cannot be used as a variable name.
    </b></details>
    <br>

<details>
<summary>What is Unicode?</summary><b>
→ Unicode is an international standard for character encoding. 
It assigns a unique code to every character known as a `code point`.
This helps to identify characters more easily and with fewer chances of errors.
</b></details>
<br>

<details>
<summary>Explain all the keywords present in the JavaScript with examples.</summary><b>
  
  <center>
    <table>
      <tr>
     <td align="center"><button/><br/><b>await</b></button></td>
     <td align="center"><button/><br/><b>break</b></button></td>
     <td align="center"><button/><br/><b>case</b></button></td>
     <td align="center"><button/><br/><b>catch</b></button></td>
     <td align="center"><button/><br/><b>class</b></button></td>
     <td align="center"><button/><br/><b>const</b></button></td>
    </tr>
     <tr>
     <td align="center"><button/><br/><b>continue</b></button></td>
     <td align="center"><button/><br/><b>debugger</b></button></td>
     <td align="center"><button/><br/><b>default</b></button></td>
     <td align="center"><button/><br/><b>delete</b></button></td>
     <td align="center"><button/><br/><b>do</b></button></td>
     <td align="center"><button/><br/><b>else</b></button></td>
    </tr>
     <tr>
     <td align="center"><button/><br/><b>else</b></button></td>
     <td align="center"><button/><br/><b>enum</b></button></td>
     <td align="center"><button/><br/><b>export</b></button></td>
     <td align="center"><button/><br/><b>extends</b></button></td>
     <td align="center"><button/><br/><b>false</b></button></td>
     <td align="center"><button/><br/><b>finally</b></button></td>
    </tr>
     <tr>
     <td align="center"><button/><br/><b>for</b></button></td>
     <td align="center"><button/><br/><b>function</b></button></td>
     <td align="center"><button/><br/><b>if</b></button></td>
     <td align="center"><button/><br/><b>implements</b></button></td>
     <td align="center"><button/><br/><b>import</b></button></td>
     <td align="center"><button/><br/><b>in</b></button></td>
    </tr>
     <tr>
     <td align="center"><button/><br/><b>instanceof</b></button></td>
     <td align="center"><button/><br/><b>interface</b></button></td>
     <td align="center"><button/><br/><b>let</b></button></td>
     <td align="center"><button/><br/><b>new</b></button></td>
     <td align="center"><button/><br/><b>null</b></button></td>
     <td align="center"><button/><br/><b>package</b></button></td>
    </tr>
     <tr>
     <td align="center"><button/><br/><b>private</b></button></td>
     <td align="center"><button/><br/><b>protected</b></button></td>
     <td align="center"><button/><br/><b>public</b></button></td>
     <td align="center"><button/><br/><b>return</b></button></td>
     <td align="center"><button/><br/><b>super</b></button></td>
     <td align="center"><button/><br/><b>switch</b></button></td>
    </tr>
     <tr>
     <td align="center"><button/><br/><b>static</b></button></td>
     <td align="center"><button/><br/><b>this</b></button></td>
     <td align="center"><button/><br/><b>throw</b></button></td>
     <td align="center"><button/><br/><b>try</b></button></td>
     <td align="center"><button/><br/><b>true</b></button></td>
     <td align="center"><button/><br/><b>typeof</b></button></td>
    </tr>
     <tr>
     <td align="center"><button/><br/><b>var</b></button></td>
     <td align="center"><button/><br/><b>void</b></button></td>
     <td align="center"><button/><br/><b>while</b></button></td>
     <td align="center"><button/><br/><b>with</b></button></td>
     <td align="center"><button/><br/><b>yield</b></button></td>
    </tr>
    </table>
  </center>

</b></details>
<br>

<details>
<summary>What are shorthand operators, explain with a suitable example?</summary><b>

→ Shorthand operators are a combination of assignments with arithmetic or bitwise operators, this helps to keep the code compact.
Some of the Shorthand operators and their applications are shown below:

1. +=

```bash
        let a = 10;
        a += 5;
        console.log("Value is: " + a);
```

```bash
 Value is: 15
```

2. -=

```bash
        let a = 10;
        a -= 5;
        console.log("Value is: " + a);
```

```bash
 Value is: 5
```

3. \*=

```bash
        let a = 10;
        a *= 5;
        console.log("Value is: " + a);
```

```bash
 Value is: 50
```

4. /=

```bash
        let a = 10;
        a /= 5;
        console.log("Value is: " + a);
```

```bash
 Value is: 2
```

5. %=

```bash
        let a = 10;
        a %= 5;
        console.log("Value is: " + a);
```

```bash
 Value is: 0
```

</b></details>
<br>

<details>
<summary>What is “use Strict” in JavaScript?</summary><b>
→ Strict Mode is a new feature in JavaScript introduced in ES5, which
allows executing a function or script in Strict Mode.

This Mode can be applied by just adding "use strict" at the beginning of a function or a script.

This mode can be used to write safe code using the below properties:

1.  Using "Strict Mode" prohibits the use of syntaxes which later going to be introduced in EcmaScript.

    ### Example:

    It doesn't allow to use of 'arguments', 'eval', 'with' keywords to use as an identifier.

    ```bash
                "use strict"

                let arguments = 90;
                console.log(arguments);
                //Will throw an error

    ```

2.  "Strict Mode" eliminates some JS silent errors and throws errors.

    ### Example:

    Instead of creating a new global variable, it throws an error if an undeclared variable/mistyped variable is assigned a value.

    ```bash
                "use strict"

                x= 12;
                //Will throw an error
    ```

3.  It prohibits or throws errors when unsafe action is taken.

    ### Example:

    This mode doesn't allow deleting objects or variables.

    ```bash
                    "use strict"

                delete Object.prototype;
                //Will throw an error

    ```

</b></details>
