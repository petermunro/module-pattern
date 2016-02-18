# Lab 4

## Module Pattern

To emulate a simple hand-held calculator, create some calculator functions: `add`, `subtract`, and `multiply`. Also have three 'memory' functions to save results:

    add(2, 9);                              // 11
    memoryStore(add(2, 9));
    memoryAdd(5);
    var storedResult = memoryRetrieve();    // 16


1.	Using the [classic](https://www.christianheilmann.com/2007/08/22/again-with-the-module-pattern-reveal-something-to-the-world/) Module pattern, wrap your code in a module.
2.	Now call this code from outside the module.

### Revealing Module Pattern

1.	Refactor your code to use the [Revealing Module](https://www.christianheilmann.com/2007/08/22/again-with-the-module-pattern-reveal-something-to-the-world/) pattern. What changes?


### Mountain Trail

1.	In pairs, perform code reviews on each others’ JavaScript code, with a view to modularizing it.
2.	Refactor your code to reflect the results of the code review.
3.	Install a local web server (eg `npm install http-server –g`), and serve your codebase from it.
4.	How many HTTP requests are made to the server for your app? Explore this using the Network tab in browser developer tools.
5.	Write down your results.

### Stretch Tasks

1.	In Chrome devtools, emulate slow network connectivity using throttling.
    To do this, open devtools, hit ESC (or select 'Show console' from the devtools menu),
	and go to 'Network Conditions'. Select a slower speed so you can see what some
	mobile devices may experience. Monitor network traffic ('Network' tab) and view the results.
1.	What do AMD and CommonJS modules offer beyond the JS module patterns?
1.	Research ES6 modules. Which platforms support them?
1.	Write some code that uses ES6 modules. Using Babel.js, compile it down to ES5 and run it.
