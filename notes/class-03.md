# HTML Lists, CSS Boxes, JS Control Flow

## Chapter 3: Lists

`<ol>` Ordered List - numbers

`<li>` List

`<ul>` Unordered List - bullets

`<dl>` Definition List - terminology

`<dt>` Definition Term

`<dd>` Definition

Nested List - lists indented under the parent list

---

## Chapter 13: Boxes

CSS acts if each HTML element has its own customizable box.


width 
height
min- or max-    width or height

overflow - tells the browser what to do with the content contained within a box
  - hidden - hides any extra content that does not fit within the box
  - scroll - adds a scrollbar to view the extra content

**Border** - separates edge of box from another
  - border
  - border-width 
  - border-style
  - border-color

  * border-image
  * border-radius
    * border-radius: 40px 60px;

**Margin** - outside the edge of the border
  - margin

**Padding** - space between the border and content within the box
  - padding
    - ex. 
      - padding: 12px 4px; 
    - 12px - top and bottom
    - 4px - left and right
  - padding-top
  - padding-right
  - padding-bottom
  - padding-left

#### Centering Content 
  - `text-align: center;`

#### Change Inline/Block display

  inline
  
  block

  inline-block

    - `display: inline-block;`


**Visibility** hidden or visible

**Box Shadows** 
  - box-shadow
    * horizontal offset
    * vertical offset
    * blue distance
    * spread of shadow

---
## JS Chapter 4: Decisions and Loops

The if...else statements checks a condition. Depending on if which statement is true determines the output.

Switch statement is very similar however a condition isnt prepared. Variables can be listed to a varies of cases. Depending on the case, will depend on the output. If no cases match, you can also set a default option for this as well. 
The `break;` statement will skip the rest of the code if the statement above the break; code line is true. 

JavaScript tries to make sense of statements rather than report an error. Therefor JavaScript is said to be a *weak* language.

- string
- number
- boolean
- null
- undefined

Unary operator - one operand

`==`  compares values

`===`  compares values and data types 

`||` = or 

`&&` = and 

**Short Circuit**

#### Loops

- *for*
  - specific number of times
- *while*
- *do while* 
  - runs statement at least once



