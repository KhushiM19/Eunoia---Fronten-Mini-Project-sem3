# Eunoia---Fronten-Mini-Project-sem3

<h1>About the Website : “eunoia”</h1>
Eunoia is a creative and modern web-based platform designed to explore fashion and beauty trends, while encouraging self-expression through curated moodboards. It offers a visually engaging and user-friendly interface, providing users with tutorials, styling tips, and interactive features like audio, video, and image content across multiple web pages.

<h1>Concepts & Functionalities Used</h1>
HTML5 Semantic Elements: Structured layout using <section>, <header>, <nav>, etc.
CSS Styling: UI design, transitions, and responsive layout with media queries.
JavaScript: Interactivity for modals, form validation, and dynamic content.
Modals: "Learn More" section uses custom JavaScript modals.
Embeds: <iframe>, <audio>, and <video> for multimedia content.
Tables & Lists: Organize categories and trends effectively.
Form Validation: Ensures clean input on login/register pages.
Responsive Design: Fluid containers and breakpoints for all devices.
html2canvas: Captures moodboard section as an exportable image.

<h1>User Interface & Experience</h1>
Minimal and Trendy Design: The UI uses soft colors, a serif logo font (Tan Pearl), rounded corners, and bento-style layout blocks to enhance aesthetic appeal.
Glassmorphism Effects: Subtle use of frosted-glass backgrounds adds modern UI feel.
Clean Navigation: Clearly labeled navigation bar with smooth transitions.
Interactive Media: Embedded audio and video keep the site engaging.
Resonsive Design: Responsive across screen sizes due to media queries.

<h1>Web Page Descriptions</h1>

<h3>1. Homepage</h3>
The homepage serves as the central hub of the website, welcoming users with a hero section that includes the brand’s tagline and a brief introduction. It features a clean header with navigation links, a search bar, and a sign-in button. Below the hero, the content is divided into featured categories: Fashion Trends (with image), Beauty, and Moodboard creation.
Additional sections include:
Trending Styles Table – A tabular overview of current style popularity.
Fashion Categories List – A list highlighting fashion niches.
Audio Podcast Player – Shows the usage of <audio> tag.
Video Section – Shows the usage of <video> tag.
A modal with glass morphism (using css)  is also implemented to provide more details about Eunoia through the “Learn More” button.

<h3>2. Fashion Page</h3>
The fashion page focuses on current and emerging trends. It includes images, detailed style descriptions, and a curated list of popular categories like Streetwear, Minimalist looks, and Statement Jewelry. 
Major Tags Used: <div>, <img>, <iframe>, <ul>, <li>, <button>, <span>, <script><a>.
<h4> Main Features:</h4>
<li>Slick Carousel for trendy outfit sliding.</li>
YouTube iframe for embedded fashion videos.
Toggle Details JavaScript function to show/hide more info.


CSS Highlights:
border-radius, box-shadow, and object-fit for clean visuals.
hover effects on cards and buttons.
Smooth transition animations for UI polish.


3. Beauty Page
The Beauty page introduces users to top beauty trends, skincare tips, and curated product recommendations. A welcoming header leads into a product carousel that showcases must-have items with reviews, images, and direct links to shop.
Main Features:
Interactive Product Carousel displaying skincare items with ratings and external links.
Ingredient of the Week section, currently spotlighting Niacinamide, with benefits listed using <ul> and <li>.
Skincare Routine Notepad Section presents daily care steps using a visually distinct styled list (<ol>), designed like a notepad for better readability.
Makeup Tutorials Video Grid implemented using multiple <iframe> tags for YouTube videos arranged in a grid layout.


Major Tags Used:
 <section>, <img>, <a>, <button>, <ul>, <li>, <ol>, <iframe>, <p>, <div>, <h2>, <strong>, <em>
CSS Highlights:
border-radius and box-shadow used in product cards.
Styled notepad effect with unique font and padding.
Smooth transitions in carousel navigation.
Responsive video embedding.


4. Moodboard Page
 The Moodboard page allows users to visually express their style using images and text. Users can upload, drag, resize, and layer content. A checklist guides creation, and the board can be saved or exported.

 Major Tags Used: <html>, <head>, <body>, <input>, <button>, <script>, <textarea>, <div>, <ul>, <li>, <img>.

 Main Features:
Upload and drag-drop images onto canvas
Add and resize text areas
Export board as PNG using html2canvas, save/load via localStorage


CSS Highlights:
position: absolute for freeform layout
border-radius, box-sizing, and z-index for layering and polish
Soft pastel background, dashed text areas, and shadowed elements for aesthetic design


5. Login/Register Page
This is a clean, responsive, and user-friendly login and registration page designed for Eunoia, featuring smooth transitions between forms, client-side validation, and a modern pastel-themed aesthetic.
Key Features:
Dual Form Toggle:
 A single container holds both the login and registration forms. Users can easily switch between them with a smooth toggle by clicking “Sign Up” or “Login”.

Client-Side Validation:
JavaScript is used to validate:
Proper email formatting.
Minimum password length.
Matching passwords during registration.
Name validity using alphabet-only checks.

Visual Aesthetics:
Background: Soft pink-to-white vertical gradient.
Components: Rounded cards with subtle drop shadows.
Color Palette: Coral (#FF6F61) for buttons and highlights, paired with soft backgrounds and muted greys for readability.
Responsive & Centered Layout: The form container is centered both vertically and horizontally using Flexbox, ensuring it looks polished on both desktop and mobile devices.
Navigation:  Includes a “Back to Home” link for easy navigation to the main site.


Usage Notes:
Both forms currently use action="#" and method="POST" without backend integration.
The JavaScript prevents submission by default (for validation). Uncomment e.target.submit(); when connecting to a server.


