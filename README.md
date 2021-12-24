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
### home page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Asian Info Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Asian Info Private Limited</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="http://im.rediff.com/money/2012/jan/11jo20.jpg  " alt="Building" />
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
        Copyright &#169; 2021 Asian Info Private Limited, Developed by Souvik Kundu.
      </div>
    </div>
  </body>
</html>
~~~

### product page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Asian Info Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Asian Info Private Limited.</div>
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
                  <img src="https://m.media-amazon.com/images/I/61s1QQiqkKL._SL1100_.jpg" alt="product image">
                  </div>
                  <div class="itemname">Quick Heal </div>
                  <div class="itemprice">Price: Rs.745 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://m.media-amazon.com/images/I/51GlGdNR0wL._SL1000_.jpg"  alt="product image">
                  </div>
                  <div class="itemname">K7 Total Security</div>
                  <div class="itemprice">Price: Rs.999 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://m.media-amazon.com/images/I/61+szGyH9IS._SL1500_.jpg"  alt="product image">
                </div>
                <div class="itemname">Ubuntu Installation Drive</div>
                <div class="itemprice">Price: Rs.1500</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://m.media-amazon.com/images/I/61tUB2uBVtS._SL1132_.jpg"  alt="product image">
              </div>
              <div class="itemname">Vypar billing software</div>
              <div class="itemprice">Price: Rs.999</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="https://m.media-amazon.com/images/I/71HpEfZSgkL._SL1500_.jpg"  alt="product image">
            </div>
            <div class="itemname">Ms office 365</div>
            <div class="itemprice">Price: Rs.3500 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://m.media-amazon.com/images/I/61W8fnM+u4L._SL1072_.jpg"  alt="product image">
          </div>
          <div class="itemname">MacFee Antivirus</div>
          <div class="itemprice">Price: Rs.1500 </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="https://m.media-amazon.com/images/I/51U8B1LvQOL._SL1301_.jpg"  alt="product image">
        </div>
        <div class="itemname">Windows 10</div>
        <div class="itemprice">Price: Rs.4000 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="https://m.media-amazon.com/images/I/71AMCTkRkeS._SL1500_.jpg"  alt="product image">
      </div>
      <div class="itemname">Photo Recovery Software</div>
      <div class="itemprice">Price: Rs.500 </div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="https://m.media-amazon.com/images/I/71Vv4h65mpL._SL1080_.jpg"  alt="product image">
    </div>
    <div class="itemname">Max Security software</div>
    <div class="itemprice">Price: Rs.5030 </div>
</div>    <div class="productitem"> 
  <div class="itemimage">
  <img src="https://m.media-amazon.com/images/I/71x7273wT5L._SL1500_.jpg"  alt="product image">
  </div>
  <div class="itemname">Disk Recovery Software</div>
  <div class="itemprice">Price: Rs.500 </div>
</div>    <div class="productitem"> 
  <div class="itemimage">
  <img src="https://m.media-amazon.com/images/I/41ab22J-kAL.jpg"  alt="product image">
  </div>
  <div class="itemname">Driver pack Software </div>
  <div class="itemprice">Price: Rs.575 </div>
</div>    <div class="productitem"> 
  <div class="itemimage">
  <img src="https://m.media-amazon.com/images/I/61LxBuzh54L._SL1046_.jpg"  alt="product image">
  </div>
  <div class="itemname">Norton Anti Virus Software</div>
  <div class="itemprice">Price: Rs.1500 </div>
</div>
    
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Asian Info Private Limited, Developed by Souvik Kundu.
      </div>
    </div>
  </body>
</html>
~~~
### people page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Asian Info Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Asian Info Private Limited.</div>
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
          <h1>Our Crew</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://www.shell.com/covid-19-a-message-from-ceo-ben-van-beurden/_jcr_content/pagePromo/image.img.960.jpeg/1592836936166/shell-ceo-ben-van-beurden.jpeg" alt="product image">
                  </div>
                  <div class="itemname">Mr.kevin</div>
                  <div class="itemprice">CEO </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://static.standard.co.uk/2021/05/18/13/bbfb11aa604b32993a18cdf596e2ec7bY29udGVudHNlYXJjaGFwaSwxNjIxNDIzOTkz-2.36062104.jpg?width=968&auto=webp&quality=75&crop=968%3A645%2Csmart"  alt="product image">
                  </div>
                  <div class="itemname">Mr.Jack</div>
                  <div class="itemprice">Branch Manager </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://www.shell.com/media/speeches-and-articles/2018/moving-with-the-times/_jcr_content/par/textimage_2228/image.img.960.jpeg/1539005793828/ben-van-beurden-new.jpeg?imwidth=960"  alt="product image">
                </div>
                <div class="itemname">Mr. Rubin</div>
                <div class="itemprice">Capital Manager</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://6erxg60qvo1qvjha44jrgpan-wpengine.netdna-ssl.com/wp-content/uploads/2019/11/Mattias-Perjos-president-CEO-Getinge.jpg"  alt="product image">
              </div>
              <div class="itemname">Mr.Ruther</div>
              <div class="itemprice">Technical Lead</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="https://ehealth.eletsonline.com/wp-content/uploads/2021/02/gore.jpg"  alt="product image">
            </div>
            <div class="itemname">Mr.Ram</div>
            <div class="itemprice">Team Lead </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://ichef.bbci.co.uk/news/976/cpsprodpb/165C4/production/_121888519_parag-agarwal_hires.jpg"  alt="product image">
          </div>
          <div class="itemname">Mr.Ravi</div>
          <div class="itemprice">Senior Employee</div>
      </div>

    
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Asian Info Private Limited, Developed by Souvik Kundu.
      </div>
    </div>
  </body>
</html>
~~~
### contact page:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Asian Info Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Asian Info Private Limited</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <div class="contenttext">
          Mail us at asianifotech@gmail.com
          <br>
          contact us at 9988774455
          <br>
          Our main branch is located at:- 5-99 little parks lane, Ringroad, opposite to clock tower , blue building 2nd floor.
        </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Asian Info Private Limited, Developed by Souvik Kundu.
      </div>
    </div>
  </body>
</html>
~~~
## OUTPUT:

### Home Page:

![output](./images/ty.png)


### Product page:

![output](./images/product.png)

### people page:

![output](./images/qw.png)

### contact page:

![output](./images/re.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
