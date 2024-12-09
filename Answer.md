Welcome to the HTML5 Basics Assignment repository!
This assignment is designed to help you build foundational knowledge of HTML5, understand its structure, and practice creating web page content using semantic elements.

Learning Objectives
By completing this assignment, you will:

Understand the structure and purpose of HTML5 in web development. Learn to create basic web page content using core HTML5 elements. Explore semantic HTML elements and their benefits for readability and SEO. Gain a basic understanding of accessibility and SEO best practices in HTML.

Assignment Content
HTML5 Basics Learn the structure of an HTML document (e.g., , , , ). Explore core elements such as headings, paragraphs, lists, links, and images.
Semantic HTML Introduction to semantic tags like , , ,
, and . Learn how semantic elements improve content readability and support SEO.
Accessibility and SEO Basics Understand the importance of accessible HTML and SEO-friendly practices. Use attributes like alt, title, and semantic structures to improve usability.
Activities
Creating a Simple Webpage: Design a basic webpage that includes text, images, and links. Use common HTML tags like h1, p, a, img, and ul or ol. Structure a webpage with semantic tags such as header, footer, nav, section, and article. Ensure the content is well-organized for readability and SEO.

Answers

Here's a simple web page example based on your learning objectives, incorporating HTML5 structure, semantic HTML, and accessibility practices:

<title>My Accessible Web Page</title>
<!-- Header Section -->
<header>
    <h1>Welcome to My Accessible Web Page</h1>
    <nav>
        <ul>
            <li><a href="#home" title="Go to Home section">Home</a></li>
            <li><a href="#about" title="Go to About section">About</a></li>
            <li><a href="#contact" title="Go to Contact section">Contact</a></li>
        </ul>
    </nav>
</header>

<!-- Main Content Section -->
<section id="home">
    <h2>Home</h2>
    <p>Welcome to my website! This page is designed with HTML5 and aims to follow best practices for accessibility and SEO.</p>
    <img src="image.jpg" alt="An example image of a website" width="300">
</section>

<!-- About Section -->
<section id="about">
    <h2>About Us</h2>
    <article>
        <h3>Our Mission</h3>
        <p>I aim to create content that is both accessible and user-friendly. my focus is on improving SEO and user experience through proper HTML structure.</p>
    </article>
</section>

<!-- Contact Section -->
<section id="contact">
    <h2>Contact</h2>
    <p>For inquiries, please reach us at <a href="mailto:info@example.com">info@example.com</a>.</p>
</section>

<!-- Footer Section -->
<footer>
    <p>&copy; 2024 My Accessible Web Page. All rights reserved.</p>
</footer>
Key Features:

HTML5 Structure:
The document starts with to indicate HTML5.

The , , and tags structure the page.

The tag specifies the character set and viewport settings.

Semantic HTML:
: Contains the main header and navigation links for the page. : Defines the navigation menu.
: Organizes content into sections like Home, About, and Contact. : Defines a standalone piece of content, such as the "Our Mission" text. : Contains footer information.
Accessibility and SEO:
Alt text on images: The alt attribute improves accessibility by describing the image content for screen readers.

Semantic Tags: Using tags like

, , and
improves the content’s structure, making it more readable and SEO-friendly.
Links with title attribute: The title attribute provides additional context for links.

Email link: The mailto: link allows users to easily contact via email.

This structure helps with both user experience and search engine optimization, improving the web page's readability and accessibility.
