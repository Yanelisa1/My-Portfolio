# HTML-CSS
Yanelisa# HTML-CSS   
WEEK 1
UNIT1: INTRODUCTION TO HTML,CSS AND JAVA SCRIPT

HTML is a markup language for web that defines the structure of web pages.
CSS is the language we use to style web page.
Javascript is  the programming language of the web.

WEEK1 
UNIT2: TEXT FORMATTING
HTML SYNTAX


HTML is a language used to structure web pages,it uses tags which are closing tagc(<p>) and opening tags(</p>).
HTML have four elements used for making up headlines, which are h1,h2,h3,h4,h5 and h6.
There are four HTML elements,two for bold and two for italic
We use the <i> and <b> elements to apply visual italics and <em> and <strong> element to add emphasis and serve a language-related purpose
HTML have three types of lists; unordered list(ul),ordered list(ol) and define list
We have two elements <cite> and <block quotes> wich serve a semantic purpose and they provide a way to apply custom styling.
HTML uses a single element called  <time>,it is used to convey the exact date or time to computers
It consist of an opening tag(<time>)and a closing tag(</time>)
Superscript,subscript and small texts are the elements that can help you get the details right when it comes to typography and conveying the full meaning of our content

WEEK1 
UNIT3: HTML CAPABILITIES
HTML ATTRIBUTES

HTML have four important global attributes whiich are;
Class attribute which allows us to assign a reusable name to any element 
ID attribute can be used for CSS targeting
Lang attrribute allows us to specify the language of the content using a short language code
Dir attribute indicates the direction in which the text flows
Aria is a powerful tool that greatly enhances web accessibility,It is particulary valuable for ensuring that everone can use the full functionality of a complex interface in an ap.
HTML have three important characters <,> and &

WEEK1
UNIT4: HTML NAVIGATION AND LINKING
HTML LINKS

HTML navigation and linking are crucial for creating interactive and interconnected web pages.
HTML links are created using the Anchor<a> tag and include an href attribute specifying the URL of the destination
Absolute URL specifies the complete web address including the protocol & domain
Relative URL specifies the path to a file relative to the current page's location ommitting the protocol & domain
HTTP(Hypertext Transport Protocol) must be included in an absolute URL,It defines the rules for communication on the web and is crucial for linking.

WEEK2 
UNIT5: HTML WORKING WITH GRAPHICS AND IMAGES
IMAGES

Working with graphics and images in HTML involves adding visual content to web pages
When inserting images use the <img> tag 
We have four attributes to be included for every image:
1.ALT(Alternative) which provides a text description of the image
2.SRC(Source) which specifies the URL of the image file to be displayed
3.Width which specifies the width of the image in pixels      
4.Height which specifies the height of the image in pixels
Common image formats include GIF,SVG,JPG & PNG
Responsive images use CSS attribute (srcset,size) to provide different image sources for different devices and screen sizes
Responsive width referes to desgning web elements to adapt dynamically to different screen sizes.
<figcaption> and <figure> are HTML elements used to semantically associate images with their captions
<figure> which encloses media content like images,videos along with their captions
<figcaption> which provides a caption for the content

WEEK2
UNIT6: HTML WORKING WITH MEDIA

Working with media in HTML involves integrating various types of multimedia content into web pages.
Working with Audio: Insert audio files with the <audio> tag. Specify audio sources (src attribute) and optional attributes like controls for playback control.
Working with Video: Embed videos using the <video> tag. Provide video sources (src attribute) and optional attributes like controls for playback control.
Working with Captions and Subtitles: Include captions for accessibility using <track> element. Provide alternative text or transcripts for audio content.
Embedding Media via Iframes: Embed external content using <iframe> tag.Specify the source URL with the src attribute. 

WEEK2
UNIT7: HTML CONTENT IDENTIFICATION

Involves uniquely identifying elements in HTML,done using id attribute for individual identification and class attribute for grouping.
HTML supports multiple languages through the lang attribute,helps in indicating the language used in the content for accessibility and search engine optimization.
Generic elements like <div> and <span> are used for structuring content.
They have no inherent meaning and are styled or scripted as needed.         
<div>: Used for creating divisions or sections in a document.
<span>: Used for applying styles to inline elements or grouping inline elements for scripting purposes.

WEEK2
UNIT8: HTML INTERGRATION

Involves using HTML code in different context to create content,structure and functionality.
An HTML page is structured using various HTML tags, each serving a specific purpose. A typical HTML document has a basic structure that includes:
<!DOCTYPE html>: Declares the document type and version of HTML.
<html>: The root element of an HTML page.
<head>: Contains meta-information about the document, like its title and links to scripts and stylesheets.
<body>: Contains the content of the document, such as text, images, links, and other media.
The head of an HTML document (<head> tag) includes elements that are not directly visible to users but are crucial for the document's metadata, linking resources, and other configurations:
<title>: Specifies the title of the document, which appears in the browser's title bar or tab.
<meta>: Provides metadata about the HTML document, such as character set, author, and viewport settings.
<link>: Used to link external resources like CSS files to style the HTML document.
<script>: Used to include JavaScript files or code which can manipulate the HTML document's content or behavior.
<style>: Contains internal CSS styles for the document.
Content structuring involves organizing elements within a webpage to create a logical hierarchy and layout.It includes using semantic elements like:
Main:The main element is used once per webpage and tells the browser where the main content is located.
Header: Head is where the file's metadata lives and is not displayed to users. Header is used for site headers, article headers, and headers within the content. A header is usually found at the top of most web pages and may include a logo, site name, and navigation.
Footer:The footer signifies that there are extra things to convey, regardless of its position on the page.
Article:Some articles begin with metadata like hashtags or share buttons, which are suitable for a footer element. The article element wraps around any type of content unit, whether it is a long written article, a short snippet, a teaser card, a tweet, or even an app element. It represents a standalone unit of content.
Section:The section element is used to mark sections of content. For example, in a long essay with subheadings, each segment can be wrapped in a section element. It is also useful for dividing different topic zones on a website. Each section typically starts with its own headline.
Aside:the aside element is for content that is off to the side, like sidebar information or additional details that accompany an article but are not part of its main flow. Advertisements can also be marked as an aside. Although the position on the page does not matter, the semantic meaning of these elements is crucial. The visual layout often conveys meaning, and these HTML elements help transfer that meaning from the design to the content.

WEEK3
UNIT9:WORKING WITH FORMS AND INTERACTIVE ELEMENTS

HTML Form Tag: Use the <form> tag to define a form on your webpage.
Form Controls: These are elements used within a form to collect user input.
Text input: <input type="text">
Password input: <input type="password">
Checkbox: <input type="checkbox">
Radio buttons: <input type="radio">
Select dropdown: <select><option>...</option></select>
Textarea: <textarea></textarea>
Form Submission:Specify the action attribute of the form tag to determine where the form is sent.
Form Submssion Handling:Use JavaScript to handle form submission asynchronously (preventDefault() method),Validate form data before submission and display error messages if validation fails.
AJAX Form Submission:Submit forms asynchronously using AJAX and Update parts of the page dynamically without reloading the entire page.
Form Reset:Allow users to reset form fields to their default values and Use the <input type="reset"> button or JavaScript to reset form fields.
Autofill and Autofocus:Use the autofocus attribute to automatically focus on a form element when the page loads and Use the autocomplete attribute to control autofill behavior.
File Upload:Allow users to upload files using the <input type="file"> element and Handle file uploads on the server-side.
Hidden Fields:Use <input type="hidden"> to store data in the form that is not visible to the user and Useful for passing additional data along with form submissions.
Date and Time Picker:Use HTML5 date and time input types (<input type="date">, <input type="time">, <input type="datetime-local">) or JavaScript libraries for date and time selection.
Form Accessibility:Ensure forms are accessible to users with disabilities by providing proper labels, ARIA attributes, and keyboard navigation.

WEEK3
UNIT10: ORGANIZING TABULAR INFORMATION IN HTML

Organizing tabular information in HTML involves using the <table>, <tr>, <th>, and <td> tags.
table>: Defines the table.
<tr>: Defines a row within the table.
<th>: Defines a header cell (typically bold and centered).
<td>: Defines a data cell.
Define Headers:Use <th> within <tr> to define column headers.
Add Data:Use <td> within <tr> to add data cells.
Multiple Rows:Add more <tr> for additional rows.
Styling:Apply CSS to style the table, rows, headers, and cells as needed.

WEEK3
UNIT1: INTRODUCTION TO CSS

CSS(Cascading Style Sheet) is a stylesheet language used to describe the presentation of a document in HTML.
CSS describes how elements should be rendered on screen, on paper, in speech, or on other media.
CSS has two parts:
1.The selector:Indicates the HTML element you want to style.
2.The declaration block:Contains one or more declarations separated by semicolons. 
In CSS, each style declaration consists of two parts:
1.A property: The aspect of the element you want to change (e.g., color, width, height).
2.A value: Assigned to properties to specify how to style the elements.

UNIT2: ADDING CSS SELECTORS

Comments are used in CSS to explain your code and can help you and others understand the intention behind your CSS rules.
Element selectors allow you to apply styles to HTML elements directly. When you use an element selector, all elements of that type in the document will be styled according to the CSS rule defined.
Class selectors target HTML elements that have a specific class attribute followed by the class name.They are defined using a period ('.') followed by the class name.
When multiple selectors share the same style declarations, they can be grouped together to reduce code redundancy. To group selectors, separate each selector with a comma.
Descendent selectors target elements that are nested within other elements, allowing you to style specific elements within a particular context.

UNIT3: CSS IMAGES AND COLORS

Identify a Color Scheme
A color scheme is a selection of colors used in design for a range of media. For web design, it's essential to choose colors that complement each other and align with the message and emotion the website intends to convey.Users can also explore other combinations like monochromatic (where two similar colors are chosen) and analogous (involves various shades of greens and blues, or triadic, which creates a pattern on the color wheel using an equilateral triangle). There is also the option of tetradic, which generates a square's worth of colors. 
Formatting Color in CSS
In CSS, colors can be specified in various ways:
Keyword: like red, blue, etc.
HEX code: a # followed by a 6-digit hexadecimal code, e.g., #FF5733.
RGB: an rgb function with three values for red, green, and blue, e.g., rgb(255, 87, 51).
RGBA: similar to RGB but with an alpha (transparency) value, e.g., rgba(255, 87, 51, 0.5).
HSL: a hsl function with values for hue, saturation, and lightness, e.g., hsl(11, 100%, 60%).
HSLA: similar to HSL but with an alpha value for transparency, e.g., hsla(11, 100%, 60%, 0.5).
Background and Text Color in CSS
To set the background color of an element, you can use the background-color property. To set the text color, use the color property. 
Understanding Images in CSS
In CSS, images can be used as backgrounds or directly inserted via the HTML <img> tag. CSS provides a wide range of properties to control how these images are displayed and interact with other elements, such as background-image, background-size, background-repeat, and object-fit.
Working with Background Images in CSS
To set a background image for an element, you use the background-image property. You can control the size of the image with background-size and whether the image repeats with background-repeat.

UNIT4: CSS BOXES

In general, people who are not designers usually categorize fonts into two types: 
Serif and Sans serif.
Serif fonts have small lines at the ends of the letters called serifs. In the past, serif fonts were used for printed materials with long text blocks. When letters were manually set on a printing press, they were never perfectly aligned. The serifs helped connect the letters, making the text easier to read. 
Sans serif fonts do not have serifs and have a more modern appearance. With computer typesetting, sans serif fonts are mainly used on the web for extended text because they look clean and are easy to read.]
Applying Type Formatting with CSS- This CSS rule will apply to all <p> (paragraph) elements in your HTML, setting the text to a bold, italic Arial font, size 16 pixels, and center-aligned.
Understanding and Applying Size in CSS
Size in CSS can refer to dimensions of elements (width and height), text size (font-size), or the size of other properties like border thickness. CSS allows sizes to be specified in various units, including pixels (px), ems (em), rems (rem), percentages (%), and viewport units (vw/vh).
For text, em is relative to the font size of the element, rem is relative to the font size of the root element (<html>), and pixels are a fixed size. Viewport units are based on the size of the browser window, where vw is a percentage of the viewport’s width, and vh is a percentage of the viewport’s height.
Understanding the Box Model in CSS 
The CSS box model is a fundamental concept that describes the layout of HTML elements. Each element is represented as a rectangular box, consisting of:
Content: The actual content of the box, where text and images appear.
Padding: The space between the content and the border.
Border: Surrounds the padding (if any) and content.
Margin: The outermost layer, representing the space between the element's border and its surrounding elements.
Working with Border, Padding, and Margin in CSS
To manipulate the appearance of the box model components, you use the border, padding, and margin properties. Each of these properties can target specific sides of an element (top, right, bottom, left) or all sides at once.This  CSS rule defines a class named .box that will apply a 200 pixels width, 20 pixels padding on all sides, a 10 pixels margin on all sides, and a 5 pixels solid black border around an HTML element.

UNIT5: ADVANCED CSS PROPERTIES AND CONCEPTS

Styling Links with CSS
Links in HTML are defined with the <a> tag and can be styled with CSS to improve their appearance and make them more engaging for users. There are four pseudo-classes that are commonly used to style links:
Link - applies styles to links that have not yet been visited.
Visited - applies styles to links that the user has visited.
Hover - applies styles when the mouse hovers over the link.
Active - applies styles at the moment the link is clicked.
Inheritance in CSS is a mechanism where some CSS properties, like font-size and color, are passed from parent elements to their children. This means that if you set a property on a parent element, the child elements will inherit that property unless they have the same property set to a different value.Not all CSS properties are inherited by default, but you can force inheritance using the inherit value.
Debugging CSS with Borders and Background Colors
A common technique for debugging layout issues in CSS is to use border and background color styles to make the dimensions and positioning of elements visible. By applying a high-contrast border or background color, you can visually identify where elements are located on the page, how much space they occupy, and how they interact with each other.

WEEK
MODULE1: INTRODUCTION TO SQL

SQL which stands for Structured Query Language, is a standard programming language specifically designed for managing and manipulating relational databases. 
Requesting Data from a Database
SELECT Statement is used to retrieve data from a database. It allows you to specify which columns you want to retrieve data from. For example SELECT First_Name,Last_Name FROM Employees.
WHERE Statement is used  to filter records based on specified conditions. It allows you to retrieve only the rows that meet specific criteria. For Example SELECT * FROM customers WHERE city = 'New York'.
Statement Criteria uses the AND logical operator For Example "SELECT first_name, last_name FROM people WHERE state_code=CA AND shirt_or_hat=shirt." You can string multiple conditions with AND or even use OR to get results that meet one of two conditions. Just remember those parentheses they are your guiding light in complex queries.
Statement Responses Use the LIKE operator which allows us to look for values that match part of a field,Instead of a long OR statement, try 'state_code LIKE 'C%'.You can fine-tune your search with percent signs at different ends.If you want a specific number of results, throw in LIMIT. It helps when dealing with large databases.
The ORDER BY clause is used to sort the result set returned by a SELECT statement. It allows you to specify one or more columns by which to sort the rows, as well as the direction (ascending or descending) of the sorting.For Example SELECT * FROM products ORDER BY price DESC.
Finding More Data It is not just about matching records.Functions like LENGTH give us insights into field sizes. DISTINCT helps find unique values, and COUNT tallies records matching specific criteria.

MODULE1: Data Types And Arithmetic Operators



















  






