# [Guvi Zen](https://www.guvi.io/zen/)

## HTML Task to know usage of basic tags.

1. Fix the bugs in below snippet

```HTML
    <html lang="en">
    <head>
        <title>Document</title>
            <body>
                guvi
        
    
    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        </div>
            <div>
                Guvi Geek Network
            </div>
        </body>
</head>
    </html>
```
2. Try the below one

```HTML
<html lang="en">
    <head>
        <title>Document</title>
            <body>
                guvi

    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        </div>
            <div>
                Guvi Geek Network
            </div>
        </body>
</head>
    </html>
```

---

3. Design a contact us form with all fields as required.

<!DOCTYPE html>
<html lang="en">
   <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width , initial-scale=1.0">
    <title>Contact US</title>
    <style>
        body{
            font-family: Arial, Helvetica, sans-serif;
            margin: 20px;
        }
        form{
            max-width: 400px;
            margin: auto;
            display: flex;
            flex-direction: column;

        }
        label{
            margin-bottom: 5px;
        }
        input, textarea{
            margin-bottom: 15px;
            padding: 10px;
            border: 1px solid #f7f2f2;
            border-radius: 5px;

        }
        button{
            padding: 10px;
            background-color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover{
            background-color: #4cae4c ;
        }
    </style>
   </head>
   <body>
    <h1>Contact Us</h1>
    <form action="submit_form.php" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="text" id="email" email="email" required>

        <label for="subject">Subject:</label>
        <input type="text" id="subject" subject="subject" required>

        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <button type="submit">Submit</button>

    </form>
   </body>
</html>

4. Use certain HTML elements to display the following in a HTML page.

- Programming Language
  - JavaScript
    1. Angular
    2. React
    3. Vue.js
  - Python
    1. Django Framework
    2. Flask Framework
  - Java
    1. Spring
    2. Maven
    3. Hibernate
- Database
  - MySQL
  - MongoDB
  - Cansandra

<!DOCTYPE html>
<html lang="en">
   <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

   </head>
   <body>
  <h2>Programming language</h2>
  <ul>
    <li>
        JavaScript
        <ul>
            <li>Angular</li>
            <li>React</li>
            <li>Vue.js</li>
        </ul>
    </li>
    <li>Python
        <ul>
            <li>Django Framework</li>
            <li>Flask Framework</li>
        </ul>
    </li>
    <li>
        Java
        <ul>
            <li>Spring</li>
            <li>Maven</li>
            <li>Hybernate</li>
        </ul>
    </li>
  </ul>
  <h2>Database</h2>
  
    <ul>
       <li>MySQL</li>
       <li>MongoDB</li>
       <li>cansandra</li>
    </ul>
  
   </body>
     
</html>

5. Create an element that helps you to open the https://google.com in separate new tab.

<!DOCTYPE html>
<html lang="en">
   <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width , initial-scale = 1.0">
   </head>
   <body>
    <a href="https://google.com" target="_blank"></a>
   </body>
     
</html>

6. In the form, add two radio buttons with grouping them for employee type(Salaried and own business)

<!DOCTYPE html>
<html lang="en">
   <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width , initial-scale = 1.0">
   </head>
   <body>
    <form>
        <label>
            <input type="radio" name="choice" value="option1">
            salaried
        </label></br>
        <label>
            <input type="radio" name="choice" value="option2">
            Own Bussiness
        </label></br>
    </form>
   </body>
     
</html>

7. Design form shown in the link (http://evc-cit.info/cit040/formguide/card_0.png)

---

8. Use the table tag to design given image [Click here](https://www.bapugraphics.com/assets/img/port_upload_dir/table-4.jpg).

---

9. Write HTML input tags snippet to show default values for all Form elements.
<DOCTYPE !>
<html>
    <head>
         <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width , initial-scale = 1.0">
    </head>
    <body>
        <form>
    <!-- Text Input -->
    <label for="textInput">Text Input:</label>
    <input type="text" id="textInput" name="textInput" value="Default Text"><br><br>

    <!-- Email Input -->
    <label for="emailInput">Email Input:</label>
    <input type="email" id="emailInput" name="emailInput" value="example@example.com"><br><br>

    <!-- Password Input -->
    <label for="passwordInput">Password Input:</label>
    <input type="password" id="passwordInput" name="passwordInput" value="defaultPass"><br><br>

    <!-- Number Input -->
    <label for="numberInput">Number Input:</label>
    <input type="number" id="numberInput" name="numberInput" value="10"><br><br>

    <!-- Date Input -->
    <label for="dateInput">Date Input:</label>
    <input type="date" id="dateInput" name="dateInput" value="2024-01-01"><br><br>

    <!-- Checkbox -->
    <label for="checkboxInput">Checkbox:</label>
    <input type="checkbox" id="checkboxInput" name="checkboxInput" checked><br><br>

    <!-- Radio Buttons -->
    <label>Radio Buttons:</label><br>
    <input type="radio" id="radio1" name="radioGroup" value="Option1" checked>
    <label for="radio1">Option 1</label><br>
    <input type="radio" id="radio2" name="radioGroup" value="Option2">
    <label for="radio2">Option 2</label><br><br>

    <!-- Select Dropdown -->
    <label for="selectInput">Select Dropdown:</label>
    <select id="selectInput" name="selectInput">
        <option value="Option1" selected>Option 1</option>
        <option value="Option2">Option 2</option>
        <option value="Option3">Option 3</option>
    </select><br><br>

    <input type="submit" value="Submit">
</form>
    </body>
</html>


10. In your, HTML page add the below line and Highlight it without using any CSS.

- "HTML & CSS is awesome"

<!DOCTYPE html>
<html lang="en">
   <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width , initial-scale = 1.0">
   </head>
   <body>
    <q>HTLM & CSS is awesome</q>
   </body>
     
</html>

11. Create an HTML page, which should contain all types of input elements.
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Input Elements Example</title>
</head>
<body>
    <h1>Input Elements Example</h1>
    <form action="#" method="post">
        <label for="text">Text Input:</label>
        <input type="text" id="text" name="text"><br><br>

        <label for="email">Email Input:</label>
        <input type="email" id="email" name="email"><br><br>

        <label for="password">Password Input:</label>
        <input type="password" id="password" name="password"><br><br>

        <label for="number">Number Input:</label>
        <input type="number" id="number" name="number"><br><br>

        <label for="range">Range Input:</label>
        <input type="range" id="range" name="range" min="1" max="100"><br><br>

        <label for="checkbox">Checkbox Input:</label>
        <input type="checkbox" id="checkbox" name="checkbox"><br><br>

       <label for="radio1">Radio Input 1:</label>
        <input type="radio" id="radio1" name="radio" value="option1">
        <label for="radio1">Option 1</label><br>
        
        <label for="radio2">Radio Input 2:</label>
        <input type="radio" id="radio2" name="radio" value="option2">
        <label for="radio2">Option 2</label><br><br>

        <label for="select">Select Input:</label>
        <select id="select" name="select">
            <option value="option1">Option 1</option>
            <option value="option2">Option 2</option>
            <option value="option3">Option 3</option>
        </select><br><br>

        <label for="textarea">Textarea Input:</label>
        <textarea id="textarea" name="textarea" rows="4" cols="50"></textarea><br><br>

        <label for="file">File Input:</label>
        <input type="file" id="file" name="file"><br><br>

        <label for="color">Color Input:</label>
        <input type="color" id="color" name="color"><br><br>

        <input type="submit" value="Submit">
    </form>
</body>
</html>
