<p align="center"><img height = "150px" width= "500px" src="https://bit.ly/3nIMsKt"/></p>
<h1 align="center">JavaScript Marathon Assignment</h1>

## Day-1

<details>
<summary>Explain the use of JavaScript ( or What you can do using a JavaScript)</summary>
<b>
→ Javascript is a high-level programming language that can be used for full-stack web development for various platforms.
But originally JS was developed for enhancing the frontend of a webpage and now it is enriched with a lot of functionalities(like OOPS, API DEVELOPMENT, ETC) and also become very stable and developer-friendly with time.
</b></details>
<br>
<details>
<summary>What is the difference between client-side and server-side?</summary><b>
→ Client-side means that the processing takes place on the user's personal computer. 
It requires a browser to run the scripts on the machine without involving any processing on the server. 
Server-side means that the processing of the request takes place on a web server.
</b></details>
<br>

<details>
<summary> What is Nodejs?</summary><b>
→ Nodejs is a runtime environment for Javascript. It runs on the `v8 engine` and executes JavaScript code outside a web browser.  
It is a platform for creating scalable and robust applications.
</b></details>
<br>

<details>
<summary>Explain Scope in JavaScript</summary><b>
→ In JS for every variable, function, and object there exists a scope linked with it, after which they are not reachable.

### Example:

```bash
      let a = "Can be reached throughout whole code";

        {
          let b = "Can be reached only inside this scope";
        }
```

</b></details>
<br>

<details>
<summary>JavaScript is asynchronous or synchronous.</summary><b>
→ JavaScript shows both synchronous and asynchronous behavior. 
If a less time-consuming task is executing then the execution will be done synchronously, but if a more time-consuming task kicks in the stack then JS starts showing its asynchronous behavior.
Most asynchronous JavaScript operations have two primary triggers i.e. WebAPIs and `promises``.
</b></details>
<br>

<details>
<summary>JavaScript is Single-threaded or Multi-threaded.</summary><b>
→ JavaScript is a single-threaded language because it has only one call stack and one memory heap. 
JS executes the code sequentially and function calls are get stored in the call stack. These calls are popped out of the stack when their execution is done. 
Here it behaves like a synchronous language.

But this approach can be harmful if a time-consuming task is executed.
In this case, the JavaScript engine halts the execution of the other sequential code. So to rescue JS manages these situations with the help of `WebAPI's` and `promises`.
If it finds any function which is going to take time then the time-consuming function will be handled asynchronously.
</b></details>
<br>

<details>
<summary>Explain DOM in your own word.</summary><b>
→ DOM (Document Object Model) is not a programming language. It is an API used by JS to convert the web document into nodes and objects so that it becomes easy to interact with the web page using a programming language.
In simple words, DOM provides an object-oriented representation of the web page and allows a web page to be manipulated.
</b></details>
