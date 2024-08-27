# Nicholas-Solis-mod2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Menu</title>
    <link rel="stylesheet" href="styles2.css">
  <styles>
      
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


body {
    font-family: Arial, sans-serif;
    text-align: center;
    background-color: #f8f8f8;
    padding: 20px;
}


header h1 {
    margin-bottom: 20px;
}


.menu {
    display: flex;
    justify-content: space-around;
    margin: 20px;
}


.menu-item {
    background-color: #ccc;
    max-width: 30%;
    padding: 15px;
    border-radius: 5px;
    margin: 15px;
    border: 2px solid black
}


.menu-title {
    color: white;
    padding: 5px;
    font-weight: bold;
    text-align: right;
    margin-bottom: 10px;
    border-radius: 3px;
    
    
}


.chicken {
    background-color: #21aa09;
    border: 2px solid black
    
}

.beef {
    background-color: #c9302c;
    border: 2px solid black
}

.sushi {
    background-color: #f0ad4e;
    border: 2px solid black
}


.menu-item p {
    font-size: 14px;
    color: #333;
}

@media (max-width: 991px) {
    .menu {
        flex-direction: column;
        align-items: center;

    }

}


    
  </styles>
</head>
<body>
    <header>
        <h1>Our Menu</h1>
    </header>
    <section class="menu">
        <div class="menu-item">
            <div class="menu-title chicken">Chicken</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua...</p>
        </div>
        <div class="menu-item">
            <div class="menu-title beef">Beef</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua...</p>
        </div>
        <div class="menu-item">
            <div class="menu-title sushi">Sushi</div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua...</p>
        </div>
    </section>
</body>
</html>
