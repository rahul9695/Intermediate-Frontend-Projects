# Preview Link
https://rahul9695.github.io/Intermediate-Frontend-Projects/Amazon-Homepage-UI/index.html

## HTML Code Explanation 
- `<!DOCTYPE html>`: Declares the document type and HTML version as HTML5.
- `<html lang="en">`: Defines the HTML document, specifying the language as English.
- `<head>`: Contains metadata about the document, including character encoding, viewport settings, and the page title.
   - `<meta charset="UTF-8">`: Sets the character encoding to UTF-8 for handling various characters and symbols.
   - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Configures the viewport settings for responsive design.
   - `<title>Amazon-HomePage || HTML-CSS</title>`: Sets the webpage title.
   - `<link rel="stylesheet" href="./css/styles.css">`: Links an external CSS stylesheet for styling.
- `<body>`: Encloses the main content of the webpage.
   - `<header>`: Represents the webpage header, typically containing navigation menus and a logo.
   - `<section class="hero-section">`: Represents the hero or main content of the page.
   - `<section class="shop-section">`: Represents the shopping-related content of the page.
   - Inside the "shop-section," there are several "shop card" elements, each providing information about different products and a link to shop for them.
- `<footer>`: Represents the webpage footer, typically containing links and information about the website.
   - Lists of links are categorized into sections such as "Get to know Us," "Connect with Us," "Make Money with Us," and "Let Us Help You."
- Throughout the HTML structure, there are comments (`<!-- ... -->`) providing descriptions of different sections or elements within the code for clarity and maintenance.

## CSS Code Explanation

| Selector            | Property-Value Pairs                                      | Explanation                                                                                              |
| ------------------- | --------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| `html`              | `scroll-behavior: smooth;`                                | Enables smooth scrolling behavior when navigating to in-page anchor links, providing a visually pleasing scroll effect. |
| `*`                 | `margin: 0;`<br>`padding: 0;`<br>`box-sizing: border-box;`<br>`font-family: 'Open Sans', sans-serif;` | Resets the margin and padding for all elements and uses `box-sizing` to include padding and border in the element's total width and height. Sets the default font to 'Open Sans'. |
| `header`            | `width: 100%;`<br>`background-color: #000000;`           | Styles the header section to occupy the full width and have a black background color.                  |
| `.navbar`           | `height: 60px;`<br>`display: flex;`<br>`align-items: center;`<br>`justify-content: space-between;`<br>`cursor: pointer;`<br>`color: #fff;` | Styles the navigation menu with a fixed height, flex layout, and white text color. Creates space between navigation items and uses a pointer cursor. |
| `a`                 | `text-decoration: none;`<br>`color: #fff;`              | Removes underlines from links and sets the default text color to white.                                   |
| `.nav-logo img`     | `margin-top: 10px;`<br>`width: 128px;`                   | Adds margin at the top of the Amazon logo and sets its width to 128 pixels.                              |
| `.address .delivery` | `margin-left: 20px;`<br>`font-size: 0.8rem;`<br>`color: #ccc;` | Styles the delivery link with left margin, smaller font size, and gray color.                            |
| `.location:hover`   | `color: #ccc;`                                          | Changes the color of the location link to gray on hover.                                                |
| `.nav-search`       | `display: flex;`<br>`justify-content: space-evenly;`<br>`max-width: 620px;`<br>`width: 100%;`<br>`height: 40px;`<br>`border-radius: 4px;` | Styles the search bar container with flexible layout, even spacing, and rounded corners.           |
| `.select-search`    | `background: #f3f3f3;`<br>`width: 50px;`<br>`text-align: center;`<br>`border-top-left-radius: 4px;`<br>`border-bottom-left-radius: 4px;`<br>`border: none;` | Styles the search bar select element with a light gray background and rounded corners on the left side. |
| `.search-input`     | `max-width: 600px;`<br>`width: 100%;`<br>`font-size: 1rem;`<br>`border: none;`<br>`outline: none;`<br>`padding-left: 10px;` | Styles the search input field with a maximum width, borderless design, and left padding.                 |
| `.search-icon`      | `max-width: 45px;`<br>`width: 100%;`<br>`display: flex;`<br>`justify-content: center;`<br>`align-items: center;`<br>`font-size: 1.2rem;`<br>`background: #febd68;`<br>`color: #000;`<br>`cursor: pointer;`<br>`border-top-right-radius: 4px;`<br>`border-bottom-right-radius: 4px;` | Styles the search icon with a maximum width, centered content, background color, and pointer cursor. Adds rounded corners to the right side. |
| `.sign-in, .returns span` | `font-size: 0.875rem;`<br>`font-weight: 600;`        | Styles the sign-in and returns links with increased font size and bold text.                             |
| `.sign-in p, .returns p` | `font-size: 0.75rem;`                                   | Styles the text inside the sign-in and returns links with a smaller font size.                           |
| `.cart`             | `display: flex;`                                       | Applies flex layout to the cart section.                                                                  |
| `.cart p`           | `margin-top: 10px;`<br>`font-weight: 500;`             | Adds top margin and increases font weight for the cart text.                                             |
| `.header-banner`    | `padding: 10px 20px;`<br>`background: #222f3d;`<br>`color: #fff;`<br>`font-size: 0.875rem;` | Styles the header banner with padding, a dark background color, white text color, and a specific font size. |
| `.header-banner a:hover` | `color: #ccc;`                                      | Changes the color of banner links to gray on hover.                                                       |
| `.banner-content`   | `margin: 0 auto;`<br>`max-width: 1280px;`<br>`display: flex;`<br>`align-items: center;`<br>`justify-content: space-between;` | Styles the banner content with centered alignment, maximum width, and space between elements.             |
| `.menu`             | `max-width: 1280px;`<br>`display: flex;`<br>`align-items: center;`<br>`gap: 5px;`<br>`cursor: pointer;` | Styles the menu section with maximum width, flex layout, alignment, and a pointer cursor.                |
| `.menu svg`         | `margin-right: 7px;`                                  | Adds right margin to SVG icons within the menu.                                                           |
| `.links`            | `display: flex;`<br>`align-items: center;`<br>`list-style: none;`<br>`gap: 15px;`<br>`flex-grow: 1;`<br>`margin-left: 15px;` | Styles the links section with a flexible layout, aligned items, no list-style, spacing between items, and flexible growth. |
| `.links a`          | `padding: 10px 0;`                                    | Adds padding to the links in the links section.                                                           |
| `.deals a`          | `font-size: 0.9rem;`<br>`font-weight: 500;`<br>`white-space-collapse: collapse;`<br>`text-wrap: nowrap;` | Styles the "Shop deals in Electronics" link with specific font properties and text behavior.           |
