# Exercise CSS grid and flexbox

Exercise & rules
1. See the "MakeThis.gif" and make that.
2. Only change the CSS file. No changing of the HTML document (or the DOM).
3. Use CSS grid for the overall layout and Flexbox for the card/`<article>` "design". See if you can do it without media queries - remember (or look up): repeat, auto-fill, minmax?
4. Only use "rem" as the unit for margin, padding etc. 

```css
main {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr)); /* Keep adding new columns - even if theres is no content for them. content does not alwys take up full width */
    /*grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));*/ /* Don't add more columns than theres is content for. && +content "always" take full width */
    grid-gap: 1rem; 
}
```