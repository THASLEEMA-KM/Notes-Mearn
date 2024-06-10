-----------------------------------------------
CSS Cascading style sheet
---------------------------------------------
    used to style html elements
    diff ways to apply CSS in HTML elements 
        inline CSS: used to style attribute
            syntax : style =" css-property : value; "
        internal CSS :  used to style tags
            syntax : <style> css-selectors {css-property:value;}</style>
        external CSS : apply  style via external css file
            syntax : <style> css-selectors {css-property:value;}</style>
            use link tag inside head tag
    CSS selectors : used to select HTML elements
        use tags
        use id - to denote its an id we use a #tag infront of the id in the css page
        use class - we can style multiple tags using same group for this we have to set them in a class. also in css we denote it as period(.)
        to style whole content in the page we use * astrich
        also we can style multiple tags using , comma 

        descendant selectors
        we can select html elemnts using a parent child method

    boxmodel

    CSS property:
        float: float the html elements
        position we can manage positioins of certain html elements
            static : default position
            fixed : 
            absolute
            relative
            sticky
        flex : to arrange html elemnts row and colomn wise
        justify content spacing horizontally
        align items spacing vertically
        flex wrap : wrap it used to fit the display in order to decrease the size of the screen
        flex grow - we can enlarge size to particular div
        flex shrink used to reduce the size of particular div
        vh view height
        flex direction column can arrange elements columnly
        flex direction row can arrange elements row wise. 
            if there is only one content we dont have to set flex direction
            coz default flex direction value set as row.


            before hovering an image we havae to set values for the image
            to nullify this value transform property is used 
                transform: translate(value);

        grid : same as flex. but it is easier to arrange cintents in the div.
                it has no default value as compoaredto flex . 
                for this we have to put this ina  parent class.
                grid-template-column : to arrange contents on columnly
                grid-template-row:
                we can give space bw columns.
                display:grid
                display:inline-grid

                to combine 2 columns grid-column-start and grid-colomn-end
                grid-template-column: auto auto auto auto :means 4 columns.
                and adjust the size respectively.
                grid units


        no - repeat prpoperty used to avoid repaeting the image
        background size: cover property used to cover the image in the browser
        background position center used to position the image in the center

--------------------------------------------------
bootstrap
--------------------------------------------------            
    frame wowrk of CSS.
    have pre defined styles for elements
    easier way to design.
    to build responsive sites
    div is a container tag . to use that we can give a claass name to that div named as 'container'. 
    -container: it is a type if bootstrapclass. it will give margin left nd right spaces. 
        we can't edit the style ..it wll give default values for the margin lt rt, to give extra style use CSS.
    -container-fluid: another type of bootstrap clas  that will give smaller spaces in the lft nd rgt sides.
     we can give values from 1 to 5
     -m: it is a class for margin.
        -mt: used to give margin top
        -mb: used to give margin bottom
        -ms: left margin margin start
        -me: right margin margin end
        1 is the min value and 5 is the max value.
        (mt-1,mt-5) etc.
    -border: bt class for border
         border-value: to give width to that border.
    -shadow- to get shadow effect
    -p:to give padding. and set values upto 5 withca hiphen.
        pt padding top
        pb padding bottom
        ps padding left
        pe padding right
    -color: we can set color using the bootstrap class name. forthis use with a hiphen(bordre-dark: give black color to that border)
            primary/danger/succsess/warniing/info/dark/light/secondary
    -rounded: to curve the border edges.
    -bg: to set background color.
        bg-info: it will set blue colorfor the background.
    -text: class used to style the texts.
            text-info
            text-center: to align the text in center part.
            we cant give extra size to the text. it will be same size as the heading have.
    -img-fluid: this class sets the image as responsive.ie,cover 100% into that screen.
    -img-thumbnail: to set image as a thumbnail.thumbnail means it will set a border.
    -w: class for width.
        we can give 100% value, only use multiple of 25(ie, 25, 50,75,100)
        w-50: 
    -text-start: aligns contents from left.
    -fs: font size.
        fs-1 bigger font size.
        fs-5 smaller font size
    -fw: font weight 
        fw-bold: becomes bold fonts
    -btn: class for button.
        if we give btn class name it automatically removes the bgcolor,border of that button. and we've to set the style
        btn-color : to give color for the button
    -d-flex: used to display contents as flex.
            it starts from left side.
    -justify-content- to align vertically
            justify-content-evenly
            justify-content-between
            justify-content-aruond
    -align-items-center
    -flex-row: align items as row
    -flex-column align items as column
    -grid- in btstrp it equally divides a row into 12.
    -font: font family
            font-monospace
    -to make responsive we use breakpoints in bootstrap
        :sm/md/lg/xl/xxl
    -navbar : class for navigation bar
        -navbar-brand: for icon
        -navbar-toggler: to decide when the button is to be displayed
        -data-bs-toggler
        -data-bs-target: 
        collapse: used to collapse the contents inside the tags.
        nav-item: to display list
        form-control input textbox
    -carousel: moving/rotating elements. to slideshow contents.
                -sliding/fading/autoplaying
                -carousal slide : sliding effect, carousal-fade 
                -carousal-indicators: the navigating items displayed in the bottom part of the slide
                -carousal-inner :content to be displayed inthe slide
                -class-active: to decide which slide is to be displayed
                -data-bs-slide-to carousal: it will set to the class having 
                -data-bs-intervel: to give animation time
                data-bs-target-#id of curresponding
                -we canset animation time
    -modal: popup box
            data-bs-toggle modal
            modal-dialog
            modal-content
            modal-header: title and close button
            modal-footer:
            data-bs-dismiss=modal :to close modal
    -offcanvas:
        data-bs-toggle=offcanvas
    -dropdown
    -accordion:collapsing more than one contents
            -mostly in Q/A
            -data-bs-toggle:collapse
    -alert
        alert alert-danger
    -badge: to display notifications 
    -breadcrumb
    -btn-group
    -list-group
        -list-item
        -active
    -pagination
    -placeholder
    -popover
    -prodressbar
    -scrollspy:nav bar changes wrt scrolling the page 
    -spinners: loading icons
    -toast: to display alertbox 
    -tooltip
    animation sites
        -animate.css
        -aos
        -locomotive scrolling

-------------------------------------------------
Java Script
---------------------------------
Node JS :- not a language, provides runtime environment and js library
    command=// ctrl+/
    to clear screen terminal :- cls
BASIC CONCEPTS IN JS
    to display content in js console.log(content);
    data types : type of the data.
    we can identify the data using the 'typeof'.
        -console.log(typeof "content")
    types of contents -
        - text :- single qoutes, double qoutes
        - number:- all types of numbers
        - boolean:- 0 and 1 true or false.
        - object
    to display output open terminal and run using the commmand 
        node filename.js
    to combine diff types of contents
        -use comma (,)
        -use plus(+)- concatination. it converts the particular data/content into string.
        -use tilde(`) (template literals)
        
    identifiers : set of rules to setup name for a variable
    variable :- used to store data in the js
        -using var keyword : 
            syntax : var variablename / var variablename =value
        -using const keyword : 
        -using let keyword :
    hoisting in js : using s data before creating it 

        ----------var----------                ----------const----------        -----let-------
        - use var keyword                     -use const keyword                -use let keyword
        - reassigned with                     - cannot reassigned               - reassigned
            any type of data
        -global scope                         - block scope                     -block scope
            can access anywhere and 
            changeble anytime
        -hoisted with undefined               - hoisted without value           -hoisted without value
    ------------------------------------------------------------------------------------------------------------------
    -Operators in JS
        -Assignment Operator  : = variable-name=value;
        -Arithmetic Operators : + - * / % (modulus) **(power)
        -Relational Operators : > < >= <= == ===
            - == is checks the value but === checks the value and its type.
        -Logical Operators : && || !
            - to combine two relational Operators
            - -----AND------- ------OR------ -----NOT-----
                T && T = T     T || T = T       !T = F 
                T && F = F     T || F = T       !F = T
                F && T = F     F || T = F 
                F && F = F     F || F = T 
        -Increment / Decrement Operators : ++ --
        -Shorthand Operators : += -= . if the variables are same on both sides
        -ternary Operators :(?:) condition?condition become true: condition becom false
        -truthy Operator :(&&) condition && condition become true
        -Spread opertaor : (...) used to expand an iterating variable to a single variable
        -Rest Operator : (...) Used to combine rest of the data to a single Array
    -Conditional Statements
            -if Statements
                syntax : if(condition)
                            {
                                if body:
                                    condition satisfied
                                    when condition satisfied.
                            }
            -if else Statements
                syntax : if(condition)
                            {
                                if body:
                                    condition satisfied
                                    when condition satisfied.
                            }
                        else
                        {
                            executes when condition false
                        }  

            -else-if Ladders
                syntax : if(condition)
                            {
                                if body:
                                    condition satisfied
                                    when condition satisfied.
                            }
                            else-if
                            {

                            }
                            else
            -switch cases 
    -looping Statements in js
            -repeating same thing multiple times
            -while loop
                -syntax :
                initialise a variable
                    while (condition should include that initialised variables)
                    {
                        execute when cndtn becom true
                        change value of variable used in condition
                    }

                    
            -for loop
                syntax : 
                    for(initialization; condition ; incre/decre )
                    {
                        
                    }
        -break Statements : to exit from a loop when a particular condtn reaches
        -continue Statements : to skip loop for a certain data.
        -Nested Loop : a loop in another loop
    -Functions : used to perform specific tasks during the code.
            -2 parts
                -function definition : defining the task to be performed
                    syntax : function function-name(parameters usewd to perform task)
                    {
                        defining the task in funbody
                    }
                -function call : to execute a function
                    syntax : function-name(arguments to be passed to the fun def)

    -return statements : which helps to return data from fun-def to fun-call. it must be in the last of the fun-def.
            -types of Functions
                -arrow fun : alternaative of fun definition,function-name = (parameters used to perform task)=>{defining task in function-body}
                if there is only one statement , there is no need to use curly brackets.
                -predefined Functions : console.log(), Math.floor()
                -callback function : fun def inside another fun call.the called func is completes its execution  only after completion of function inside it.
                -anonymous function : nameless functions, and they are self executing functions
                -Nested Functions : defineinig  a function inside another function deinition
                    clossure property - 
                -recursive function : calling a function inside its own definition.
    -Array : used to store multiple data.
                    type of the content in array is object. any type of data can be stored. its dynamic array. size is not fixed.
                    all data have unique id called index. and always starts from 0. to access array elements use this index
                    array-name[index number]
                    total count of items in an array : using 'length' 
                -for-of : we can also use for-of to access array elements using this. there is no need to use index number
                            for (let name-of-newVariable to be assigned  of array-name)
                -for-in :   for (let name-of-newVariable to be assigned  in array-name) it gives the index number

                -Methods : array-name.Method() multiple data can be insert at a time
                        -push(item) : used to insert data at the end of the array.
                        -unshift(item) : used to insert data at first of the array
                        -pop() : used to delete item from the end
                        -shift() : used to delete item from the start
                        -sort(compareFn) : a method used to sort array elements.
                            -compareFn : (num1,num2)=> num1-num2 (ascending order)
                                        (num1,num2)=> num2-num2 (descending order)
                        -forEach(callback :( value,index,array )=>void ) : alternative  to for-of loop
                        -filter(callbackfn) : return a new array with items satisfying the condition from an existing array
                        -find(callbackfn) : return an item satisfying the condition from an existing array
                        -map(callbackfn) :  same as forEach. as foreach doesnt returns any value, map() returns a new array with values after applying a maping function 
                                            to the existing array.
                        -reduce(callbackfn) : it will return a s1ngle value which is either smallest/largst/total sum from an existing array after applying 
                                                reduce function
                        -reduceRight(callbackfn) :  it will return a s1ngle value ( either smallest/largst ) which is the first item from an existing array after applying 
                                                reduce function
                                                "if we are applying an arithmetic operation on an array the data in the array must be in number type. if not use another Methods 
                                                to convert into number type array. method used fofr this are forEach() and map(). forEach returns void type dat, map() rerurns an array,
                                                so map() is used."
                        -some(callbackfn) : returns true / false based on a condition applied to all items given in an array
                        -flat(depth) : it will returns a new array with corresponding depth as dimension. 
                                -depth : 
                                -infinity : the argument to be passed in flat(). it will return it as one dimensional array. 
                                            if we dont know the size of the array , then use argument as "Infinity".
                                            if we know the size of the given array we can give  corresponding depth value 
                        -includes(key) : same as some() , returns a boolean answer,(true/false), here no need to give condition.
                                        return boolean base on the key present in the given array.
                        -indexOf() : index number of the corresponding array
                        -splice(StartingIndex, deleteCount) : to remove an item from a particular position.It returns an array with the deleted items.
                                                            : it is also used to replace a value witha new value on an array.
                                                            : splice(StartingIndex, deleteCount,newItemName)
                                        -StartingIndex : denotes the index number of the item to be deleted.
                                        -deleteCount : denotes how many items are to be deleted from thta starting index.
                        -join(seperator) : to return a string with array value seperated using the given seperator.
    -STRING : string is stored in the computer memory same as array.
                it is an array of characters. it stores charecter by characters.
            -Methods
                -substring(startingIndex,endingIndex) : used to take a particular part from a string.
                                                        but it will not include the last index.
                -toLowerCase : to convert the given string into small letters
                -toUpperCase : to convert the given string into capital letters
                -startsWith : to check the string is starting with the given value
                -endsWith : to check the string is ending with the given value
                -trim() : used to remove unwanted spaces in a string
                -includes() : to check a sustring present or not.
                -split() : to split a string using given seperator
                -slice() : same as substring. substring returns part oh=f the array, but slice canremove the charecters from the last.
                            for this give a minus value as its second index => 
                                arrayname.slice(0,-1) : 
                -eval(string-expression) : used to evaluate an expression as string

    -Object : Data are stored as a key-value pair .
            - use key to access value from an object 
                syntax : object-name['key'] / object-name.key
            - in : using 'in' operator we can check a key is in object
                syntax : "key" in object-name=> returns true / false
            - insert value to an existing object.
                -object-name[key]=value
            -Object.values(object-name) : return an array of values of the given object. it is not a method of object.and so it can't 
                                        applied to the object.its a javascript global methods
            -Object.keys(object-name)   : return an array of keys of the given object 
            -Object.assign(target-object,source)  : used to insert data in an existing object 
                                        target-object - is the objectName and source - is the key value pairs to be added in the existing array.
                                        can add more key-values into the array. single key-value is added in the form of object {},
                                        multiple kry-value added in th form of array[]
        -Methods
            -hasOwnProperty() : same as "in" , we can check a key is in object
    OOPS :  object Oriented Language
            JS is a partially OOP.oop is based on real world entity

                -Object : real time entity
                -class : blue print of object.
                    -constructor() : method used to initialise the property of the class . it aassign values to that prpoperty
                    -method : functions inside the class
                -Reference : used to refer property of its class
                    using this keyword (this)
                -constructor() : method used to initialise class property
                -Access specifiers : Used to specify the Access of a variable / function
                    -public
                    -private
                    -protected
                -Features :
                    - Inheritance    : Used to get data from Other class to another class.
                        -Classical Inheritance :  Use keyword "extends" Inheritance of 2 classes
                        -Prototype Inheritance : Use keyword "__proto__" Inherting between 2 Objects
                    - Polymorphism   : to implement Polymorphism in js Use REST operator(...) 
                                        (its not spread operator). 
                                        rest op used with functions . 
                                        it combines rest of all the arguments with it  and convert it to an array
                    - Abstraction    : hiding the important data from the user
                    - Encapsulation  : data inside another data like class,object etc...
            -TRY-Catch-finally BLock : used to handle the runtime errors
JAVASCRIPT - Front end CONCEPTS
-----------------------------------------   
    - used to provide behaviour to web page
    - ways to applying JS in HTML
        - Internal : use 'script' tag to provide js code in HTML
        - External : link External Js file with HTML using 'script' tag
    - DOM : Document Object Model for a web page.
            - a tree structure corresponding to a webpage, ther e will be a single root/ node  (html tag) which is made up of js object
            - js can access webpage / HTML elements  via DOM using 'document' object
    - DOM Methods : Selecting HTML elements to js code : 
        - using tag name : document.getELementsByTagName('tag-name')
        - using class name : document.getELementsByClassName('class-name')
        - using id : document.getELementByID('id-name')
        - using querySelector : document.querySelector('tag/#id/.classname')it will return only one value. and that will be the first.
        - querySelectorAll : document.querySelectorAll('tag/#id/.classname') to access all athe elements
    - Event : triggered by user actions
            - Mouse Related Events : click, move , drag...
            - Keyboard Related Events : keypressdown, keyup.......
            - Text based Events
    - Access / Update content of a tag  
        - innerHTML
        - innerText
        
    - Permenent Data storage in Browser : Limited storage, Data ara stored as key-value (both must be same, string type)
        - Using Local storage : data permenently stored
        - Using Session storage : data automatically delete when the tab is closed
        - Methods 
            -setItem(key,value) : Used to store data in local/ session storage
            -getItem(key,value) : use to get data from local/ session storage
            -removeItem(key) : used to delete  data from local/ session storage
    - API : Application Programming Interface - Used to communicate  Application in internet
        - URL - Uniform Resource Locator : 
            - ex : https://jsonplaceholder.typicode.com/users/1
                baseURL : https://jsonplaceholder.typicode.com/ 
        - URI : Uniform resource Identifier : ex : users
        - Path Paramaeter : ex : 1
        - Query Paramater : values followed with ? in url
            ex : https://in.search.yahoo.com/search?fr=mcafree&type=E211IN1274G0&p=jsplaceholder
        - Body Paramaeter : 
        -Types of API Architectural Structures:
            Client - Server Communication
            - REST API  : HTTP, JSON
            - SOAP API  : HTTP, XML
            - GRAPHL 
    - JSON : JAVASCRIPT OBJECT NOTATION
        - { "key" : value}
    - HTTP : HYPER TEXT TRANSFER PROTOCOL
        - HTTP Requests
            - GET ( to get data from server to client)
            - POST ( to store or add data to server from client)
            - PUT ( to edit or update existing data to server from client)
            - DELETE ( to remove a data from server )
        - HTTP Response Codes : to identify the status of client request by Browser 
            - 1xx : Informational
            - 2xx : Success
            - 3xx : Redirection 
            - 4xx : Client error 
            - 5xx : Server error
    - XML : Exetensible Markup Language.
    - Resolving Function Call in 
        - Synchronus Function : Execute function wthout  delay
        - Asynchronus Function : Execute with a delay
        - Js Use Call Stack to monitor it use event loop

            - Single Threaded Programming Language 
            javascript is a single threaded Programming language js uses a single stack 
            Synchronous data are stored in Call Stack 
            Types of Asynchronus 
                Callback : hold in Callback Queue
                API Call :hold in microtask Queue priority queue
            Resolving Asynchronus functions 
                - if we use call back to resolve Asynchronus function it may lead 'Call back Hell'
                    call back hell is Nesting of callback scenario
                - Promise : avoid callback hell 
                    - Has 2 states 
                        - Resolved State : use 'then' method to get the Response
                        - Reject state : use 'catch' method to get the reason to fail the function call
                        - Pending state : waiting duration to get Response for Asynchronus function call.
                    - Async-Await keyword : used to resolve Promise
                        - 'async' keyword used in a function to indicate it is Asynchronus
                        - use 'await' keyword infront of Asynchronus func call to wait till its completion
                        - only resolved state will get after await to completes the async function call
                        - to get reject state use 'try-catch' block
            Event Loop : it checks the Call Stack is empty or not
    - API Call Resolving using JS
        - Using XMLHTTPRequest : AJAX (Asynchronus Js XML)
        - fetch() : returns Promise
        - axios library : return Promise         
------------------------------------------------------
Object : Data are stored as a key-value pair .

        - use key to access value from an object 
            syntax : object-name['key'] / object-name.key
        - in : using 'in' operator we can check a key is in object
            syntax : "key" in object-name=> returns true / false
        - insert value to an existing object.
            -object-name[key]=value
        -Object.values(object-name) : return an array of values of the given object. it is not a method of object.and so it can't 
                                     applied to the object.its a javascript global methods
        -Object.keys(object-name)   : return an array of keys of the given object 
        -Object.assign(target-object,source)  : used to insert data in an existing object 
                                    target-object - is the objectName and source - is the key value pairs to be added in the existing array.
                                    can add more key-values into the array. single key-value is added in the form of object {},
                                    multiple kry-value added in th form of array[]
    -Methods
        -hasOwnProperty() : same as "in" , we can check a key is in object
        
------------------------------------------------------------------------------------

REACT - ADVANCED Front End  TECHNOLOGY
---------------------------------------
- Features 
    - Components
    - Virtual DOM
    - JSX Language
    - High Performance
    - Data binding (sharing) : One way Data binding (from parent to child)
- Basic Concepts
    - Library, not a frame work.
    - React App is a collection of libraries.(Libraries - collection of files)
        to design page
        to send requests
        to make behaviour corresponding to that req
    - *Components : Part of User interface 
    - React App is a collection of Components
        - They are arranged in a tree structure
        - There will be a root Component in React app which is known as "App" (default name)
    - React Used to create Single Page Applications , which means page starts from a single page.always starts from the 'App'
    - Pure functions : which doesnt cause side effects, used to create react func compo
    - Declarative Approach 
    - *Virtual DOM : Light weight memory representation of real DOM
        - Reconciliation : the process to detect changes in page. only changed section refreshed.thus loadidng time reduced;website become faster
    - *JSX : Java Script XML -  (Language used to write code in React) - Used to display contents on browser
        - ex : JSX Elements : const heading = <h1>Heading 1</h1> ( we can assighn it into a variable , combination of html tags and js )
        - Rules for Using JSX 
            - Every JSX elements must be inside a single parent tag 
            - Parent Tag can be any container tag / react fragment (nameless tag <>...</>)
            - Every tag must has closing tag. ex : <h1>content</h1> , <br></br> instead of this use (<br/> = self closing tag) in react
            - Attribute class is "className" in React
            - Instead of Attribute 'for' use 'htmlFor' in JSX 
            - Use {js-expression} : To provide JS expression in JSX
        - React App Creation
            - CRA (using create-react-app command )
            - Vite : build tool for web projects
                - Installing vite Globally : npm i -g create-vite 
                - React app using vite : npm create vite@latest or [npm create vite@latest react-app -- --template react] 
        - React App File & Folder structure
                    - package.josn file : npm configuration file for the project
                    - package-lock.json file: holds versions history of all installed packages
                    - .gitignore file : containd files/folder name which is ignored while adding to git 
                    - index.html file: entry html page ot react app
                    - node-modules folder: used to hold copies of dependent libtraries of react project.(we can install using command : npm install)
                    - public folder : react project can access data stored in public folder as Globally
                    - src folder : define react app here
                        - assets folder : used to hold media files used in react app
                        - main.jsx file : created a ReactDOM with root as div with an id as 'root',
                                          and render the parent (App) Component inside the node 
                    - to run react app : use command 'npm run dev' 
                    - Babel Library : transpile JSX code to simple react function which is understood by browser.
                                      Used to convert the jsx into the langs which are understandable to the browser - html/js 
                - General Rules for Creating Components
                    - create a js / jsx file, filename must starts with caoptal letter
                - Different types of Components : 
                    - Class Based Components : use class to create component it can inherit react component class 
                        - Statefull Component, coz it can create state 
                    - Functional Components : stateless components, coz fun cant create object, use function to sreate Component 
                        using 'rfce' we can load the basic structure of functional based component structure
                    - Life cycle Methods of React Components
                        - Mounting Phase : Putting JSX into Browser
                            - constructor()
                            - getDerivedStateFromProps()
                            - render() if it is true jsx component is rended into DOM
                            - componentDidMount()
                        - Updating Phase : when component is Updating
                            - getDeriverdStateFromProps()
                            - shouldComponentUpdate() if it is true render() invoked
                            - render() 
                            - getSnapshotBeforeUpdate()
                            - componentDidUpdate()
                        - Unmounting Phase : Removing componemt From DOM
                            - componentWillUnmount()
--------------------------------------------------------------------------------------------------------
- Difference between functional and class based compoenent                                                                     
            Functional Component                                  ClassCompoenent                                                                     
        ------------------------------------------------------------------------------------------------------                     
            1. JS Pure function to accept props                 1. Is class extended from react compoenent                     
            and return JSX Element                              it render function return JSX Element                         
            2. It executes from top to bottom, once             2. Compoent alive depending on different life                  
            it return JSX, then it cannot be alive              cycle                                                          
            3. Stateless component                              3. Statefull component                                         
            4. Hooks are used                                   4. Hooks are not used                                          
            5. Life cycle method is not available               5. Can use life cycle method in component                      
            6. No need render function                          6. It requires render to return JSX                              
            7. No need of constructor                           7. Constructor used to initialise state                        
--------------------------------------------------------------------------------------------------------
- Props Object : Property of a component, Using Props a component can get the shared data from its parent, 
                                 props will get as an argument of functional component
                - Styling JSX elements in React Component - Using CSS
                    - Using inline CSS   : Using style Attribute
                            - syntax : style={{Property:value}} (style as object, so represented as key-value pairs)
                    - Using External CSS : Using External css file,import css file to component file
                    - Using Module files : file with extention as .module.css is known as CSS Module file in component
                - React Events Binding 
                    - Binding a function without argument : event={function-name}
                    - Binding a function with argument : event={()=>function-name(arg)}
                    - Binding a function with argument as event : event={(event)=>function-name(e)}
                - Conditional Rendering : based on a condition we can control the JSX elements in browser
                    - if statements : use the operator truthy(&&) 
                    - if else statements : use ternary operator (?:)
                - React State : is an object used to store data /infronmation regarding a component , whenevever state change the component re-render 
                    - Use setState(value) : to update state
                - React Hooks : its a predefined function used to provide react component features to functional component
                    - Hooks are function name starts with 'use' keyword
                    - to use a hook in functional component we must call the hook
                    - Rules for calling hooks in functional component
                        - Import hook from react, in component
                        - hooks can be called at the top of level of component
                        - hooks cannot be conditional
                    - Types of hooks
                        - Predefined hooks
                            - useState(initial-value) : to help functional component to create state
                            - Syntax : const [state-name, state updating]
                            -useEffect(callback function, dependency) : used to provide side effects to your component
                                - function : used to define side effects applied to componenet
                                - dependency : based on dependency  useEffect will get invoked
                                    - no dependency : useeffect hook will call all timee in component
                                    - [] : useeffect will call only at the time in component creation
                                    - [data] : useeffect will call  at the time in component creation as well as data changes
                        - Customised hooks :
                            - create a function with the name starts with 'use' keyword
                        - Handling List using React
                            - using 'map' method
                            - to uniquely identify each item in a list use 'key' attribute in component
                        - Styling Framework in React
                            - Material UI : https://mui.com/material-ui/ 
                                - to installl : npm install @mui/material @emotion/react @emotion/styled
                            - React BOotstrap : npm install react-bootstrap bootstrap, we have to add bootstrap theme to 
                            properly work bootstrap, bootswatch.com will provide theme, chose a theme and download its bootstrap.min.css into src of project folder, we have to import bootstrap.min.css into main.jsx file
                        - React Forms
                            - Controlled Components : data changes in  the form is handled by the component by storing its state using change event
                            - Uncontrolled : form handled by real DOM
                            - To submit form, preventDefault() 
                        - Set up path for Component in React
                            - install react-router-dom :it is a client-side routing , to install use the command npm i react-router-dom 
                            - React app muster render in "BrowserRouter" component
                            - Components needs to setup path must be inside 'Routes' component of react router dom in App.jsx 
                            - using Route component define each component path
                            - Link component used to redirect from one page to another within the page
                        - Route is a HOC(Higher Order Component : a component become argument of another component ) 
                        - React Toastify : A Library used to alert 
                        - Export const : used to export multiple item
                        - Export default : used to export singel item . Export is must be at end part
                        - API Call in React
                            - Axios Library : to use this install axios library : npm i axios
                            - Create a folder for services
                        - State Lifting : Used to share data btw componenets on react. here we create the state in the parent. 
                            (lifting the state from child to parent) sharing data btw siblings as well as child to parent.
    ---------------------------------------------------------------------------------------------------------------------------------------
-                       JSON SERVER
    ---------------------------------------------------------------------------------------
         1. Create a folder to hold json file
         2. Create package.json file inside the folder using the commamd :- npm init -y                               
         3. Create db.json file
         4. Create Resources for that file, a resource is a file that to be permenently stored in the json
         5  to run json file install json server : npm i json-server / npm i json-server@0.17.4 
         6. to run json file in local host :npx json-server db.json / node index.js
    ---------------------------------------------------------------------------------------------------------------------------------------
-                   JSON SERVER DEPLOYING Using NODE JS
    ---------------------------------------------------------------------------------------
        1. Create index.js file server folder
        2. Update script in package.json to "start":"node index.js"
        3. Create .gitignore file and add 'node_modules' in that
        4. Define json-server to run json file in index.js
            - import json-server
            - create a server  to run json file using create() method of jsonSerever 
            - create middleware usdby json server
            - set up route json file in server using router() method
            - set up port for server application 
                process.env.PORT = to get available port number in browser
            - use middleare route in server app
            - listen the app in given port to resolve client request
        5. to run the server use 'node index.js'

---------------------------------------------------------------------------------------------------------------------------------------
-                   REDUX-STATE MANAGEMENT TOOL
    ---------------------------------------------------------------------------------------
 
         - REDUX - stae management tool . introduced to avoid props drilling, this is done by the way of creating a common data store which is equally accessible to all componenets
                            -props drilling - mamy no of coupling/ relations btw componenets
                            - toolkit library 
                            - Provider - it is a comonet from react-redux it will hepls to provide the store globallly to the application 
                            - A componwnnt cant directly store/udate data in comm store. to this uses a function called action , in this action we define the logic 
                            reducer used to update state in store, only this can update the state in store, the result is comes from action
                            - useSelector- it is a hook used to access the updated state ina common store, that is called by the component, this state is from react-redux library
        - install redux-react library - npm install @reduxjs/toolkit redux-react
        -Redux- features
            - Store - using configureStore() we can create a redux store in react,use 'provider' coponent to make the store available for react app
            - Create Slice to combine both action and reducer together using createSlice() , it returns actions and reducers , to create slice we have to pass configuration with following data : name, initialstate, reducers where we will define action to update state
            - Action - define logic to update state
                - when componenet dispatch actions with argument to update the state with argument then acitonfunction will get from its 'payload'
            - Reducer - used to hold updated state to store
            - redux devtools extention : used to  debugging application's state changes.
            - useSelector hook - use state from store to compo, usage syntax: "useSelector(state=>state.reducer-name)"
            - useDispatch hook - used to dispatch the actions defined in the store , used to execute the actions from component
            - createAsyncThunk() - used to create actions with asynchronous A func that accepts aredux action type string and  callback function that should return a promise
               first argumennt - action typeString = name of the slice/funcname
               second argument - callbackfun
               - returns a standard redux thunk action creator, 3 states that are pendomg,fullfilled,rejected
               - its output returns extraReducer,where 
            - ExtraReducer : it can resolve a promise in differentcases, w can add cases using builder project
------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------
-               MONGODB
    --------------------------------------------------
    - No structured Query language
    - It is a document database designed for ease of application development and scaling
    - To Run ,
        MongoDB Atlas  : The fully managed service for MongoDB deployments in the cloud
            (use atlas version)
        MongoDB Enterprise  : The subscription-based, self-managed version of MongoDB

        MongoDB Community  : The source-available, free-to-use, and self-managed version of MongoDB
    - used to store and manage data permenently

                    SQL                                                  MongoDB
        -Relational structrd qry lang dbms                  - document orented/NoSql db
        - data stored in table with row nd column           - str data as collctio od json docs
        - uses fixed schema to store (if we want to store   - ysed dynamic schma
        detail of a person, we have to setup 
        those initially,thus it is fixed)
        - optimised for comple join and transaction         - optimised for scalbility and performance
        -support rich set of data types                     - limited set of dayta type 
        - declaratv qyry lang                               - expresv qry lang basd on json
        - ACID Property(atomcty, cnsistncy,                 - NoSQL DB , CAP(consitncy,Avlblty Partitn tolernc)
        isoltion Durblty)
        - Uses traditionl bussnss applctn                   - Used in bigdata & realtime app

    Creating db in mongo
    - db name and collection m=name needed
        no space in db
        collection name must be starts with small letters
        collection name must be in plural form
        fileds must be in dbl quotes
        mongo db will create a new id for all new document which is a hexa decimal object id id stored in key _id
        to show all data bases : show databases
        to switch that db : use dbname
        CRUD opertaions 
            to read all document in a collection : find() (db.collectionName.find())
            to read a documnet in a collection satisfyingthat condition : findOne()
                db.collectionName.findOne({key:value})
                if condtn staisfies then it retrn entired docmnt otherwise retrns null
            insert a data in mongodb collection : db.collectionName.insetOne({key:value})
            insert more than on at a time : db.collectionName.insertMany([{},{},{}...{}])
            we can display total document count : countDocuments()
                db.collectionName.countDocuments()
            we can limit the count of documents  by reading all using limit()
                db.collectionName.find().limit(number to limit)
            we can sort the documents by reading all documents : sort()
                db.collectionName.find().sort({key:(for ascending value as 1, for descending value as 0)})
            we can skip data after sorting : use skip()
                db.collectionName.find().sort({key:value}).skip(the number to be skip)
            we can find documents based on a condition using find(). here args are given as the condition 
                db.collectionName.find({condition as key:value})  
            to querying while reading documents : use $
                $gt/$gte/$lt/$lte
                db.collectionName.find({key:{$gt/$gte/$lt/$lte:value}}) 
                db.users.find({age:{$gte:23,$lte:26}})

                db.users.find({$and:[{age:{$gt:23,$lt:26}}]})

            to get only mentioned docs while reading use $in
                db.collectionName.find({key:{$in:["value","value"]}})
            to check a key is exist or not : $exist()
                db.collectionName.find({key:{$exists:true}})
            to compare multiple fields in the same docmnts use :$epxr
                db.collectionName.find({$expr:{$gt:["$key","$key"]}})
            to update multiple value use updateMany()
                db.collectionName().updateMany({key:value},$set:{key:value})
                db.users.updateMany({age:27},{$set:{age:25}})
            to update single value
                db.collectionName.updateOne({key:value},{$inc:{key:value}}), here ade is incremented by a value(3)
                db.users.updateOne({uname:"Tom"},{$inc:{age:3}})
            to insert a data to an array
                db.collectionName.updateOne()
                db.users.updateOne({uname:"Jerry"},{$push:{hobbies:"Swimming"}})
            to delete a data frm an array
                db.users.updateOne({uname:"Jerry"},{$pull:{hobbies:"Swimming"}})
            to delete a document  deleteOne()
                db.collectionName.deleteOne({key:"value"})
                db.users.deleteOne({key:"value"})
            to delete more than one, use deleteMany()
                db.collectionName.deleteMany({key:{$exists:true}})
                db.users.deleteMany({uname:{$exists:true}})
                
        - Aggregation : used to join multple collection to get common result
                - $lookup : similar to left-outer joining in sql ,  adds a new array field to each input document.
                - Syntax :
                            {
                                $lookup:
                                    {
                                    from: <collection to join>, 
                                    localField: <field from the input documents>,
                                    foreignField: <field from the documents of the "from" collection>,
                                    as: <output array field>
                                    }
                            }
                    - db.users.aggregate({$lookup:{from:"projects",localField:"email",foreignField:"userid",as:"userprojects"}})

        - MongoDB Atlas : cloud version of MongoDB
            - 
        ----------------------------------------------------------------------------------------------------------------------------------
-                                           NODE JS SERVER /BACKEND
        ----------------------------------------------------------------------------------------------------------------------------------
        1. its a run time environment , also it have java script libraray for JS
        2. Features
            - Extremely fast
            - Asynchronous
            - Single Threaded with event loop
            - Highly Scalable
            - Open source language
        3. Node JS has Global objects
            - it can be access anywhere from node js app without exporting or importing
            - ex : console.log() , setTimout()
        4. Node JS Module System : A file is considered as module in  node to accesss data from one file it has to export from there and before using it in another file it has to import
            - to import module : require('module name/module path') method
            - to export module : module.exports / exports
            - Built in modules
                - File system : hanling fil e related events
                - http modules : create web server
                - https modules : create web server
                - Events : work with Event eMitter
                - crypto : providing tool like hashing, encryption etc.
                - process : used to provide currently runnning process in the node js app
                    - Environmental variable :- used to hold configuration / confidential data regarding the 
                        project to access environmemtal  variable through out app use 'process.env,variable-name'
        5. Node JS Packages :
            - Used to resolve common problems
            - we have to install package via npm 
            - it adds package.json , package-lock.json file , node_modules
        6. Backend Concepts
            - Client-Server Architecture : 
            - REST API : http requests and data in json
            - CRUD : Create (POST). Read(GET),Update(PUT),Delete(DELETE)
            - CORS : Cross Origin Resource Sharing Protocol is must enabled in server
        7. BACK-END WORKING
                Requests are send to an event queue, then the event loop checks whther it is blocking or non blocking
                then checks the type of the req. 
                The nonblcking req are send to I/O polling and it doesnt need any external libraries,
                The blocking type req are send to a single threaded thread pool. it need external libraries,
                The event loop solves the req one by one. also check whther it needs any externl applction
                if it is a nonblocking it send back the crrsoondng response immedaltly, not much time delay
                if it is a blocking the req are send from a thread pool to the external source like DB, FILE SYSTEM, COMPUTATION,
        8. Node js
            - Server side environment
            - written in C/C++ languages
            - building faster and scalable server side app
            - genereate db queries
            - 



        ----------------------------------------------------------------------------------------
-                    EXPRESS JS - FRAMEWORK OF NODE JS
        ----------------------------------------------------------------------------------------
        1. used in Client-Server Architecture as a web server
            - Create folder for server
            - inside folder create package.json using npm init -y
            - we ahve to update  package.json script value as "start" :"node index.js" instead of test
            - Install packages for creating express web server
                - express : npm i express : used to create server
                - cors : npm i cors : used to enable cors
                - dotenv : npm i dotenv : used to load environmental variable to process
            - create .env file : to store environmental variable of a project
            - create .gitignore file : used to avoid files and folders while uploading to git
                add node_modules,.env 
            - create index.js file to define express server
                - import all the packages,(dotenv,express,cors)
                - create express server
                - use cors in our express server
                - use json parser in express server
                - create port for server
                - start to listen server app for client
                - resolve get req to server using express
                - Run server app using node index.js
            - Create Routes in express server
                - create a folder
                - create router.js file
                    - import express server
                    - create an object of router class of express
                    - router obj is capable of defining route for app
                    - export router from the file
                    - import router in index.js
                    - use router in express server app
            - Create Controller folder to define loigc to solve client req
                - Create a folder
            - Create Models todefine schema and model for mongodb collection using mongoose
                - create a folder
                - create a js file to define schema and model
                    - import mongoose
                    - create schema object to define  structure of the docmnt
                    - creaye model
                    - export model
            - Create DB connection folder
                - create js file to define db connection
                - get connection string
                - use mongoose to connect db with node js
                - import index.js db file
        ------------------------------------------------------------------------------------ 
-                        MONGOOSE- ODM(OBJECT DATA MODEL) FOR NODE JS
        ------------------------------------------------------------------------------------ 
        1. install mongoose using : npm i mongoose
        2. Create SChema : Structure of the dcomnt  that we want to store in a collection
            - create obj of schema class
        3. Model : copy of the collection in db
            - create model call model method
        
       
    

        
