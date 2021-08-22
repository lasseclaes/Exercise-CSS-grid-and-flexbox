# Exercise CSS grid and flexbox

Exercise & rules

1. Fork (on GitHub) and clone (in VS Code) this repository (...or if we're not ready for that just yet: download the repository as a .zip-file and unzip it).
2. See the "MakeThis.gif" and make that.
3. Only change the CSS file. No changing of the HTML document (or the DOM).
4. Use CSS grid for the overall layout and Flexbox for the card/`<article>` "design". See if you can do it without media queries - remember (or look up): repeat, auto-fill, minmax?
5. Only use "rem" as the unit for margin, padding etc.

```css
main {
  display: grid;
  grid-template-columns: repeat(
    auto-fill,
    minmax(300px, 1fr)
  ); /* Keep adding new columns - even if theres is no content for them. content does not always take up full width */
  /*grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));*/ /* Don't add more columns than theres is content for. && +content "always" take full width */
  grid-gap: 1rem;
}
```

## Tutorial

_Don't go directly to the solution - try to see if you can write it on your own first! Compare your work with Jen Simmons' solution in the video. If you are totally lost you can use the video as a tutorial. It's important that you write and understand this yourself._

Jen Simmons' video on this very example at
https://www.youtube.com/watch?v=dQHtT47eH0M (8min 52sec)

<a href="http://www.youtube.com/watch?feature=player_embedded&v=dQHtT47eH0M" target="_blank"><img src="http://img.youtube.com/vi/dQHtT47eH0M/0.jpg" 
alt="Jen Simmons showing how to use flexbox and grid combined in web layout" width="240" height="180" /></a>

## Solution

SEE "css/style-solution.css"
