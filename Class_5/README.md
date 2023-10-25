# Class Lecture

## Web Development

- **<"table"></"table">**: Creating a table formate.
- **<"tr><"/tr>**: For creating a row in a table.
- **<"th"></"th>**: For creating a table head.
- **<"td"></"td>**: For creating table data on a row.
- **<"thead>** :	Groups the header content in a table.
- **<"tbody">**:	Groups the body content in a table.
- **<"tfoot>**:	Groups the footer content in a table.
- **<"colspan="value">**: For merging value wise column together.
- **<"rowspan="value">**: For merging value wise row together.
- **<"link rel="stylesheet" href="style.css">**: For adding css file to HTML file.




## HTML

### Today's Class code


## HTML
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
  <link rel="stylesheet" href="style.css">
  <title>XYZ Company website</title>
</head>
<body>
  <!-- <table>
    <caption>Daffodil Students Info</caption>
    <tr>
      <th>Name</th>
      <th>ID</th>
      <th>Department</th>
    </tr>
    <tr>
      <td>shohidul Islam</td>
      <td>193-15-13529</td>
    </tr>
    <tr>
      <td>Abbas</td>
      <td>232327832</td>
    </tr>
    <tr>
      <td>Tariqul</td>
      <td>2220970347</td>
    </tr>
    <tr>
      <td>Mushfiq</td>
      <td>232987283782</td>
    </tr>
    <tr>
      <td>Ummay</td>
      <td>23987983</td>
    </tr>
    <tr>
      <td>Sadab</td>
      <td>2329873927</td>
    </tr>
  </table> -->

  <!-- <table>
    <tr>
      <th colspan="2">Full Name</th>
      <th>ID</th>
    </tr>
    <tr>
      <td>shohidul Islam</td>
      <td>Islam</td>
      <td>193-15-13529</td>
    </tr>
    <tr>
      <td>Mahmud</td>
      <td>Abbas</td>
      <td>232327832</td>
    </tr>
    <tr>
      <td>Tariqul</td>
      <td>Islam</td>
      <td>2220970347</td>
    </tr>
    <tr>
      <td>Mushfiq</td>
      <td>Rohoman</td>
      <td>232987283782</td>
    </tr>
    <tr>
      <td>Ummay</td>
      <td>Dristy</td>
      <td>23987983</td>
    </tr>
    <tr>
      <td>Taznim</td>
      <td>Sadab</td>
      <td>2329873927</td>
    </tr>

  </table> -->

  <table>
    <tr>
      <th>Name</th>
      <td>Md. Yeamin Islam</td>
    </tr>
    <tr>
      <th>Number</th>
      <td rowspan="2">0989048904893</td>
    </tr>
    <tr>
      <th>Same Number</th>
    </tr>
  </table>
</body>
</html>

```

## CSS
```css
table, th, td {
  border: 1px solid red;
  border-collapse: collapse;
}
```


## Closing of HTML 