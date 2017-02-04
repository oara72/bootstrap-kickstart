# Grids

* For proper alignment and padding, rows must be wrapped within a .container respectively for fixed-width and full-width.

* Use rows to create horizontal groups of columns.

* Only columns may be immediate children of rows, and content should be placed within columns.

* Bootstrap offers a lot of classes to set up layouts fast, classes like .row to create a new row or .col-xs-4 to create a small sized column equal to 1/3 of the container.

* Gutters between columns are created via padding.

* The negative margin is why the examples below are outdented. It’s so that content within grid columns is lined up with non-grid content.

* Grid columns are created by specifying the number of twelve available columns you wish to span. It could wither be 12 columns by using for example .col-sm-1 or three .col-sm=4 or six .col-sm-2 etc.

* When trying to add more than 12 columns within a row, the extra columns will automatically wrap onto a new line.

```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Bootstrap Basic Template</title>
<!-- Bootstrap -->
<link href="css/bootstrap.min.css" rel="stylesheet">
</head>
<body>


<!-- jQuery (necessary for Bootstrap’s JavaScript plugins) -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></  -
script>
<!-- Include all compiled plugins (below), or include individual files as needed -->
<script src="js/bootstrap.min.js"></script>
</body>
</html>
```

## Grid across multiple devices

![](img/multipledevices.jpg "accros multiple devices")




