<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Kingdom Greater Glory in Jesus Christ</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #4a7c59;
      color: white;
      padding: 1rem 2rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    nav {
      background: #3a5a3a;
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      padding: 1rem 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      font-size: 1.1rem;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
      background: white;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      border-radius: 8px;
    }
    section {
      margin-bottom: 3rem;
    }
    h2 {
      color: #4a7c59;
      border-bottom: 2px solid #4a7c59;
      padding-bottom: 0.5rem;
    }
    .welcome {
      font-size: 1.2rem;
      margin-top: 0.5rem;
      margin-bottom: 2rem;
    }
    footer {
      text-align: center;
      padding: 1rem 2rem;
      background: #3a5a3a;
      color: white;
      margin-top: 3rem;
    }
    form label {
      display: block;
      margin-top: 1rem;
      font-weight: bold;
    }
    form input, form textarea {
      width: 100%;
      padding: 0.5rem;
      margin-top: 0.25rem;
      border: 1px solid #ccc;
      border-radius: 4px;
      font-size: 1rem;
      resize: vertical;
    }
    form button {
      margin-top: 1.5rem;
      background-color: #4a7c59;
      color: white;
      border: none;
      padding: 0.75rem 1.5rem;
      font-size: 1.1rem;
      cursor: pointer;
      border-radius: 4px;
    }
    form button:hover {
      background-color: #3a5a3a;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(150px,1fr));
      gap: 10px;
    }
    .gallery img {
      width: 100%;
      border-radius: 6px;
      object-fit: cover;
      cursor: pointer;
      transition: transform 0.3s ease;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>

<header>
  <h1>Kingdom Greater Glory in Jesus Christ</h1>
  <p class="welcome">Welcome to Kingdom Greater Glory in Jesus Christ!</p>
</header>

<nav>
  <a href="#about">About Us</a>
  <a href="#sermons">Sermons</a>
  <a href="#donate">Donations</a>
  <a href="#photos">Photo Booth</a>
  <a href="#contact">Contact</a>
</nav>

<main>

  <section id="about">
    <h2>About Us</h2>
    <p>Kingdom Greater Glory in Jesus Christ is a faith-based ministry established to promote soul-lifting messages and sermons centered on the person of Jesus Christ. Our mission is to bring hope to the lost sheep of the Lord all over the world, help young couples build strong relationships, strengthen marriages, and foster friendship and unity within homes.</p>
    <p>We also provide support to those who are hurting and facing various challenges, especially individuals impacted by illnesses such as cancer. Our ministry is dedicated to walking alongside those in need with love, prayer, and encouragement.</p>
  </section>

  <section id="sermons">
    <h2>Sermons</h2>
    <p>Welcome to our Sermons page! Here you can find inspiring messages that nurture your faith and bring you closer to Jesus Christ.</p>
    <p>Watch our latest sermons on YouTube here: <a href="https://www.youtube.com/@soulharvestersglobaloutrea3960" target="_blank" rel="noopener noreferrer">Kingdom Greater Glory Sermons on YouTube</a></p>
  </section>

  <section id="donate">
    <h2>Donations</h2>
    <p>Your generous support helps Kingdom Greater Glory in Jesus Christ continue its mission of spreading hope, strengthening families, and ministering to those in need.</p>
    <p>If you feel moved to give, your donations make a real difference in:</p>
    <ul>
      <li>Outreach programs</li>
      <li>Supporting families and couples</li>
      <li>Assisting those facing illness, including cancer patients</li>
      <li>Organizing events and ministry activities</li>
    </ul>
    <p>Thank you for partnering with us in this mission.</p>
    <button onclick="alert('Donation button placeholder — link to your payment platform here!')">Donate Now</button>
  </section>

  <section id="photos">
    <h2>Photo Booth</h2>
    <p>Welcome to our Photo Booth! Here you’ll find a gallery showcasing moments of worship, fellowship, and ministry activities.</p>
    <div class="gallery">
      <!-- Replace src with your ministry photos -->
      <img src="https://via.placeholder.com/200x150?text=Photo+1" alt="Ministry Photo 1" />
      <img src="https://via.placeholder.com/200x150?text=Photo+2" alt="Ministry Photo 2" />
      <img src="https://via.placeholder.com/200x150?text=Photo+3" alt="Ministry Photo 3" />
      <img src="https://via.placeholder.com/200x150?text=Photo+4" alt="Ministry Photo 4" />
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form onsubmit="event.preventDefault(); alert('Thank you for reaching out! We will get back to you soon.'); this.reset();">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required />

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required />

      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="5" required></textarea>

      <button type="submit">Send Message</button>
    </form>

    <div style="margin-top: 2rem;">
      <h3>Our Contact Information:</h3>
      <p>Phone: (Your Phone Number)</p>
      <p>Email: (Your Email Address)</p>
      <p>Address: (Your Ministry Address)</p>
      <p>Social Media:  
        <a href="#" target="_blank" rel="noopener noreferrer">Facebook</a> |  
        <a href="#" target="_blank" rel="noopener noreferrer">Instagram</a> |  
        <a href="#" target="_blank" rel="noopener noreferrer">Twitter</a>
      </p>
    </div>
  </section>

</main>

<footer>
  <p>&copy; 2025 Kingdom Greater Glory in Jesus Christ. All rights reserved.</p>
</footer>

</body>
</html>
