

<header>
    <h1>AMAZE NEST STUDIO</h1>
    <p>Freelance Content Creator</p>
</header>

<nav>
    <a href="#about">About Me</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#services">Services</a>
    <a href="#client-area">Client Area</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about" class="black-bg">
    <h2>About Me</h2>
    <p>Hello! I'm Ángel Herrera, a freelance content creator...</p>
</section>

<section id="portfolio">
    <h2>Portfolio</h2>
    <!-- Portfolio items here -->
</section>

<section id="services" class="black-bg">
    <h2>My Services</h2>
    <!-- Services here -->
</section>

<section id="client-area">
    <h2>Client Access Area</h2>
    <form action="" method="POST">
        <input type="text" placeholder="Enter Access Code" name="access_code">
        <button type="submit">Access</button>
    </form>
    <div>
        <h3>Client Management</h3>
        <form class="client-form">
            <input type="text" placeholder="Client Name" name="client_name" required>
            <button type="button" onclick="addClient()">Add Client</button>
            <button type="button" onclick="removeClient()">Remove Client</button>
        </form>
    </div>
</section>

<section id="contact" class="black-bg">
    <h2>Contact Me</h2>
    <form class="contact-form" action="mailto:example@example.com" method="post" enctype="text/plain">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" rows="4" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
    </form>
</section>

<footer>
    <p>Connect with me on social media:</p>
    <nav>
        <a href="#">Instagram</a>
        <a href="#">TikTok</a>
        <a href="#">LinkedIn</a>
    </nav>
</footer>

<script>
    function addClient() {
        // Logic to add a client (requires backend)
        alert("Client added! Implement backend logic.");
    }
    
    function removeClient() {
        // Logic to remove a client (requires backend)
        alert("Client removed! Implement backend logic.");
    }
</script>

</body>
</html>
