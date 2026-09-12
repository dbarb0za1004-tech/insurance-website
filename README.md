<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name+"viewpoint" content="width=device-width, initial-scale=1.0">
    <title>Protect Your Family | Life Insurance</title>
    <link rel="stylesheet" href="css/style.css">
</head>

<body>
    <header>
      <nav class="navbar">
        <div class="logo">Protect Your Future</div>
        <ul class="nav-links">
          <li><a href="#home">Home</a>></li>
          <li><a href="#life">Life Insurance</a></li>
          <li><a href="#Mortgage">Mortgage Protection</a></li>
          <li><a href="#expense">Final Expense</a></li>
          <li><a href="#Contact">Contact</a></li>
        </ul>
      </nav>
    </header>

  <main>
    <!-- Hero Section -->
    <section ID="home" class="hero">
      <div class="hero-content">
        <h1>Protect What Matters Most</h1>
          <P>Life Insurance and mortgage protection and final expense solutions designed to help protect the people and things you care about.
          </P>
        <a href="#contact" class="button">Get More Information</a>
      </div>
    </section>
    <!-- Life Insurance -->
    <section ID="life" class="section">
        <h2>Life Insurance</h2>
          <P>Life Insurance can help provide financial protection for your loved ones if you pass away.</P>
          <div class="cards">
            <div class="card">
              <h3>Family Protection</h3>
              <P>Help provide financial support for the people who depend on you.</P>
            </div>
            <div class="card">
            <h3>Financial Security</h3>
            <P>Help your family handle expenses and financial obligations</P>
            </div>
            <div class="card">
            <h3>Peace of Mind</h3>
            <P>Knowing you have a plan can provide greater peace of mind</P>
            </div>
          </section>
            <!-- Mortgage Protection -->
      <section id="mortgage" class="section mortgage">
        <h2>Mortgage Protection</h2>
          <P>Your home is one or your family's biggest financial commitments. Let's explore options that may help protect your family and home.</P>
             <a href="#contact" class="button">Learn More</a>
      </section>
            <!-- Contact Form -->
            <section id="contact" class="section">
              <h2>Request More Information</h2>
                <P>Complete the form below and we will contact you to discuss your options.</P>
              <form id="leadform">
                <label for="first name">First Name</label>
                <input type="text" id="firstName" name="firstName" required>
                <label for="lastName">Last Name</label>
                <input type="text" id="lastName" name="lastName" required>
                <label for="phone">Phone Number</label>
                <input type="tel" id="phone" name="phone" required>
                <label for="email">Email Address</label>
                <input type="email" id="email" name="email" required>
                <label for="zip">Zip Code</label>
                <input type="text id="zip" name="zip" required>
                <label for="interest">What are you interested in?</label>
                <select id="interest" name="interest">
                  <option value="Life">Life Insurance</option>
                  <option value="mortgage">Mortgage Protection</option>
                  <option value="both">Both</option>
                </select>
                <label for="message">How can we help?</label>
                <textarea id="message" name="message" rows="5"></textarea>
                <label class="consent">
                  <input type="checkbox" id="consent" required>I agree to be contacted regarding by request for information.</label>
                <button type="submit">Request Information</button>
              </form>
            </section>     
  </main>
            <footer>
              <p>@ 2026 Protect Your Future</p>
              <P>Insurance products and availability may vary.</P>
            </footer>
            <script src="js/script.js"></script>
            </footer>
</body>
          </html>
