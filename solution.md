# Assignment 4.1 — Student Registration Form

**File name: `registration.html`**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Student Registration</title>
</head>
<body>
    <h1>Student Registration Form</h1>

    <form>
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="fullname" required>
        <br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required>
        <br><br>

        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" required>
        <br><br>

        <label for="age">Age:</label>
        <input type="number" id="age" name="age" required>
        <br><br>

        <button type="submit">Register</button>
    </form>
</body>
</html>
```

**Submission:** Save as `registration.html`, open it in your browser, and submit a screenshot of the form.