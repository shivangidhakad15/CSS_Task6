# CSS_Task6
README for Table with Alternate Colored Rows using `nth-child` in HTML with CSS
--------------------------------------------------------------------------------

This README provides instructions on how to create a table with alternate colored rows using the `nth-child` selector in CSS. By following these steps, you can easily style your table to have a visually appealing design. Here's how to get started:

1. HTML Structure:
   - Begin by opening the HTML file where you want to create the table.
   - Inside the `<body>` element, create a `<table>` element to represent the table.
   - Within the table element, create a `<thead>` element for the table header and a `<tbody>` element for the table body.
   - Inside the `<thead>` element, create a `<tr>` element to represent the table header row.
   - Inside the `<tbody>` element, create multiple `<tr>` elements to represent the table data rows.
   - Add `<th>` elements within the header row and `<td>` elements within the data rows to define the cells of the table.

2. CSS Styling:
   - Open your CSS file or create a new one.
   - Select the table element using its ID or class and apply desired styling. For example:
     ```css
     #myTable {
       width: 100%;
       border-collapse: collapse;
     }
     ```
   - Style the table rows using the `nth-child` selector. For example, to set alternate background colors for the rows:
     ```css
     #myTable tbody tr:nth-child(even) {
       background-color: #f2f2f2;
     }
     #myTable tbody tr:nth-child(odd) {
       background-color: #ffffff;
     }
     ```
   - Customize the styles further by adding properties like font size, font color, cell padding, or other desired attributes.

3. Apply CSS to HTML:
   - In your HTML file, link the CSS file by adding the following line of code within the `<head>` section:
     ```html
     <link rel="stylesheet" href="path/to/your/css-file.css">
     ```
   - Replace `"path/to/your/css-file.css"` with the actual path to your CSS file.

4. Save and Preview:
   - Save both your HTML and CSS files.
   - Open the HTML file in a web browser to see the table with alternate colored rows based on the applied CSS styles.

Congratulations! You have successfully created and styled a table with alternate colored rows using the `nth-child` selector in HTML and CSS. Feel free to customize the table further by adjusting the styles, adding additional columns, or incorporating any desired features to suit your project's requirements.
