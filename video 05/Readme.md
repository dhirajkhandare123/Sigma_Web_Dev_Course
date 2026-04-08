# HTML Documentation: Images, Tables, and Lists
This repository serves as a quick-reference guide for essential HTML elements used to structure content and display media.

### 1. Image Tag (<img>)
The <img> tag is used to embed images in a webpage. It is an empty element, meaning it contains attributes only and does not have a closing tag.

src: Specifies the path to the image.

alt: Provides alternate text for screen readers or if the image fails to load.

width / height: Sets the dimensions (optional).

Example:

'''
<img src="https://via.placeholder.com/150" alt="Placeholder Image" width="150" height="150">
'''

<hr>

### 2. Table Tags
Tables allow you to arrange data into rows and columns. They are built using a nested structure of tags.

<table>: The wrapper for the entire table.

<tr>: Defines a table row.

<th>: Defines a table header (bold and centered by default).

<td>: Defines a table cell (standard data).

Example:
'''
<table>
  <tr>
    <th>Language</th>
    <th>Type</th>
    <th>Year</th>
  </tr>
  <tr>
    <td>HTML</td>
    <td>Markup</td>
    <td>1993</td>
  </tr>
  <tr>
    <td>CSS</td>
    <td>Styling</td>
    <td>1996</td>
  </tr>
</table>
'''
<hr>

### 3. Lists
HTML provides two primary ways to group related items: ordered and unordered lists.

A. Unordered List (<ul>)
Used for items where the order doesn't matter. It uses bullet points.

Example:
'''
<ul>
  <li>HTML5</li>
  <li>CSS3</li>
  <li>JavaScript</li>
</ul>
'''
B. Ordered List (<ol>)
Used for items that follow a specific sequence. It uses numbers or letters.

Example:
'''
<ol>
  <li>Open the editor</li>
  <li>Write the code</li>
  <li>Save as .html</li>
</ol>
'''
