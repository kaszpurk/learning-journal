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
'*' is the Universal selector
- Be careful with universal selectors
**Don't forget to link the style sheet, underneath the title sheet. Not linking the sheets will not apply css elements**
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

### Foreground Color
RGB: Express a color in terms of how much Red, Green & Blue are used
- RGB Example: 100, 100, 90
Hex Codes: 6-digit codes that represent the amount of Red, Green & Blue preceded by a #
- Hex Example: #ee3e80
- Color Names: 147 predefined color names that are recognized by browsers (e.g. DarkCyan)
### Background Color
If you do not specify a background color, it will be transparent
You can use RGB, Hex or Color Names
By default, most browser windows have a white background, but browser users can set a background color for their windows, so to ensure a white background apply that property
### Color
Hue: Near the colloquial idea of color
Saturation: Amount of gray in a color, Max Saturation is no gray, Min Saturation is mostly gray
Brightness: How much black is in the color, Max Brightness, almost no black, Min Brightness the color is very dark
### Contrast
- Low contrast is hard for those that are visually impaired, additionally it affects monitors of poor quality or sunlight on a screen 
- High contrast is easy to read but can be tiring on the eyes, adjusting font size and thickness can eleviate the strain
- Medium contrast is ideal for long spans of text and reading
### Opacity
- CSS3 introduced Opacity
- Opacity is expressed in a value between 0.0 and 1.0 
- Expressed like RGB with a 4th value indicating the Opacity (0-100%)
- The RGBA value will only affect the element on which it is applied
- In the case of some browsers not recognizing RGBA colors, specify a solid color 
### HSL & HSLA
Property begins with the letters **hs1**
RGBA; A=Alpha is expressed between 0.0 & 1.0
- Hue is an angle
- Saturation is a percentage
- Lightness is a percentage
    - HSL Example: 'background-color: #646464 background-color: hsl(0.0%,.78%);'
    - HSLA Example: 'background-color: #646464, background-color: hsla (0,100%,0.5);'
