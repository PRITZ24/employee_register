# employee_register
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Employee Registration Form</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f0f4f8;
      margin: 0;
      padding: 0;
    }

    .container {
      width: 400px;
      margin: 50px auto;
      background: #fff;
      padding: 30px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      border-radius: 10px;
    }

    h2 {
      text-align: center;
      color: #333;
    }

    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
      color: #444;
    }

    input, select {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 14px;
    }

    button {
      width: 100%;
      margin-top: 20px;
      padding: 10px;
      background: #007BFF;
      color: white;
      border: none;
      border-radius: 6px;
      font-size: 16px;
      cursor: pointer;
    }

    button:hover {
      background: #0056b3;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Employee Registration</h2>
    <form>
      <label for="fullname">Full Name</label>
      <input type="text" id="fullname" name="fullname" required>

      <label for="email">Email Address</label>
      <input type="email" id="email" name="email" required>

      <label for="phone">Phone Number</label>
      <input type="tel" id="phone" name="phone" required>

      <label for="department">Department</label>
      <select id="department" name="department">
        <option value="HR">HR</option>
        <option value="Engineering">Engineering</option>
        <option value="Sales">Sales</option>
        <option value="Marketing">Marketing</option>
      </select>

      <label for="position">Position</label>
      <input type="text" id="position" name="position">

      <button type="submit">Register</button>
    </form>
  </div>
</body>
</html>
