# Video 1
- Oletuksena että on vähän tietoa jostain koodauskielestä. 
- Kaikki videot voidaan katsoa missä järjestyksessä vaan. Kaikkien viedoitten tekijät esiteltään.

# Video 2
- designed to interact with elements in a web page (buttons)
- you dont need to compile it or build it beforehand, you can just run it.
- why learn javascript? javascript is found everywhere, most used programming  language in the world.

# Video 3
- JS on client, means JS in browser. You want to put JS in different file than html. use src script to load javascript when that page is active. DOM is the functions and objects that JS has access to in the web browser.
- Server side, reading files reading databases need something called node JS. then execute it through terminal. DOM does not exist here. You get packages instead, some are built in with node and there are third party packages (NPM) for almost anything.

# Video 4
- You can sue Visual studio code to write JS and download extensions to support you. All languages are present in VSC.
- Node JS, used to execute JS script outside of browser. Even if you plan to write in browser, node JS works there too. Use NVM to install and update node JS, for windows without WSL differnet tool than mac or linus.

# Video 5
- A tutorial on how to install nvm into your VSC. And how to make updating it easier by adding it into bash profile.

# Video 6
-How to make your first application with Node. You can use single or double quotes. You can assign variables for your text too, and they showed different ways of implementing it into your code. 

# Video 7
- Commenting your code, either single line // or multiline start/* */stop. When to use it and how to use it, you dont need as many as you think at the start. Getting rid of non necessary commenting by naming functions with what they do. 

# Video 8
- Commenting code makes it grey. Can give usefull information. Use a keyword, for example TODO. You can search TODO (or whatever keyword you use) and see what you still have undone.
- cmd/ctrl + / comments a line or lines out / in. Remember to use code only when needed, if you can implement commenting into code do that! ex: naming function!

# Video 9
- Three ways to declare variable, var let and const. 
- var is available during whole function (even if you declare it not on line 1).  
- Let is block scoped {}, only after declaration from your declaration line ->. Use in loops !
- const block scoped {}, only assigned once, cant reassign. Use by default!

# Video 10
- var makes the variable available, And you might try to use it before its been assigned (without errors!).
- If you try to print something with let before assigning it you will get a error. Good to use in loops since it can be changed in a block scope
- const cant be reassigned in its scope. Use as default if possible. Easier to follow code, reader knows it should only be used once. 

# Video 11
- How string concantanetion works in code, and a understanding of how numbers and letters are written. use + to do it.

# Video 12
- Can add spacing to variable directly or manually when combining strings later on. Cant add a number and string, need to be carefull. or might get wrong / confusing answers. 

# Video 13
- Differences in concatenation and template literals.
- Placeholders in template literals

# Video 14
- template `${xxxx}`, a template need backticks. Dont need to worry about converting strings or numbers.

# Video 15
- Weakly typed language compared to c# for example. Simple language.  typeof, instanceof. 
- use === to do type testing. 

# Video 16
- Typeof testing with array returns object. BE CAREFUL.
- instanceof returns true /false
- need to chose right way of testing, depending on what your code needs to do. 

# Video 17
- increment and decrement ++ --, % remainder
- Math object, Math.PI, Math.squrt(xxx)

# Video 18
- increment and decrement ++ --, % remainder
- Math object, Math.PI, Math.squrt(xxx)

# Video 19
- parseint() parseint ignores numbers after a decimal, parsefloat() for decimal numbers, tostring() numbers to string..
- using letters can give nan or JS can interpet them as hexadecimal numbers.

# Video 20
- Showing examples of converting strings to numbers and what kind of results or errors those give.
- Showing some special cases and explains why they happen. 

# Video 21
- errors in code, can be from javascript or the developer himself. Try Catch Finally.

# Video 22
- Code after error does not get printed to the console. Finally will always run!
- log errors!! 

# Video 23
- new date(). month counting starts from 0! year month day hour min sec.
- set and get, Month Time Day...

# Video 24
- date is based on UTC, not your own timezone! Supporting material for more info on dates, if interested

# Video 25
- == checkts fo equality regardless data type, === checks equal value and data type. Should use ===!. != and  !==
- can skip {} in if statements if you want. Ternary statement!! (one liner)

# Video 26
- important to use === so it checks data type and value!!! When checking values!
- For quick simple checks, ternary check can be cleaner and shortens code

# Video 27
- when comparing strings, convert to upper or lowercase for comparison. 
- & && and | ||. most times use && and ||
- switch statements always checks for equality, not less than or more than. BREAK STATEMENTS!

# Video 28
- try to avoid ! (not operators) to keep code more simple and readable.

# Video 29
- create with [] or Array() give length in paranthesis either a number or variable that has a number!

# Video 30
- same as 29

# Video 31
- Can add data when creating the array or after. Index in array starts at 0!
- Last item in array is length-1! if something is not at that index in array prints undefined

# Video 32
- when adding data to array at creating, put it inside [], indexes separated by ",".

# Video 33
- array.push() array.pop(), array.shift() array.unshift(), 
- concat join arrays, arr1.concat() 2nd array in paranthesis or arr1.concat() and insert new values in parenthesis

# Video 34
- when joining arrays, we make a completly new array!

# Video 35
- while, for , for of. <--- Most commonly used
- remember to increase starting value in loops, so it does not run forever! value++
- for of loop is same as foreach in c#, javascript foreach loop works a bit differently!

# Video 36
- Visual studio code has ready snippets of code you can get with starting the for and finding the right loop you want and pressing tab!

# Video 37
- functions are very good if you want to use the same block of code in multiple places. And if you make a change to your pricing for example you just need to change original block of code!
- dont name function with special characters.

# Video 38
- How to pass parameters into functions, what errors we get when it goes wrong.

# Video 39
- arrow function. It needs to be assigned to a variable.
- works as return, if you give it 2 numbers and have => a + b; it would return the sum of those. 
- inherited from its parent scope

# Video 40
- Single line arrow function returns automatically. Can create arrow functions across multiple lines too! then use return keyword!

# Video 41
- json is lightweight data exchange format. language independant and user readable. 
- for multi item arrays [] and single objects in {}

# Video 42
- JSON stringify is a method that takes a object or objects and returns back a stringified version of it
- JSON.parse to return it to a object or array!

# Video 43
- objects created with constructors work same as literals!
- Can access specific areas of the object and even change them!
- check function on object with name.method()'
- globalThis, to reference global object always!

# Video 44
- properties are name value pairs separated by commas. Can represent data (properties) or methods. 

# Video 45
- promise is a cleaner version of callbacks. return new Promise() call resolve when success and reject when operation fails
- .then() 

# Video 46
- setTimeout(resolve, ms) call function, .then(( => sucess))  .catch(( => error))
- can setup callout and then a new callout to next by doing .then return promiseTimeout(1000) and .then to call next callback and so forth...

# Video 47
- async/await standard in many languages. async to indicate it will have a wait call inside function await.
- return 42; same as Promise.resolve
- erros can be caught with try/catch, that we are familiar with already!

# Video 48
- cant use await if not inside a async function.
- await will block execution, but allow the thread to be used by something else in the background! If something else can / needs to happen

# Video 49
- packages is reusable bundles of code or assets. Libraries tools.. also called dependencies or modules
- NPM place to find packages, more than 1million!
- full functional webserver can be built with less than 10 lines of code! with packages
- package.json    npm init   npm install <package_name>

# Video 50
- dependencies and devdependencies
- showed how to install packages, and how to get them working as scripts. And what we should not commit to github, and keep for ourself

# Video 51
- Link to github, and some starting assignments if you want to put your knowledge to use. Easier to remember stuff when you use it also!