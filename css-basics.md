[Learning Journal](https://stanels42.github.io/learningjournal/)  
Read 5
# CSS Basics

## Terms

Block Elements - look like they are stacked on top of one another  
Inline Elements - elements that are in line(I know right?), left to right, with each other
###### There are other formations but these are the most common

| Selectors | Code | Uses |
|:----------|:----:|:-----|
| Universal Selector | `*{}` | Used to select **everything** on the webpage. Useful for selecting the font or other such thing. |
| Type Selector | ex. `p{}` | Used to select all elements of that type |
| ID Selector | `#examp{}` | Used for fine control of an element with that spific ID tag |
| Class Selector | `.examp{}` | Used for controling all elements of a given class |
| Child Selector | `li>a{}` | For selecting all children that match the 'Parent>Child relationships |
| Discendant Selector | `article p{}` | Simular to the child selector but the elements **don't** need a direct relationship |
| Adjacent Sibling Selector | `h1+p{}` | selecting element by referencing another element with the same parent and shows up Adjacent |
| General Sibling Selector | `h1~p{}` | for selecting an element that is paired(same parent) with another  |

`!improtant` - Used to override any other modifiers that might be used on an element

Color names - There are 127 built in color names
Hex codes - prefaced with a `#` and fallowed bya string of charactors
RGB Values - A set of 3 values each going up to 255 that combine to create a color
Hue - Is the more common idea of color.
Stauration - Refers to how much **grey** is in a given image or color. At max the color would look mostly grey.
Brightness - Refers to how much **black** is in a given image or color. At full brightness there would be no black
Contrast - Helps elements stand out from one another. low can be hard to read. high can strain the eyes after time. finding a middle ground is reccomended
opacity - The value of how transparent a certain color is. In programming it is a value between 0 and 1.

## Code
|  Code  |  Use  |
|:-------|:------|
| `s {d}` | The standerd format for CSS. 's' standing for 'element selection' and 'd' standing for the declaration |
|`<link>`  | Allow for the loading of an external CSS file |
|`<style>`  | Allows for the implamation of CSS directly into the HTML script |
|`property: value;` | The code format for changing the  |
|`color`| Used for changing the color of an element. All color changing elements use the 3 different systems listed above |
|`background-color`| Used for changing the background color of any given element |
|`opacity`| The value of how much you can 'see' through a color |
|`rgba`| Simular to the Red, Green, Blue (RGB) color selector but with another value that allows for the control of opacity |
|`hsl`/`hsla`| temp |

## Rules
`!important` overrides any other command. When faced with 2 or more commands of equal importance only the last one will be listened to. Will always use the most specific selector.

When picking colors make sure there is enough contrast between the background and the text to be both readable while not putting too much strain on the eyes.