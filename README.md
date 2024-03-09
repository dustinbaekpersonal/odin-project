# Frontend Dev: HTML, CSS, Javascript

This repository shows learning process of frontend web development using Odin Project.
https://www.theodinproject.com/


## :wrench: Developer set up
1. Install npm and node.js


## :eyes: Lessons Learned 
1. To open html on Chrome
```bash
$ open ./src/index.html
```

2. Normally we would only have the index.html at the root directory and all other HTML files in their own directory.

Good analogy: 
    Think of your domain name (town.com) as a town, the directory in which your website is located (/museum) as a museum, and each page on your website as a room in the museum (/museum/movie_room.html and /museum/shops/coffee_shop.html).


3. Don't use inline CSS (i.e. declaring styles in HTML is bad)

4. Important thing to learn in CSS is Cascade. (what determines which rules get applied to HTML)
- Specificity: More specific takes precedence. ID selector > Class > Type, More selectors more specific
- Inheritance: Inheritance refers to certain CSS properties that, when applied to an element, are inherited by that element’s descendants, even if we don’t explicitly write a rule for those descendants.
- Rule Order: Last defined is winner.

5. Every single thing on webpage is rectangular box.
- padding: increases space between border of a box and content of the box
- margin: increases space between the borders of a box and the borders of adjacent boxes
- border: adds space btw margin and padding 

6. Flexbox is default to use to move boxes around
- 