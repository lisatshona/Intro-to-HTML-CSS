# INTRO TO HTML, CSS & JAVASCRIPT


HTML is a markup language used to create web pages. Hypertext defines the links between the web pages. HTML is core to front-end development work. HTML can be created using any text editor. It uses tags to structures the Web pages. Tags are used to indicate the title and the body. It has it's elements, these elements can be nested within other the elements. The elements can also have attributes. HTML is used for developing fundamentals about web programming.
Each opened tag should be closed at the end. The language uses tags to define manipulation that has been done on the text.


**HTML FORMATTING**

**HTML has 6 headlines** from h1-h6. H1 is the largest that attracts the attention of the reader, then h6 is the least important and doesn't grab much attention. To emphasize something we use Italics.
To convey a warning or highlight we use Bold words.

**HTM Lists** are important elements, we have 3 types namely ordered,unordered and definition list. Unordered lists is just a list that the order doesn't matter, each element is enclosed in then the list is wrapped to show its unorderd list. Ordered list is whereby the ordered of the list matters. Definition list is used to define terms as the word says. We use a specific tags for definition of lists. 

**HTML Quotes** are used to format a text as a quote, block quote is used to format large chuncks of text as quote and are usuallly displayed with a different background. Inline quotes format small texts as quote and are displayed with quotation marks. 

**HTML date elements** are used to display date on a web page and we use format that is understood by computer. The value attribute specifies the date to be displayed. A specific tag element is used to create a date picker and it can be used to customise the date picker. Time picker allows you to select the time of the day. Using datetime element allows you to combine both time and date ,starting with date and follows time. The datetime can be separated by leaving or T inbetween.

**HTML Code, pre and br**
Code is used to define a piece of a computer code. The content inside is displayed in the browser's default monospace font.
<br> tag inserts a single line break, it is mostly used in poems and writting addresses. It is an empty tag with no end tag.
pre tag is used to define the preformatted text which preserves the text spaces, line breaks, tabs and others that are ignored.

**HTML Superscrips, Subscripts&small text**
Superscripts is a character that is raised above the baseline more like an exponent. The tag used to create subscripts is the one lowered beyond the baseline. I can say they use characters.

**HTML Capabilities and Attributes**

They allow you to customize the appearance and functionality of your web.You can use tags to format text, create links, add images, embed videos, create tables, and more.
HTML Attributes always come in name/value which defines the properties of an element and are placed inside an element tag. Certain attributes are assigned for specific elements. ID name ensures that there is ony one element with that ID so its easy to use it and link it to Javascript. HTML has so many attributes that can be used to modify the web pages.

**ARIA Roles** are used to provide information about purpose and state of an element. This is important to users using screen readers or other assistive technology. The commonly used aria roles are buttons, links, menu, tree, lists and checkbox. Each role has it's own set  of attributes that can be used to further define the element's purpose and state.

**HTML Extra-spaces** can be very tricky but there are various ways to handle it. You can use the non-breaking space character instead of the regular space character. The non-breaking prevents browser from collapsing multiple spaces into one. Using CSS to set the white-space property to pre or pre-wrap which will prevent the browser from collapsing multiple spaces. Pre value displays text as it is in HTML source code, including multiple space. Pre-wrap value will wrap text as word boundaries, but will preserve multiple space.
Adding comments to the code makes it easier for a reader to understand the purpose of a specific line and prevent confusing if there an error.

**Navigation and Linking**

The nav tag is used to define a set of navigation links, but it is only intended for major blocks of navigation links. Not all navigation links should be inside the nav element. Links are a connection from one web source to another. It has an anchor and a direction, those are the two ends it has. The external links direct you to a source. An internal links targets a source on the same website. URL, HTTP, HTTPS must be used for communication on the web and it is neccessary for linking. 
URL is the address of a website to access the website content. They are either absolute or relative. Relative Url focus on the current's file location where's absolute start from the root of the website. CSS is used to apply the visual appearance to the menu.


**Images**

Images have 4 attributes. SRC tells browser which image to load. ALT provides the description of the image. Height and width show the size of the image. Images can be inserted using URL to access internet file or proving full path to the location of the current file. Images can be adjusted the way you want them to. Images have 4 different formats which are GIF, SVG, PNG & JPG. Responsive images will automatically adjust to fit the size of the screen. There are techniques used to make large images small but still delivering beautiful images. You are able to add a caption of your own using figcaption element. SVG can display large pictures without pixelation. You can add  chapter divisions to videos by referencing VTT file listing chapters.

**Lang element** is used to specify the language of a web page. Setting it on the main element is the best, it will apply to the whole page. Being secific about the direction is important especially if there is more than one language used, dir element is used to specify the direction.
Meta charset with is equals to UTF-8 and placed within the head element of html, this shows that there will be characters, scripts and emojis used..
Div is a block-level emement used to create sections,sidebars & everything in between. Span is inline element used to a color part of a text.

**Audio element** has openning and closing tag unlike the image element. It is used to embed sound content in documents. It may contain one audio sources or more but the browser will choose the most suitable one. 
**The video element** contains one or more source tags with different vid sources, allowing you to load, play, and pause videos as well as setting duration and volume. The text between the video tags will be displayed on the browser that do not support the video element. Video has 480p compressed using H.264 codec. Track element is used to link it to a text file and add captions to the video. Source lang attribute is used to show the language and add default attribute to make this track default when captions are enable. Chapters allow the user to jump to any part of the video. We use track element within the video element to display the caption.

**Content Identification** is the process or recognizing and categorizing different elements within an HTML webpage, this is done using html and other techniques like css. 
**Integration** is the process pf incorporating HTML code into a web page. Attributes, elements,role, tools are the ones that create the content of a web page. The head element contains all the important information that will not be displayed in a web browser then head element contains all the content. 
When searching something in a browser, the results are in HTML file, then browser will follow the instructions and give you what you want.
The head contains all the metadata that browser need to know but will not be displayed on the page. The body consist of all the content where most of action takes place.
Script element is used to load javascript file.
There are 6 important elements namely, main, head, footer, article, section, aside. They are the ones that structure the content. There is a lot of creativity when designing the webpage.

**Forms** is an html element used to input data containing interactive controls. Form element defines a form and the area where the user will enter their information. The input element allows users to enter a value like a text field, password or checkbox. The type attribute defines the type of input element and name attribute gives the input element a name. If you forget to use the type attribute to  each input it will assume that it is a text. Value attribute is differently used for different input types.

**HTML tables** are mostly used to organize and display data on a web page. Table element has tr element for rows,td element for cells, th is used to define header cell in a table and has attributes. Table Header is applied on columns and on rows, it has alignment of the conten within a cell.

**CSS**

CSS is a designed language used for styling the HTML document. CSS has a rule which consist of a selector (which points out the html element you want to style) and declaration (has property and value). The universal selector is used to style all the html elements. Group selector minimize the code because it groups all the elements with same style definition. There is external, internal and Inline CSS that work differently. CSS uses color property to set color for different HTML elements. There are various ways used to apply the color. Color palettes may not include color names. You can use a color for a text only or background or for the whole page or selected element. You can custom your own colors using canvas.

Web supports 3 types of image formats. Background images can be used on a certain portion or repeated. Background images can be controlled by specifying if it will be in the centre, right or left. The position and height can be stated too. Percentage is used to adjust an image. Only css-named colors work directly in css.
Serif makes letters connect and text to be easily read. San Serif makes the web clean and easy to read, mostly set as default font on computers especially if there is no font declared. There are different fonts used neitherless one should apply the one that will not complicate things. The only way to measure the font is either absolute or relative. The size of the heading can be adjusted to outline the purpose of the heading. Every html element has it's property though it might have a value of zero. Padding is the space between the content and border. Margin being the space between the elements. Border-radius allows us to round the corners of elements. 
Font-family property is always added to the body element.
Inheritances it also applied to certain elements but can only be inherited when declared in the head, some elements can not be inherited.

**JAVASCRIPT**

Is a programming language that is used to make webpages interactive also known as untyped language. JS allows you to work with 3 primitive data types, it also defines two trivial data types. 
JS Variables are containers that stores data, before using variable it needs to be declared. Storing value in a variable is known as initialization.
It can hold value of any data type.
Operators are used to perform mathematical and logical computations on operands. There are arithmetic and assignment operators.
Assignments operators assign values to JS variables.
Comments are written using //.

**Javascript Strings and Arrays**

JS Array is a collection of strings or array elements that can hold more than one value, they are converted to strings using the toString() method . They are declared in 2 ways to create empty array. They are mutable, Pop- is used to remove the last element of the array and also returns the removed element.
Push-method adds one or more elements to the end of an array and returns the new length of the array.
Shift- removes the first element of the array thus reducing the size of the original array by 1.
Unshift- is used to add one or more elements to the beginning of the given array.
String is a collection of characters, they are converted to array using the split method. They are primitive and immutable. We use single, double or backticks to write them. Console.log() is the easiest way to print output of a string.

**Function** 
is a group of reusable code which can be called anywhere in a program. It is executed when something calls it. When JS reaches return, the function will stop executing.
Parameters are variables that are placeholders for the values that are to be input to a function when it's called. The parantheses operator () is used to call function followed by unique function name. Parameters are the names listed in the function definition. If a function is called with a missing argument then the missing values are undefined. Statement block is in curly braces.

**BOOLEANS**

They are presented by True or False. Booleans function is used to find out if the expression is true or not. Operators (==,>,<) are used to compare. Everything within a value is True and everything without a value is False.
It is useful to store them in variables to keep track of their values & change them over time. Conditional statements are used to perform different actions based on different conditions. We compare Logical And Operator, then Logical Or Operator.
If statement is used to specify a block of a code to be executed, if a specified condition is true.
Else statement used if the same condition is false.
Else if to specify a new condition to test, if first condition is false.
Switch to specify many alternative blocks of code. It is evaluated once. The value of expression is compared with the values of each case. Break is used to break out of the switch block. 
Default specifies the code to run if there is no case match.
JavaScript Sprints contains algorithm and data structures. The gold code practical was a bit complicated, else statements were used to compare situations. Other than that they are not difficult. 

**Type Conversions**

Operators & functions convert values given to them to the right type automtically.
String conversion is used when we need the string to form a value. eg alert(value).
Numeric conversion happens in mathematical functions & expressions automatically.
Boolean conversion happens in logical operations.

**Formatting Numbers**

toString-returns numeric value into string
toExponential- return numbers into string also but the number is in exponential form.
toFixed-return numbers into string but with a specific decimal, decimal specified in () after the method name.
toPrecision-return numbers into string but with a specific length with length specified inside () after method name.
valueOf- return a number as a number.Turn objects into primitive values e.g (typeOf=number) or (typeOf=object)

**Converting variables to numbers**

Number() - Convert JS variables into numbers.
ParseInt() - Creates JS Integer. Parse string & return number but only the first number will be returned.
ParseFloat() -Parse string & return float number but only the first number will be returned.

**DOM**
 Is a programming interface for web documents. It represents the structure of HTML and XML documents.
 It provides structural representations of the document and defines a way that structure is to be accessed.
 Javascript has syntax that have objects. To access an object, property, or method, it's reference must include every object that contains it, separated by a dot.
 **JavaScript Objects** are Window, Document, Form & Image.
 
 **JS Methods** are the following:
 alert()- causes an alert dialog box to appear over the page that launched it.
 write()-writes the content of the page.
 focus()- causes cursor to be inserted into a form element.

 **Javascript APIs**
  Allow developers to interact with various features and functionalities of web browsers and other environments.
  JavaScript APIs are available for web development. Each API serves specific purposes and provides functionalities that can enhance the capabilities of web applications.
  
 **APIs in Web and XML page**

document.getElementById(id)
document.getElementsByTagName(name)
document.createElement(name)
parentNode.appendChild(node)
element.innerHTML
element.style.left
element.setAttribute
element.getAttribute
element.addEventListener
window._content
window.onload
window.dump()
window.scrollTo()

**Flowcharts** are valuable for documenting processes, analyzing complex systems, designing algorithms, and communicating ideas visually.
There are shapes used to demonstrate each condition/statement of the process.

**Loops** are control structures in programming languages that allow you to execute a block of code repeatedly based on a certain condition.

**For loop** Is used when you know the number of times you want to execute a code of block.
**While** Is used when you want to execute a block of code as long as the condition is True.
**Do-While** Code inside is executed at least once.



**Node.js**

Node.js is one of the powerful open-source and cross-platform runtime environment built on Chrome’s V8 JavaScript engine for executing JavaScript code outside of a browser. It stands out as a game-changer. It is primarily used for Server-side Javascript.
It operates within a single process to avoid creating a new thread for every request.
Node.js provides a set of asynchronous I/O primitives in its standard library. Node.js doesn't waste CPU cycles waiting but instead but resumes operations when response arrives.
Node.js efficiently handles thousands of concurrent connections using a single server. It avoids the complexities of managing thread concurrency, which can lead to bugs.
Node.js supports the latest ECMAScript standards. You can choose the version you want to use, independent of users’ browser updates.

**Key features of Node.js**
1. Non-blocking I/O: Node.js is asynchronous, enabling efficient handling of concurrent requests.
2. Event-driven architecture: Developers can create event-driven applications using callbacks and event emitters.
3. Extensive module ecosystem: npm (Node Package Manager) provides access to thousands of reusable packages.

**Node.js Datatypes**
Booleans, String, Undefined, Number, Null

Framework is like a structure that provides a base for the application development process. With the help of a framework, you can avoid writing everything from scratch. Frameworks provide a set of tools and elements that help in the speedy development process. It acts like a template that can be used and even modified to meet the project requirements. Frameworks are based on programming languages.
Frameworks for Node.js are:
Express, Sails& Koa

**REACT.JS** 

React is a powerful JavaScript library for building dynamic and interactive user interfaces (UIs). It has the following features
1. Javascript Syntax Extension (JSX)
2. Virtual DOM
3. One-way Data Binding
4. Performance
5. Extension
6. Components
7. Conditional statements in JSX

**ReactJS Advantages**


**Composable**: We can divide these codes and put them in custom components. Then we can utilize those components and integrate them into one place.

**Declarative**: In ReactJS, the DOM is declarative. We can make interactive UIs by changing the state of the component and ReactJS takes care of updating the DOM according to it.

**SEO Friendly**: ReactJS affects the SEO by giving you a SPA (Single Page Application) which requires Javascript to show the content on the page which can be rendered and indexed.

**Community**: ReactJS has a huge community because of its demand each company wants to work with ReactJS. Companies like Meta, Netflix, etc built on ReactJS.

**Easy to learn**: HTML-like syntax of JSX makes you comfortable with the codes of React, it only requires a basic knowledge of HTML, CSS, and JS fundamentals to start working with it.
If you want to learn more refer to this article React JS Advantages.

**Debugging is Easy**: The debugging of ReactJS is unidirectional which means while designing any app using ReactJS the child components are nested within parent components. So, the data flow is in a single direction it gets more easier to debug errors.


**PYTHON**
Is a highly popular dynamic programming language. Compatible with all major Operating System.It is easy to use as it is similar to other programs.
Is an interpreted language, with new executable file being created when you run a code. This new file is the one that runs.

Python variable is a container that stores values. Once an object is assigned to a variable, it can be referred to by that name. Variable must start with a letter or underscore character.
Memory is where files and data is stored. Each file has its unique name then information about that file and information contained within that file. When writing and running computer program, we are automatically interacting with computer's memory. Programs generate bits (binary digits containing 0 & 1 only) of data called variables.
When assigning one variable to another, we're not creating a duplicate; instead, we're assigning both variables to the same location in memory. Python is employed in developing vast, complicated systems. Any text editor can be used to write python.
Jupyter is a web application that allows you to write and execute Python programms in a web browser that command line.
Variable is a basic unit of program assigned to a value. They begin with small letters in python. = sign is used as asignment operator.

**Variables in Python**

1. Integer(whole numbers)
2. Floats(Decimal numbers)
3. Complex numbers(Used for complex mathematical calculations)
4. Strings(Collection of characters, + is used to concatenate them) can not be used to add strings and numbers.
5. Booleans(True/ False)
 Error messages provide a lot of information in Python.

**Data Structures**

A data structure is a particular way of organising data in a computer so that it can be used effectively. The idea is to reduce the space and time complexities of different tasks. Allow for the storage of a list of values in a single variable.
List as a data structure, can contain any data type, including a list within a list. The order is important.
Set as data structure, contains unique elements and is declared using curly braces. The order is not important.
Tuples contain any data type but once declared they can not be modified. They store a large amount of data.
Dictionaries, is a data structure that store the value of value:key-pairs. They are declared within curly braces & separated by a comma. Can be created by the built-in function dict().

**Operators**

Operators are instructions used to perform operations on values and variables. They manipulate & perfom actions on data.
Arithmetic operator is mostly used to perform mathematical calculations. (+, -, *, /).
Division operator returns a floating-point value even if the results are a whole number.
Modulus operator (%) provides the remainder after division and will return the remainder.
Strings can also be manipulated using operators. Addition operator for strings works only with two strings, while the multiplication operator can work with either a string or a number.
Comparison operators evaluate two variables or values and produce a Boolean result.
Logical operators, such as "and," "or," and "not," operate on Boolean values only. "OR" is used when at least operand is true.

**Control Flow**
 Python uses indentation to identify a block
 
1. The if statement-allows you to execute a block of code only if a certain condition is met.
2. The if-else statement- the code under that will be executed if the condition is false. 
3. The nested-if statement-is an if statement that is the target of another if statement.
4. The if-elif-else ladder-As soon as one of the conditions controlling the if is true, the statement associated with that if is executed, and the rest of the ladder is bypassed. If none of the conditions is true, then the final “else” statement will be executed.

**Python Functions**

Python Functions is a block of statements that return the specific task. Defined using "def" followed by the function name and arguments in parentheses.
Function body indented and contains the code that performs the desired operation on the inputs and returns output. Functions can take one or more arguments, and they may or may not return a value. Function may mutate a variable without returning anything.

**Some Benefits of Using Functions**

1. Increase Code Readability 
2. Increase Code Reusability

*args:they pass non-keyworded, variable length argument list to a function. It is a tuple of arguments that can be accessed by indexing (e.g., args[0], args[1], etc.).
**kwargs: They pass key-worded, variable length argument list to a function. It is a dictionary of arguments that can be accessed by key (e.g., kwargs['name'], kwargs['age'], etc.).


**Classes and Objects**
Almost everything in Python is an object, with its properties and methods.
A Class is a template that defines the properties and behavior of an object. It is like an object constructor, "class"is used as keyword.
Objects is an instance of a class, it also contain methods & attributes defined by a class. Methods in objects are functions that belong to the object.

**Inheritance**
Inheritance in Python is a mechanism that allows one class to inherit the attributes and methods of another class. The inheriting class, also known as the subclass or derived class, inherits all the fields and methods of the parent class, also known as the superclass or base class.

**Data types**

**Java**

Back-end. Java is a highly popular, object-oriented programming language, that means java is the collection of objects, and these objects communicate through method calls to each other to work together.
**Class** is a user-defined blueprint or prototype from which objects are created. Methods is the behavior of an object. **Object** a basic unit of Object-Oriented Programming and represents real-life entitiesIt is an entity that has behavior and state, Example: Dog, Cat, Monkey etc. are the object of “Animal” **class**.Object has 
1. State: It is represented by the attributes of an object
2. Behavior: It is represented by the methods of an object
3. Identity: It gives a unique name to an object and enables one object to interact with other objects.

An interface can have methods and variables, but the methods declared in an interface are by default abstract. Interfaces specify what a class must do and not how.

The **behavior** is (running on the road) which is the **Method**
Instance variables: Every object has its own unique set of instance variables. The state of an object is generally created by the values that are assigned to these instance variables.
When the class is public, the name of the file has to be the class name. Java does not allow space in between class names. Each word starts with a Capital letter 
All the method names should start with a lowercase letter.
Identifiers are the names of local variables, instance and class variables, and labels, but also the names for classes, packages, modules and methods. Java Identifiers can be a class name, method name, variable name, or label. 
Computers are just data processors. They need a set of precise instructions, called a program, to do anything. They only undestand machine language.
When it comes to getting stuff done, **algorithms** are the real heroes. They are a step-by-step of how a task can be completed. 

Java is statically typed and also a strongly typed language because, in Java, each type of data (such as integer, character, hexadecimal, packed decimal, and so forth) is predefined as part of the programming language and all constants or variables defined for a given program must be described with one of the Java data types. Allows for type inference with local variables.
**Java Data Types** have different sizes and values that can be stored in the variable.

1. Primitive Data Type: such as boolean, char, int, short, byte, long, float, and double: only single values and have no special capabilities.
2. Non-Primitive Data Type or Object Data type: such as String, Array, etc.

An **IDE** is specialized software that is tailor-made for creating and running programs. IDE can be used for editing and running code, and it makes coding quicker and simpler.
It has a debugger, which is a lifesaver for spotting and fixing errors in your program.

Variable can be seen as a place in the computer's memory that holds information. It is the basic unit of storage in a program.
In Java, **Variables** are the data containers that save the data values during Java program execution. Every Variable in Java is assigned a data type that designates the type and quantity of value it can hold. A variable is a memory location name for the data. Variables are declared before using them. Java can declare a variable as VAR. The value stored in a variable can be changed during program execution.

data_name can only be given to a memory location. It can be assigned values in two ways: 
1. Variable Initialization
2. Assigning value by taking input
   
In Java it is wise to selected descriptive names

**Variables can be initialized in 3 ways:**

1. datatype: Type of data that can be stored in this variable.
2. variable_name: Name given to the variable.
3. value: It is the initial value stored in the variable.

**Types of variables in Java**

1. **Local Variables**: A variable defined within a block or method or constructor. 
These variables are created when the block is entered, or the function is called and destroyed after exiting from the block or when the call returns from the function.
2. **Instance Variables**: non-static variables and are declared in a class outside of any method, constructor, or block. 
Instance variables are declared in a class, these variables are created when an object of the class is created and destroyed when the object is destroyed
3. **Static Variables**: Static variables are also known as class variables.
These variables are declared similarly to instance variables. The difference is that static variables are declared using the static keyword within a class outside of any method, constructor, or block


**Java Arithmetic Operations**(-, +, /, *, %)
They work with numeric values, such as bytes, shorts, ints, longs, floats, and doubles. 

**Data Structures** A programming language uses control statements to control the flow of execution of a program based on certain conditions.

**Java’s Selection statements**: 
1. if: if statement is the most simple decision-making statement. It is used to decide whether a certain statement or block of statements will be executed or not i.e if a certain condition is true then a block of statements is executed otherwise not.
2. if-else: The if statement alone tells us that if a condition is true it will execute a block of statements and if the condition is false it won’t. But what if we want to do something else if the condition is false? Here comes the else statement. We can use the else statement with the if statement to execute a block of code when the condition is false.
3. nested-if: A nested if is an if statement that is the target of another if or else. Nested if statements mean an if statement inside an if statement. Yes, java allows us to nest if statements within if statements. i.e, we can place an if statement inside another if statement. 
4. if-else-if: versatile tool that can be used to control the flow of a program. It can be used to execute different code blocks based on multiple conditions, which can be helpful for things like grading tests, determining eligibility for discounts, or making other decisions.
4. switch-case jump (break, continue, return): The switch statement is a multiway branch statement. It provides an easy way to dispatch execution to different parts of code based on the value of the expression.

Switch expressions are like switch statements, but they are more convenient. They do not require break statements like switch statements do. Switch expressions are excellent for assignments, but they are not just limited to that. You can include more than just assignments in your cases.

**Repetition Structure**

**Loops** structures that cause a block of code to repeat.

1. **while loop**: A while loop is a control flow statement that allows code to be executed repeatedly based on a given Boolean condition. The while loop can be thought of as a repeating if statement.While loop starts with the checking of Boolean condition. If it evaluated to true, then the loop body statements are executed otherwise first statement following the loop is executed **Entry control loop**. Its the best to use if the loop may or may not need to run at all.
   
2. **for loop**: for loop provides a concise way of writing the loop structure. Unlike a while loop, a for statement consumes the initialization, condition and increment/decrement in one line thereby providing a shorter, easy to debug structure of looping. Its a count-controlled loop.
   
3. **DO-WHILE** do while loop is similar to while loop with only difference that it checks for condition after executing the statements, and therefore is an example of **Exit Control Loop**. Do while loop starts with the execution of the statement(s). There is no checking of any condition for the first time. Its the best to use if the contents definitely need to be executed at least once
After the execution of the statements, and update of the variable value, the condition is checked for true or false value. If it is evaluated to true, next iteration of loop starts.
When the condition becomes false, the loop terminates which marks the end of its life cycle.
It is important to note that the do-while loop will execute its statements atleast once before any condition is checked, and therefore is an example of exit control loop.

**Nested loop** means a loop statement inside another loop statement.
Sometimes, you must break free from a loop, no matter what is going on in there. You can do that with the **break statement**

