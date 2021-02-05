# Javascript
# how to use:
  Javascript code is inserted in HTML file between Script tag in head tag or body tag.
      <script>
          alert("Hello!!")
      </script>
  Script can also be placed in external file and put file name in the src attribute.
      <script src="script1.js">
      </script>
      
      
      
# comments
  single line comment: //comment
  Multiline comment: /* comment 1
                        comment 2
                        comment 3 */
                        
                        
                        
 # Use of strict
   Using `use strict` keyword it enables strict mode and whole script will works on modern way.
   Have to write `use strict` at starting of the script.
   
   
   
 # Variables
   Varibles can creat with let keyword and assign a value to it.
   We can also change the value of variables.
   
   
      
## Datatypes
  There are 8 basic datatype:
    1. Number
    2. String
    3. Boolean
    4. BigInt
    5. Null
    6. Object
    7. Symbol
    8. Undefined
 ## String
  Strings can be surrounded by 3 types of quotes:
    " " (Double quotes)
    ' ' (Single quotes)
    ` ` (Back ticks)
   To print value of strings have to use ` `(Back ticks) and ${ };
   
        let msg="ABC";
        alert(`hello, ${msg}`);
 ## Boolean
  It has 2 values: true and false
 ## Null
  It forms a separate type of its own which contains only the null value.
  It is special value which describes nothing or empty.
  ## undefiened
   The meaning of undefined is “value is not assigned”.
   If a variable is declared, but not assigned, then its value is undefined.
  ## Object can store multiple values in it.
  ## Symbol type is used to create unique identifiers for objects.  
  ## Typeof
   Using typeof we can check datatype of argument.
          Typeof 10;
          
   # alert
   It shows the message and wait fot the user to press ok.
       alert("Good morning");
   # prompt
   It will prompt the message with OK and Cancel button.
   Have to give 2 values.
   
       result = prompt(title, [default]);
       result = prompt("Marks", 20);
      default value is for value which we want to show as default value in the prompt box.
   # confirm
   The function confirm shows a modal window with a question and two buttons: OK and Cancel.
    let isBoss = confirm("Are you the boss?");
    alert( isBoss ); // true if OK is pressed
    
  # Type conversion
  when we need the string form of a value we can use string conversion.
    
    let value = true;
    alert(typeof value); // boolean
    value = String(value); // now value is a string "true"
    alert(typeof value); // string
    
  Numeric conversion happens in mathematical functions and expressions automatically.

    let str = "123";
    alert(typeof str); // string
    let num = Number(str); // becomes a number 123
    alert(typeof num); // number  
    
  boolean conversion happens in logical operations but can also be performed explicitly with a call to Boolean(value).  
  
  
  # Mathematical Operators
  





          
          
          
          
      
   





   


      
      
      
  
  
  +
