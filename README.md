# Career-Connect
HireHub  
 
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Career Connect | Job Hiring Agency</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>

    <!-- Header Section -->
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#job-listings">Jobs</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <img src="images/banner.jpg" alt="Career Connect Banner" class="header-img">
        <h1>Your Gateway to Professional Opportunities</h1>
        <p>Connecting the best talent with leading companies</p>
    </header>

    <!-- Job Listings Section -->
    <section id="job-listings">
        <h2>Featured Job Listings</h2>
        <div class="job">
            <img src="images/software-engineer.jpg" alt="Software Engineer">
            <div class="job-details">
                <h3>Software Engineer</h3>
                <p>Location: New York, USA</p>
                <p>Experience: 3+ years</p>
                <button>Apply Now</button>
            </div>
        </div>
        <div class="job">
            <img src="images/marketing-specialist.jpg" alt="Marketing Specialist">
            <div class="job-details">
                <h3>Marketing Specialist</h3>
                <p>Location: London, UK</p>
                <p>Experience: 2+ years</p>
                <button>Apply Now</button>
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about">
        <h2>About Us</h2>
        <p>At Career Connect, we specialize in matching job seekers with their ideal roles and helping companies find the right talent. Our team works tirelessly to create opportunities and bridge the gap between professionals and their career aspirations.</p>
        <img src="images/team.jpg" alt="Our Team" class="about-img">
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Submit</button>
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="social-media">
            <a href="#"><i class="fab fa-facebook-f"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-linkedin-in"></i></a>
        </div>
        <p>&copy; 2024 Career Connect. All rights reserved.</p>
    </footer>

</body>
</html>

