<!DOCTYPE html>
<html>
    <head> 
        <title>Azzam Alghamdi</title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">    <!--الاستجابة لشاشات رسبونسف -->

        <!-- start css -->
        <style>
            body {
                margin: 0;
                background-image: 
                linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
                  url("صورة جامعة الباحة.jpg");
                background-repeat: no-repeat;
                background-size: cover;
                background-position: center;
                min-height: 100vh;
                 margin: 0;
                 padding-top: 80px
                }
        </style>
       <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
       <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">



                                <!-- start java script -->
                <script>
                document.addEventListener("DOMContentLoaded", function() {    // الانتظار حتى تحميل الصفحة 

                const btn = document.getElementById("theme-toggle");   // تحديد زر تغيير الوضع 

                btn.addEventListener("click", function() {
                    document.body.classList.toggle("dark-mode");   // متابعة الظغط على الزر 

                    if (document.body.classList.contains("dark-mode")) {
                    btn.innerHTML = '<i class="fa-solid fa-sun"></i>';      // عدم عودة الصفحة الى الوضع الشمسي اذا حدثت الصفحة 
                    localStorage.setItem("theme", "dark");
                    } else {
                    btn.innerHTML = '<i class="fa-solid fa-moon"></i>';
                    localStorage.setItem("theme", "light");     // العودة الى الوضع الشمسي 
                    }
                });

                // تحميل الوضع المحفوظ
                if (localStorage.getItem("theme") === "dark") {
                    document.body.classList.add("dark-mode");
                    btn.innerHTML = '<i class="fa-solid fa-sun"></i>';
                }

                });
                </script>


                <script>
                window.onscroll = function() {
                    // يظهر الزر إذا نزلت الصفحة أكثر من 100 بكسل
                    let btn = document.getElementById("top");                    // زر التوب 
                    btn.style.display = (window.scrollY > 100) ? "block" : "none";
                };

                </script>
               

    </head>

    <body>
        <style>
           .nav {
             background-color: #193554be;
             padding: 15px 50px;
            display: flex;
             justify-content: space-between;
            align-items: center;

               position: fixed;     
                 top: 0;
                left: 0;
                width: 100%;
                z-index: 1000;
               height: 70 px ;
            }

           .nav ul{ 
            list-style: none;
            display: flex;
            gap: 25px;  /* المسافة بين الزرار */
            }


           .nev li{ 
            margin-left: 20px;
    
            }

             .nav a{ 
             color: white;
             text-decoration: none;
             }
/* ------------------------------------------------------------------------------------------------------------------------------*/
          
            #about-me {
             display: flex;
             justify-content: space-between;
            align-items: flex-start;
            gap: 10px;
            }

            .box {
                background-color: rgba(255,255,255,0.1);
                padding: 30px;
                border-radius: 30px;
                width: 40%;                                                
                margin:20px 20px 30px ;
            }

            .information {
                background-color: rgba(255,255,255,0.1);
                padding: 30px;
                border-radius: 30px;
                width: 40%;
                margin:20px  80px 0px 0px;
                
            }

           
/*-------------------------------------------------------------------------------------------------------------------------------------------- */



           h1{
                color: aliceblue;
                text-align: center;
                 margin-top: 20px
            }
            h4{
               color: aliceblue;
                text-align: center;
                

            }

            h2{
                color: aliceblue;
            }

            p{
                color: aliceblue;
            }
       
             
                .social-buttons {
                    margin-top: 25px;
                    text-align: center;
                }

                .social-buttons a {
                    display: inline-block;
                    margin: 8px;
                    padding: 8px 18px;
                    background-color: rgba(255,255,255,0.2);
                    color: white;
                    text-decoration: none;
                    border-radius: 20px;
                    transition: 0.3s;
                }

                .social-buttons a:hover {
                    background-color: #000000;
                }
 
/*----------------------------------------------------------------------------------------------------------------------------------------------*/

                .Education-box {
                    display: flex;
                    gap: 20px;
                    margin-top: 30px;
                }

                .box-too{
                    background-color: rgba(255,255,255,0.2);
                    padding: 20px;
                    width: 250px;
                    border-radius: 15px;
                    color: white;
                    margin-right :90px;    
                     margin-left: 50px;
                     margin-top: 90px;
                     font-family: 'Times New Roman', Times, serif;
                }
                .edu-img {
                width: 100%;
                height: 180px;
                object-fit: cover;  
                border-radius: 10px;
                margin-bottom: 10px;
                }

/*-------------------------------------------------------------------------------------------------------------------------------------------*/


                    .skills{
                        width:60%;
                        margin:40px auto;
                    }

                    .skill{
                        margin-bottom:20px;
                    }

                    .progress{
                        background:#ccc;       
                        height:13px;
                        border-radius:20px;
                    }

                    .bar{
                        height:13px;
                        background:#163e59;
                        border-radius:20px;
                    }

                    h3{
                        color: aliceblue;
                    }
                    
/*-------------------------------------------------------------------------------------------------------------------------------------------*/                        
          
                .project {
                    display: flex;
                    gap: 20px;
                    margin-top: 20px; 
                    text-align: center;
                }

            .project1{
                    background-color: rgba(255,255,255,0.2);
                    padding: 20px;
                    width: 550px;
                    border-radius: 15px;
                    color: white;
                    margin-right :90px; 
                     margin-left: 50px;
                     margin-top: 90px;
                     font-family: 'Times New Roman', Times, serif; }
        .project-imeg {
                width: 100%;
                height: 180px;
                object-fit: cover;  
                border-radius: 10px;
                margin-bottom: 10px;
                }

                
                
/*----------------------------------------------------------------------------------------------------------------------------------------------*/
        .footer{
            background-color: #193554be;
            color: white;
            text-align: center;
            padding: 20px;              
            margin-top: 50px;
        }
/*--------------------------------------------------------------------------------------------------------------------------------------------*/
        /* نجبر الخلفية تتغير */
        .dark-mode {
            background: #111 !important;
        }

        /* نخلي النص فاتح */
        .dark-mode h1,
        .dark-mode h2,
        .dark-mode h3,
        .dark-mode h4,
        .dark-mode p,
        .dark-mode a {
            color: #f1f1f1 !important;
        }

        /* نخلي الصناديق أغمق */
        .dark-mode .box,
        .dark-mode .information,
        .dark-mode .box-too,
        .dark-mode .project1 {
            background-color: rgba(255,255,255,0.08) !important;
        }

/* تحسين الصور */
        img {
            max-width: 100%;
            height: auto;
        }

/* عدم التغيير في الجوال وتم الاستعانه فيه بالذكاء الاصطناعي لعدم التوافق بسهولة  */


        @media (max-width: 768px) {

            .nav {
                display: flex;
                flex-direction: column;
                align-items: center;
                padding: 10px 0;
            
                position: relative; 
            }

            .nav ul {
                display: flex;            
                flex-direction: column;
                gap: 5px; 
                padding: 0;
                margin: 0 0 15px 0; 
            }

            
            header, .hero-section {
                padding-top: 20px;
                text-align: center;
            }

        
            #about-me, .Education-box, .project {
                flex-direction: column;
                align-items: center;
            }

            .box, .information, .box-too, .skills, .project1 {
                width: 90% !important;
                margin: 10px auto;
            }
        }

        #top{
            position: fixed;
            bottom: 20px;
            right: 20px;
            padding: 12px 16px;
            background: #333; 
            color: white;
            border: none;
            border-radius: 50%;
            cursor: pointer;
            display: none; 
            z-index: 1000;
        }
           

            #Contact .box {
            max-width: 600px;         
            margin: 40px auto;        
            padding: 20px;
            background: #9d959551;       
            border-radius: 10px;
            
        }

        #Contact .form-control {
            margin-bottom: 15px;    
            width: 100%;           
            padding: 8px;
        }

          


         </style>


      
    <!--start html  -->
    
    <!-- شريط التنقل العلوي -->

      <nav class="nav">
        <ul>
         <li><a href="#about-me">Home</a></li>     
         <li><a href="#Education">My Education</a></li>    <!--done-->
         <li><a href="#skills">Skills</a></li>
         <li><a href="#project">project</a></li>
         <li><a href="#Contact">Contact me</a></li>
        </ul>
         <div>
         <button id="theme-toggle">
             <i class="fa-solid fa-moon"></i>
         </button>

         <button id="top" onclick="window.scrollTo({top: 0, behavior: 'smooth'})"> <!-- زر التوب -->
             <i class="fa-solid fa-arrow-up"></i>
        </button>


     </nav>
    
</div>


     <!-- القسم الاول من الصفحة المعلومات الشخصية -->
         <h1 > AZZAM ALGHAMDI  </h1>
         <h4> Information Technology Student</h4>
        <section id="about-me">
         <div class="box"> 
            <h2 >About me </h2>
            <P> My name is Azzam Al-Ghamdi, and I am an information technology student at Al-Baha University. </P>
            <p> I am currently working as an intern at the Deanship of E-Learning and Information Technology, developing the website.</p>
            <p> I am a dedicated and curious person. I enjoy teamwork and collaborating with others to create meaningful projects. I also value creativity and trying new approaches to learning.</p>
            <p> My goal is to become a skilled professional in the tech industry and contribute to innovative projects that make a difference. I believe that continuous learning and hard work are the keys to success.</p>
         </div>

         <div class="information">
            <h2> General Information </h2>
            <p>Location: Saudi Arabia, Al-Baha, Baljurashi</p>
            <p> Workplace: Al-Baha University, Deanship of E-Learning</p>           <!--done-->
            <p> Age: 21 years </p>
            <p> Languages: Arabic and English </p>
         </div>
         </section>

         <br>
         <div class="social-buttons">
            <a href="https://www.linkedin.com/in/ateqazzam@gmile.com" target="_blank">LinkedIn</a>       <!-- done-->
            <a href="445004852@stu.bu.edu.sa">Email</a>
            <a href="tel:0542252039">Phone</a>
        </div>


        <!-- القسم الثاني الدراسة -->

         <br><br><br><br>
         <hr>
        <section id="Education">
               <h1 text="text-align">My Education</h1>

         <div class="Education-box">
             <div class="box-too">
             <img src="صورة الابتدائي .jpeg" class="edu-img">
             <h2>Primary school study</h3>
             <p>Primary school studies began in 2011</p>
             <p>Badr Elementary School in Baljurashi City</p>
             <p>I completed my studies there from first grade to sixth grade and graduated in 2016. </p>
        </div>

        <div class="box-too">
             <img src="صورة الثانوي .jpeg" class="edu-img">
            <h2>Intermediate and secondary school</h3>
            <p>She then transferred to Badr Intermediate and Secondary School and began studying there in 2017.</p>
            <p> I graduated from middle school in 2019 with honors and moved on to high school in 2021</p>
            <p> I completed my secondary education at Badr High School, where I studied some subjects under the tutelage of my father, may God protect him.</p>
            <p> I graduated from high school in 2022 with a cumulative GPA of 99 and an excellent grade.</p>
        </div>

        <div class="box-too">
              <img src="صورة الجامعة .jpeg" class="edu-img">
            <h2>university</h2>
            <p>I joined Al-Baha University, College of Computers and Information, in 2023, majoring in Information Technology.</p>
            <p>I studied many subjects in college, such as Java programming, data structures, web technologies, networks, operating systems, and many other subjects. </p>
            <p> By my third year, I was directed by the college to choose an organization for cooperative training.</p>
        </div>
        <div class="box-too">
            <h2>Cooperative training</h2>
            <p>I went to the Deanship of E-Learning and Information Technology at Al-Baha University and submitted my application for training there.</p>
            <p>I was accepted for training with them by the Dean's Deputy, Dr. Ahmed Al-Habash. </p>
            <p> In the Application Development Agency department, under the supervision of the esteemed engineer Ahmed Murtadha</p>
        </div>
        </section>

        <hr> 
      

        <!-- القسم الثالث المهارات -->
        <section id="skills">
            <div class="skills">
                 <h1>My Skills</h1>

                <div class="skill">
                 <h2>HTML - 90%</h2>
           <div class="progress">
          <div class="bar" style="width:90%"></div>
          </div>
         </div>
       
        <br> 

        <div class="skill">
            <h2>CSS - 60%</h2>
            <div class="progress">
            <div class="bar" style="width:60%"></div>
            </div>
        </div>
 
        <br> 

        <div class="skill">
            <h2>JavaScript - 50%</h2>
            <div class="progress">
            <div class="bar" style="width:50%"></div>
            </div>
        </div>

        <br> 

        <div class="skill">
            <h2>Problem Solving - 80%</h2>
            <div class="progress">
            <div class="bar" style="width:80%"></div>
            </div>

            <br> 

            <div class="skill">
            <h2>work pressure - 100%</h2>
            <div class="progress">
            <div class="bar" style="width:100%"></div>
            </div>
        </div>
            </section>


        <!-- القسم الرابع مشاريعي-->
         <hr> 
       <section id="project">
    <h1 class="project-title"> My Project</h1>
    <div class="project">
             <div class="project1">
             <img src="لقطة شاشة 2026-02-27 165220.png" class="project-imeg">
            <h2>A program for measuring student grades using the Java language.</h2>
            <p>I developed a software program where students enter their grades to calculate their cumulative GPA.</p>
            <p> Students can also find out their grade based on the score.</p>
            <p> They can also check their eligibility for honors and excellence awards.</p>
        </div>

        <div class="project1">
              <img src="لقطة شاشة 2026-02-28 015854.png" class="project-imeg">
            <h2>Mobile application development</h2>
            <p>While studying mobile application development, my team and I developed a store program.</p>
            <p>The app displays tech sales such as headphones, chargers, and other tech items. </p>
            <p> You can add to the cart and proceed to checkout, etc. We received an excellent rating for this course from the course instructor, Dr. Moaz Krishan.</p>
        </div>
    </section>

    <br>
    <br> 
    <br>
    <br>  

      
            <section id="Contact">
            <h1 class="project-title">Contact me</h1>
            <div class="container">
                <div class="box"> <h2 style="text-align: center;">Contact me</h2>
                <form id="complaintForm">
                <div>
                    <label class="d-block text-white mb-2">Name</label>
                    <input type="text" name="visitor_name" class="form-control" placeholder="Enter your name" required>
                </div>

                <div class="input-group mb-3">
                    <label class="d-block text-white mb-2">Message</label>
                    <textarea name="visitor_message" class="form-control" rows="5" placeholder="Write your message here..." required></textarea>
                </div>

                <button type="submit" name="send_msg" class="btn btn-primary w-100">Send Message</button>
            </form>
        </div>
    </div>
</section>



    
         <br><br>


         <footer class="footer">
            <p>© 2026 Azzam Alghamdi | All Rights Reserved</p>
            <p>Information Technology Student</p>
        </footer>

    </body>
</html> 
