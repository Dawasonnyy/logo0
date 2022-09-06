<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="index.css" />

    <title>Document</title>
  </head>
  <body >
    <div id="desktop">

        <nav class="nav_nav">
            <div class="nav">
          <div class="logo">Dawit</div>
          <ul class="nav__list">
            <li class="nav__list--link home"><a href="desktop.html">home</a></li>
    
            <li class="nav__list--link"><a href="#" onclick="ContactPop()">Contact </a></li>
    
            <li class="nav__list--link "><a href="projects.html">Projects</a></li>
    
            <li class="nav__list--link"><a href="New folder/Resume.pdf" target="_blank">resume</a></li>
          </ul>
        </nav>
        
    
        <div class="home__page">
            <div class="contact__remove" onclick="Remove()">
                <div class="desktop__main" >
                   <div class="desktop__main-img">
                    <img src="./New folder/background.jpg" alt="Me" />
                  </div>
                  
                  <div class="desktop__main-description">
                    <h1 class="desktop__main-header">HI THERE!</h1>
                    <h5 class="desktop__main-subheader">I am Dawit</h5>
                    <p  class="desktop__main-para1 animation1">Frontend developer</p>
                    <p class="desktop__main-para2 animation2">UX/UI Developer</p>
                  </div>
                 
                </div>

                <div class="desktop__aboutme-page">

                 
                    <div class="desktop__aboutme">
                      <h1 class="desktop__aboutme-header">About me</h1>
                      <p class="desktop__aboutme-para">Hi, I’m Dawit Israel, a Front-end developer focused on creating beautiful and user friendly applications while writing clean code. </p>
                    </div>
                  </div>   
                </div>
                  
                  <div class="desktop__contact-page" >
                  
                    <form  action="" class="desktop__input--field" id="contact_page">
                      <div class="contact__contents">
                        <div class="desktop__address">
                          <figure class="desktop_contact-fig">
                            
                            <img src="New folder/location.png" alt="location" class="desktop__contact-img"><br>
                            <label class="contact__para">Address: <span class="contact__span">Addis Ababa,Ethiopia</span></label>
                          </figure>
    
                          <figure class="desktop_contact-fig">
                            <img src="New folder/call.png" alt="location" class="desktop__contact-img"><br>
                            <label class="contact__para">Phone: <span class="contact__span">+251 92 358 0987</span></label>
                          </figure>
                          
    
                          <figure class="desktop_contact-fig">
                            <img src="New folder/mail.png" alt="location" class="desktop__contact-img"><br>
                            <label class="contact__para">Email: <span class="contact__span">dawitisrael9b@gmail.com</span></label>
                          </figure>
                        </div>
    
                      </div>
                      <hr>
                      
                  <div class="desktop__input">

                    <h1 class="desktop__header"> Get In touch with me</h1>
                    <input type="text" name="user__name" id="desktop__name" placeholder="Your Name"/>
                    <br />
                    
                    <input type="email" name="user__email" id="desktop__email" placeholder="Your Email" />
                    <br />
                    
                    <textarea name="message" id="desktop__message" placeholder="Your Message"></textarea>
                    <br />
                   <button class="submit" onclick="Pip()"><a href="#">Submit</a></button>
                  </form>
                  </div>
                  <div class="desktop__loading" id="load"><img class="img__spinner" src="/New folder/spinner.png" alt="spinner"></div>
                <div class="desktop__success" id="successpage" >
                  <h3 class="desktop__success-page">Looking Forward to speaking with you :)</h3>
                  <img  onclick="Remove()" src="/New folder/cancel2.png" alt="cancel"  id="xbtn" class="cancel__img">
                </div>
               
                  </div>
                  

                  <div class="contact__remove" onclick="Remove()">
                 <div class="desktop__lang-page">
                  <h1 class="desktop__skills-header">Skills</h1>
        <div class="desktop__lang">

          <div class="desktop__lang1">
         

          <figure class="desktop__lang-fig">
            <img src="/New folder/css.png" alt="css" class="desktop__lang-img">
            <h4 class="desktop__lang-header">css</h4>

          </figure>

          <figure class="desktop__lang-fig">
            <img src="New folder/html.png" alt="html" class="desktop__lang-img">
            <h4 class="desktop__lang-header">html</h4>

          </figure>

          <figure class="desktop__lang-fig">
            <img src="New folder/java.png" alt="java" class="desktop__lang-img">
            <h4 class="desktop__lang-header">javascript</h4>

          </figure>
          <figure class="desktop__lang-fig">
            <img src="New folder/mobx.png" alt="mobx" class="desktop__lang-img">
            <h4 class="desktop__lang-header">mobx</h4>

          </figure>
        </div>
          <div class="desktop__lang2">
        

          <figure class="desktop__lang-fig">
            <img src="New folder/nuxt.png" alt="nuxt" class="desktop__lang-img">
            <h4 class="desktop__lang-header">nuxt</h4>

          </figure>

          <figure class="desktop__lang-fig">
            <img src="New folder/react.png" alt="react" class="desktop__lang-img">
            <h4 class="desktop__lang-header">react</h4>

          </figure>

          <figure class="desktop__lang-fig">
            <img src="New folder/typescript.png" alt="typescript" class="desktop__lang-img">
            <h4 class="desktop__lang-header">typescript</h4>

          </figure>

          <figure class="desktop__lang-fig">
            <img src="New folder/vue.png" alt="vue" class="desktop__lang-img">
            <h4 class="desktop__lang-header">vue</h4>

          </figure>
        </div>
        <h1 class="desktop__skills-header">Other</h1>
        <div class="desktop__other-lang">
          

          <figure class="desktop__lang-fig">
            <img src="New folder/firebase.png" alt="vue" class="desktop__lang-img">
            <h4 class="desktop__lang-header">Firebase</h4>

          </figure>

          <figure class="desktop__lang-fig">
            <img src="New folder/git.png" alt="vue" class="desktop__lang-img">
            <h4 class="desktop__lang-header">Git</h4>

          </figure>

          <figure class="desktop__lang-fig">
            <img src="New folder/photoshop.png" alt="vue" class="desktop__lang-img">
            <h4 class="desktop__lang-header">photoshop</h4>

          </figure>

        </div>
      </div>

        </div>
    
    
        <div class="footer">
            <footer>
                <footer class="desktop__footer">
                   <div class="desktop__wrapper">
                    
                    <figure class="desktop__logo-figure">
                      <a href="https://github.com/Dawasonnyy" class="desktop__footer-logo-links"
                        ><img
                          src="./New folder/github.png"
                          alt="github"
                          class="desktop__footer-logos"
                      /></a>
                    </figure>
                    <figure class="desktop__logo-figure">
                      <a href="https://www.linkedin.com/in/dawit-israel-b3a046245" class="desktop__footer-logo-links"
                        ><img
                          src="/New folder/insta.png"
                          alt="insta"
                          class="desktop__footer-logos"
                      /></a>
                    </figure>
                    <figure class="desktop__logo-figure">
                      <a href="https://t.me/dawa_sonny" class="desktop__footer-logo-links"
                        ><img
                          src="/New folder/linkedin.png"
                          alt="linkedin"
                          class="desktop__footer-logos"
                      /></a>
                    </figure>
                    <figure class="desktop__logo-figure">
                      <a href="https://wa.me/251923580987" class="desktop__footer-logo-links"
                        ><img src="/New folder/whatsapp.png" alt="whatsapp"
                        class="desktop__footer-logos"></a
                      >
                    </figure>


                   </div>
                   
                    <div class="footer__para">
                      2022 - Created by Dawit Israel
                    </div>
                  </footer>
            </footer>
          </div>
        </div>
    

    
</div>
    
    
  <div class="mobile" id="mobile">

    <div class="mobile__home--page">
        <nav class="mobile__nav" >
          <div class="mobile__menu--btn">
            <img
              src="./New folder/menu.png"
              onclick="Pop()"
              alt="menu"
              class="mobile_menu-img"
            />
          </div> <div class="mobile__logo"><a href="mobile.html">Dawit</a></div>
        </nav>
        <ul class="mobile__menu--list" id="swipe">
          <li class="mobile__list--links"><a href="mobile.html">Home</a></li>
          <li class="mobile__list--links"><a href="#"  onclick="RemoveSlide(),  ContactPop()" >Contact Me</a></li>
          <li class="mobile__list--links"><a href="#">My resume</a></li>
          <li class="mobile__list--links"><a href="mobileprojects.html">Previous Projects</a></li>
        </ul>
        <div class="contact"onclick="Remove()" >
          <div class="mobile__main" >
             <div class="mobile__main-img">
              <img src="./New folder/background.jpg" alt="Me" />
            </div>
            
            <div class="mobile__main-description">
              <h1 class="mobile__main-header">HI THERE!</h1>
              <h5 class="mobile__main-subheader">I am Dawit</h5>
              <p  class="mobile__main-para1 animation1">Frontend developer</p>
              <p class="mobile__main-para2 animation2">UX/UI Developer</p>
            </div>
           
          </div>
  
         
          
        
        
  
        <div class="mobile__contact-page" >
          <form  action="" class="input__field" id="contact">
            <h1 class="mobile__header"> Get In touch with me</h1>
            <input type="text" name="user__name" id="mobile__name" placeholder="Your Name"/>
            <br />
            
            <input type="email" name="user__email" id="email" placeholder="Your Email" />
            <br />
            
            <textarea name="message" id="message" placeholder="Your Message"></textarea>
            <br />
           <button class="submit_btn" onclick="Pip()"><a href="#">Submit</a></button>
          </form>
          <div class="loading" id="load"><img class="img__spinner" src="/New folder/spinner.png" alt="spinner"></div>
        <div class="success" id="successpage" >
          <h3 class="mobile__success-page">Looking Forward to speaking with you :)</h3>
          <img  onclick="Remove()" src="/New folder/cancel2.png" alt="cancel"  id="xbtn" class="cancel__img">
          
        </div>
        </div>
      </div>
  
        
  
        <div class="mobile__aboutme-page">
          <div class="mobile__aboutme">
            <h1 class="mobile__aboutme-header">About me</h1>
            <p class="mobile__aboutme-para">Hi, I’m Dawit Israel, a Front-end developer focused on creating beautiful and user friendly applications while writing clean code.</p>
          </div>
        </div>
  
        <div class="mobile__lang-page">
          <div class="mobile__lang">
            <h1 class="mobile__lang_header">Skills</h1>
            <div class="mobile__lang1">
           
  
            <figure class="mobile__lang-fig">
              <img src="/New folder/css.png" alt="css" class="mobile__lang-img">
              <h4 class="mobile__lang-header">css</h4>
  
            </figure>
  
            <figure class="mobile__lang-fig">
              <img src="New folder/html.png" alt="html" class="mobile__lang-img">
              <h4 class="mobile__lang-header">html</h4>
  
            </figure>
  
            <figure class="mobile__lang-fig">
              <img src="New folder/java.png" alt="java" class="mobile__lang-img">
              <h4 class="mobile__lang-header">javascript</h4>
  
            </figure>
          </div>
          <div class="mobile__lang2">
            <figure class="mobile__lang-fig">
              <img src="New folder/mobx.png" alt="mobx" class="mobile__lang-img">
              <h4 class="mobile__lang-header">mobx</h4>
  
            </figure>
          
            
          
  
            <figure class="mobile__lang-fig">
              <img src="New folder/nuxt.png" alt="nuxt" class="mobile__lang-img">
              <h4 class="mobile__lang-header">nuxt</h4>
  
            </figure>
  
            <figure class="mobile__lang-fig">
              <img src="New folder/react.png" alt="react" class="mobile__lang-img">
              <h4 class="mobile__lang-header">react</h4>
  
            </figure>
          </div>
          <div class="mobile__lang2">
            <figure class="mobile__lang-fig">
              <img src="New folder/typescript.png" alt="typescript" class="mobile__lang-img">
              <h4 class="mobile__lang-header">typescript</h4>
  
            </figure>
  
            <figure class="mobile__lang-fig">
              <img src="New folder/vue.png" alt="vue" class="mobile__lang-img">
              <h4 class="mobile__lang-header">vue</h4>
  
            </figure>
          </div>
          <h1 class="mobile__lang_header other">other</h1>
          <div class="mobile__lang3">
            <figure class="mobile__lang-fig">
              <img src="New folder/firebase.png" alt="firebase" class="mobile__lang-img">
              <h4 class="mobile__lang-header">Firebase</h4>
  
            </figure>
            <figure class="mobile__lang-fig">
              <img src="New folder/git.png" alt="git" class="mobile__lang-img">
              <h4 class="mobile__lang-header">git</h4>
  
            </figure>
            <figure class="mobile__lang-fig">
              <img src="New folder/photoshop.png" alt="photoshop" class="mobile__lang-img">
              <h4 class="mobile__lang-header">photoshop</h4>
  
            </figure>



          </div>
          </div>
        </div>
      </div>
  
      
  
      <footer class="mobile__footer">
        <figure class="mobile__logo-figure">
          <a href="https://github.com/Dawasonnyy" class="mobile__footer-logo-links"
            ><img
              src="./New folder/github.png"
              alt="github"
              class="mobile__footer-logos"
          /></a>
        </figure>
        <figure class="mobile__logo-figure">
          <a href="https://www.instagramcom/in/dawa_sonny class="mobile__footer-logo-links"
            ><img
              src="/New folder/insta.png"
              alt="insta"
              class="mobile__footer-logos"
          /></a>
        </figure>
        <figure class="mobile__logo-figure">
          <a href="https://www.linkedin.com/in/dawit-israel-b3a046245" class="mobile__footer-logo-links"
            ><img
              src="/New folder/linkedin.png"
              alt="linkedin"
              class="mobile__footer-logos"
          /></a>
        </figure>
        <figure class="mobile__logo-figure">
          <a href="https://wa.me/251923580987" target="_blank" class="mobile__footer-logo-links"
            ><img src="/New folder/whatsapp.png" alt="whatsapp
            class="mobile__footer-logos"></a
          >
        </figure>
      </footer>
      <div class="mobile__message-mebtn"> <a href="#" "><img
        src="./New folder/messenger.png"
        alt="messenger"
        class="messagebtn"
        onclick=" ContactPop()"
      /></a>
        
      </div>




</div>

    <script src="script.js"></script>
  </body>
</html>
