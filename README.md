<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    .receipt {
    width: 50%;
    margin: 40px auto;
    background-color: #fff;
    padding: 20px;
    border: 1px solid #ddd;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

header {
    text-align: center;
}

header h1 {
    font-size: 24px;
    margin-bottom: 10px;
}

.order-details table {
    width: 50%;
    border-collapse: collapse;
}

.order-details th, .order-details td {
    border: 1px solid #ddd;
    padding: 10px;
    text-align: left;
}

.payment-details {
    margin-top: 20px;
}

footer {
    text-align: center;
    margin-top: 20px;
}
</style>
<body>
    <div class="receipt">
        <header>
            <h1>City In</h1>
            <p>Address:Shalimark chowk daund</p>
            <p>Phone Number: 555-555-5555</p>
        </header>
        <section class="order-details">
            <h2>Order Details</h2>
            <table>
                <tr>
                    <th>Item</th>
                    <th>Quantity</th>
                    <th>Price</th>
                </tr>
                <tr>
                    <td>Grilled Chicken Sandwich</td>
                    <td>1</td>
                    <td>$12.99</td>
                </tr>
                <tr>
                    <td>French Fries</td>
                    <td>1</td>
                    <td>$4.99</td>
                </tr>
                <tr>
                    <td>Soft Drink</td>
                    <td>1</td>
                    <td>$2.99</td>
                </tr>
                <tr>
                    <td>Dessert</td>
                    <td>1</td>
                    <td>$6.99</td>
                </tr>
            </table>
        </section>
        <section class="payment-details">
            <h2>Payment Details</h2>
            <p>Subtotal: $27.96</p>
            <p>Tax (8%): $2.24</p>
            <p>Total: $30.20</p>
            <p>Payment Method: Credit Card</p>
            <p>Card Type: Visa</p>
            <p>Card Number: ************1234</p>
        </section>
        <footer>
            <p>Thank you for dining with us!</p>
        </footer>
    </div>
</body>
</html>


    
 

