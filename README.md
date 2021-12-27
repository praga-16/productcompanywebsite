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

### Home Page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple Inc.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Apple Inc.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/office.jpg" alt="Building" />
          <div class="contenttext">
            Apple Inc. is an American multinational technology company that specializes in consumer electronics, computer software and online services. Apple is the largest information technology company by revenue (totaling $274.5 billion in 2020) and, since January 2021, the world's most valuable company. As of 2021, Apple is the fourth-largest PC vendor by unit sales[9] and fourth-largest smartphone manufacturer.[10][11] It is one of the Big Five American information technology companies, alongside Amazon, Alphabet (Google), Meta (Facebook), and Microsoft.[12][13][14]

            Apple was founded in 1976 by Steve Jobs, Steve Wozniak and Ronald Wayne to develop and sell Wozniak's Apple I personal computer. It was incorporated by Jobs and Wozniak as Apple Computer, Inc. in 1977, and sales of its computers, among them the Apple II, grew quickly. It went public in 1980, to instant financial success. Over the next few years, Apple shipped new computers featuring innovative graphical user interfaces, such as the original Macintosh, announced in a critically acclaimed advertisement, "1984", directed by Ridley Scott. The high cost of its products and limited application library caused problems, as did power struggles between executives. In 1985, Wozniak departed Apple amicably,[15] while Jobs resigned to found NeXT, taking some Apple employees with him.[16]
            
            As the market for personal computers expanded and evolved throughout the 1990s, Apple lost considerable market share to the lower-priced duopoly of Microsoft Windows on Intel PC clones. The board recruited CEO Gil Amelio, who prepared the struggling company for eventual success with extensive reforms, product focus and layoffs in his 500-day tenure. In 1997, Amelio bought NeXT to resolve Apple's unsuccessful operating-system strategy and entice Jobs back to the company; he replaced Amelio. Apple became profitable again through a number of tactics. First, a revitalizing campaign called "Think different", and by launching the iMac and iPod. In 2001, it opened a retail chain, the Apple Stores, and has acquired numerous companies to broaden its software portfolio. In 2007, the company launched the iPhone to critical acclaim and financial success. Jobs resigned in 2011 for health reasons, and died two months later. He was succeeded as CEO by Tim Cook.
            
            The company receives significant criticism regarding the labor practices of its contractors, its environmental practices, and its business ethics, including anti-competitive behavior and materials sourcing. In August 2018, Apple became the first publicly traded U.S. company to be valued at over $1 trillion,[17][18] and, two years later, the first valued at over $2 trillion.[19][20] The company enjoys a high level of brand loyalty, and is ranked as the world's most valuable brand; as of January 2021, there are 1.65 billion Apple products in active use.[21]
            
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Apple Inc. Developed by Pragatheesvaran AB 
      </div>
    </div>
  </body>
</html>
~~~

### Products:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple Inc.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/11.jpg" alt="product image">
                  </div>
                  <div class="itemname">Apple 10S</div>
                  <div class="itemprice">Price: Rs.39500/- </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/12.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Air pods</div>
                  <div class="itemprice">Price: Rs.4500/- </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/13.png"  alt="product image">
                </div>
                <div class="itemname">Apple tv</div>
                <div class="itemprice">Price: Rs.4700/- </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/14.jpg"  alt="product image">
                </div>
                <div class="itemname">Desktop</div>
                <div class="itemprice">Price: Rs.200099/- </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/15.jpg"  alt="product image">
              </div>
              <div class="itemname">Headphone</div>
              <div class="itemprice">Price: Rs.40000/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/16.jpg"  alt="product image">
            </div>
            <div class="itemname">Tab</div>
            <div class="itemprice">Price: Rs.99970/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/17.jpg"  alt="product image">
            </div>
            <div class="itemname">Macbook</div>
            <div class="itemprice">Price: Rs.121070/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/18.jpg"  alt="product image">
            </div>
            <div class="itemname">Macbook pro</div>
            <div class="itemprice">Price: Rs.222570/- </div>
          </div>  <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/19.jpg"  alt="product image">
            </div>
            <div class="itemname">iWatch</div>
            <div class="itemprice">Price: Rs.65000/- </div>
        </div>
      
            </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Apple Inc. Developed by Pragatheesvaran AB
      </div>
    </div>
  </body>
</html>
~~~

### People:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple Inc.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
    </head>
    <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
      <div class="content">
        <div class="homecontent">
          <h1>Our company employees:</h1><br><br>
          <div class="productitems">
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/1.jpg" alt="product image">
                </div>
                <div class="itemname">Amudhan</div>
                <div class="itemprice">Managing Director</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/2.jpg"  alt="product image">
                </div>
                <div class="itemname">Keerthi</div>
                <div class="itemprice">Office manager</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/3.jpg"  alt="product image">
              </div>
              <div class="itemname">Varma</div>
              <div class="itemprice">Assistant HR</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/4.jpg"  alt="product image">
              </div>
              <div class="itemname">Praga</div>
              <div class="itemprice">Marketing Manager</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/5.jpg"  alt="product image">
            </div>
            <div class="itemname">Harish</div>
            <div class="itemprice">Professional Staff</div>
        </div>  <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/6.jpg"  alt="product image">
          </div>
          <div class="itemname">SIDDHU</div>
          <div class="itemprice">Operation Manager</div>
      </div>
          </div>
        </div>
        </div>        
    </div>
    <div class="footer">
      Copyright &#169; 2021 Apple Inc. Developed by Pragatheesvaran AB
    </div>
  </div>
</body>
</html>
~~~

### Contact Us:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple Inc.</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ail.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us:</h1><br><br>
          <h1>Address:</h1><br><br>
          <div class="contenttext">
            75/W Apple Park Inc.,<br>
            Cupertino,<br>
            Califonia.
          </div><br>
          <h1>Phone:</h1><br><br>
          <div class="contenttext">
              Mr.Rajesh  (MARKETING MANAGER): 8660156869<br><br>
              Mr.Siddharth (OPERATION MANAGER): 8868432145<br><br>
              Mr.Vijay (OFFICE MANAGER): 7384588585<br><br>
          </div>
          <h1>E-Mail:</h1><br><br>
          <div class="contenttext">
              Sales:appleinc@gmail.com
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Apple Inc. Developed by Pragatheesvaran AB
      </div>
    </div>
  </body>
</html>
~~~

## OUTPUT:

### Home Page:

![output](./images/homepage.jpg)

### Products:

![output](./images/products.jpg)

### People:

![output](./images/people.jpg)

### Contact Us:

![output](./images/contact.jpg)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
