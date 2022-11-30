<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="nitya.css">
    <title>Payment form</title>
</head>
<body>
    <div class="container">
        <form action="/action_js/" method="get">
            <h1 class="main-heading">Payment form</h1>
            <hr>
            <p>Required feilds are followed by *</p>
            <h2>User information</h2>
            <p>First Name : *<input type="text"name = "name"required placeholder=" Enter Your Name">
                <p>Last Name :  <input type="text" name="name" placeholder="Enter your surname">
                <fieldset>
                    <legend>Gender</legend>
            </p>
            <p>Female <input type="radio" name="gender" id="Male" required>Male <input type="radio" name="gender" id="female"required/></p>
        </fieldset> 
    
        <p>Address  :<textarea name="address" id="address" cols="100" rows="8" placeholder="enter your address"></textarea></p>
        <p>Email   : *<input type="email" name="email" id="eamil"required placeholder="enter your email"></p>
        <p>Pincode :* <input type="number" name="pincode" id="pincode"required placeholder="enter pincode"></p>
        <h3>Payment information</h3>
        <p>Card type *
            <select name="card_type" id="card_type"required>
                <option value="">----select card type----</option>></option>
                <option value="Visa">Visa</option>
                <option value="Debit card">Debit card</option>
                <option value="Credit card">Credit card</option>
                <option value="Rupay">Rupay</option>
    
            </select>
        </p>
        <p>
            Card Number <input type="number" name="card_number" id="card_number"required placeholder="enter card number">
        </p>
        <p>
            Expiration Date: * <input type="date" name="expr_date" id="expr_date"required placeholder="enter expri date">
        </p>
        <p>CVV : * <input type="password" name="cvv" id="cvv"required placeholder="enter cvv number"></p>
    
         <input type="submit" value="Pay Now"required>
    
        </form>

    </div>
  
</body>
</html> 
