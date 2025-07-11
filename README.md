# Admission_Enquiry_Form

## Date: 07/07/2025

## Objective:
To design a simple Admission Enquiry Form using basic HTML that collects student details such as name, contact, program of interest, and a message for further communication.

## Tasks:
#### 1. Set Up the HTML Structure:
Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document structure.
Set the ```<title>``` as "Admission Enquiry Form".

#### 2. Add a Page Heading:
Use ```<h1>``` to title the page as “Admission Enquiry”.

#### 3. Create the Form Layout:
Use the ```<form>``` tag to wrap all input elements. Set method="post" for structure.

#### 4. Add Input Fields:
Include the following fields using appropriate HTML elements:

Full Name

Email Address

Phone Number 

Program of Interest 

Message

#### 5. Add Submit and Reset Buttons:
Use submit and reset at the bottom of the form.

#### 6. Use HTML-only:
No CSS or JavaScript is to be included. Focus on structure and accessibility.

## HTML Code:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Admission Enquiry Form</title>
  </head>
  <body>
    <h1>Admission Enquiry</h1>
    <form action="">
      <div>
        <label for="fullname">Full Name</label>
        <input type="text" name="fullname" placeholder="Enter your full name" />
      </div>
      <div>
        <label for="email">Email</label>
        <input type="email" name="email" placeholder="Enter your email" />
      </div>
      <div>
        <label for="phone">Phone Number</label>
        <input
          type="number"
          name="phone"
          placeholder="Enter your phone number"
        />
      </div>
      <div>
        <label for="program">Program Of Interest</label>
        <select name="program" id="">
          <option value="default">Choose your program</option>
          <option value="aids">AI-DS</option>
          <option value="aiml">AI-ML</option>
          <option value="cse">CSE</option>
          <option value="it">IT</option>
        </select>
      </div>
      <div>
        <label for="state">State</label>
        <input type="text" name="state" placeholder="Enter your state">
      </div>
      <div>
        <label for="city">City</label>
        <input type="text" name="city" placeholder="Enter your city">
      </div>
      <div>
        <label for="message">Message</label>
        <textarea name="message" id=""></textarea>
      </div>
      <button type="submit">Submit</button>
      <button type="reset">Reset</button>
    </form>
  </body>
</html>

```
## Output:
![alt text](image.png)
## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
