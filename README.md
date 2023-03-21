# My-QR-Code-Project
<!DOCTYPE html>
<html lang="en">
<head>
    <link
    rel="icon"
    type="image/png"
    sizes="32x32"
    href="images/favicon-32x32.png"/>

    <link rel="stylesheet" href="style.css"/>
<title>QR Code</title>
</head>
<body>
    <div class="card">
     <img src="images/image-qr-code.png" alt="" />
     <h3 class="title">Improve your front-end skills by building projects</h3>

     <p>
        Scan the QR code to visit frontend Mentor and take your coding skills to next level
     </p>
    </div>
    
</body>
</html>

CSS part

@import url('https://fonts.googleapis.com/css2?family=Outfit&display=swap');



*{
    margin: 0;
    box-sizing: border-box;
}

body{
    background-color: #d5e1ef;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    font-family: 'Outfit', sans-serif;
}

.card{
    width: 320px;
    padding: 16px;
    border-radius: 19px;
    background-color: white;
    box-shadow: 0px 3px 15px rgba(0, 0, 0, 0.2);
}

.card > img {
    max-width: 100%;
    border-radius: 10px;
}

.title{
    text-align: center;
    margin: 20px 0;
    font-size: 1.4rem;
    color: hsl(218, 44%, 22%)
}

.card > p {
    text-align: center;
    margin-bottom: 20px;
    color: hsl(220, 15%, 55%);
}
