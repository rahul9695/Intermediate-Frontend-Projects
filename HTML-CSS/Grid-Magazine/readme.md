# Preview Link

https://rahul9695.github.io/Intermediate-Frontend-Projects/HTML-CSS/CGrid-Magazine/index.html

## HTML Code Explanation:

- `<!DOCTYPE html>`: Declares the document type and version of HTML.
- `<html lang="en">`: The root element of an HTML page, with the language attribute set to "en" for English.
- `<head>`: Contains metadata about the document, like character encoding and title.
  - `<meta charset="UTF-8">`: Specifies the character encoding of the document as UTF-8.
  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Sets the viewport settings for responsive design.
  - `<title>Magazine</title>`: Sets the title of the web page to "Magazine."
  - External resource links:
    - Google Fonts and Font Awesome are linked to for custom fonts and icons.
    - `<link rel="stylesheet" href="styles.css">` links an external CSS file.
- `<body>`: Contains the visible content of the web page.
  - `<main>`: Represents the main content of the page.
    - `<section class="heading">`: A section containing the heading and article metadata.
      - `<header class="hero">`: The header section with a hero image and title.
        - `<img src="..." alt="..." class="hero-img">`: An image element.
        - `<h1 class="hero-title">`: The main title.
        - `<p class="hero-subtitle">`: A subtitle.
      - `<div class="author">`: Information about the author.
        - `<p class="author-name">`: Author's name with a link.
        - `<p class="publish-date">`: Publication date.
      - `<div class="social-icons">`: Social media icons with links.
- `<section class="text">`: A section for the article text.
  - Paragraphs and other content.
- `<section class="text text-with-images">`: A section with text and images.
  - `<article class="brief-history">`: An article with a list of historical information.
    - `<ul class="lists">`: An unordered list.
      - List items with historical information.
  - `<aside class="image-wrapper">`: An aside section with images and a quote.
    - `<img src="..." alt="..." class="image-1">`: Images.
    - `<img src="..." alt="..." class="image-2">`
    - `<blockquote class="image-quote">`: A blockquote with a quote.

## CSS Code Explanation:

- `*`, `::before`, `::after`: Universal selector and pseudo-elements.
  - Resets margin, padding, and box-sizing for all elements.

- `html`:
  - Sets the base font size to 62.5% (10px on a 16px default font).

- `body`:
  - Sets the font family to 'Baskervville' with a fallback to serif fonts.
  - Sets text color to linen.
  - Sets background color to a dark blueish-gray (rgb(20, 30, 40)).

- `h1`:
  - Sets the font family to 'Anton' with a fallback to sans-serif fonts.

- `h2`, `h3`, `h4`, `h5`, `h6`:
  - Sets the font family to 'Raleway' with a fallback to sans-serif fonts.

- `a`:
  - Removes text decoration (underlines) from anchor links.
  - Sets the text color to linen.

- `main`:
  - Defines styles for the main content area.
  - Uses CSS Grid for layout:
    - Three columns, with flexible middle content.
    - Rows have a 3rem gap.

- `img`:
  - Makes all images responsive by setting their width to 100%.
  - Ensures images cover their containers using `object-fit`.

- `hr`:
  - Styles horizontal lines, setting margin and border properties.

- `.heading`:
  - Styles the heading section:
    - Spans the middle column.
    - Uses CSS Grid with 2 equal-width columns and vertical spacing.

- `.text`:
  - Styles the article text:
    - Spans the middle column.
    - Sets font size, letter spacing, and column width.
    - Aligns text justified.

- `.hero`:
  - Styles the hero section:
    - Spans the full width.
    - Uses a relative position for child elements.

- `.hero-title`:
  - Styles the hero title with a large font size and orangered color.

- `.hero-subtitle`:
  - Styles the hero subtitle with a smaller font size and orangered color.

- `.author`:
  - Styles author information with font and size settings.

- `.author-name a:hover`:
  - Adds a background color on hover to author's link.

- `.publish-date`:
  - Sets the color for the publication date.

- `.social-icons`:
  - Styles social media icons with a grid layout and font size.

- `.first-paragraph::first-letter`:
  - Styles the first letter of the first paragraph with a large size, orangered color, and float.

- `.quote`:
  - Styles blockquotes with a blueish-green color, font, and text alignment.

- `.quote::before`, `.quote::after`:
  - Adds double quotes to the blockquote content.

- `.text-with-images`:
  - Styles a section with text and images using CSS Grid for layout.
  - Adjusts spacing and responsiveness for different screen sizes.

- `.lists`:
  - Removes list styling (bullets) and sets top margin for unordered lists.

- `.lists li`:
  - Adds margin between list items.

- `.list-title`, `.list-subtitle`:
  - Styles list titles and subtitles with a blueish-green color.

- `.image-wrapper`:
  - Styles the aside section with images.
  - Uses CSS Grid with 2 columns and 3 rows.
  - Sets the gap between grid items.

- `.image-1`, `.image-2`, `.image-3`:
  - Styles images within the image wrapper.
  - Adjusts their grid placement and sizes.

- Media queries:
  - Apply responsive styles for different screen widths.
  - Adjust font sizes and layout for smaller screens.
