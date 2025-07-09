# Saveetha_Admission_clone
## Date:09-07-2025
## Sachin B
## 212222060207


## Objective:
To design a landing page clone of Saveetha Engineering College’s Admission Enquiry form using HTML and CSS. This activity reinforces skills in layout design, form creation, user input handling, responsive structure, and visual styling based on a real-world example.

## Tasks:
#### 1. Analyze the Landing Page Layout:
Observe the split-screen layout with a promotional section on the left and a form on the right.

Note the use of background images, text styling, and branding elements.

#### 2. Create the HTML Structure:
Use semantic tags like ```<section>, <header>, <form>, and <footer>``` to organize content.

Structure the form with input fields such as name, email, phone, password, city, state, course, specialization, captcha, and checkbox.

#### 3. Add Form Functionality:
Include appropriate input types (text, email, tel, password, select, etc.) with placeholders and labels.

Use the <button> element for the "APPLY NOW" action.

#### 4. Apply CSS Styling:
Implement a split layout using flexbox or grid.

Style the form elements with padding, shadows, background colors, and rounded borders.

Include hover effects and button transitions to match the original look.

#### 5. Incorporate Images and Branding:
Add the institution logo and use matching fonts and colors.

Place a background image or blurred overlay behind the form content if needed.

#### 6. Ensure Responsiveness:
Make sure the page adapts to different screen sizes using media queries.

Maintain readability and layout integrity on both desktop and mobile.

## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saveetha Admission Enquiry Clone</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="bg-img">
        <form class="enquiry-form">
            <h2>Admission Enquiry</h2>
            <label for="name">Full Name</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
            <label for="email">Email</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <label for="phone">Phone</label>
            <input type="tel" id="phone" name="phone" placeholder="Enter your phone number" required>
            <label for="password">Password</label>
            <input type="password" id="password" name="password" placeholder="Create a password" required>
            <label for="city">City</label>
            <input type="text" id="city" name="city" placeholder="Your city" required>
            <label for="state">State</label>
            <input type="text" id="state" name="state" placeholder="Your state" required>
            <label for="course">Course</label>
            <select id="course" name="course" required>
                <option value="">Select course</option>
                <option value="BTech">B.Tech</option>
                <option value="MTech">M.Tech</option>
                <option value="PhD">Ph.D</option>
            </select>
            <label for="specialization">Specialization</label>
            <input type="text" id="specialization" name="specialization" placeholder="E.g., Computer Science" required>
            <label for="captcha">Captcha</label>
            <input type="text" id="captcha" name="captcha" placeholder="Enter captcha" required>
            <div class="checkbox-row">
                <input type="checkbox" id="agree" name="agree" required>
                <label for="agree" class="checkbox-label">I agree to the terms and conditions</label>
            </div>
            <button type="submit">APPLY NOW</button>
        </form>
    </div>
</body>
</html>
```

## CSS Code:

```
body, html {
    height: 100%;
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
}

.bg-img {
    background-image: url('clg.png');
    min-height: 100vh;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
}

.enquiry-form {
    background: rgba(255,255,255,0.95);
    padding: 30px 24px;
    border-radius: 12px;
    box-shadow: 0 4px 16px #ccc;
    max-width: 370px;
    width: 100%;
    display: flex;
    flex-direction: column;
    gap: 10px;
}

.enquiry-form h2 {
    text-align: center;
    color: #003366;
    margin-bottom: 8px;
}
.enquiry-form label {
    font-weight: 500;
}
.enquiry-form input,
.enquiry-form select {
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 1rem;
    background: #f8fafc;
}
.checkbox-row {
    display: flex;
    align-items: center;
    gap: 7px;
    margin: 7px 0 10px 0;
}
.enquiry-form button {
    background: #003366;
    color: #fff;
    border: none;
    border-radius: 4px;
    padding: 11px 0;
    font-size: 1.07rem;
    font-weight: 600;
    cursor: pointer;
    margin-top: 10px;
    transition: background 0.2s, transform 0.2s;
}
.enquiry-form button:hover {
    background: #0055aa;
    transform: translateY(-2px) scale(1.03);
}

@media (max-width: 600px) {
    .enquiry-form {
        padding: 12px 4px;
        max-width: 98vw;
    }
}
```

## Output:

![Screenshot 2025-07-09 213914](https://github.com/user-attachments/assets/384980be-9f2f-490c-b7c7-846ca8013700)

## Result:
A landing page clone of Saveetha Engineering College’s Admission Enquiry form using HTML and CSS is designed successfully.
