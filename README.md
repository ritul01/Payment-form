# Payment-form
The payment form is made by using HTML and CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payment Form</title>
  <!--  <link rel="stylesheet" href="payment.css">  -->
</head>
<body>
    <div class="container">
        <form action="">
            <h1 class="main_heading">Payment Form</h1>
            <hr>
            <h2>Contact Information</h2>
            <p>Name: *<input type="text" name="name" required placeholder="Joncena"></p>
            <fieldset>
                <legend>Gender</legend>
                <p>
                    Male <input type="radio" name="gender" id="male" required>
                    Female <input type="radio" name="gender" id="female" required>
                </p>
            </fieldset>
            <p>Adderss: <textarea name="address" id="address" cols="100" rows="5" placeholder="Enter your Addresss"></textarea></p>
            <p>Email: *<input type="email" name="email" id="email" required placeholder="example@gmail.com"></p>
            <p>Pincode: *<input type="number" name="pincode" id="pincode" required placeholder="123456"></p>
            <hr>
            <h2>Payment Information</h2>
            <p>Card Types: *
                <select name="card type" id="card type" required>
                    <option value="">--Select a card type--</option>
                    <option value="visa">visa</option>
                    <option value="master card">master card</option>
                    <option value="Rupay">Rupay</option>
                </select>
            </p>
            <p>
                Card Number *<input type="number" name="card number" id="card number" required placeholder="213654546454">
            </p>
            <p>
                Expiry Date: *<input type="date" name="exp date" id="exp date" required>
            </p>
            <p>CVV *<input type="password" name="cvv" id="cvv" required placeholder="***"></p>
    
            <input type="submit" value="Pay">
        </form>
    </div>
</body>
</html>
