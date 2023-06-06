# RESTAURANT-HTML

### AIM :
      To Create a commercial website using HTML & CSS .

### ALGORITHM :
	
      Step 1: Start by creating a new folder. 
      Step 2: Create and Open the “index.html”, write the code.
      Step 3: Create a new CSS file “style.css” 
      Step 4: Design the basic structure of your website using HTML tags like <header>,      
                            <nav>, <main>, and <footer>.
      Step 5: Implement navigation menus using HTML lists (<ul> or <ol>) and CSS                                                   
                 styling.
      Step 6: Test your website by opening the HTML file in a web browser. Make any  
                            necessary adjustments to the HTML and CSS code to achieve the desired   
                            layout and design.
                 
 ### PROGRAM :
    
    index.html
      <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Document</title>

        <!-- fontawesome link here -->
        <link rel="stylesheet" href="fontawesome-free-5.15.3-web/css/all.min.css" />

        <!-- style link here -->
        <link rel="stylesheet" href="assets/res-style.css" />
      </head>
      <body>
        <header class="header">
          <div class="logo">Absolute</div>

          <nav class="navbar">
            <a href="#">home</a>
            <a href="#">about</a>
            <a href="#">menu</a>
            <a href="#">customers</a>
            <a href="#">break</a>
          </nav>

          <div class="icons">
            <div id="menu-bar" class="fas fa-bars"></div>
            <a class="contact-btn" href="#">contact</a>
          </div>
        </header>

        <div class="home">
          <div class="main-home">
            <div class="home-inner-content">
              <div class="home-image">
                <img src="images/background content.png" alt="" />
              </div>
            </div>

            <div class="home-inner-content">
              <div class="home-text-content">
                <h1>RESTAURANT ABSOLUTE</h1>
                <p>Step in to experience the taste of taste.</p>
                <a href="#">contact us</a>
              </div>
            </div>
          </div>
        </div>

        <div id="about" class="about">
          <div class="main-about">
            <div class="about-content">
              <div class="about-inner-content">
                <img class="myimageabout" src="images/About us.png" alt="" />
              </div>
            </div>

            <div class="about-content">
              <div class="about-inner-content">
                <div class="about-text-content">
                  <h1>About us</h1>
                  <p>
                    We serve with honour and previlege by understanding the needs of
                    the customers. The taste here is unique and is an epitome of
                    finest dishes.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="quality">
          <div class="main-quality">
            <div class="main-inner-quality">
              <div class="quality-content">
                <h1>Our food quality</h1>
                <p>The customers' feedback reflects the quality of our food!</p>
              </div>
            </div>

            <div class="main-inner-quality">
              <div class="quality-content qulity-image">
                <img src="images/egg.png" alt="" />
              </div>
            </div>
          </div>
        </div>

        <div class="gallery">
          <h1>Gallery</h1>

          <div class="main-gallery">
            <div class="inner-gallery">
              <div class="gallery-image">
                <img src="images/gallery1.png" alt="" />
              </div>
            </div>

            <div class="inner-gallery">
              <div class="gallery-image">
                <img src="images/gallery2.png" alt="" />
              </div>
            </div>

            <div class="inner-gallery">
              <div class="gallery-image">
                <img src="images/gallery3.png" alt="" />
              </div>
            </div>

            <div class="inner-gallery">
              <div class="gallery-image">
                <img src="images/gallery4.png" alt="" />
              </div>
            </div>

            <div class="inner-gallery">
              <div class="gallery-image">
                <img src="images/gallery5.png" alt="" />
              </div>
            </div>

            <div class="inner-gallery">
              <div class="gallery-image">
                <img src="images/gallery6.png" alt="" />
              </div>
            </div>
          </div>
        </div>

        <div class="enjoy-our-food">
          <div class="food-main-content">
            <h1>enjoy our food</h1>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Culpa quidem
              sit nostrum pariatur perferendis soluta saepe nam eveniet velit
              exercitationem iusto, molestias sapiente laborum? Hic, eaque.
              Voluptatum sit incidunt ipsa.
            </p>
          </div>
        </div>

        <div class="our-menu-food">
          <h1>our menu</h1>

          <div class="main-menu-food">
            <div class="inner-menu-food">
              <div class="menu-food-content">
                <img src="images/menu2.png" alt="" />

                <div class="menu-food-text">
                  <h2>North Indian</h2>
                  <p>Everyone's Favorite Chapati with Panner</p>
                  <p><span>Price / INR 150.00</span></p>
                </div>
              </div>
            </div>

            <div class="inner-menu-food">
              <div class="menu-food-content">
                <img src="images/mwnu1.png" alt="" />

                <div class="menu-food-text">
                  <h2>South Indian</h2>
                  <p>The popular and favourite one Biriyani</p>
                  <p><span>Price / INR 200.00</span></p>
                </div>
              </div>
            </div>

            <div class="inner-menu-food">
              <div class="menu-food-content">
                <img src="images/menu3.png" alt="" />

                <div class="menu-food-text">
                  <h2>Chinese</h2>
                  <p>The icon Noodles</p>
                  <p><span>Price / INR 300.00</span></p>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="before">
          <img src="images/before footer.png" alt="" />
        </div>

        <div class="footer">
          <div class="main-footer">
            <div class="footer-logo">Absolute</div>
          </div>

          <footernav class="footer-navbar">
            <a href="#">home</a>
            <a href="#">about</a>
            <a href="#">menu</a>
            <a href="#">customers</a>
            <a href="#">break</a>
          </footernav>
        </div>
      </body>
    </html>

### OUTPUT :

![Screenshot (413)](https://github.com/JANANI0210/restaurant-html/assets/86832944/4cb637c0-3177-4bdc-bb15-06e3d5ae6a72)

### RESULT :
    Thus, Create a commercial website using HTML & CSS has been created and executed successfully.


