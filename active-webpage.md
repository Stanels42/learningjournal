[Learning Journal](https://stanels42.github.io/learningjournal/)
# Active Web Pages With JS
Read 6

### Vocab
- Content Layer
    - The HTML that give the page structure
- CSS
    - What makes the page look pretty. Used for layout (Control the HTML)
- Javascript
    - What makes the web fun. No serously adds all(*most) interactions toa site

`object.method(parameter)`
The general structure of how methods are used  
_Note the Javascript will run where it is found in HTML if there are parts of the HTML that **aren't** loaded yet, there will be an error_

### Javascript Vocabulary

|   Code   |   Use   |
|:--------:|:--------|
| `var variableName;` | _Variables_ are used whenever you need to store some data. There are 3 main type String (words), Bool (true/false), and Numeric (numbers) |
| `//` | _Comments_ Used for making notes that have no effect on how the code runs |
| `if(`_Argument_`){`**Code**`}` | **If Statement** The code will only run if the argument in the statement is true |
| `}else{`**Code**`}` | **Else Statement** Can only be placed after an if statement and will run if all previous code statements return false |
| `}else if(`_Argument_`){`**Code**`}` | **Else If Statement** A hybred of the if and else statement. Can only be placed after an if. Will only run if the argument is true. _NOTE:_ once an if statement receves a true answer it will run the coresponding code before dropping out of the statement |
| `while(`_Argument_`){`**Code**`}` | A type of loop that will run aslong as the argument remains true |
| `for(inti=0,i<`_Argument_`,i++){`**Code**`}`| A loop that will repeat for a 'set'(i can be manipulated) number of times untill the argument is nolonger true |

### Rules of Variavle Names
1. Case Matters `string` =/= `String`
2. Can't start with a symble or number. Must be a letter.
5. Names can still contain `$`, `_` and numbers
4. No key words. They belong to the computer, pick something else
3. Name for function. Give a name that makes sence.
6. If the name has multipe words in it use camel case (Capitalize every word but the first). _shouldLookLikeThis_