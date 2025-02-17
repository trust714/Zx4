# Zx4Acode - code editor | FOSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Support My Project</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
            padding: 2em;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
        .donate-button {
            background-color: #009cde;
            color: white;
            padding: 15px 30px;
            border-radius: 5px;
            text-decoration: none;
            display: inline-block;
            margin: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Support My Work</h1>
        <p>Help me continue creating amazing content!</p>
        
        <!-- PayPal Donation Button -->
        <form action="https://www.paypal.com/donate" method="post" target="_blank">
            <input type="hidden" name="business" value="georgetaderera0@gmail.com">
            <input type="hidden" name="currency_code" value="USD">
            <button type="submit" class="donate-button">Donate via PayPal</button>
        </form>

        <!-- Optional: Add product/service purchase buttons -->
        <h2>Buy My eBook ($10)</h2>
        <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
            <input type="hidden" name="cmd" value="_xclick">
            <input type="hidden" name="business" value="georgetaderera0@gmail.com">
            <input type="hidden" name="item_name" value="My eBook">
            <input type="hidden" name="amount" value="10.00">
            <input type="hidden" name="currency_code" value="USD">
            <button type="submit" class="donate-button">Purchase eBook</button>
        </form>
    </div>
</body>
</html>https://www.paypal.com/cgi-bin/webscr
