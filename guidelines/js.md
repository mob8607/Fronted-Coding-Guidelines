## JavaScript Coding Guidelines


### Comments
Every method and property inside a class should be commented.
Try to describe the method as short and as simple as possible.

#### Block Comments
All block comments are written in a YUIDoc like style.
The actual content of the comment is intended by 4 spaces.
Between the description and the properties is a line break.
    /**
        My awesome comment

        @param {String}
        @return {Object} MyCoolObject
    */

#### Inline Comments
Use inline comments inside class methods.
    {
        myMethod: function() {
            // Dat inline comment
            // is splitted into 2 lines
        } 
    }

### Single or Double Quotes ?
Single quotes are much more seksy but actually it doesn't really matter.
Just take a style and stick with it.
    var text = 'My text',
        myOtherText = 'This time we use "double quotes" in our text.';

### Definitions and Declarations

#### Variables
Define your variables at the top. Every variable declaration
starts on a new line. To declare several variables just use one 
"var" statement. The order goes from undefined variables to defined ones.
    var myVar,
        awesome,
        baz,
        foo = 'hello';
        defined = 123;

#### Functions
Function declarations can be oneliner if there is 
only one statement inside the function body but 
usually they looks like this:
    function myFunction() {
        var variable = 'hello'
        return variable;
    } 

    // one liner
    function oneLineer() {}

#### Class methods and properties

### Statements

### Naming Conventions

### Pro tips
