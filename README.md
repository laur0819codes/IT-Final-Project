<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel = "stylesheet" href="style.css" />
    <link rel = "stylesheet" href="mediaqueries.css" />


</head>
<body>
    <nav id="desktop-nav"> 
        <div class="logo"> John Laurence Mendoza </div>
        <div> 
            <ul class="nav-links"> 
                <li><a href="#about"> About </a></li>
                <li><a href="#field"> Field of Interest </a></li>
                <li><a href="#sdg"> SDG </a></li>
                <li><a href="#affiliations"> Affiliations </a></li>
                <li><a href="#contacts"> Contacts </a></li>
            </ul>
        </div>
    </nav>

  <nav id="hamburger-nav">
        <div class="logo"> John Laurence </div>
        <div class="hamburger-menu"> 
        <div class="hamburger-icon" onclick= "toggleMenu()"> 
            <span></span>
            <span></span>
            <span></span>
        </div>
        <div class="menu-links"> 
                <li><a href="#about" onclick= "toggleMenu()"> About </a></li>
                <li><a href="experience" onclick= "toggleMenu()"> Experiences </a></li>
                <li><a href="#sdg" onclick= "toggleMenu()"> SDG </a></li>
                <li><a href="#sdg" onclick= "toggleMenu()" > Projects </a></li>
                <li><a href="#contacts" onclick= "toggleMenu()" > Contacts </a></li>


        
</div>
     </div>
  </nav>
    <section id="profile">
        <div class = "section__pic-container"> 
            <img src="./assets/ID .png" alt="John Laurence Profile Picture
            ">
        </div>
        <div class="section__text">
            <p class="section__text__p1"> Hello, I'm  </p>
            <h1 class="title"> John Laurence </h1>
            <p class="section__text__p2"> Software Engineer </p>
            <div class="btn-container">
                <button class="btn btn-color-2" onclick="window.open('./assets/Resume-CV.pdf')"> 
                    Download CV </button>

<button class="btn btn-color-1" onclick="location.href='#contacts'">
                        Contact Info </button>
     </div>
            <div id="social-container">
                <img src="./assets/linkedin.png" alt="My LinkedIn profile" class="icon2"
                onclick="location.href='https://www.linkedin.com/in/john-laurence-mendoza-3b08bb273/edit/forms/intro/new/?profileFormEntryPoint=PROFILE_SECTION'">

  <img src="./assets/github.png" alt="My Github profile" class="icon2"
                onclick="location.href='https://github.com/laur0819codes'">
            </div>
        </div>
    </section>

<section id="about"> 
        <p class="section__text__p1"> Get to Know More </p>
        <h1 class="title"> About Me </h1>
        <div class="section-container">
            <div class="section__pic-container"> 
                <img src="./assets/profile2.jpeg" alt="Profile Picture" class="about-pic"/>
            </div>
            <div class="about-details-containers"> 
                <div class="about-containers"> 
                    <div class="details-container">
                        <img src="./assets/experience.png" alt="experience icon" class="icon"/>
                        <h3> Experiences </h3>
                        <p> 1 year <br> Front End Development</p>

 </div>
                    <div class="details-container">
                        <img src="./assets/education.png" alt="education icon" class="icon"/>
                        <h3> Education </h3>
                        <p> Science, Technology Engineering and Mathematics <br> Bachelors of Science in Computer Science</p>

</div>
                </div>
                    <div class="text-container">
                        <p> <b> Hi! I'm Laurence</b>, an aspiring software engineer and enthusiastic leader with a vision for a brighter future. I’m fueled by a passion for innovation, teamwork, and making meaningful contributions to the world around me. My dream is to achieve success while empowering others to reach their full potential and serving our country with integrity and dedication. I believe in the power of giving back to the community, creating opportunities for growth, and inspiring positive change. With a heart full of ambition and a drive to lead with purpose, I’m excited to embrace every challenge and turn dreams into reality! </p>
                    </div>
            </div>
        </div> 
        <img src="./assets/arrow.png" alt="arow icon" class="icon arrow" onclick="location.href='#field'"/>
    </section>

<section id="field">
        <p class="section__text__p1"> Explore My </p>
        <h1 class="title"> Field of Interest </h1>
        <div class="details-container">
        <div class="about-containers">
            <div class="about-details-containers">
                <h2 class="field-sub-title"> Interests </h2>
                <div class="article-container"> 
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Computer Science</h3>
                            <p> Solving problems with technology.</p>
                        </div>


</article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Photography</h3>
                            <p> Capturing moments creatively</p>
                        </div>


 </article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Public Speaking</h3>
                            <p> Engaging audiences confidently</p>
                        </div>


  </article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Fashion Arts</h3>
                            <p> Expressing creativity through style</p>
                        </div>


 </article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Cosmology</h3>
                            <p> Exploring the universe's mysteries</p>
                        </div>


 </article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Music</h3>
                            <p> Listening to Kpop, POP, and OPM</p>
                        </div>


  </article>
                </div>

</div>
            <div class="about-details-containers">
                <h2 class="field-sub-title"> Talents and Hobbies </h2>
                <div class="article-container"> 
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Dancing</h3>
                            <p> Expressing through movement</p>
                        </div>


 </article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Singing</h3>
                            <p> Not a great singer but Kareoke is Life!</p>
                        </div>


                    </article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Hosting</h3>
                            <p>Leading events with charm </p>
                        </div>

</article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Travelling</h3>
                            <p> Exploring new places and cultures</p>
                        </div>


 </article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Leadership</h3>
                            <p> Inspiring and guiding teams </p>
                        </div>


</article>
                    <article>
                        <img src="./assets/checkmark.png" alt="title-icon" class="icon"/>
                        <div>
                            <h3> Technology</h3>
                            <p> Exploring innovative solutions</p>
                        </div>


   </article>
                </div>

   </div>
        </div>
        </div>

 <img src="./assets/arrow.png" alt="Arrow icon" class="icon arrow" onclick="location.href='#sdg'"/>

       

        
</section>

<section id="sdg">
        <p class="sdg-section__text__p1">Advocating for Sustainable Development Goals</p>
        <h1 class="title-sdg">My Advocacies</h1>
        <div class="experience-details-container">
          <div class="about-containers">
       <!-- No Poverty Advocacy -->
            <div class="details-container color-container">
              <div class="article-container">
                <img
                  src="./assets/Sustainable_Development_Goal_01NoPoverty.svg.png"
                  alt="No Poverty Advocacy"
                  class="project-img"
                />
              </div>
              <h2 class="experience-sub-title project-title">No Poverty</h2>
              <p class="project-description">
                Committed to eradicating poverty and ensuring economic opportunities for all.
              </p>
              <div class="btn-container">
                <button
                  class="btn btn-color-2 project-btn"
                  onclick="location.href='https://sdgs.un.org/goals/goal1'"
                >
                  Learn More
                </button>
              </div>
            </div>
 <!-- Equality Education -->
            <div class="details-container color-container">
              <div class="article-container">
                <img
                  src="./assets/E_SDG-goals_icons-individual-rgb-04-1024x1024.png"
                  alt="Quality Education"
                  class="project-img"
                />
              </div>
              <h2 class="experience-sub-title project-title">Quality Education</h2>
              <p class="project-description">
                Ensure inclusive and equitable quality education and promote lifelong learning opportunities for all
              </p>
              <div class="btn-container">
                <button
                  class="btn btn-color-2 project-btn"
                  onclick="location.href='https://sdgs.un.org/goals/goal4'"
                >
                  Learn More
                </button>
              </div>
            </div>
            <!-- Gender Equality Advocacy -->
            <div class="details-container color-container">
                <div class="article-container">
                  <img
                    src="./assets/E_SDG-goals_icons-individual-rgb-05-1024x1024.png"
                    alt="Gender Equality Advocacy"
                    class="project-img"
                  />
                </div>
                <h2 class="experience-sub-title project-title">Gender Equality</h2>
                <p class="project-description">
                  Promoting equal rights and opportunities regardless of gender.
                </p>
                <div class="btn-container">
                  <button
                    class="btn btn-color-2 project-btn"
                    onclick="location.href='https://sdgs.un.org/goals/goal5'"
                  >
                    Learn More
                  </button>
                </div>
              </div>
        </div>
        </div>
        <img
          src="./assets/arrow.png"
          alt="Arrow icon"
          class="icon arrow"
          onclick="location.href='#community-service'"
        />
     <section> <section id="community-service">
        <p class="cs-section__text__p1">Giving Back to the Community</p>
        <h1 class="cs-title">Community Service Projects</h1>
      
 <div class="service-container">
          <!-- School Donation Program -->
          <div class="service-program">
            <h2 class="service-title">School Donation Program</h2>
            <p class="service-description">
                During my senior high school years, I was a member of the Supreme Student Government (SSG). As part of our school’s annual Love Community Action Program, we organized a school donation drive, contributing to meaningful community outreach and fostering a spirit of generosity and compassion among students.
            </p>
            <div class="service-images">
              <img src="./assets/school1.jpeg" alt="School Donation 1" class="service-img" />
              <img src="./assets/school2.jpeg" alt="School Donation 2" class="service-img" />
              <img src="./assets/school3.jpeg" alt="School Donation 3" class="service-img" />
              <img src="./assets/school4.jpeg" alt="School Donation 4" class="service-img" />
            </div>
          </div>
         <!-- Coastal Clean Up Program -->
          <div class="service-program">
            <h2 class="service-title2">Coastal Clean Up Program</h2>
            <p class="service-description">
              An initiative focused on cleaning our coasts to promote environmental sustainability and marine life preservation.
            </p>
            <div class="service-images">
              <img src="./assets/eco-isko1.jpeg" alt="Coastal Cleanup 1" class="service-img" />
              <img src="./assets/eco-isko2.jpeg" alt="Coastal Cleanup 2" class="service-img" />
              <img src="./assets/eco-isko3.jpeg" alt="Coastal Cleanup 3" class="service-img" />
              <img src="./assets/eco-isko4.jpeg" alt="Coastal Cleanup 4" class="service-img" />
            </div>
          </div>
        </div>
  <img
          src="./assets/arrow.png"
          alt="Arrow icon"
          class="icon arrow"
          onclick="location.href='#affiliations'"
        />
        
</section> 
      
</section>

               
            
  </section>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Affiliations</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <section id="affiliations">
    <div class="container">
      <h1 class="section-title">My Affiliations</h1>
      <p class="section-description">Here are the organizations I’m proud to be a part of:</p>
      <div class="affiliations-grid">
        <div class="affiliation-card">
          <h3 class="affiliation-name">Department of Science and Technology</h3>
          <p class="position">SEI - Scholar</p>
        </div>
        <div class="affiliation-card">
          <h3 class="affiliation-name">ACCESSS - Association of Computer Science Students</h3>
          <p class="position">First Year Representative</p>
        </div>
        <div class="affiliation-card">
          <h3 class="affiliation-name">College of Informatics and Computing Sciences Student Council</h3>
          <p class="position">First Year Representative</p>
        </div>
        <div class="affiliation-card">
          <h3 class="affiliation-name">Association of DOST-SEI Scholars - Alangilan Campus</h3>
          <p class="position">Marketing and Sponsorship Assistant Head</p>
        </div>
        <div class="affiliation-card">
          <h3 class="affiliation-name">Junior Philippine Computer Society BatStateU Alangilan Chapter</h3>
          <p class="position">Member</p>
        </div>
        <div class="affiliation-card">
          <h3 class="affiliation-name">CICS Dance Crew</h3>
          <p class="position">Member</p>
        </div>
      </div>
    </div>
  <img
          src="./assets/arrow.png"
          alt="Arrow icon"
          class="icon arrow"
          onclick="location.href='#contacts'"
        />


  </section>
</body>
</html>


<section id="contacts">
  <p class="csection__text__p1">Get in Touch</p>
  <h1 class="ctitle">Contact Me</h1>
  <div class="contact-info-upper-container">
    <div class="contact-info-container">
      <img
        src="./assets/email.png"
        alt="Email icon"
        class="icon contact-icon email-icon"
      />
      <p><a href="mailto:24-05554@g.batstate-u.edu.ph"> 24-05554@g.batstate-u.edu.ph </a></p>
    </div>
    <div class="contact-info-container">
      <img
        src="./assets/linkedin.png"
        alt="LinkedIn icon"
        class="icon contact-icon"
      />
      <p><a href="https://www.linkedin.com">LinkedIn</a></p>
    </div>
  </div>
</section>
      <footer>
        <nav>
          <div class="nav-links-container">
            <ul class="nav-links"> 
              <li><a href="#about"> About </a></li>
              <li><a href="#field"> Field of Interest </a></li>
              <li><a href="#sdg"> SDG </a></li>
              <li><a href="#affiliations"> Affiliations </a></li>
              <li><a href="#contacts"> Contacts </a></li>
          </ul>
          </div>
        </nav>
        <p> Copyright &#169; 2024 John Laurence. All Rights Reserved </p>
      </footer>
    <script src="script.js"></script>
  </body>
</html>
