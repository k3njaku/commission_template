# Codebase Documentation

## Overview
This document provides a detailed overview of the codebase, including the HTML file `index.html` and its connection to other files.

### index.html

#### Code:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
  <table>
    <thead>
      <tr>
        <th>Project</th>
        <th>Tier</th>
        <th># of days</th>
        <th>Daily rep target</th>
        <th>Total target</th>
        <th>Ranges</th>
        <th>Target (New REP)</th>
        <th>Adjusted Target</th>
        <th>Payout per metric</th>
        <th>Comments</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>ABCL</td>
        <td>A</td>
        <td>20</td>
        <td>0.4</td>
        <td>8</td>
        <td>8+</td>
        <td>4</td>
        <td></td>
        <td>4000 PKR</td>
        <td></td>
      </tr>
      <tr>
        <td>ABCL</td>
        <td>B</td>
        <td>20</td>
        <td>0.3</td>
        <td>6</td>
        <td>6-7</td>
        <td>3</td>
        <td></td>
        <td>3000 PKR</td>
        <td></td>
      </tr>
      <tr>
        <td>ABCL</td>
        <td>C</td>
        <td>20</td>
        <td>0.2</td>
        <td>4</td>
        <td>4-5</td>
        <td>2</td>
        <td></td>
        <td>2000 PKR</td>
        <td></td>
      </tr>
      <tr>
        <td>ABCL</td>
        <td>Opportunity Kicker</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>5000 PKR</td>
        <td>Per opportunity as per AE</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td>Precanto</td>
        <td>Per approved appointment</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>5000 PKR</td>
        <td>Per Approved Appointment</td>
      </tr>
      <tr>
        <td>Precanto</td>
        <td>Per showup</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>5000 PKR</td>
        <td>Per Showup</td>
      </tr>
      <tr>
        <td>Precanto</td>
        <td>Per opportunity</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>5000 PKR</td>
        <td>Per Opp</td>
      </tr>
      <tr>
        <td>Precanto</td>
        <td>Per closed deal</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>5000 PKR</td>
        <td>Per Closed</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td>FP&amp;A Strategy</td>
        <td>Per showup</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>5000 PKR</td>
        <td>Per Showup</td>
      </tr>
      <tr>
        <td>FP&amp;A Strategy</td>
        <td>Per opportunity</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>5000 PKR</td>
        <td>Per Opp</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td>AVIBRA</td>
        <td>A</td>
        <td>20</td>
        <td>0.35</td>
        <td>7</td>
        <td>7+</td>
        <td>4</td>
        <td></td>
        <td>4000 PKR</td>
        <td></td>
      </tr>
      <tr>
        <td>AVIBRA</td>
        <td>B</td>
        <td>20</td>
        <td>0.25</td>
        <td>5</td>
        <td>5-6</td>
        <td>3</td>
        <td></td>
        <td>3000 PKR</td>
        <td></td>
      </tr>
      <tr>
        <td>AVIBRA</td>
        <td>C</td>
        <td>20</td>
        <td>0.15</td>
        <td>3</td>
        <td>3-5</td>
        <td>2</td>
        <td></td>
        <td>2000 PKR</td>
        <td></td>
      </tr>
      <tr>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td>Skellam</td>
        <td>Per Scheduled</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>5000 PKR</td>
        <td></td>
      </tr>
      <tr>
        <td>Skellam</td>
        <td>Per Showup</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>5000 PKR</td>
        <td></td>
      </tr>
      <tr>
        <td>Skellam</td>
        <td>Per Opportunity</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>5000 PKR</td>
        <td></td>
      </tr>
      <tr>
        <td>Skellam</td>
        <td>Per Closed</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td>5000 PKR</td>
        <td></td>
      </tr>
    </tbody>
  </table>
</body>
</html>
```

#### Explanation:
- **Document Structure**: The `<!DOCTYPE html>` declaration defines this document as an HTML5 document.
- **Language Attribute**: The `<html lang="en">` tag specifies that the language of the document is English.
- **Character Set**: The `<meta charset="UTF-8">` tag sets the character encoding for the document to UTF-8, which is essential for proper text rendering.
- **Viewport Settings**: The `<meta name="viewport" content="width=device-width, initial-scale=1.0">` tag ensures proper scaling on mobile devices.
- **Title**: The `<title>` tag sets the title of the document, which appears in the browser tab.
- **Stylesheet Link**: The `<link rel="stylesheet" type="text/css" href="style.css">` tag links to the external CSS file for styling.
- **Table Element**: The `<table>` element is used to define a table in the HTML document.
- **Table Head and Body**: The `<thead>` and `<tbody>` elements are used to define the head and body of the table, respectively.
- **Table Rows and Columns**: The `<tr>` and `<td>` elements are used to define the rows and columns of the table, respectively.

### style.css

#### Code:
```css
/* Empty for now */
```

#### Explanation:
- **Empty Stylesheet**: The `style.css` file is currently empty but will be used for styling the HTML document in the future.

### Connections to Other Files
- **style.css**: This file will be responsible for the visual styling of the HTML document.

## File and Directory Structure
```
RandomProjs/
├── codebase.md
├── style.css
└── index.html
```

## Additional Files
(Details from other files will be added here after analysis)

---