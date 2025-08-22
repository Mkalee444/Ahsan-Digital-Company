
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>AHSAN DIGITAL CLASS</title>
    <style>
        body
         {
          font-family: Arial,
        sans-serif;
         margin: 0;
          padding: 0;
           background: white;
            }
        h2{
         color: sandybrown;
         }
        header 
        {
         background: black;
         color: sandybrown;
          padding: 20px 0;
           text-align: center;
           height: 1cm;
           position: none;
            }
        nav
         { background: sandybrown;
          }
        nav a { color: #fff;
         text-decoration: none;
          margin: 0 20px;
           padding: 14px 0;
            display: inline-block;
             }
        nav a:hover
         {
          background: sandybrown;
           }
           .content
            { 
            padding: 30px;
             }
        section 
        {
         display: none;
          }
        section.active
         { 
         display: block;
          }
          
          css.courses-grid {
          display: flex;
          flex-wrap: wrap;
          gap: 24px;
          margin-top: 16px;
          }.course-card {
          flex: 1 1 255px;
          background: #fff;
          border-radius: 15px;
          box-shadow: 0 3px 14px #17858222;
          padding: 22px 17px;
          min-width: 200px;
          max-width: 300px;
          transition: transform 0.18s, box-shadow 0.15s;
          margin-bottom: 10px;
          }.course-card h3 {
          margin-top: 0;
          font-size: 20px;
          color: #178582;
          }.course-card.web { border-left: 6px solid #178582; }.course-card.marketing { border-left: 6px solid #F4A259; }.course-card.design { border-left: 6px solid #e94b86; }.course-card.app { border-left: 6px solid #1CA887; }.course-card.data { border-left: 6px solid #5172c2; }.course-card.ai { border-left: 6px solid #BFA181; }.course-card:hover {
          transform: translateY(-7px) scale(1.03);
          box-shadow: 0 8px 24px #17858238;
          border-color: #0A1828;
          }
          @media (max-width: 750px) {.courses-grid { flex-direction: column; align-items: stretch;}
          }
          
          
          ```css.hero-banner {
          background: linear-gradient(90deg,#17858211,#bfa18122 85%);
          padding: 28px 12px 18px 12px;
          border-radius: 12px;
          text-align: center;
          margin-bottom: 25px;
          box-shadow: 0 2px 13px #bfd2df35;
          }.hero-banner h2 {
          font-size: 2.2em;
          color: #0A1828;
          }.cta-btn {
          margin-top: 16px;
          background: #178582;
          color: #fff;
          border: none;
          padding: 12px 34px;
          border-radius: 25px;
          font-size: 1.1em;
          cursor: pointer;
          font-weight: bold;
          box-shadow: 0 3px 12px #17858222;
          transition: background.2s, transform.16s;
          }.cta-btn:hover {
          background: #BFA181;
          color: #0A1828;
          transform: scale(1.08);
          }.announcement {
          background: #f0e7c3;
          color: #734B12;
          padding: 9px 14px;
          margin: 22px 0 25px 0;
          font-size: 1.08em;
          border-left: 5px solid #BFA181;
          border-radius: 8px;
          }.features {
          display: flex;
          gap: 17px;
          margin: 25px 0 18px 0;
          flex-wrap: wrap;
          justify-content: center;
          }.feature-card {
          background: #fff9ef;
          border-radius: 12px;
          box-shadow: 0 2px 10px #ffae0039;
          padding: 14px 28px;
          min-width: 160px;
          text-align: center;
          }.feature-card h3 {
          margin: 0;
          color: #178582;
          }.feature-card p {
          margin: 4px 0 0 0;
          color: #0A1828;
          font-size:.99em;
          }.featured-courses {
          margin: 18px 0 2px 0;
          }.featured-courses h4 {
          color: #5172c2;
          font-size: 1.08em;
          margin-bottom: 8px;
          }.mini-course {
          display: inline-block;
          background: #f6faff;
          color: #178582;
          border-radius: 18px;
          box-shadow: 0 1px 6px #bfd2df45;
          padding: 8px 14px;
          margin: 0 10px 8px 0;
          font-size:.97em;
          font-weight: 500;
          position: relative;
          }.tag {
          background: #BFA181;
          color: #fff;
          border-radius: 9px;
          padding: 2px 12px;
          margin-left: 10px;
          font-size: 0.93em;
          }.tag.new {
          background: #178582;
          }.testimonials {
          background: #e5fafd;
          border-left: 6px solid #178582;
          margin: 28px 0 0 0;
          padding: 14px 18px;
          border-radius: 10px;
          }.testimonials h4 {
          color: #b86bad;
          margin-bottom: 8px;
          }.testimonials p {
          color: #555;
          font-style: italic;
          margin-bottom: 8px;
          }
          @media (max-width:700px) {.features { flex-direction: column; gap: 9px;}.feature-card { min-width: unset; }
          }
          css.about-ceo {
          background: #f6faff;
          border-left: 6px solid #178582;
          padding: 14px 20px;
          margin: 19px 0 6px 0;
          border-radius: 10px;
          font-size: 1.08em;
          color: #0A1828;
          }
                  
    </style>
</head>
<body>

<header>
    <h1>AHSAN DIGITAL CLASS</h1>
</header>
<nav>
    <a href="#" onclick="showSection('home')">Home</a>
    <a href="#" onclick="showSection('courses')">Courses</a>
    <a href="#" onclick="showSection('about')">About Us</a>
    <a href="#" onclick="showSection('contact')">Contact Us</a>
</nav>

<div class="content">
<section id="home" class="active home fade-in">
  <div class="hero-banner">
    <h2>Welcome to <span style="color:#178582;">AHSAN DIGITAL CLASS</span></h2>
    <p>Unlock tech knowledge, boost your skills, and prepare for the future—right here in Nigeria!</p>
    <button class="cta-btn" onclick="showSection('courses')">Start Learning Now</button>
  </div>
  <div class="announcement">
    <b>Notice:</b> Enrolment for July 2025 is now open! Grab your spot early for new AI & App courses.
  </div>
  <div class="features">
    <div class="feature-card">
      <h3>🌍 15+ Courses</h3>
      <p>Web, Mobile, Data, Design & More</p>
    </div>
    <div class="feature-card">
      <h3>🏆 10,000+ Learners</h3>
      <p>Join a growing tech community across Nigeria!</p>
    </div>
    <div class="feature-card">
      <h3>🎓 Expert Instructors</h3>
      <p>Learn from certified, hands-on trainers</p>
    </div>
  </div>
  <div class="featured-courses">
    <h4>Featured Courses</h4>
    <div class="mini-course">
      <span>Web Development</span>
      <span class="tag new">New</span>
    </div>
    <div class="mini-course">
      <span>AI & Automation</span>
      <span class="tag">Hot</span>
    </div>
    <div class="mini-course">
      <span>Graphic Design</span>
    </div>
  </div>
  <div class="testimonials">
    <h4>Student Voices</h4>
    <p>“AHSAN Digital gave me the confidence to launch my tech career!” – <i>Fatima, Lagos</i></p>
    <p>“The courses are practical and easy to follow.” – <i>Chinedu, Abuja</i></p>
  </div>
</section>

    <section id="courses" class="courses">
    <h2>Courses Offered</h2>
    <div class="courses-grid">
    <div class="course-card web">
    <h3>Web Development</h3>
    <p>HTML, CSS, JavaScript, Responsive Design, Hosting</p>
    </div>
    <div class="course-card marketing">
    <h3>Digital Marketing</h3>
    <p>SEO, Social Media, Branding, Content Creation</p>
    </div>
    <div class="course-card design">
    <h3>Graphic Design</h3>
    <p>Photoshop, Canva, Branding, UI Basics</p>
    </div>
    <div class="course-card app">
    <h3>App Development</h3>
    <p>Mobile Basics, UI/UX, Prototyping</p>
    </div>
    <div class="course-card data">
    <h3>Data Analysis</h3>
    <p>Excel, Power BI, Visualization</p>
    </div>
    <div class="course-card ai">
    <h3>AI & Automation</h3>
    <p>AI Concepts, Tools, Business Applications</p>
    </div>
    </section>
    
    <section id="about" class="about">
    <h2>About Us</h2>
    <p>AHSAN DIGITAL CLASS is dedicated to empowering Nigerians with in-demand technology skills for a brighter future. We believe everyone deserves a chance to grow in today’s fast-paced digital world, whether you're a student, entrepreneur, or professional.</p>
    <div class="about-ceo"></div>
    <img src="storage/emulated/0/Pictures/Screenshot/MySite.jpg">
    <strong>Founder & CEO:</strong> Engr Umar Lawal Ado
    <p style="margin-top:8px; color:#178582;">
    “Our mission is to make tech accessible and practical. Join us and let's shape the future together!”
    </p>
    </div>
    <ul style="margin-top:12px; color:#0A1828;">
    <li>Trusted by learners across Nigeria</li>
    <li>Certified and experienced instructors</li>
    <li>Modern, hands-on curriculum</li>
    </ul>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@ahsandigitalclass.com</p>
        <p>WhatsApp: +234 8012345678</p>
    
</div>
POWERED BY ENGR UMAR LAWAL 
<script>
    function showSection(sectionId) {
        document.querySelectorAll('section').forEach(sec => sec.classList.remove('active'));
        document.getElementById(sectionId).classList.add('active');
    }
</script>

 