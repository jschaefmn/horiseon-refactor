# Horiseon-Refactor

## Description
- We have been contacted by the owners of Horiseon to improve the code for their website to help improve their Search Engine Optimization and minimize the amount of written code.

### What Was Changed?
1. Retitled the title to Horiseon
2. Restructured the file layout to put the index.html file directly in the root folder
3. Moved assets folder directly into root folder and deleted "develop" folder
4. Changed the div class "header" to the semantic header tag
5. Added accessibility descriptions for the search engine optimization, online reputation management, and social media marketing pictures
6. Changed the div class "footer" to the semantic footer tag
7. Changed div class "content" and "benefits" to semantic section tags
8. Noticed the the 3 h3 tags in the benefits section were all repeating themselves in the css, so I made a single h3 selector that had the necessary properties
9. Noticed all three content section images css properties were repeating themselves, so got it under one css selector with their necessary properties
10. Noticed all three content h2 css properties were repeating themselves, so I got it into one css selector with the necessary properties
11. Noticed the "search engine optimization" link in the navbar wasn't redirecting to it's section on the page and fixed it.
12. Was able to condense the search engine optimization, online reputation management, and social media marketing css from three individual selectors into one.

### Link and Screenshot to Deployed Application
Visit https://jschaefmn.github.io/horiseon-refactor/

<img src="./assets/images/horiseon-deployed-site.png">