# Flexbox Tasks

This repository contains HTML and CSS files for a series of tasks related to using Flexbox for layout design.

## Task 0: Add display flex

- Use the starter HTML and CSS files from this task to task 7.
- Copy the contents of the starter files into the files (0-index.html and 0-styles.css for this task) that you need to produce and make the necessary changes according to the task description.
- Add the external CSS file to the HTML using `<link rel='stylesheet' href='0-styles.css'>`.
- Set the property `display: flex;` for the row class inside your CSS.
- Entirely remove the row::after declaration and remove the float: left inside [class*='col-'].
- All elements should now appear the same as before using the float.

Repo:
GitHub repository: alx_html_css
Directory: flexbox
File: 0-index.html, 0-styles.css

## Task 1: Add new classes on sections

- Add specific classes to the outermost section tags for services, works, about, latest_news, testimonial, and contact.
- Use these classes to target specific sections in your CSS for styling.

Repo:
GitHub repository: alx_html_css
Directory: flexbox
File: 1-index.html, 1-styles.css

## Task 2: Reverse order Latest news cards

- Use flex-direction property to reverse the order of cards inside the Latest News section.
- Set `flex-direction: row-reverse` for the row class inside section-latest-news.

Repo:
GitHub repository: alx_html_css
Directory: flexbox
File: 2-index.html, 2-styles.css

## Task 3: Simplify services list

- Remove the second ul in the Services section and place the li elements under the first ul.
- Set `flex-wrap: wrap` for the row class inside the section-services.

Repo:
GitHub repository: alx_html_css
Directory: flexbox
File: 3-index.html, 3-styles.css

## Task 4: Playing around with the spacing between flex service items

- Adjust widths and margins for better spacing between flex service items.
- Use calc() to set widths for .col-1-3 and .col-1-2.
- Remove padding and set margin to 1rem for [class*='col-'].
- Adjust margins in ul.row declaration.

Repo:
GitHub repository: alx_html_css
Directory: flexbox
File: 4-index.html, 4-styles.css

## Task 5: Flexify the header

- Wrap header-logo and navbar-menu with a div with header-container class.
- Set `display: flex; justify-content: space-between;` for the header-container class.
- Remove unnecessary rules related to header-logo and navbar-menu.

Repo:
GitHub repository: alx_html_css
Directory: flexbox
File: 5-index.html, 5-styles.css

## Task 6: Flexify the navbar

- Set `display: flex;` for the nav class.
- Remove the display declaration inside .nav .nav-item.
- Adjust margin for .nav .nav-item + .nav-item.

Repo:
GitHub repository: alx_html_css
Directory: flexbox
File: 6-index.html, 6-styles.css

## Task 7: Align center logo and navbar

- Set `align-items: center;` for the header-container class.

Repo:
GitHub repository: alx_html_css
Directory: flexbox
File: 7-index.html, 7-styles.css
