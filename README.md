This README is a brief overview of the code files and their associated CSS styles. The code consists of five HTML files (index.html, about.html, contact.html, projects.html) and four CSS files (general.css, index.css, about.css, contact.css).

*HTML Files*
The HTML pages all contain a centered style with a light gray, white blue and orange combination for a simple presentation.
The nav bar serves as a tool for navigation through the website alongside a logo on the left corner as a secondary home/index button. However it uses the default font as i couldnt decide between few types i had in mind.

1. `index.html`: This filepage represents the homepage of the portfolio website. It includes a header with a logo and navigation menu, a main section with a hero banner and introductory text, and a footer with copyright information. It's main objective is to redirect the user to the desired location, and introduce a nice simple professional homepage.

2. `about.html`: This page contains brief personal information about the portfolio. It includes a header, a main section with details about the owner, including an image, description, and a list of skills, and a footer. The image is of myself :D, the <li> and <p> are centered to focus the user on the information only.

3. `contact.html`: This page contains a contact form for visitors to get in touch with the portfolios owner. It includes a header, a main section with a contact form, and a footer.
It keeps the theme of white and gray contrast for a simple yet appealing view. Form contains input for Name, Email and a brief Message for the owner.

4. `projects.html`: This page displays a list of projects. It includes a header, a main section with project cards (each card representing a project with a title, description, and a link), and a footer. It uses the section container for a smooth alignment and easy edit.

*CSS Files*

1. `general.css`: This file provides general styling rules for the website layout. It sets the font family, margin, padding, and background color for the body element. It styles the header, navigation, h1 headings, logo, menu, and footer. These styles ensure consistent design elements throughout the website. The body contents to be in a column direction with a centered style, nav to be reasonably spaced between the <a> alongside a hover dynamic option. It contains a <h1> edit in order to ensure consistency and a footer for a copyright info.

2. `index.css`: This file contains specific styles for the homepage (`index.html`). It styles the hero section with a background image, sets the font size and color for the h1 heading, and defines styles for links within the hero section. The background image lacks a accesibility feature although on the other hand the page's height is edited in order to avoid scrolling and be used as an intro only. The buttons are dynamic and serve as a secondary <a> compared to the nav bar.

3. `about.css`: This file contains specific styles for the about page (`about.html`). It styles the about section, including the alignment, padding, and text alignment. It also defines styles for the about content, including the image, paragraphs, and the unordered list of skills. The image is edited with rounded borders to display a portrait. The paragraph and list are centered with the <p> using a padding and the <li> containing no special order.

4. `contact.css`: This file contains specific styles for the contact page (`contact.html`). It defines styles for the title, contact section, contact form, form groups, labels, input fields, and the submit button. The form contains input styles text and email to ensure correct input of information. The section contents are centered as the rest of the website, using padding to properly space the input blocks. Button retains the theme and a hover display similar to that of the index page.

5. `projects.css`: This file contains specific styles for the projects page (`projects.html`). It styles the projects section, project cards, project titles, descriptions, and the links within the project cards. The cards contain info for the owners past projects and a <a> in blue to contrast the cards background and distinguish in order to spike interest of the user for further information.

The CSS files use classes to target and apply styles to specific elements, which helps maintain separation of concerns and enables consistent styling across multiple pages. The classes are defined in the HTML files and referenced in the CSS files using the `.class-name` selector. This approach allows for easier maintenance and scalability of the code.
