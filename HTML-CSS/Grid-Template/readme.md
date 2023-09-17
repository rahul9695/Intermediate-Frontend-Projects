# Preview Link

https://rahul9695.github.io/Intermediate-Frontend-Projects/HTML-CSS/Grid-Template/index.html

## HTML Code Explanation

- `<!DOCTYPE html>`: Declares the document type and HTML version as HTML5.
- `<html lang="en">`: Defines the HTML document, specifying the language as English.
- `<head>`: Contains metadata about the document, including character encoding, viewport settings, and the page title.
   - `<meta charset="UTF-8">`: Sets the character encoding to UTF-8 for handling various characters and symbols.
   - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Configures the viewport settings for responsive design.
   - `<title>Grid Template || CSS Grid Project</title>`: Sets the webpage title.
   - `<link rel="stylesheet" href="./styles.css">`: Links an external CSS stylesheet for styling.
- `<body>`: Encloses the main content of the webpage.
   - `<main class="test-grid">`: Defines the main content container with the class "test-grid."
   - Inside the main container, there are several articles representing user testimonials.
   - Each article contains:
     - A profile section with an image, name, and graduate status.
     - Paragraphs containing user testimonials and feedback.
     - Background color and text color classes for styling.
- The articles are organized within the main container to display user testimonials and feedback.

## CSS Code Explanation

| Selector                   | Property-Value Pairs                                                                                                      | Explanation                                                                                                                                   |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| `@import`                  | `url('https://fonts.googleapis.com/css2?family=Barlow+Semi+Condensed:wght@200;300;400;500;600;700;800;900&display=swap');` | Imports the 'Barlow Semi Condensed' font family from Google Fonts and makes it available for use in the stylesheet.                            |
| `:root`                    | `--clr-primary-100: 263 55% 52%;`<br>...<br>`--fs-3: 1.25rem;`                                                            | Defines CSS custom properties (variables) to store color values, font families, font weights, and font sizes for easy reuse throughout the stylesheet. |
| `*`, `*::before`, `*::after` | `box-sizing: border-box;`                                                                                                | Sets the `box-sizing` property to `border-box` for all elements, ensuring that padding and border are included in the element's total width and height.  |
| `body`                     | `display: grid;`<br>`place-content: center;`<br>...<br>`line-height: 1.5;`                                                | Styles the `body` element with a grid layout to center its content both vertically and horizontally. Also sets font properties and background color. |
| `h2`, `p`                  | `margin: 0;`<br>`font-weight: var(--fw-500);`                                                                           | Applies styles to `h2` and `p` elements, including removing margins and specifying font weight.                                             |
| `.test-grid`               | `display: grid;`<br>...<br>`width: min(95%, 70rem);`                                                                   | Styles a grid container named `.test-grid` with responsive width and various grid-related properties.                                        |
| `.test.quote`              | `background-image: url("...");`<br>...                                                                                 | Applies styles to elements with both `.test` and `.quote` classes, including a background image and positioning.                            |
| `.test:nth-child(1)` ... `.test:nth-child(5)` | `grid-area: one;`<br>...<br>`grid-area: five;`                                                                        | Assigns specific grid areas to elements with `.test` class based on their order.                                                             |
| `.test`                    | `font-size: var(--fs-500);`<br>...<br>`box-shadow: ...;`                                                               | Styles elements with the `.test` class, including font size, padding, border-radius, and box shadow.                                          |
| `.text-neutral-100`, `.text-secondary-100`, ... | `color: ...;`                                                                                                           | Defines classes to set text colors based on custom color variables defined earlier.                                                            |
| `.bg-primary-100`, `.bg-secondary-100`, ... | `background: ...;`                                                                                                      | Defines classes to set background colors based on custom color variables defined earlier.                                                      |
| `.profile`                 | `display: flex;`<br>`gap: 1rem;`                                                                                       | Styles elements with the `.profile` class as a flex container with a gap between child elements.                                             |
| `.test img`                | `width: 1.75rem;`<br>`aspect-ratio: 1;`<br>`border-radius: 50%;`                                                        | Styles images within elements with the `.test` class, controlling their width, aspect ratio, and border-radius.                                |
| `.border`                  | `border: 2px solid #a775f1;`                                                                                           | Defines a class to apply a 2px solid border with a specific color.                                                                              |
| `img`, `picture`           | `max-width: 100%;`<br>`display: block;`                                                                                 | Styles images and picture elements to be responsive and display as block elements.                                                            |
| `.test .name`, `.test .graduate` | `font-size: ...;`<br>...<br>`opacity: ...;`                                                                         | Styles elements with `.name` and `.graduate` classes, specifying font size and opacity.                                                        |
| `.test > p:first-of-type`, `.test > p:last-of-type` | `font-size: ...;`<br>...<br>`opacity: ...;`                                                                     | Styles the first and last paragraphs within elements with the `.test` class, setting font size and opacity.                                   |
| `.flow > *:where(:not(:first-child))` | `margin-top: 1em;`                                                                                                    | Adds top margin to child elements within an element with the `.flow` class, except for the first child.                                      |
| `@media` queries           | Varying CSS properties based on screen width                                                                            | Defines responsive design breakpoints using media queries to adjust styles for different screen sizes.                                        |
