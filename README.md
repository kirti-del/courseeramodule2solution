# courseeramodule2solution
h1 {
    color: black;
    text-align: center;
}

p {
    margin-top: 50px;
    padding: 10px;
}
.textbox {
    float: left;
    overflow: auto;
    width: 400px;
    height: 250px;
    border: 1px solid black;
    background-color: #a9acbb;
    margin: 20px;
   
}

.textbox>div {
    float:right;
    width: 235px;
    padding: 8px;
    text-align: center;
    border-bottom: 1px solid black;
    border-left: 1px solid black;
    font-family: Times;
    margin: 0;
    width: 230px;
    text-align: center;
    font-style: Times;
    font-size: 24px;
    font-weight: bold;
    height: 45px;
    padding-top: 10px;
}

#chicken{

    border-left-style: solid;
    background-color: pink;
}

#beef {
   background-color: red;
}

#sushi {
    background-color: peachpuff;
}

section>p {
    padding: 40px 15px 15px 15px;
}

.row {
    width: 100%;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project</title>
    <link href="E:\Desktop\pro.css" rel="stylesheet" type="text/css">
</head>
<h1>Our menu</h1>
    <div class="row">
        <div class="col-lg-4 col-md-6 col-sm-12 ">
            <div class="textbox">
                <div id="chicken">Chicken</div>
            <section class="chicken">
                <p>
                    Lorem ipsum dolor sit amet, consectetur 
                    adipiscing elit,sed do eiusmod tempor incididunt
                    ut labore et dolore magna aliqua. Ut enim ad
                    minim veniam, quis nostrud exercitation ullamco 
                    laboris nisi ut aliquip ex ea commodo consequat.
                </p>
            </div>
            </section>
        </div>
        <div class="col-lg-4 col-md-6 col-sm-12 ">
            <div class="textbox">
                <div id="beef">Beef</div>
            <section class="beef">
                <p>
                    Lorem ipsum dolor sit amet, consectetur 
                    adipiscing elit,sed do eiusmod tempor incididunt
                    ut labore et dolore magna aliqua. Ut enim ad
                    minim veniam, quis nostrud exercitation ullamco 
                    laboris nisi ut aliquip ex ea commodo consequat.    
                </p>
            </div>
            </section>
        </div>
        <div class="col-lg-4 col-md-12 col-sm-12 ">
            <div class="textbox">
                <div id="sushi">Sushi</div>
            <section class="sushi">
                <p>
                    Lorem ipsum dolor sit amet, consectetur 
                    adipiscing elit,sed do eiusmod tempor incididunt
                    ut labore et dolore magna aliqua. Ut enim ad
                    minim veniam, quis nostrud exercitation ullamco 
                    laboris nisi ut aliquip ex ea commodo consequat.    
                </p>
            </div>
            </section>
        </div>
    </div>
</body>
</html>
