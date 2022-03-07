# 🏗️ Refactor the code to meet Acceptance Criteria

Implement the following user story:

- AS A marketing agency
  I WANT a codebase that follows accessibility standards
  SO THAT our own site is optimized for search engines

## Acceptance Criteria

- GIVEN a webpage meets accessibility standards
  WHEN I view the source code
  THEN I find semantic HTML elements

- WHEN I view the structure of the HTML elements
  THEN I find that the elements follow a logical structure independent of styling and positioning

- WHEN I view the image elements
  THEN I find accessible alt attributes

- WHEN I view the heading attributes
  THEN they fall in sequential order

- WHEN I view the title element
  THEN I find a concise, descriptive title

## Assets

The following image demonstrates the web application's appearance and functionality:

![Webpage titled "Horiseon" features links for "Search Engine Optimization," "Online Reputation Management," and "Social Media Marketing." There is also a heading, a spot for an image and more content positioned relative to the right.](../assets/images/horiseon.png)

--

# Solutions

1. Title was changed to Horiseon
2. "Search engine optimization" was missing an ID that links to the UL ID in the header; ID was added.
3. All images were written with an alt attribute for accessibility.
4. The last image had a </img> at the end which was removed.
5. The last heading was changed to h4, for sequential order.
6. File name was changed to match the job description.
7. Comments were added for better readability.
8. for Benefit lead, brand and cost p... display: inline-block and text-align: center were added so text can look more organized.
9. The benefits class was disproportionate to the content... so I included a padding of 33px to the benefits class.
10. CSS link placed under title
11. Header element placed and removed (.) fromm css header.
12. Section elements added
13. Footer element added and (.) from css removed for footer since it is no longer a class.
14. Css classes were put into one due to identical properties.
15. Div's were changed to Nav's for header (for css styling as well)

---

© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.

# Code Refactor Starter Code
