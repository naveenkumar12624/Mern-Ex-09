# Exp -9 Create a Birthday card using HTML and CSS
## AIM:
To write html & css code to create birthday card.
## PROCEDURE:
### STEP 1:
Create a html code for the birthday card.
### STEP 2:
Make style for the birthday card using css.
### STEP 3:
Link the css with html by link tag
### STEP 4:
Verify the output by running the birthday card in any web browser. 
## PROGRAM:
### HTML:
```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
  <div class="card">
    <h1>
        BIRTHDAY INVITATION
    </h1>
    <img src="images.png" >
  
    <h2>Wishing you a fantastic day <br>filled with joy and happiness.<br>May all your dreams come true!<br>Have a wonderful birthday!</h2>
    <p>Time: On 7 p.m. Onwards<br>Venue: Nehru Hall.<br>Chennai.</p>

    <img src="1.jpg">
  </div>
</body>
</html>

```
### CSS:
```css
body {
    background-color: #322e2e;
    font-family: Arial, sans-serif;
    text-align: center;
  }
  
  .card {
    background-color: #9847ce;
    height: 90vh;
    width: 400px;
    margin: 0 auto;
    padding: 20px;
    border-radius: 30px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
  }
  
  h2 {
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-size:20px;
    color: #ffffff;
    text-align: left;
  }
  
  p {
    text-align: right;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 10px;
    color: #ffffff;
    line-height: 1.5;
  }

```
## OUTPUT:
![image](https://github.com/naveenkumar12624/Mern-Ex-09/assets/93427235/e7d32c4e-321a-472c-97d0-2bd76ce87209)


## RESULT:
html & css code to create birthday card has been created and output has been verified.
