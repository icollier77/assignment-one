# 01 HTML CSS Git: Code Refactor

## Project Goal

This is the website (landing page) for Hori*seo*n - a digital media marketing agency. 

The website has to adhere to the accessibility standards to ensure its higher SEO ranking and higher usability. 

The goal of this project is to refactor the existing code to make sure that the site is more accessible.

----
### Original Website Design

The screenshot below shows how the website is supposed to look. Any changes made to the website during refactoring should not alter its appearance. 

![Alt text](../assignment1/Assets/01-html-css-git-challenge-demo.png)

----

## Changes Made

I made the following changes to the code to increase the website's accessibility:
1. Replaced non-semantics elements (eg, "div") with semantic elements as much as possible. Semantic elements convey information about the content to the screen readers and clarify the logical structure of the page. 
2. Added a title to the meta description.
3. Changed h3 to h4 in the footer to ensure the logical structure of the page.
4. Added alt descriptions to all images.
5. Fixed broken navigation link (added id) and cleaned the code by removing / in the closing tags and the unnecessary closing tag for img.
6. Consolidated properties and selectors in the css file in accordance with the DRY principle. 
7. Added comments to the html and css files to clearly show the purpose of each section of the code. This simplifies any editing aftewards, especially by other programmers.
   

-----
-----

## Project Takeaways

This project showed the importance of selecting each HTML element with the accessibility in mind. I asked myself the following questions when evaluating which element I should use: 
* What meaning does this part has in the overall page?
* How important is it? 
* Is it connected to other elements?
* If a person used the tab key to navigate the website, should s/he navigate to this part?
* Can this part be a standalone content on some other website?

It was especially interesting to consider the difference between 'section' vs 'article', and 'aside' vs 'div'.

----
 ## Link to deployed web application

