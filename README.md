# Lecture Notes
Figma for website mock up.

## 3 ways to style with CSS.

- Inline -> Putting the style attribute on the element itself.
  - Inline not recommended (Can be used as a last resort)
  - old way to do it
  - Only used if you can't do use the other 2 ways. 
  - Will override previous rules. 

- Interal -> using a style tag inside the HTML file. 
  - one page at a time. 
  - Not recommended.

- External -> Seperate file with the link the head of the HTML. (App.css,styles.css,style.css)
  - Can be used on multiple HTML pages. 

- CSS Selectors - What elements do you want to style?
  - id 
  - class
  - element
- Rule - how to style the elements ath were selected?
  - key -> style application (width, height, background color)
  - Value -> what do you want to the style application to be equal to (100px, aqua, etc..)

- Specificty - more specific a CSS slector is, the priority it is given. 
    - IDs go only to one element
  - Inline is the most specific. Will override all other rules
  - ID is the next most.
  - Classes are the next most specific
  - Elements
  - Order matters here.

- Box Model - Everything is a box. 
  - content -> viewer is going to see/everything inside.
  - padding ->  space between content and border
  - border -> Edge of what is shown for the element
  - Margin -> space between elements

- Optional
  - Size units
    - px - pixels
    - percentages
  - Block vs Inline vs inline-block
  - Float
  - Tables
