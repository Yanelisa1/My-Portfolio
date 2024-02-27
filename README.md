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








  












