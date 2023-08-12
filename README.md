# CustomFont_css
This repo help to how to use local fonts in our webpage using css

index.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Custom Font</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div>
      <h1>Hacked</h1>
    </div>
  </body>
</html>

````

style.css
```
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
@font-face {
    /* Give name for your font */
    font-family: Hacked; 
     /* path to your font */
    src: url(./Fonts/HACKED.ttf)
  }
body{
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 40px;
    color: #ffffff;
    background-color: rgb(0, 0, 0);
    letter-spacing: 20px; 
    
    /*using font  */
    font-family: Hacked; 
}

````
