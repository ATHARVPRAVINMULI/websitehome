<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to my portfolio</title>
    <link rel="stylesheet" href="style.css ">
    <script src="https://kit.fontawesome.com/61e35a8cae.js" crossorigin="anonymous"></script>
</head>
<body>
    <div id="header">
        <div class="container">
            <nav>
                <img src="images/Logo.png" class="logo">
                <ul id="sidemenu">
                    <li><a href="#header">Home</a></li>
                    <li><a href="#about">About me</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#portfolio">Work</a></li>
                    <li><a href="#contact">Contact Me</a></li>
                    <i class="fa-solid fa-xmark" onclick="closemenu()" style="color: #ffffff;"></i>
                </ul>
                <i class="fa-solid fa-bars" onclick="openmenu()" style="color: #ffffff;"></i>
            </nav>   
            
            <div class="header-text">

            <p> Freelancer </p>
            <h1> Hi, I'm <span>Atharva Muli </span><br>from India </h1>
        </div>
        </div>
    </div>
<!-------------------------------------------------------------------------------------------------About Me ---------------------------------------------------------------------------->
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="images/intro.jpeg" alt="">
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">About Me </h1>
                    <p> I am a Web Pentester , having a lot of interest in Cyber Security and Digital Forensics related work , 
                        I make my own methodology basic on my knowage related to crime . Also having a good command on English 
                        language with a good leadership and team management skill , in my graduation year , I manage many Tech 
                        and Non-Tech events . Love to work with people who are more intelligent than me <br>
                    </p>
                    <p> <br>Taking about behavior , so i believe on simple life with progress . I want my atmosphere to be very funny , intelligent , open minded . 
                        Their is no any use of bad words . Everyone will be focus on their own goals with enjoyment . </p>
                    <div class="tab-titles">
                        <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                        <p class="tab-links" onclick="opentab('experience')">Experience</p>
                        <p class="tab-links" onclick="opentab('education')">Education</p>
                    </div>
                    <div class="tab-contents active-tab" id="skills">
                        <ul>
                            <li><span>Reconnissam</span> Finding the crucial information of other company</li>
                            <li><span>Web Pester</span> Testing Breaches in website</li>
                            <li><span>Digital Forensics investigation</span> Crime Scene Investigation</li>
                            <li><span>Network mapper</span> Analysis the vurnabality in networks</li>
                            <li><span>Business Management</span> Analysis of Bussiness and product growth</li>
                            <li><span>English Communication</span> Good command on English communication with proper grammar</li>

                        </ul>
                    </div>
                    <div class="tab-contents" id="experience">
                        <ul>
                            <li><span>2025 - Current</span> Working with Cyber Secure India Company</li>
                            <li><span>2024 - November</span> Completed Internship related to Cyber Security</li>
                            <li><span>2025 - Jan</span> Infosys STP </li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="education">
                        <ul>
                            <li><span>BSC (cs) Hons.</span> Dr.G.Y.P.C of MGMU</li>
                            <li><span>12th</span> Kulbhushan College Chatrapati Sambhaji Nagar</li>
                            <li><span>10th</span> Shri saraswati bhawan high school </li>
                        </ul>
                    </div>

                </div>
            </div>
        </div>
    </div>

    <!------------------------------------------------------------------------------------Services-------------------------------------------------------------------------------------->
    <div class="skills">
        <div class="container">
            <h1 class="sub-title">My Skills</h1>
            <div class="services-list">
                    <div>
                        <i class="fa-solid fa-hat-cowboy"></i>
                        <h2>Web Pentester</h2>
                        <p>Hellow , I am a security pentester , who finds breaches as well vurnabalites in the website , I have a experience of 1 year in this field.</p>
                        <a href="#">Learn more</a>
                    </div>
                    <div>
                        <i class="fa-solid fa-arrow-up-wide-short"></i>
                        <h2>Business Helper</h2>
                        <p>Helping many MNC to grow in their specific domains , I make some methodology which helps to develope the Business fast on wild scale . </p>
                        <a href="#">learn more</a>
                    </div>
                    <div>
                        <i class="fa-solid fa-handcuffs"></i>
                        <h2>Dectetive</h2>
                        <p> I am a passionate crime scane and the crimal psychology detecteor , I love to solve crime , talk with crimnals .</p>
                        <a href="#">Learn more</a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!------------------------------------------------------------------------------------------Portfolio---------------------------------------------------------------------------------------->
    <div id="portfolio">
        <div class="container">
            <h1 class="sub-title">My Work</h1>
            <div class="work-list">
                <div class="work">
                    <img src="images/Tester.jpg" alt="Certificate 1">
                    <div class="layer">
                        <h3>Vurnabality Tester</h3>
                        <p>In the journey of web pen testing , I learn about the SQL injection attack, broken web authentication, Cross side scripting , how the attacker understand 
                            our security algrothiums, which steps he do not talk to avoid catching and all, currently learning more </p>
                        <a href="#"><i class="fa-solid fa-link"></i></a>
                    </div>
                </div>
                        <div class="work">
                        <img src="images/Bussiness.jpg" alt="Certificate 1">
                        <div class="layer">
                        <h3>Business Journey</h3>
                        <p>In my academy , I manage many events and also attend maany different kinds of events, with this i learn about the B2C B2B bussiness , what psychology we need to grow our bussiness 
                            which type of failure we should create by ourself for our bussiness and all other things. </p>
                        <a href="#"><i class="fa-solid fa-link"></i></a>
                        </div>
                    </div>
                    <div class="work">
                <img src="images/Crime.jpg" alt="Certificate 1">
                <div class="layer">
                    <h3>Crime Journey</h3>
                    <p>In this , i learn about the different types of crime which can perform with simple method . How to understand criminal, what should we do to reduce crime in india , I am not sure i will do it or not but i will try my best
                        to reduce crimes in india and all other things. </p>
                    <a href="#"><i class="fa-solid fa-link"></i></a>
                        </div>
                    </div>
        </div>
        <a href="#" class="btn">See More</a>
    </div>

    <!---------------------------------------------------------------------------------------------Contact Me---------------------------------------------------------------------------->
    <div id="contact">
        <div class="container">
            <div class="row">
                <div class="contact-left">
                    <h1 class="sub-title">Contact Me</h1>
                    <p><i class="fa-solid fa-globe"></i>atharvmuli@gmail.com</p>
                    <p><i class="fa-solid fa-globe"></i>9309330318</p>
                    <div class="social-icons">
                        <a href=""><i class="fa-solid fa-phone"></i></a>
                        <a href=""><i class="fa-brands fa-linkedin"></i></a>
                        <a href=""><i class="fa-solid fa-globe"></i></a>
                        <a href=""> <i class="fa-solid fa-hashtag"></i></a>
                    </div>
                    <a href="images/Final Resume_pic.pdf" download class="btn btn2">Download CV</a>

                        </div>
                            <div class="contact-right">
                                <form name="submit-to-google-sheet">
                                    <input type="text" name="Name" placeholder="Your Name" required>
                                    <input type="email" name="Email" placeholder="Your Email" requied>
                                    <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                                    <button type="Sumbit" class="btn btn2">Submit</button>
                                </form>
                                <span id="msg"></span>
                            </div>
                        
                </div>
            </div>                   
        </div>
        <div class="copy-right">
            <p>Copyright @ AM. Made with my <i class="fa-solid fa-heart" style="color: #ff0000;"></i> for you all </p>
        </div>
    </div>
    <script>

       var tablinks = document.getElementsByClassName("tab-links");
       var tabcontents = document.getElementsByClassName("tab-contents");

       function opentab(tabname){
        for(tablink of tablinks){
         tablink.classList.remove("active-link");

        }
        for(tabcontent of tabcontents){
         tabcontent.classList.remove("active-tab");
        }
        event.currentTarget.classList.add("active-link");
        document.getElementById(tabname).classList.add("active-tab")
       }



    </script>
    <script>

        var sidemeu = document.getElementById("sidemenu");

        function openmenu(){
            sidemeu.style.right = "0";

        }
        
        function closemenu(){
            sidemeu.style.right = "-200px";
            
        }
    </script>
    <script>
  const scriptURL = 'https://script.google.com/macros/s/AKfycbw9_VzA7g-C9ROh-KPkAHZa5Yg6-gIJ78_EdjQtmNv-btqH6E9XQAzH0kBVMhOJuTFUNw/exec'
  const form = document.forms['submit-to-google-sheet']
  const msg = document.getElementById("msg")

  form.addEventListener('submit', e => {
    e.preventDefault()
    fetch(scriptURL, { method: 'POST', body: new FormData(form)})
      .then(response => {
        msg.innerHTML = "Thank you for feedback, visit again"
        setTimeout(function(){
            msg.innerHTML = ""
        },5000)
        form.reset
      })
      .catch(error => console.error('Error!', error.message))
  })
</script>
    
</body>
</html>
