# e-commerce_site
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="css1.css">
  <title>Product Landing Page - K-POP</title>
</head>

<body>
  <header id="header">
    <nav id="nav-bar">
      <img id="header-img" src="https://tse3.mm.bing.net/th?id=OIP.XnvMX4m3gn5PkOLqTjEf5QHaB2&pid=Api&P=0" alt="logo" class="logo">
      <ul>
        <a class="nav-link" href="#features">Features</a>
        <a class="nav-link" href="#how-it-work">How It Works</a>
        <a class="nav-link" href="#pricing">Pricing</a>
      </ul>
    </nav>
  </header>

  <div id="container">
    <section class="message-box">
      <h1>Hand-made and Imported K-Pop merchandise and masterpieces</h1>
      <form id="form" action="https://www.youtube.com/">
      <input id="email" type="email" name="email" placeholder="example@mail.com">
      <input id="submit" type="submit" value="Get Started" class="btn"></input>
      </form>
    </section>

    <section id="features">
      <div class="feature">
        <i class="fab fa-free-code-camp fa-3x"></i>
        <div>
          <h2>Premium Materials</h2>
          <p>Our K-POP MERCH is made up of BEST MATERIAL which is sourced locally. This will increase the longevity of your
            purchase.</p>
        </div>
      </div>
      <div class="feature">
        <i class="fas fa-shipping-fast fa-3x"></i>
        <div>
          <h2>Fast Shipping</h2>
          <p>We make sure you receive your order as soon as we have finished making it. We also provide free returns
            if you are not satisfied.</p>
        </div>
      </div>
      <div class="feature">
        <i class="fas fa-battery-full fa-3x"></i>
        <div>
          <h2>Quality Assurance</h2>
          <p>For every purchase you make, we will ensure there are no damages or faults and we will check and test the
            pitch of your instrument.</p>
        </div>
      </div>
    </section>
    <section id="how-it-work">
      <iframe id="video" src="https://fashionchingu.zendesk.com/hc/en-us?_ga=2.225972056.394095978.1667420479-1545829040.1667420479&_gl=1*mg5oei*_ga*MTU0NTgyOTA0MC4xNjY3NDIwNDc5*_ga_ZX0M5YM2NF*MTY2NzQyMDQ3OS4xLjEuMTY2NzQyMDYzNS4wLjAuMA.."></iframe>
    </section>
    <section id="pricing">
      <div class="price-box">
        <h3>K-POP TOOLS</h3>
        <h2>$40-$60</h2>
        <p>PINS
            PEN
            CUPS
            WALL-POSTER
        </p>
        <a href="https://kpopmerch.store/" class="btn">SELECT</a>
      </div>
      <div class="price-box">
        <h3>K-POP CUSTOMIZED</h3>
        <h2>$60-$80</h2>
        <p>Bottle
            Cup
            T-Shirt
            Hoodie
            Shoes
        </p>
        <a href="https://www.etsy.com/in-en/market/kpop_customized" class="btn">SELECT</a>
      </div>
      <div class="price-box">
        <h3>K-POP CLOTHING</h3>
        <h2>$80-$100</h2>
        <p>T-Shirt
            Hoodie
            Jeans
            Sweat Shirt
            Shoes
        </p>
        <a href="https://www.fashionchingu.com/" class="btn">SELECT</a>
      </div>
    </section>
  </div>
  <footer id="main-footer">
    <div>
      <a href="https://www.instagram.com/hvg.ig/">Instagram</a>
      <a href="#">LinkedIn</a>
      <a href="#">Github</a>
    </div>
    <p class="my-name">This Page is created by Harshvardhan Gupta</p>
    <p>&copy;Copyright 2022, Original K-POP MERCHANDISE</p>
  </footer>
</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.5;
  }
  
  ul {
    list-style: none;
  }
  
  a {
    text-decoration: none;
  }
  
  #header {
    display: flex;
  }
  
  #nav-bar {
    position: fixed;
    top: 0px;
    display: flex;
    width: 100%;
    justify-content: space-between;
    align-items: center;
    background-color: rgb(255, 255, 255);
    overflow: hidden;
  }
  #container {
    max-width: 960px;
    margin: 2rem auto 0;
    overflow: hidden;
  }
  
  .logo {
    width: 300px;
    cursor: pointer;
  }
  
  @media (min-width: 1200px) {
    body {
        background-color: rgb(244, 156, 156);
    }
  }
  
  .btn {
    display: inline-block;
    padding: 0.4rem 1.5rem;
    color: #333;
    text-transform: uppercase;
    font-weight: bold;
    background-color: hsl(58, 89%, 50%);
  }
  
  .nav-link {
      float: left;
      display: block;
      color: #000000;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
      font-size: 17px;
  }
  
  
  .message-box {
    margin: 1.5rem;
    padding: 0.8rem;
    text-align: center;
  }
  
  .message-box h1 {
    font-size: 1.7rem;
    margin-bottom: 1rem;
  }
  
  .message-box input {
    display: block;
    margin: auto;
    width: 30%;
    padding: 0.4rem;
    margin-bottom: 1rem;
  }
  
  #features {
    padding: 1rem;
    margin-top: 3rem;
    margin-bottom: 3rem;
    display: flex;
    flex-direction: column;
  }
  
  #features .feature {
    display: flex;
    justify-self: center;
    align-items: center;
  }
  
  #features .feature i {
    color: hsl(58, 100%, 52%);
  }
  
  #features .feature div {
    padding: 1rem;
    margin-left: 3rem;
  }
  
  #features .feature div h2 {
    font-size: 1.5rem;
    margin-bottom: 0.5rem;
  }
  
  #how-it-work {
    padding: 3rem;
    margin: auto;
    text-align: center;
  }
  
  #how-it-work #video {
    width: 600px;
    height: 340px;
  }
  
  #pricing {
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 3rem 0.2rem;
  }
  
  .price-box {
    border: solid #333 3px;
    border-radius: 2px;
    text-align: center;
  }
  
  .price-box:first-child {
    margin-right: 1.2rem;
  }
  
  .price-box:last-child {
    margin-left: 1.2rem;
  }
  
  .price-box h3 {
    background-color: #ddd;
    font-size: 1.05rem;
    padding: 1rem;
  }
  
  .price-box h2 {
    padding: 1rem;
  }
  
  .price-box p {
    padding: 0 4rem 1rem;
  }
  
  .price-box .btn {
    display: inline-block;
    margin: 1rem;
  }

  #main-footer {
    background-color: rgb(77, 194, 226);
    padding: 1rem 4rem;
    margin-top: 2rem;
    display: flex;
    justify-content: space-between;
    overflow: hidden;
  }
  
  #main-footer div a {
    color: #333;
    padding: 0.5rem 1rem;
  }
  
  #fcs {
    text-decoration: underline;
    color: #333;
  }
  @media only screen and (max-width: 800px) {
    #navbar {
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 1.5rem 0.3rem;
    }
  
    #navbar ul li {
      padding: 1rem 1rem;
    }
  
    #features .feature {
      flex-direction: column;
    }
  
    #features .feature div {
      padding: 1rem;
      margin: 0.5rem;
      text-align: center;
      margin-bottom: 2rem;
    }
  
    #how-it-work {
      padding: 1rem;
    }
  
    #how-it-work #video {
      width: 80%;
      height: 30%;
    }
  
    #pricing {
      flex-direction: column;
    }
  
    #pricing .price-box {
      margin: 1rem;
    }
  
    .price-box:first-child {
      margin-right: 0;
    }
  
    .price-box:last-child {
      margin-left: 0;
    }
  
    #main-footer {
      padding: 2.5rem 0.5rem;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
  
    #main-footer .my-name {
      margin: 1rem 0;
    }
  }
