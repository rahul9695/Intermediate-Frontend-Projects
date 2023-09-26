# Preview Link 



# HTML Explanation

## Header (`<header>`)
The header section typically appears at the top of the webpage and serves as the main navigation area. In this specific HTML code:

- It contains a `<div>` with the class "nav," which holds the navigation and logo elements.
- The logo is an `<img>` element wrapped in an anchor `<a>` tag, creating a clickable logo that may link to the homepage.
- The navigation links are contained within a `<div>` with the class "nav-links," which is further divided into two parts: "page-links" and "social-links."
- "page-links" includes links to various sections of the webpage, such as Home, Intro, Services, etc.
- "social-links" contains links to social media profiles, utilizing font-awesome icons for popular platforms like Facebook and Twitter.

## Intro (`<div id="intro">`)
The intro section typically introduces visitors to the website's main content. In this HTML code:

- It is divided into two main parts: "intro-top" and "intro-bottom."
- "intro-top" includes a heading, a larger introductory text, a couple of paragraphs, and a quote from the CEO.
- The text provides an overview of the company's mission and services.
- An image of a consultant is placed on the right.
- "intro-bottom" consists of three "card-item" elements, each featuring a hexagonal icon, a heading, and a description. These represent the key services offered by the company.

## Services (`<div id="services">`)
The services section showcases various service packages offered by the company:

- "service-top-text" includes a heading and a larger subheading, introducing visitors to the services.
- "service-cards" contains a series of "service-card-item" elements, each representing a different service package.
- Each "service-card-item" includes an image, a heading, a description, bullet-pointed features, and a price.
- Users can click on "Details" to learn more about each service package.

## Service Details (`<div class="service-details">`)
The service details section provides more information about one of the service packages:

- The "details-img" displays an image related to the service.
- The "details-right" section contains text explaining the service in more detail.
- Sub-details are presented with counts and descriptions, showcasing the benefits of choosing the service package.

## Testimonials (`<div class="customer-testimonials">`)
The testimonials section displays comments from satisfied customers:

- "test-top-text" features a heading and introductory text.
- The "slider" contains a series of individual "testimonial" elements, each representing a customer testimonial.
- Each "testimonial" includes an image, a quoted comment, and the name and role of the customer.
- Users can navigate through testimonials, and a "scroll-bar" indicates more testimonials to the left.

## Call Me (`<div class="call-me">`)
The call me section encourages visitors to request a callback:

- It features two main parts: "call-me-left-text" and "call-me-form."
- "call-me-left-text" provides a heading, a subheading, and several bullet-pointed steps explaining the process.
- "call-me-form" displays a form where users can enter their name, phone number, email, select their service of interest, agree to terms, and submit their request.

## Projects (`<div class="projects">`)
The projects section showcases images of the company's projects:

- "project-top-text" includes a heading and subheading.
- "photos-links" offers filter options for the project images, including "Show All," "Design," "Development," "Marketing," and "SEO."
- The "photo-gallery" displays individual "photo-item" elements, each featuring an image, project name, and an overlay for additional information.

## Consultants (`<div class="consultants">`)
The consultants section introduces the team members:

- "consult-top-text" provides a heading and introductory text.
- "consult-profiles" contains individual "consult-card" elements for each team member.
- Each "consult-card" includes an image, the consultant's name, role, and links to their social media profiles.

## About (`<div class="about-wrapper">`)
The about section provides information about the company:

- It consists of two parts: "about-left-img" and "about-right-text."
- "about-left-img" displays an image related to the company.
- "about-right-text" includes a heading, a subheading, several bullet-pointed values or features, and statistics about the company's performance.

## Contact (`<div class="contact-wrapper">`)
The contact section offers contact details and a contact form:

- "contact-left-text" contains a heading, a subheading, and information about the company's location, phone numbers, and email.
- The "contact-social-links" section provides links to the company's social media profiles.
- "contact-form call-me-form" features a form with fields for name, email, message, and a checkbox to agree to terms, along with a "SUBMIT MESSAGE" button.


## Footer (`<div class="footer-wrapper">`)
The footer section typicall`yappears at the bottom of the webpage:

- "footer-left" contains a short description of the company.
- "footer-right" includes links categorized under "Links," "Tools," and "Partners."

## Copyright (`<div class="copyright-wrapper">`)
- The copyright section displays copyright information and the company name.

# CSS Explanation

1. Font Importation:

- Purpose: Importing custom fonts ('Montserrat' and 'Open Sans') from Google Fonts.
- Property: `@import url(...)`

2. Universal Selector Reset:

- Purpose: Resetting margins, padding, and box-sizing for all elements.
- Properties: `* { margin: 0; padding: 0; box-sizing: border-box; }`

3. Global Body Styles:

- Purpose: Setting font family for the entire document.
- Properties: `body { font-family: 'Open Sans', sans-serif; }`

4. Header Section:

- Purpose: Styling the header section, including a background image.
- Properties:
   - `#header { height: 110vh; ... }`
   - `background: linear-gradient(...), url(...);`
   - `background-size: cover;`
   - `background-attachment: fixed;`

5. Navigation Bar:

- Purpose: Styling the navigation bar, including its layout and logo.
- Properties:
   - `.nav { display: flex; ... }`
   - `.nav .logo { margin-block: auto; }`
   - `.nav .logo a img { width: 120px; }`

6. Navigation Links:

- Purpose: Styling navigation links, both the main links and social links.
- Properties:
   - `.nav-links { display: flex; ... }`
   - `.nav-links .page-links { display: flex; ... }`
   - `.page-links a { color: white; ... }`
   - `.page-links .active { color: rgba(0, 255, 191, 0.5); }`

7. Social Media Icons:

- Purpose: Styling social media icons with hexagon backgrounds.
- Properties: `.hexagon { background: url(...); ... }`

8. Header Text Content:

- Purpose: Styling the header's text content.
- Properties:
- `.header-center-text { color: white; ... }`
- `.header-center-text h1 { font-family: 'Montserrat', sans-serif; ... }`
- `.header-center-text p { color: rgba(255, 255, 255, 0.8); ... }`
- `.header-center-text a { ... }`

9. Intro Section:

- Purpose: Styling the introductory section with text and images.
- Properties: Various properties for layout and styling of the intro section.

10. Service Section:

- Purpose: Styling the service section with text, images, and pricing.
- Properties: Various properties for layout and styling of service cards and text.

11. Details Section:

- Purpose: Styling the details section with text and interactive elements.
- Properties: Various properties for layout and styling of details and interactivity.

12. Testimonials Section:

- Purpose: Styling the customer testimonials section with a slider.
- Properties: Styling for testimonials, slider, and navigation.

13. Call-to-Action Section:

- Purpose: Styling the call-to-action section with a contact form.
- Properties: Styling for the contact form and its components.

14. Projects Section:

- Purpose: Styling the projects section with a photo gallery.
- Properties: Styling for the photo gallery and buttons.

15. Consultants Section:

- Purpose: Styling the consultants section with profiles.
- Properties: Styling for consultant profiles and social links.

16. About Section:

- Purpose: Styling the about section with images and statistics.
- Properties: Styling for images, text, and statistic counters.

16. Contact Section:

- Purpose: Styling the contact section with contact details and a form.
- Properties: Styling for contact details, form fields, and social links.

17. Footer Section:

- Purpose: Styling the footer section with links and copyright information.
- Properties: Styling for footer links and copyright notice.

These sections collectively style different parts of a web page, making it visually appealing and functional.