# Todo

- [x] **Add a meta viewport tag**: In `index.html`, add a meta tag to the `<head>` that contains the following: `name="viewport", content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0"`
- [x] **Create a new stylesheet**: Create a new stylesheet in the `css` folder named `responsive.css`
- [x] **Link stylesheet to html**: Add a link to your new `responsive.css` stylesheet in `index.html`
- [x] **Add breakpoint for smaller screens at 1100px**
  - [x] Add a breakpoint for 1108px in your `responsive.css` stylesheet
  - [x] Within this breakpoint:
    - [x] Set the width of the `.wrapper` class to 90%
    - [x] Change the `#social` selector to have an absolute position, with an automatic width, 82px from the top, and 4px from the right
- [x] **Add a breakpoint for tablets at 900px**
  - [x] Add a breakpoint for 900px in your `responsive.css` stylesheet
  - [x] Within this breakpoint:
    - [x] Set the `body` text to a font size of 85%
    - [x] Change the `#logo h1` to 35px for height and width
    - [x] Change the `#logo h2` font size to 2.2em
    - [x] Adjust the top positioning on the `#social` selector to 72px
    - [x] Change the `col-3 p` selector to have a column count of 2. _Hint: look at the `style.css` stylesheet and make sure you grab all three column-count attributes!_
- [x] **Add a breakpoint for 750px**
  - [x] Within this breakpoint:
    - [x] Set the font size of the `#navbar nav a` selector to 0.9em;
    - [x] Change the `.col-3 p` column count to 1
    - [x] For the `.col-1`, `.col-2`, and `.col-3` selectors, set the width to 100%, left margin to 0, and float to none
    - [x] Remove the right border by setting `.border-right` border property to 0
    - [x] Set the `#details div` height to auto

**Bonus Challenge**
Add a breakpoint for 700px. Within this breakpoint, we are going to hide all of
the navigation links, and display the "hamburger menu" icon that is currently
set to be hidden. We also want to hide the text saying "Exceptional Realty
Group", leaving the icon visible. Third, we want to adjust the spacing on the
logo and social selectors so they remain in line with each other.
