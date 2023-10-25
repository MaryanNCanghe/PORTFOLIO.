#MY PORTFOLIO FINAL PROJECT
####Video Demo: https://www.youtube.com/watch?v=AzL7Aabz_LE

 
####Description

Table of Contents
Introduction
Features
Technologies Used
Description


#Introduction
As a students of CS50, I have worked on a variety of projects that demonstrate my expertise in different domains and Languages.
This project portfolio serves as a comprehensive collection of my work, providing my potential skills and a overview of what I can do.

To access and explore my project portfolio, follow the link:
https://maryanncanghe.github.io/PORTFOLIO./#home


Technologies Used
The portfolio website is built using the following technologies:

HTML5
CSS3
JavaScript

Description:
I've designed my portfolio with a structured layout, making it easy for visitors to navigate and explore my projects. The table of contents helps users quickly find the information they are interested in.

To make my portfolio visually engaging, I've incorporated interactive elements using JavaScript and css . This includes animations, transitions, and interactive project demos to give visitors a dynamic and immersive experience.

I've also made sure to include my contact information in the portfolio. This makes it easy for potentia collaborators to reach out to me. I've included links to my professional social media profiles, my email address, 
and even a contact form for convenience.

In the Portfolio section, I've listed the technologies I used to build my wesites. This serves as a testament to my technical skills and gives visitors an idea of my proficiency in web development and related fields.

I'll explain each section of the HTML code:

**Header Section (`<header>`):**
   - The header contains the website's logo and navigation menu.
   - The logo is a text "N ' Canghe."
   - The navigation menu (`<ul>`) consists of links to different sections of the webpage, such as Home, About, Services, Skills, Portfolio, and Contact.
   - There is also a menu icon with the class "fa-bars," indicating a mobile navigation menu toggle.

**Home Section (`<section id="home">`):**
   - This section represents the home and landing page of the website.
   - It includes a greeting, a changing text element that cycles through different roles (Web-Developer, Designer, Administrator, Artist, Musician), a brief description, contact information, buttons for downloading a CV and hiring, and social media icons.
   - There is also an SVG animation with a liquid shape in the background.

**About Section (`<section id="about">`):**
   - This section provides information about me.
   - It includes a title, a brief introduction, and a button to "Know More." That sent to the 'about.html' page.
**Services Section (`<section id="services">`):**
   - This section outlines the services provided by me.
   - It has a title, descriptions of services (Business Administration, Graphic Designer, Web Developer), and buttons for reading more about each service.

**Skills Section (`<section id="skills">`):
   - This section presents technical and professional skills.
   - It includes a title, a list of technical skills with progress bars, and a list of professional skills with circles indicating the skill level. Done with javaScript tools.

**Portfolio Section (`<section id="portfolio">`):
   - It includes a title, filter buttons for different categories (Products, Designs, Web-sites), and a gallery of projects with images, project titles, and links to view more details.

**Contact Section (`<section id="contact">`):
   - This section provides a form for contacting me.
   - It includes a title, a form with fields for name, email, address, phone number, and a message.
   - There is also a "Send Message" button to submit the form.

**Footer Section (`<footer>`):
   - The footer contains a copyright notice and an arrow icon that allows users to scroll back to the top of the page.

**Scripts:**
   - The HTML includes script tags for "mixitup.min.js" and "script.js.".


Know i will explain each section of the Script.js file code:
**Split Text into Letters:** (#home)
   The code begins by selecting all elements with the class "word." It then loops through each word, splits the text content of each word into individual letters, and replaces the word's content with individual `<span>` elements for each letter. This is done to achieve a text animation effect where each letter can be individually manipulated.

**Text Animation:**
   I set up a mechanism for animating the words. It defining the `changeText` function, which, when called, animates the transition between words. It fades out the letters of the current word one by one and fades in the letters of the next word, creating a smooth transition effect. The `setInterval` function is used to call this function every 3 seconds to create an automatic word rotation effect.

 **Circle Skill Animation:**(#skills)
   This function selects elements with the class "circle" and calculates the number of dots and the percentage marked. It then creates a set of div elements ("points") to represent the circular skill animation, rotating them around the circle. It marks a percentage of these points as "marked" to represent the skill level.

4. **MixItUp Portfolio Section:**(#portfolio)
   This part of the portfollio utilizes the MixItUp library to enable filtering and sorting functionality for a portfolio gallery. It initializes MixItUp for the elements with the class "portfolio-gallery."

**Active Menu Highlighting:**(#Navbar)
   The highlights on the active menu item based on the section in view. It selects menu items and sections, and as the user scrolls, it determines which section is currently in view and applies the "active" class to the corresponding menu item.

**Sticky Navbar:**
   I used This class to make the navigation bar stick to the top of the page after scrolling past a certain point.

**Toggle Mobile Menu:**
   The function handles the opening and closing of a mobile menu. When a menu icon is clicked, it toggles the "fa-xmark" class on the icon and adds or removes the "open" class on the navigation list, making it visible or hidden. It also closes the menu when the user scrolls.

**Parallax Scrolling:**
   The function uses the Intersection Observer API to add a "show-items" class to elements with specific classes (`scroll-scale`, `scroll-bottom`, and `scroll-top`) when they come into or go out of the viewport. This class is likely used to trigger parallax or other scrolling-related animations.


The stylesheet contains rules for various elements on a webpage, including fonts, colors, layouts, and animations. Here's a breakdown of some of the key sections and rules in this CSS file:

 **Font and Color Definitions:**
   - Define the font-family for the entire webpage, setting it to "Poppins" with a fallback to a generic sans-serif font.
   - Sets the background color and text color for the body of the webpage.

 **Header Styles:**
   - the webpage's header, includes positioning it at the top of the page, making it fixed, and defining its background color and border.

**Logo Styles:**
   - Styles for the logo element, specifying the font size, weight, and letter spacing.

**Navigation Styles:**
   - include the colors, font weight, and padding.
   - Defines styles for hover and active states of navigation links.
   - Includes a CSS rule for a mobile menu icon.

**Home Section Styles:**
   -  Include it minimum height, layout, and spacing.

**About Section Styles:**
   -  include text and image alignment, and background color.

**Services Section Styles:**
   - include layout and spacing.
   - Defines styles for individual service boxes and icons.

**Skills Section Styles:**
   - Include layout and spacing.
   - Defines animations for skill bars. (JAVASCRIPT)

**Gallery and Portfolio Styles:**
   - I utilize the grid layouts and image effects.
   - animations for portfolio items on hover.
   - Styles for filter buttons.

**Contact Section Styles:**
    - Its a form , with submission button.
    - Special styles for form submission confirmation. (sumit.html)

**Footer Styles:**
    -  padding, alignment, and colors.
  
**Media Queries:**
    - Contains media queries to make the webpage responsive for different screen sizes.
    - Adjusts font sizes, layouts, and other styles for smaller screens.

**Keyframes:**
    - Defines keyframe animations for various elements, including morphing, glowing, and skills progress bars.
  

These different sections of the code work together to create various dynamic effects and functionality on a web page, including text animations, filtering and sorting of a portfolio, responsive navigation behavior, and parallax scrolling effects.



Reasons that i for Choose to Be My Own Portfolio:

I decided to build my own portfolio for several reasons:

Showcasing My Skills, creating my own portfolio allowed me to showcase my technical skills, creativity, and attention to detail. It's a tangible representation of what I can do as a developer.

Customization, I wanted complete control over the design and functionality of my portfolio. By building it from scratch, I could tailor it to represent my style and personality.

Learning Experience, The process of creating my portfolio was a valuable learning experience. I had the opportunity to experiment with new technologies, design principles, and coding practices.

Ownership, I have full ownership and control over the content of my portfolio. I can update it at any time to reflect my latest work and achievements.

My portfolio is an essential part of my professional branding. It tells my story, highlights my accomplishments, and leaves a positive impression on peoples.

It isn't just a list of skills, it's a demonstration of those skills in action. It's a powerful representation of my abilities.

In conclusion, my project portfolio is a strategic and rewarding choice for self-promotion and professional development. It's a testament to my dedication to excellence in Devlopig World, and I'm excited to continue 
expanding and improving it as my career progresses.




I welcome and feedback to improve my project. If you have suggestions or improvements to the existing content,
please don't hesitate.

