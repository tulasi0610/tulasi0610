<meta charset="UFT-8">
    <meta http-equiv="X-UA-Conpatible"content="IE=edge">
    <meta name="viewport"content="widht=device-widht,initial-Scale=1.0">
     <title>Personal portfolio website-Easy Tutorials</title>
     <link rel="Stylesheet"href="style.CSS">
  </head>
  <body>
    <div id="header">
        <div class="Container">
             <nav>
       <img src="/storage/emulated/0/DCIM/Screenshots/Screenshot_2024-07-08-10-23-22-215-edit_com.android.chrome.jpg"class="logo" width="100" height="120">
                  <ul id="sidemenu">
                  <li><a href="#Header">Home</a></li>
                  <li><a href="#About">About</a></li>
                  <li><a href="#Services">Services</a></li>
                  <li><a href="#Portfolio">Portfolio</a></li>
                  <li><a href="#Contact">Contact</a></li>
                  <i class="fas.fa-times onclick="closemenu()"></i>
                  </ul>
                  <i class="fas.fa-bars onclick="openmenu()"></i> 
             </nav>
                  <div class="header-text">
                      <p>UI/UX Desiner</p>
                        <h1>Hi, I'm<span> tulsi</span><br>vasava from India</h1>
                  </div>
        </div>
   </div>
 <!............about.............>
   <div id="about">
        <div class="Container">
             <div ckass="row">
                  <div class="about-col-1"></div>
                      <img src="/storage/emulated/0/Download/1694083767587_103016.jpg" width="100" height="120">
                  </div>
                     <div class="about-col-2">
                      <h1 class="sub-title">About me </h1>
                       <p>Hii, I am vasava tulsi.
                        I am a web Designer;
                        I am studying at Shree KJ Poltechnic;
                        I am a web Devloper and web Designer; 
                        For any querry you can contect me.
                        About more info you can visit my website.
                        We can help you thanks for visiting my website.</p>
                      <div class="tab-titles">
                         <p class="tab-links  active-linkonclick="opentab('')">Skills</p>
                           <p class="tab-links onclick="opentab('')">Experience</p>
                             <p class="tab-links oneclick="opentab('')">Education</p>
                      </div>
                  <div class="tab-Contents active-tab"id="skills">
    <ul> 
       <li><span>UI?UX</span><br>Designing web/App interface</li>
       <li><spam>Web Devlopment</span><br>Web app Devlopment</li>
       <li><span>App Devlopment</span><br>Building Android/ios apps</li>
    </ul>   
    </div>
      <div class="tab-Contents" id="experience">
        <ul>
        <li><span>2024</span><br>Studing in diploma Engineering</li>
        <li><span>2024</span><br>Internship at Techo-Max Solution</li>
        </ul>
        </div>
        <div class="tab-Contents" id="Education">
        <ul>
        <li><span>2024</span><br>Study in diploma Engineering</li>
        <li><span>2024</span><br>2nd sem in computer Engineering</li>
        </ul>
        </div>
        </div>
        </div>
        </div>
        </div>
        <!... ............services........... ...>
        <div id="services">
        <div class="container">
        <h1 class="sub-title">My services</h1>
        <div class="services-list">
        <div>
        <i class="fas fa.code"></i>
        <h2>Web Design</h2>
        <p>loren ipsum dolor sit amet,consectetur adipiscing elit.sed nulla nibh,tincidunt sit amet sapien quls</p>
        <a href="#">learn more </a>
        </div>
        <div>
        <i class="fas fa.crop-alt"></i>
        <h2>UI/UX Design</h2>
        <p>loren ipsum dolor sit amet,consectetur adipiscing elit.sed nulla nibh,tincidunt sit amet sapien quls</p>
        <a href="#">learn more </a>
        </div>
        <div>
        <i class="fas fa-app.store"></i>
        <h2>App Design</h2>
        <p>loren ipsum dolor sit amet,consectetur adipiscing elit.sed nulla nibh,tincidunt sit amet sapien quls</p>
        <a href="#">learn more </a>
        </div>
        </div>
        </div>
        </div>
         <!... ............portfolio.......... ...>
         <div id="portfolio">
         <div class="container">
         <h1 class="sub-title">My work</h1>
         <div class="work-list">
         <div class="work">
         <img src="image/work-3.png">
         <div class="Layer">
         <h3>Social Media app</h3>
://facebook.com/">vasavatulasi9@gmil.com</p>
         <p><i class="fas fa-phone-square-atl">6352907016</p>
         <div class="social-icon">
         <a href=""><i class="fab fa-facebook"></i></a>
         <a href=""><i class="fab fa-twitter-square"></i></a>
         <a href=""><i class="fab fa-instagaram"></i></a>
         <a href=""><i class="fab fa-linkedin"></i></a>
         </div>
         <a href=""><i class="btn.btn2">Download CV</a>
         <div>
         <div class="contact-right">
         <form>
           <input type="text"name="Name"placeholder="your Name"required>
           <input type="email"name="email"placeholder="your email"required>
           <textarea name="Message"rows="6"placeholder="your messeger"></textarea>
           <button type="submit">submit</button>
           </from>
        <script>
          var tablinks = documents.getElementByClassname("tab-links");
          var tabContain = document.getElementByClassname("tab-Contents");
          
          functionopentab(tabname){
            for (tablink of tablinks){
             tablink.classlist.remove("active-link");
           }
           for(tabcontent of tabcontents){
              tabcontent.classlist.remove("active-tab");
            }
              event.currenttarget.classlist.add("active-link");
              Document.getelementById(tabname).classlist.add("active-tab");
         </script>
    
       </body>
    <html>
