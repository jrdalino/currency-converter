# Steps on how to create a basic Currency Converter using HTML, CSS and Javascript

## HTML (Hyper Text Markup Language)
- Create skeleton for HTML Page html_tutorial.html

## Javascript
### Step 1: Add javascript section <script> ... </script> inside <html> ... </html> after the body section

### Step 2: Create variable currency dictionary to store exchange rates
```
        var currencyDictionary = {
            'Chinese Yuan (CNY)': {'Chinese Yuan (CNY)': 1.00, 'Japanese Yen (JPY)': 15.64, 'Philippine Pesos (PHP)': 7.18, 'Singapore Dollars (SGD)': 0.20, 'Vietnamese Dong (VND)': 3275.95 },
            'Japanese Yen (JPY)': {'Chinese Yuan (CNY)': 0.064, 'Japanese Yen (JPY)': 1.00, 'Philippine Pesos (PHP)': 0.46, 'Singapore Dollars (SGD)': 0.013, 'Vietnamese Dong (VND)': 209.42 },
            'Philippine Pesos (PHP)': {'Chinese Yuan (CNY)': 0.14, 'Japanese Yen (JPY)': 2.18, 'Philippine Pesos (PHP)': 1.00, 'Singapore Dollars (SGD)': 0.028, 'Vietnamese Dong (VND)': 456.92 },
            'Singapore Dollars (SGD)': {'Chinese Yuan (CNY)': 4.89, 'Japanese Yen (JPY)': 76.54, 'Philippine Pesos (PHP)': 35.16, 'Singapore Dollars (SGD)': 1.00, 'Vietnamese Dong (VND)': 16034.70 },                                 
            'Vietnamese Dong (VND)': {'Chinese Yuan (CNY)': 0.00030, 'Japanese Yen (JPY)': 0.0048, 'Philippine Pesos (PHP)': 0.0022, 'Singapore Dollars (SGD)': 0.000062, 'Vietnamese Dong (VND)': 1.000 }
            }
```

### Step 3: Create variables
- Button
- Base Currenct Input
- Second Current Input
- Amount Input
- To Show Amount
- To Show Base
- To Show Second
- To Show Result

### Step 4: Converter Function
- Prevent defaults
- Assign input values to variables
- Initialize result
- Add Try..Catch
- Fo

### Step 5: Add Conversion Math
- if "From" Currency is the same as "To" Current, Result is the same as amount
- else, Result = Amount * ( 1 / Currency Dictionary Exchange Rate)

### Step 6: Add Button Event Listener on Click
```
btn.addEventListener('click', convertCurrency);
```

## CSS (Cascading Style Sheets)
- Add CSS before the head and the body sections
```
<html>
    <head>
        ...
    </head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css">
    <body>
        ...
    </body>    
```