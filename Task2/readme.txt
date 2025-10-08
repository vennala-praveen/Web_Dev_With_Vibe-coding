📸 HTML <img> Tag – Embedding Images
The <img> tag is used to embed images into a webpage. It’s a self-closing tag and requires at least two attributes:

html
<img src="path/to/image.jpg" alt="Description of image" width="300" height="200">
src: Specifies the image source (URL or file path)

alt: Provides alternative text for accessibility and SEO

width & height: Define image dimensions (optional but recommended)

You can also style images using CSS or wrap them in anchor tags to make them clickable.

🔗 HTML <a> Tag – Creating Hyperlinks
The <a> tag defines a hyperlink, allowing users to navigate to another page, section, or external site.

html
<a href="https://example.com" target="_blank">Visit Example</a>
href: Destination URL or anchor ID

target="_blank": Opens link in a new tab

Can link to:

External websites

Internal pages

Email (mailto:) or phone (tel:)

You can also wrap images or other elements inside <a> to make them interactive.

🔣 HTML Symbols – Special Characters
HTML supports a wide range of symbols and special characters using entities:

html
&copy;   → ©  
&reg;    → ®  
&trade;  → ™  
&hearts; → ♥  
&lt;      → <  
&gt;      → >
These entities are useful when you want to display characters that might otherwise be interpreted as HTML code or aren't available on the keyboard.

📊 HTML Tables – Organizing Data
Tables are used to display structured data in rows and columns.

html
<table>
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Alice</td>
    <td>24</td>
  </tr>
</table>
<table>: Defines the table

<tr>: Table row

<th>: Header cell (bold and centered by default)

<td>: Data cell

Tables can be styled with CSS and enhanced with <thead>, <tbody>, <tfoot>, and <caption> for better semantics and accessibility.