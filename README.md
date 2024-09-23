
<!DOCTYPE html>
<html>
<head>
    <title>Simple Form</title>
</head>
<body>

<h2>Contact Form</h2>

<form action="/submit-form" method="POST">
  <!-- Text input -->
  <label for="name">Name:</label><br>
  <input type="text" id="name" name="name"><br><br>

  <!-- Email input -->
  <label for="email">Email:</label><br>
  <input type="email" id="email" name="email"><br><br>

  <!-- Checkbox input -->
  <label for="subscribe">Subscribe to newsletter:</label>
  <input type="checkbox" id="subscribe" name="subscribe"><br><br>

  <!-- Radio buttons -->
  <label for="gender">Gender:</label><br>
  <input type="radio" id="male" name="gender" value="male">
  <label for="male">Male</label><br>
  <input type="radio" id="female" name="gender" value="female">
  <label for="female">Female</label><br><br>

  <!-- Dropdown (select) -->
  <label for="country">Country:</label><br>
  <select id="country" name="country">
    <option value="usa">USA</option>
    <option value="canada">Canada</option>
    <option value="mexico">Mexico</option>
  </select><br><br>

  <!-- Submit button -->
  <input type="submit" value="Submit">

</form>

</body>
</html>
