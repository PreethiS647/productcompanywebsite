# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :

## OUTPUT:
```
home.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Splencer Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Splencer Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/building.png" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our new product TallyPrime takes this to a new level, making your
            start to automation, or your switch to Tally simpler than ever
            before. You can now discover the product much more easily and make
            the product do more for you, without learning anything new. There is
            greater flexibility as the product adapts to your business and your
            way of working. And the transformed look and feel will only make you
            love the product even more.
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Splencer Private Limited, Developed by Deeksha.
      </div>
    </div>
  </body>
</html>

products.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Splencer Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Splencer Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Splencer Private Limited, Developed by Deeksha.
      </div>
    </div>
  </body>
</html>

people.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Splencer Private Limited</title>
    <link rel="stylesheet" href="/static/css/layout.css" />
    <link rel="icon" href="/static/img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Splencer Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Council Members</h1>
          <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/p1.jpeg"  alt="product image">
          </div>
          <div class="itemname">Lily</div>
          <div class="itemprice">CEO</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/p2.jpeg"  alt="product image">
          </div>
          <div class="itemname">Thara</div>
          <div class="itemprice">MD</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/p3.jpeg"  alt="product image">
          </div>
          <div class="itemname">Mia</div>
          <div class="itemprice">VP of Marketing</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/p4.jpeg"  alt="product image">
          </div>
          <div class="itemname">Cassy</div>
          <div class="itemprice">Cheif Architect</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/p5.jpeg"  alt="product image">
        </div>
        <div class="itemname">Amayra</div>
        <div class="itemprice">Project Manager</div>
      </div>
      <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/p6.jpeg"  alt="product image">
      </div>
      <div class="itemname">Olivia</div>
      <div class="itemprice">Technical Lead</div>
      </div>
      </div>
        </div>
      <div class="footer">
        Copyright &#169; 2021 Splencer Private Limited, Developed by Deeksha.
    </div>    
      </div>
    </div>
  </body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Splencer Private Limited</title>
    <link rel="stylesheet" href="/static/css/layout.css" />
    <link rel="icon" href="/static/img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Splencer Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us</h1>
          <div class="contenttext">
            Email: Splencerpvtltd@gmail.com
            <br>
            Phone: +919876543210
            <br>
            Address: No:88 , 1st cross st , Dubai main road ,  Dubai 400004.

          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Splencer Private Limited, Developed by Deeksha.
      </div>
    </div>
  </body>
</html>

layout.css

* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/banner1.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #16d1ae;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #5bb045;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #5bb045;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
```

### Home Page:

![image](https://github.com/PreethiS647/productcompanywebsite/assets/147313372/3a106f26-01ea-47c0-ba5f-b45cbea836e0)
![image](https://github.com/PreethiS647/productcompanywebsite/assets/147313372/5bfe424a-4207-4b4b-8768-657bf4de61c3)
![image](https://github.com/PreethiS647/productcompanywebsite/assets/147313372/f5ee122a-5903-42da-bfe3-7225f0917c76)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
