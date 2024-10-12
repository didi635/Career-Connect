# Career-Connect
HireHub  

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Career Connect - Find Your Dream Job</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="logo">Career Connect</div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#jobs">Jobs</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="banner">
    <h1>Connecting Talent with Opportunity</h1>
    <p>Your dream job is just a click away.</p>
    <a href="#jobs" class="btn">Find Jobs</a>
  </section>

  <section id="jobs" class="job-listings">
    <h2>Available Jobs</h2>
    <div class="job-card">
      <h3>Software Engineer</h3>
      <p>Location: Bangalore, India</p>
      <p>Experience: 2+ Years</p>
      <button>Apply Now</button>
    </div>
    <div class="job-card">
      <h3>Digital Marketing Specialist</h3>
      <p>Location: Mumbai, India</p>
      <p>Experience: 1+ Years</p>
      <button>Apply Now</button>
    </div>
    <!-- Add more job cards as needed -->
  </section>

  <section id="contact" class="contact-form">
    <h2>Contact Us</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" required>

      <label for="message">Message:</label>
      <textarea id="message" required></textarea>

      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© 2024 Career Connect. All Rights Reserved.</p>
  </footer>
</body>
</html>

