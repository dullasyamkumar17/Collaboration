# Collaboration
<!DOCTYPE html>
<html>
<head>
    <title>Restaurant Menu Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: white;
            text-align: center;
        }
        h1 {
            color: #333;
        }
        form {
            width: 50%;
            margin: auto;
            background: blue;
            padding: 20px;
            border: 2px solid #ccc;
            border-radius: 10px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #f2f2f2;
        }
        input[type="submit"], input[type="reset"] {
            padding: 10px 20px;
            margin: 5px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
            border: none;
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
        }
        input[type="reset"] {
            background-color: #f44336;
            color: white;
        }
    </style>
</head>
<body>

<h1>Restaurant Menu</h1>

<form>
    <table>
        <tr>
            <th>Select</th>
            <th>Item</th>
            <th>Price</th>
            <th>Quantity</th>
        </tr>
        <tr>
            <td><input type="checkbox" name="item1" value="Pizza"></td>
            <td>Pizza</td>
            <td>$10</td>
            <td><input type="number" name="qty1" min="1" max="10"></td>
        </tr>
        <tr>
            <td><input type="checkbox" name="item2" value="Burger"></td>
            <td>Burger</td>
            <td>$6</td>
            <td><input type="number" name="qty2" min="1" max="10"></td>
        </tr>
        <tr>
            <td><input type="checkbox" name="item3" value="Pasta"></td>
            <td>Pasta</td>
            <td>$8</td>
            <td><input type="number" name="qty3" min="1" max="10"></td>
        </tr>
        <tr>
             <td><input type="checkbox" name="item4" value="Cold Drink"></td>
            <td>Cold Drink</td>
            <td>$3</td>
            <td><input type="number" name="qty4" min="1" max="10"></td>
        </tr>
    </table>
    <input type="submit" value="Place Order">
    <input type="reset" value="Reset">
</form>
</body>
</html>
