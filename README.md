# Ex09 Event Registration Web Application
## Date:15-05-2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
HTML:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sports Day App</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <div class="iphone-container">
    
    <!-- Screen 1: Home -->
    <div class="iphone">
      <img src="logo1.png" alt="Saveetha Logo" class="logo" />
      <h2>SPORTS DAY EVENTS</h2>
      <img src="running.png" alt="Running" class="illustration" />
      <div class="button-group">
        <button class="btn">LOGIN</button>
        <button class="btn">REGISTER</button>
      </div>
    </div>

    <!-- Screen 2: Events -->
    <div class="iphone">
      <h2>SPORTS DAY EVENTS</h2>
      <ul class="event-list">
        <li>&#9656; CRICKET</li>
        <li>BADMINTON</li>
        <li>VOLLEYBALL</li>
        <li>TENNIS</li>
        <li>400m</li>
        <li>200m</li>
      </ul>
      <img src="cheering.png" alt="Cheering" class="illustration" />
    </div>

    <!-- Screen 3: Registration -->
    <div class="iphone">
      <h3 class="form-title">EVENT REGISTRATION FORM</h3>
      <form>
        <input type="text" placeholder="Full Name" />
        <select>
          <option>Gender</option>
          <option>Male</option>
          <option>Female</option>
        </select>
        <input type="number" placeholder="Age" />
        <input type="text" placeholder="Register Number" />
        <input type="text" placeholder="Department" />
        <input type="tel" placeholder="Mobile Number" />
        <input type="email" placeholder="Email" />
        <button class="btn">REGISTER</button>
      </form>
      <img src="volleyball.png" alt="Volleyball" class="illustration" />
    </div>

    <!-- Screen 4: Thank You -->
    <div class="iphone">
      <img src="logo2.png" alt="Saveetha Logo" class="logo" />
      <h2>THANK YOU</h2>
      <p>We greatly appreciate your participation in the sports events</p>
      <img src="sports_mix.png" alt="Sports" class="illustration" />
      <div class="contact">
        <strong>Contact Us</strong><br />
        contact@enamplo.com<br />
        +1324357660
      </div>
    </div>
  </div>
</body>
</html>
```
CSS:
```
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: #f0f0f0;
  display: flex;
  justify-content: center;
}

.iphone-container {
  display: flex;
  gap: 20px;
  padding: 20px;
  overflow-x: auto;
}

.iphone {
  width: 260px;
  height: 560px;
  background: linear-gradient(to bottom, #e0f3ff, #f6faff);
  border: 8px solid black;
  border-radius: 40px;
  padding: 20px 15px;
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
}

.logo {
  width: 140px;
  margin-bottom: 10px;
}

h2 {
  text-align: center;
  font-size: 20px;
  margin: 10px 0;
  color: #012947;
}

.illustration {
  width: 100%;
  max-height: 180px;
  object-fit: contain;
  margin-top: auto;
}

.button-group {
  display: flex;
  flex-direction: column;
  gap: 10px;
  margin-top: 20px;
}

.btn {
  background-color: #d7191c;
  color: white;
  border: none;
  padding: 10px;
  font-weight: bold;
  font-size: 14px;
  border-radius: 6px;
  cursor: pointer;
}

.event-list {
  list-style: none;
  padding: 0;
  font-size: 16px;
  color: #012947;
  margin-top: 20px;
  line-height: 1.8;
}

.form-title {
  color: red;
  font-weight: bold;
  font-size: 16px;
  margin-bottom: 10px;
  text-align: center;
}

form {
  display: flex;
  flex-direction: column;
  gap: 8px;
  width: 100%;
}

input, select {
  padding: 8px;
  font-size: 14px;
  border: 1px solid #aaa;
  border-radius: 4px;
}

p {
  text-align: center;
  padding: 10px;
  font-size: 14px;
}

.contact {
  text-align: center;
  font-size: 13px;
  margin-top: 10px;
}
```

## OUTPUT:
![443965124-855c0be0-bf37-43f5-aa7c-f4cb90eac99e](https://github.com/user-attachments/assets/3084aaa8-ec86-4c90-9dca-06e2a7f6e2c5)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
