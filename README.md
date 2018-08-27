# assessment_two
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>
    <h1>Course Sign Up Page</h1>
    <p>Please Note: First Name, Last Name, Password, and Email are required</p>
    <form action="thankyou.html" method="get">
      <label for="firstname">First Name:</label>
      <input id="firstname" type="text" name="firstname" placeholder="First Name" required>
      <label for="lastname">Last Name:</label>
      <input id="lastname" type="text" name="lastname" placeholder="Last Name" required>
<p></p>
      <label for="Email">Email:</label>
      <input id="Email" type="email" name="emailid" placeholder="name@email.com" required>
      <label for="password">Password:</label>
      <input type="password" required>
      <p>Are you over the age of 18?</p>
      <label for="yes">Yes: </label>
      <input id="yes" type="radio" name="loc" value="yes">
      <label for="no">No: </label>
      <input id="no" type="radio" name="loc" value="no">
      <p>Do you have a Credit Card or PayPal?</p>
      <select name="payment">
        <option value="Credit Card">Credit Card</option>
      <option value="PayPal">PayPal</option>
      </select>
      <input type="submit" name="" value="Submit Feedback">
    </form>
  </body>
</html>
