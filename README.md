# magazine




![Screenshot (104)](https://github.com/Tanishka-khamesara/magazine/assets/127411985/297f5083-4352-48a3-be8b-d15de72e3229)
![Screenshot (105)](https://github.com/Tanishka-khamesara/magazine/assets/127411985/46b00b60-2386-4111-ab1a-c5bf1f65f6a2)
![Screenshot (106)](https://github.com/Tanishka-khamesara/magazine/assets/127411985/ce852c24-9658-4013-bf3f-dda83eb3dbad)
![Screenshot (107)](https://github.com/Tanishka-khamesara/magazine/assets/127411985/10a95864-6704-4a98-a4a5-00039ab6d19f)
![Screenshot (108)](https://github.com/Tanishka-khamesara/magazine/assets/127411985/f7076c2b-8a5d-4730-9e39-b00b063bfe70)
![Screenshot (109)](https://github.com/Tanishka-khamesara/magazine/assets/127411985/fa90bfd0-9b08-4872-9715-41fc7b2c97bb)
![Screenshot (110)](https://github.com/Tanishka-khamesara/magazine/assets/127411985/bc94f4bc-1e29-4663-8100-6cba4cacaac7)
<!DOCTYPE html>: This declaration defines the document type and version of HTML being used. In this case, it's HTML5.

<html lang="en">: This is the opening tag for the HTML document. It specifies that the document is in English (the "en" attribute). All other HTML elements are contained within this element.

<head>: The <head> section contains meta-information about the document, such as character encoding, viewport settings, and links to external resources. It doesn't display any content on the web page itself.

<meta charset="UTF-8">: Specifies the character encoding of the document as UTF-8, which includes most characters from different languages.

<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport properties for responsive design, ensuring that the page adapts to various device screen sizes.

<title>Magazine</title>: Sets the title of the web page, which is typically displayed in the browser's title bar or tab.

<link href="./style.css" rel="stylesheet">: Links an external CSS stylesheet named "style.css" to apply styles to the HTML content.

<link href="https://fonts.googleapis.com/css?family=Anton%7CBaskervville%7CRaleway&display=swap" rel="stylesheet">: Links to Google Fonts to import and use the specified fonts in the document.

<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css">: Links to Font Awesome, providing access to a library of scalable vector icons.

<body>: The <body> section contains the visible content of the web page.

<main>: This is the main content container of the web page, where the primary content is placed.

<section class="heading">: This section contains the heading and introductory content for the web page.

<header class="hero">: This is the header section containing a logo, title, and subtitle.

<img src="..." alt="..." loading="lazy" class="hero-img">: An image of the freeCodeCamp logo with an "alt" attribute providing alternative text for screen readers. The "loading" attribute is set to "lazy" for lazy loading.

<h1 class="hero-title">OUR NEW CURRICULUM</h1>: The main title of the page.

<p class="hero-subtitle">...focus</p>: A subtitle providing additional information.

<div class="author">: This div contains information about the author and publication date.

<p class="author-name">By <a href="..." target="_blank" rel="noreferrer">freeCodeCamp</a></p>: The author's name with a link to the freeCodeCamp website.

<p class="publish-date">March 7, 2019</p>: The publication date.

<div class="social-icons">: This div contains social media icons with links to various platforms.

Social media links with Font Awesome icons.
<section class="text">: This section contains the main text content of the web page.

Several <p> elements: These represent paragraphs of text.

<blockquote>: A blockquote element used for quoting a specific text section.

<section class="text text-with-images">: Another section containing text and images.

<article class="brief-history">: An article section with a title.

<h3 class="list-title">A Brief History</h3>: A subheading.

<ul class="lists">: An unordered list containing historical information.

<li>: List items with subheadings and paragraphs of text.
<aside class="image-wrapper">: An aside section containing images and a blockquote.

Several <img> elements: These are images with "alt" attributes providing alternative text. They are also set to lazy load.

<blockquote class="image-quote">: A blockquote containing a quoted text.

This HTML code structures the content of a magazine-style web page and includes elements for text, images, links, and styling. The CSS stylesheet referenced in the <link> tag is likely used to style the page further, while Font Awesome icons enhance its visual appeal.


![Screenshot (111)](https://github.com/Tanishka-khamesara/magazine/assets/127411985/6d9fb525-80ff-4450-823f-53d19a5c5315)
![Screenshot (112)](https://github.com/Tanishka-khamesara/magazine/assets/127411985/dd4b6f60-9cb3-4654-b040-79e3c25b2ca8)

![Screenshot (113)](https://github.com/Tanishka-khamesara/magazine/assets/127411985/4dd73426-22b5-45fb-a349-66e58e4fdab3)
![Screenshot (114)](https://github.com/Tanishka-khamesara/magazine/assets/127411985/ce0713ef-760b-4296-abb7-fb16931741a5)
![Screenshot (115)](https://github.com/Tanishka-khamesara/magazine/assets/127411985/6a82b9e9-7a0c-4b71-aeb7-22061e670b9f)
![Screenshot (116)](https://github.com/Tanishka-khamesara/magazine/assets/127411985/a3452768-db71-437e-b01f-71f0c5853bcb)
![Screenshot (117)](https://github.com/Tanishka-khamesara/magazine/assets/127411985/e3e05536-b85a-44f2-98c9-56e04ab05c4d)
*, ::before, ::after: This rule applies the following styles to all elements, their before and after pseudo-elements. It's a common practice to reset or normalize default styles to ensure consistent styling across different browsers.

padding: 0;: Sets the padding to zero for all elements.
margin: 0;: Sets the margin to zero for all elements.
box-sizing: border-box;: Ensures that the padding and border are included in the element's total width and height, preventing unexpected layout issues.
html: Styles applied to the <html> element.

font-size: 62.5%;: Sets the base font size to 62.5% of the default font size (typically 16px). This makes it easier to use a relative unit like rem, where 1rem is equivalent to 10px.
body: Styles applied to the <body> element.

font-family: 'Baskervville', serif;: Sets the font family for the entire document to 'Baskervville' and falls back to a generic serif font if it's not available.
color: linen;: Sets the text color to linen.
background-color: rgb(20, 30, 40);: Sets the background color of the body to a dark blueish-gray.
Headings (h1, h2, h3, h4, h5, h6):

h1: Uses the 'Anton' font and sets the text color to orangered.
h2, h3, h4, h5, h6: Uses the 'Raleway' font for subheadings.
Links (a):

text-decoration: none;: Removes underlines from links.
color: linen;: Sets the link color to linen.
main: Styles applied to the <main> element.

display: grid;: Specifies that the main content is displayed as a grid layout.
grid-template-columns: Defines the grid columns, creating a central content area with two sidebars.
row-gap: 3rem;: Sets the gap between rows in the grid.
img: Styles applied to all images.

width: 100%;: Makes images responsive by ensuring they take up the full width of their container.
object-fit: cover;: Ensures that images maintain their aspect ratio and cover their container.
hr: Styles applied to horizontal lines (e.g., separators).

margin: 1.5rem 0;: Sets margins above and below the horizontal lines.
border: 1px solid rgba(120, 120, 120, 0.6);: Defines the border properties for the horizontal lines.
.heading: Styles applied to elements with the class "heading."

grid-column: Specifies the grid columns for this section.
display: grid;: Makes this section a grid.
grid-template-columns: Defines two columns within this section.
row-gap: Sets the gap between rows.
.text: Styles applied to elements with the class "text."

grid-column: Specifies the grid columns for this section.
font-size: Sets the font size for text.
letter-spacing: Adds letter spacing for readability.
column-width: Specifies the column width for text.
text-align: Justifies the text.
.hero: Styles applied to elements with the class "hero."

grid-column: Specifies that this section spans all columns.
position: relative;: Allows positioning elements inside this section.
.hero-title and .hero-subtitle: Styles for elements within the hero section.

.hero-title: Sets a large font size and text color.
.hero-subtitle: Sets font size and text color.
.author: Styles for the author section.

font-size: Sets the font size.
font-family: Specifies the font family.
.author-name a:hover: Styles applied when hovering over author links.

background-color: Adds a background color on hover.
.social-icons: Styles for the social media icons.

display: grid;: Specifies a grid layout for the icons.
font-size: Sets the icon size.
grid-template-columns: Defines the number of columns for the icons.
grid-auto-flow: Sets the flow of the grid items.
grid-auto-columns: Sets the width of grid columns.
align-items: Aligns grid items vertically.
.first-paragraph::first-letter: Styles the first letter of the first paragraph.

font-size: Increases the size of the first letter.
color: Sets the color.
float: Floats the first letter to the left.
margin-right: Adds margin to separate the letter from the text.
.quote: Styles applied to quoted text.

color: Sets the text color.
font-size: Sets the font size.
text-align: Aligns the text.
font-family: Specifies the font family.
.quote::before and .quote::after: Styles for pseudo-elements before and after the quoted text.

content: Adds content before and after the quoted text.
.text-with-images: Styles for sections with text and images.

display: grid;: Specifies a grid layout.
grid-template-columns: Defines two columns.
column-gap: Sets the gap between columns.
margin-bottom: Adds margin at the bottom of the section.
.lists and .lists li: Styles for lists and list items.

list-style-type: Removes list bullets.
margin-top and margin-bottom: Adds margin above and below list items.
.list-title and .list-subtitle: Styles for list titles and subtitles.

color: Sets the text color.
.image-wrapper: Styles for the image section.

display: grid;: Specifies a grid layout.
grid-template-columns and grid-template-rows: Defines the grid structure.
gap: Sets the gap between grid items.
place-items: Centers items within the grid.
Media queries: These adjust styles for different screen sizes (responsive design).

The first media query changes the layout of .image-wrapper for screens with a max width of 720px.
The second media query adjusts the layout of .text-with-images for screens with a max width of 600px.
The third media query further adjusts font sizes and social icon sizes for screens with a max width of 550px.
The fourth media query adjusts the font size of .hero-title
