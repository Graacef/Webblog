<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gracelyn Pao - Self-Improvement Blog</title>
    <style>
        /* Global Styles */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
            color: #333;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        h1, h2, h3 {
            color: #3a3a3a;
        }

        p {
            line-height: 1.8;
            font-size: 1rem;
            margin-bottom: 20px;
        }

        /* Header (Sticky) */
        header {
            position: sticky;
            top: 0;
            background-color: #fff;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            z-index: 1000;
        }

        header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
        }

        header h1 {
            font-size: 2rem;
            font-family: 'Georgia', serif;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }

        nav ul li {
            margin-right: 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: #3a3a3a;
            font-size: 1rem;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #FF6F61;
        }

        /* Home Section */
        #home {
            background-color: #e3f2fd;
            padding: 60px 0;
        }

        #home h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            color: #1e88e5;
            text-align: center;
        }

        #home p {
            font-size: 1.2rem;
            line-height: 1.8;
            max-width: 800px;
            margin: 0 auto 40px;
            text-align: justify;
        }

        #home img {
            width: 100%;
            max-width: 800px;
            height: auto;
            display: block;
            margin: 20px auto;
            border: 5px solid #FF6F61;
            border-radius: 10px;
        }

        /* About Section */
        #about {
            background-color: #fff;
            padding: 60px 0;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            opacity: 0;
            transition: opacity 1s ease-out;
        }

        #about.visible {
            opacity: 1;
        }

        #about h2 {
            font-size: 2.5rem;
            color: #1e88e5;
            text-align: center;
            margin-bottom: 20px;
        }

        #about p {
            font-size: 1.2rem;
            line-height: 1.8;
            max-width: 800px;
            margin: 0 auto;
            text-align: justify;
        }

        #about img {
            width: 100%;
            max-width: 600px;
            height: auto;
            display: block;
            margin: 20px auto;
            border: 5px solid #1e88e5;
            border-radius: 10px;
        }

        /* Contact Section */
        #contact {
            background-color: #f4f4f9;
            padding: 60px 0;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            opacity: 0;
            transition: opacity 1s ease-out;
        }

        #contact.visible {
            opacity: 1;
        }

        #contact h2 {
            font-size: 2.5rem;
            color: #1e88e5;
            text-align: center;
            margin-bottom: 20px;
        }

        #contact form {
            max-width: 600px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
        }

        #contact input, #contact textarea {
            padding: 12px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        #contact button {
            padding: 12px;
            background-color: #1e88e5;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        #contact button:hover {
            background-color: #1565c0;
        }

        /* Footer */
        footer {
            background-color: #3a3a3a;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            border-top: 2px solid #e0e0e0;
        }

        footer a {
            color: #FF6F61;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        footer a:hover {
            color: #d14f3f;
            text-decoration: underline;
        }

        /* Image Styling */
        .image-gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            margin-bottom: 20px;
        }

        .image-gallery img {
            width: 48%;
            margin-bottom: 20px;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <!-- Header (Sticky) -->
    <header>
        <div class="container">
            <h1>Gracelyn Pao's Blog</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>   

    <!-- Homepage -->
    <section id="home">
        <div class="container">
            <h2>Welcome to My Journey</h2>
            <h3>Lessons My Grandmother Taught Me</h3>
            <a href="https://ibb.co/dgRtPjS">
                <img src="https://i.ibb.co/Qd4kPpZ/453983238-1032088038367149-2400360563090602935-n.jpg" alt="Family">
            </a>

            <p>In my early childhood, I faced many tough situations that shaped who I am today. One of the most transformative experiences was losing my grandmother—a woman who embodied resilience, wisdom, and unconditional love. She was my first teacher in the art of finding beauty in the simplest moments, and her lessons remain the foundation of who I strive to be.</p>
            <p>My grandmother showed her love through small yet significant acts, like cooking meals infused with warmth and spending quiet afternoons teaching me life’s little lessons. I’ll admit, as a child, I often took those moments for granted. My youthful curiosity pulled me toward fleeting distractions—video games, friends, or the allure of endless possibilities. But when she passed away, I was left with a profound sense of loss and guilt for not cherishing her presence more.</p>
            <p>That moment of loss, though painful, became a catalyst for growth. Her memory taught me to live a life of intention, where every small moment is treasured. Now, as an adult, I’ve discovered that her lessons resonate deeply with the life I’ve chosen for myself. I’ve learned that grief, while difficult, can be a profound teacher if we allow it to shape us in positive ways.</p>

            <h3>The Power of Forgiving Yourself</h3>
            <a href="https://ibb.co/PNjKTdZ">
                <img src="https://i.ibb.co/SPybQzX/466356827-1278162793304087-5654942641319880570-n.jpg" alt="Forgiving Yourself">
            </a>
            
            <p>Life hasn’t always been simple for me. There were times when I felt lost, unsure of who I was or what I wanted to become. But over time, I’ve learned that the best way to grow is to face challenges head-on and keep moving forward, no matter how small the steps. Even the moments that seemed insignificant at the time taught me valuable lessons.</p>

            <h3>Family and Growth</h3>
            <a href="https://ibb.co/dgRtPjS">
                <img src="https://i.ibb.co/Qd4kPpZ/453983238-1032088038367149-2400360563090602935-n.jpg" alt="Family">
            </a>
            <p>Family has always been a big part of who I am. Growing up, my family wasn’t perfect—we had our challenges, just like everyone else—but the love we shared taught me some of life’s most important lessons. In many ways, it was the steady presence of family members that gave me the courage to explore life and take risks, knowing they would always be there to support me.</p>
            <p>As I grew up, I started traveling alone. At first, it felt like a way to explore the world, but it became more than that. Traveling gave me space to think about my roots and reflect on what really matters. Being on my own helped me see just how much my family’s love and lessons influenced me.</p>

            <h3>Friends and Support</h3>
            <div class="image-gallery">
                <a href="https://ibb.co/RScTpgM">
                    <img src="https://i.ibb.co/6ZF0Ryp/450736859-365779936547183-8866858334213538131-n.jpg" alt="Friends">
                </a>
            </div>
            <p>The importance of friendships also cannot be overstated. Through thick and thin, my friends have been a source of strength and support. They’ve helped me see the value of not just giving, but also receiving—because self-growth often requires leaning on others.</p>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Hello, I’m Gracelyn Pao. I’m passionate about personal growth and self-improvement. Over the years, I have learned countless lessons from my experiences and the wisdom passed down by those I admire most, like my grandmother. She taught me the importance of resilience, mindfulness, and gratitude, and these principles have shaped how I approach life.</p>
            <p>In my journey of self-improvement, I've explored the power of mindfulness practices, the importance of cultivating a growth mindset, and the beauty of embracing challenges as opportunities for growth. I created this blog to share my reflections, personal stories, and lessons learned along the way, hoping to inspire others on their own journey toward becoming the best version of themselves.</p>
            <p>My goal is to foster a community of individuals who believe in the transformative power of self-love, resilience, and continuous learning. Whether you're seeking inspiration, new perspectives, or practical tips for navigating life’s challenges, I hope you'll find something meaningful here on my blog.</p>
            <a href="https://imgbb.com/">
                <img src="https://i.ibb.co/yBHpdvb/Screenshot-2024-12-23-205440.png" alt="Myself">
            </a>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <form>
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" rows="5" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Gracelyn Pao | <a href="mailto:gracelynpao@example.com">Email</a></p>
    </footer>

    <script>
        // Add the "visible" class to About and Contact sections when they are clicked
        document.getElementById('about').classList.add('visible');
        document.getElementById('contact').classList.add('visible');
    </script>
</body>
</html>
