# Ex.06 Book Front Cover Page Design
## Date: 13.05.2025
## Name: MARIMUTHU MATHAVAN
## Regno: 212224230153

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Wolverine  Enemy Of The State - Book Template</title>
  <style>
    body {
      background:hwb(172 7% 9%);
      font-family: 'Georgia', serif;
      margin: 0;
      padding: 0;
    }
    .book {
      width: 12cm;          /* typical book width */
      height: 18cm;         /* fixed height */
      margin: 50px auto;
      padding: 20px;
      background: #e6e6aa;
      box-shadow: 0 10px 30px rgba(0,0,0,0.2);
      border: 2px solid #abac9c;
      overflow: hidden;     /* ensure content fits */
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    .cover {
      text-align: center;
    }
    .cover img {
      width: 8cm;
      margin-bottom: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.3);
    }
    .title {
      font-size: 24px;
      font-weight: bold;
      margin-bottom: 5px;
    }
    .author {
      font-size: 18px;
      color: #555;
      margin-bottom: 15px;
    }
    .description {
      font-size: 14px;
      line-height: 1.4;
      color: #333;
      text-align: justify;
    }
  </style>
</head>
<body>

<div class="book">
  <div class="cover">
    <img src="mad.jpg" alt="Wolverine  Enemy Of The State Book Cover">
    <div class="title">Wolverine  Enemy Of The State</div>
    <div class="author">By Millar. Romarita jr</div>
  </div>
  <div class="description">
    "Wolverine Enemy Of The State"  Wolverine, one of the most dangerous mutants in the Marvel Universe, is captured and brainwashed 
    by the deadly organization known as The Hand, along with Hydra and the mutant cult Dawn of the White Light.Turned into a 
    living weapon under their control, Wolverine is unleashed upon heroes, villains, and governments alike — becoming a lethal enemy 
    of the very state he once protected.
  </div>
</div>

</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-05-13 192758.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
