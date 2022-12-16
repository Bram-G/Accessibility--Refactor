# ACCESSIBILITY-REFACTOR-CHALLENGE

We were tasked with the challenge of refactoring this website and making it more accessible.
After understanding what was happening on the css and html pages I decided to make some changes.

## CHANGES-MADE
---
1. Added smooth scroll to the CSS file to make clicking the header links less jarring.
```
 html{
    scroll-behavior: smooth;
}
```
2. Changed `<div>` tags to more understandable and organized tags
ex. `<header> <nav> <figure> <main> <section> <aside>`
3. Condensed redundant CSS classes and ID's and renamed them for easier use throughout HTML doc
ex. `.search-engine-optimization h2` , `.online-reputation-management h2` and `.social-media-marketing h2` condensed into `.section-style h2` 
4. Changed title of website from `Website` to `Horiseon` to better enforce branding
5. corrected problem with navigation button not linking properly by Adding id tag to the appropriate section.
6. Organized CSS file to better represent the order of the HTML.
7. Added notes to CSS file to make it more readable for future devs
8. Added `<alt>` tags to images and icons to help users with accessibility needs.
9. Removed unnecessary classes like `.header nav ul` that were defining default properties