<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>SweetMart – Sweet Management System</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <style>
    body {
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.7;
      margin: 0;
      padding: 0;
      background-color: #f9fafb;
      color: #222;
    }

    header {
      background: #7a3e1d;
      color: #fff;
      padding: 30px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.4rem;
    }

    header p {
      margin-top: 10px;
      font-size: 1.1rem;
    }

    section {
      padding: 40px 10%;
      background: #fff;
      margin-bottom: 20px;
    }

    h2 {
      color: #7a3e1d;
      margin-bottom: 15px;
    }

    h3 {
      margin-top: 30px;
      color: #444;
    }

    ul {
      padding-left: 20px;
    }

    li {
      margin-bottom: 8px;
    }

    img {
      width: 100%;
      max-width: 100%;
      border-radius: 10px;
      margin: 20px 0;
      box-shadow: 0 4px 20px rgba(0,0,0,0.08);
    }

    .tech-stack span {
      display: inline-block;
      background: #f1f1f1;
      padding: 8px 14px;
      border-radius: 20px;
      margin: 5px;
      font-size: 0.9rem;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: #111;
      color: #aaa;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

<header>
  <h1>🍪 Sweet Management System (SweetMart)</h1>
  <p>A full-stack web application for managing a modern sweet shop</p>
</header>

<section>
  <h2>📌 Project Overview</h2>
  <p>
    <strong>SweetMart</strong> is a full-stack Sweet Shop Management System designed
    to digitize and streamline sweet shop operations. The platform provides
    a seamless experience for customers and a powerful management dashboard for administrators.
  </p>

  <ul>
    <li>Clean and responsive user interface</li>
    <li>Role-based access (User & Admin)</li>
    <li>Real-world business workflow</li>
    <li>Scalable full-stack architecture</li>
  </ul>

  <div class="tech-stack">
    <span>React.js</span>
    <span>Bootstrap</span>
    <span>CSS3</span>
    <span>Spring Boot</span>
    <span>REST APIs</span>
    <span>MySQL / PostgreSQL</span>
  </div>
</section>

<section>
  <h2>🌐 User Module</h2>

  <h3>🏠 Home Page</h3>
  <ul>
    <li>Modern hero banner with brand identity</li>
    <li>Navigation: Home, Store, About, Contact, Sign In</li>
    <li>Call-to-action buttons</li>
    <li>Fully responsive layout</li>
  </ul>
  <img src="https://github.com/user-attachments/assets/a487a377-e37a-4c4f-ad19-64cbf4d81b7b" alt="Home Page" />

  <h3>🍪 Cookie Varieties</h3>
  <ul>
    <li>Chocolate Cookie</li>
    <li>Peanut Butter Cookie</li>
    <li>Clean card-based layout</li>
  </ul>
  <img src="https://github.com/user-attachments/assets/47850446-3c83-4dd3-92b0-5fcc3c725813" alt="Cookie Varieties" />

  <h3>❓ FAQs</h3>
  <ul>
    <li>Freshness of cookies</li>
    <li>Store timings</li>
    <li>Delivery & online ordering</li>
    <li>Quality assurance</li>
  </ul>
</section>

<section>
  <h2>📖 About Page</h2>
  <p>
    The About Page communicates SweetMart’s story, mission, and values to build
    trust and emotional connection with users.
  </p>
  <img src="https://github.com/user-attachments/assets/f2b7e2ff-cd30-4e65-837f-65a75e7ecb26" alt="About Page" />

  <h3>🎯 Mission</h3>
  <ul>
    <li>Deliver warm, freshly baked cookies</li>
    <li>Use premium ingredients</li>
    <li>Ensure consistent quality</li>
    <li>Make every celebration sweeter</li>
  </ul>
  <img src="https://github.com/user-attachments/assets/867a1fa6-0f26-4651-95f3-0aaf4a8cdeee" alt="Mission Section" />
</section>

<section>
  <h2>📞 Contact Page</h2>
  <ul>
    <li>Name, Email, Phone, Message</li>
    <li>Clean card layout</li>
    <li>Backend-ready form</li>
  </ul>
  <img src="https://github.com/user-attachments/assets/653cf625-1a9e-4cd6-bc28-40c7bdeaf07a" alt="Contact Page" />
</section>

<section>
  <h2>🛒 Store Page</h2>
  <ul>
    <li>Product cards with price and stock</li>
    <li>Quantity selector (+ / −)</li>
    <li>Add to Cart functionality</li>
  </ul>
  <img src="https://github.com/user-attachments/assets/6d840999-c433-4a91-a4b2-94bc72c86075" alt="Store Page" />
</section>

<section>
  <h2>🔐 Authentication</h2>

  <h3>Login Page</h3>
  <ul>
    <li>Email & password login</li>
    <li>Show password toggle</li>
    <li>Secure authentication flow</li>
  </ul>
  <img src="https://github.com/user-attachments/assets/4611b3ef-410c-431f-b5f4-52671697d2a5" alt="Login Page" />

  <h3>Register Page</h3>
  <ul>
    <li>Name, Email, Password, Address</li>
    <li>User-friendly onboarding</li>
  </ul>
  <img src="https://github.com/user-attachments/assets/0b88728a-0787-46d2-8410-36407910eb2e" alt="Register Page" />
</section>

<section>
  <h2>🛠️ Admin Module</h2>

  <h3>Admin Dashboard</h3>
  <ul>
    <li>Manage cookies (CRUD)</li>
    <li>View inventory and categories</li>
    <li>Edit & delete products</li>
  </ul>
  <img src="https://github.com/user-attachments/assets/2aa2a678-3f6b-42c2-b5f6-67df3838ea90" alt="Admin Dashboard" />

  <h3>Orders & Contacts</h3>
  <ul>
    <li>Order history with search</li>
    <li>Customer contact submissions</li>
  </ul>
  <img src="https://github.com/user-attachments/assets/28382219-0d69-4f48-9fee-fca1fa7d5df9" alt="Order History" />
</section>

<section>
  <h2>🚀 Future Enhancements</h2>
  <ul>
    <li>Payment gateway integration</li>
    <li>Order lifecycle tracking</li>
    <li>Sales analytics dashboard</li>
    <li>Export reports (CSV / PDF)</li>
  </ul>
</section>

<footer>
  © 2025 SweetMart. All rights reserved.
</footer>

</body>
</html>
