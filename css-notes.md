# CSS
> The key to understandin ghow CSS works is to image that there is an invisible box around every HTML element.
> John Duckett, HTML & CSS, pg. 229

## Chapter 10: Introducing CSS
Block level elements look like they start on a new line:
- h1...h6, p and div elements
- Inline elements flow within the text and do not start on a new line 
    - b, i, img, em, span
- CSS associates style rules with html elements
### CSS rule contains two parts: a **selector** and a **declaration**
- Selectors indicate which element the rule applies to
    - Can apply to more than one
- Declarations indicate the how elements referred to in the selector should be styled
    - Split into two parts (1-property, 2-value) and are separated by a colon
### External CSS
- href specifies the path to the CSS file
- type specifies the type of document being linked to
- rel specifies the relationship between the HTML page and the file it is linked to
### Internal CSS
- style element should use the type atttribute to indicate that the styles are specified to css; text/css
When building a site with more than one page, you should use an external CSS style sheet:
- Allows pages to use the same rules (don't have to format each sheet)
- Keeps the content separate from how the page looks
- Means you can change the styles used across all pages by updating one file, not each page
CSS is hierchacial, if there are two or more rules, the more specific rule will take precedence over a more general rule
- Specifying a font family or color properties on the '<body>' element, they will apply to most child elements
    - An example of it not being inherited is the background, if these were inherited the page would look messy

## Chatper 11: Color

