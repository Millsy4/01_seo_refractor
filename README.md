# Project Information

In this project I was tasked with essentially improving existing code to meet SEO and accessibility standards.  In order to accomplish this, I had to change the non-semantic code to semantic code, which included changes such as: making the div with header, main content, the side content, and the footer to the semantic tags header, main, aside, and footer respectively.  After this I had to change the CSS to match the new tags, which also allowed me to delete some unnecessary CSS, such as the multiple ones referencing the imgs that were the exact same, and consolidate them into one line of CSS.  This allowed the CSS to be more concise and therefore easier to read/find relevant information.

After this I added alt attributes to all of the images in order to ensure two things: 1) if they did not load, they would display information about the picture and 2) that if the person was using a screen reader, it would be able to tell them what the picture was supposed to depict in that location.  However, one of the images, the background one, had to have the source added to the html and removed from the CSS in order to add a working alt attribute to it.

After this, I changed the div tags within the header content to nav tags with ids referencing the place where they were supposed to link to, therefore fixing the link functionality and improving the code to SEO standards.  I also had to go in and change the CSS that referenced these tags to the new tags, which allowed me to then remove some extra CSS that was essentially repeating the same information.  For the title, I changed it to describe the website by adding the website's name and information to the title tag within the HTML.

#######################################################################################################################################################################################

# 01 HTML CSS Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
