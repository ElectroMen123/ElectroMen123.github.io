<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User Input Form</title>
</head>
<body>

    <h2>User Information Form</h2>

    <form action="/submit_form" method="post">
        <!-- Name input -->
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <br>

        <!-- Class input -->
        <label for="class">Class:</label>
        <input type="text" id="class" name="class" required>
        <br>

        <!-- Mobile number input -->
        <label for="mobile">Mobile Number:</label>
        <input type="tel" id="mobile" name="mobile" pattern="[0-9]{10}" required>
        <small>Enter a 10-digit mobile number</small>
        <br>

        <!-- Submit button -->
        <input type="submit" value="Submit">
    </form>

</body>
</html>
