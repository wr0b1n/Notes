# Web Development
## Links
- https://codepen.io/
- https://developer.mozilla.org/en-US/docs/Learn
- https://www.w3schools.com/
- https://devdocs.io/
- https://docs.emmet.io/cheat-sheet/
- https://www.markdownguide.org/basic-syntax/
- https://www.loremipsum.de/
- https://www.frontendmentor.io/



# HTML
## Headers
    <h1>Heading level 1</h1>
    <h2>Heading level 2</h2>
    <h3>Heading level 3</h3>
    <h4>Heading level 4</h4>
    <h5>Heading level 5</h5>
    <h6>Heading level 6</h6>

## Lists
### Unordered list

    <ul>
        <li>first item</li>
        <li>second item</li>
        <li>third item</li>
    </ul>

### Ordered list

    <ol>
        <li>first item</li>
        <li>second item</li>
        <li>third item</li>
    </ol>

## Tables
Put `<th>` into the `<thead>` element to distinguish between header row and normal rows in CSS / JS.
Table layouts can often be replaced with CSS.


    <table>
    <tr>
        <td>John</td>
        <td>Doe</td>
    </tr>
    <tr>
        <td>Jane</td>
        <td>Doe</td>
    </tr>
    </table>

## Images

    <img src="https://developer.mozilla.org/static/img/favicon144.png" alt="MDN logo">

## Links

    <a href="https://www.mozilla.com">Mozilla</a>

- `text-docoration: none`: removes the underline


## Forms

Use different input types for different beaviour

    <form class="" action="" method="post">
        <label>Your Name:</label>
        <input type="text" name="" value="">
        <input type="color" name="" value="">
        <label>Password:</label>
        <input type="password" name="" value="">
        <input type="submit" name="">
    </form>


## Useful tips and elements

- Use `<strong>` instead of bold `<b>`
- Use `<em>` instead of italic `<i>`
- Use `hr` for horizontal lines
- Use `p` for text paragraphs
- Use `span` for different style inside a paragraph

## Search Engine Optimization (SEO)

- meta description tag in head
- alt description in img elements


# CSS

## Links

- https://colorhunt.co/
- https://emojipedia.org/
- https://developer.mozilla.org/de/docs/Web/CSS/Farben
- https://www.w3schools.com/cssref/css_default_values.asp
- https://www.favicon.cc/
- https://www.cssfontstack.com/
- https://fonts.google.com/ (commercial usable)
- https://www.flaticon.com/
- https://giphy.com/
- https://css3buttongenerator.com/
- Pesticide plug in for chrome (shows borders)

## Selectors

- selector { property : value; }
- ID > Class > Element (more specific overrides less specific)
- 1 ID per element
- 1 or more Classes per element
- sudo classes are used for states (e.g. :hover)

## Favicon

- favourite icon
- appears in tab header of site

## Box-Model
- Width / Height = Content + Padding + Border + Margin

## Display property
- css `display` allows change
- `block`: use total width of site / ordered one below the other / width can be changed (paragraph, div, heading)
- `inline`: only use their actal content size / ordered next to each other / width cannot be changed (span, anchor)
- `inline-block`: displayed like inline AND can change width (image, is best practice)
- `none`: removes element completely from HTML

## Positioning
1. Content is everything
2. Order comes from code
3. Children sit on parents (e.g. h1 inside a div --> h1 is on top) --> z-axis

## Positioning property
- css `position` allows change
- `static`: default style for all elements --> determined by html structure (display property)
- `relative`: relative to static (DEFAULT) position --> other elements are NOT effected (behaviour like a margin to the moved element --> other elements can be overlayed therefore)
- `absolute`: relative to its PARENT (has to have relative positioning) --> other elements are effected (behaviour like element is taken out of HTML flow) (e.g. image inside a div) 
- `fixed`: stays fixed even when scrolling (e.g. for navbars / sidebars)

## More positioning
- `text-align: center`: only works for inline-block (img) or FULL WIDTH block elements (p)
- `margin: 0 auto`: centers CUSTOM WIDTH block elements

## Fonts
- Sans-serif (Default font is Arial)
- Serif (has little feets at the letter's edge)
- Monospace (each character takes same space --> good for code)
- Websafe fonts can be displayed on all systems (otherwise default font will be applied)

## Font size
- Pixels: not dynamic (e.g. different font size in browser settings)
- Percent: is dynamic, gets inherited --> gets added to parents font size (100% == 16 Pixels == 1em)
- em: is dynamic, gets inherited --> gets added to parents font size
- rem: root em, ignores parent font size --> easier to use!

## Floating
- `float: left`: assign to element and let text wrap around on right side
- `clear: left`: prevents text from wrapping around
- ONLY use for wrapping text around elements! NOT for position in general

## Useful tips

- Default styles may override your own styles or prevent specific behavior (https://www.w3schools.com/cssref/css_default_values.asp)

- Element style > Html Head style > external css

- Percent is good for different devices

- Order properties in alphabetical order
