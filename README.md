<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shankar's LumenEdge</title>
    <link href="https://fonts.googlapis.com/css2?family=Poppins:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #0f0f0f, #1a1a2e, #16213e);
            color: white;
            text-align: center;
            overflow-x: hidden;
        }
        .container {
            max-width: 85%;
            margin: 50px auto;
            background: rgba(20, 20, 30, 0.9);
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 0 25px rgba(0, 255, 255, 0.2);
            backdrop-filter: blur(10px);
            animation: fadeIn 1.5s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        h1 {
            font-size: 42px;
            font-weight: bold;
            color: #00ffff;
            text-transform: uppercase;
        }
        .highlight {
            font-size: 50px;
            color: #ff00ff;
        }
        .tagline {
            font-size: 22px;
            font-weight: bold;
            color: #ffcc00;
            margin-top: 10px;
            text-transform: uppercase;
        }
        p {
            font-size: 18px;
            color: #ccc;
            line-height: 1.7;
        }
        .photo {
            margin-top: 20px;
        }
        .photo img {
            width: 230px;
            height: 230px;
            border-radius: 50%;
            border: 4px solid #00ffff;
            animation: zoomIn 1.5s ease-in-out;
        }
        @keyframes zoomIn {
            from { transform: scale(0.6); opacity: 0; }
            to { transform: scale(1); opacity: 1; }
        }
        .details, .services, .feedback {
            margin-top: 30px;
            text-align: left;
            padding: 25px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 12px;
        }
        .details h2, .services h2, .feedback h2 {
            color: #00ffff;
        }
        .contact {
            margin-top: 30px;
            font-size: 20px;
        }
        .contact a {
            text-decoration: none;
            color: #ff00ff;
            font-weight: bold;
            transition: 0.3s;
        }
        .contact a:hover {
            color: #ffcc00;
            text-decoration: underline;
        }
        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 25px;
            font-size: 18px;
            font-weight: bold;
            color: white;
            background: #ff00ff;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: 0.3s;
        }
        .btn:hover {
            background: #ffcc00;
            color: #16213e;
        }
        /* Feedback Form */
        .feedback form {
            display: flex;
            flex-direction: column;
        }
        .feedback input, .feedback textarea {
            width: 100%;
            padding: 10px;
            margin: 8px 0;
            border-radius: 6px;
            border: none;
            font-size: 16px;
            color: #333;
        }
        .feedback textarea {
            height: 100px;
            resize: none;
        }
        .feedback .submit-btn {
            background: #00ffff;
            color: #16213e;
            padding: 12px;
            border: none;
            border-radius: 6px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            transition: 0.3s;
        }
        .feedback .submit-btn:hover {
            background: #ff00ff;
            color: white;
        }
        @media screen and (max-width: 600px) {
            h1 { font-size: 32px; }
            .highlight { font-size: 40px; }
            .tagline { font-size: 18px; }
            p { font-size: 16px; }
            .photo img { width: 180px; height: 180px; }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1><span class="highlight">S</span>hankar's <span class="highlight">L</span>umenEdge</h1>
        <p class="tagline">The Edge of Innovation, The Core of Performance.</p>
        <div class="photo">
            <img src="shankar.jpeg" alt="Shankar's Photo">
        </div>
        <p>Hello! I am Shankar, a student entrepreneur with a strong passion for innovation and business development.</p>
        <p>At Shankar's LumenEdge, we focus on exploring groundbreaking startup ideas and creating solutions that make a difference.</p>
        <p>Driven by creativity, ambition, and the desire to build something impactful, I am always open to networking, collaborations, and new opportunities.</p>
        
        <div class="details">
            <h2>Personal Details</h2>
            <p><strong>Name:</strong> Shankar</p>
            <p><strong>Contact Number:</strong> +91 8186871124</p>
            <p><strong>Email:</strong> <a href="mailto:bhavani525762@gmail.com">bhavani525762@gmail.com</a></p>
            <p><strong>Location:</strong> Guntur, Andhra Pradesh, India</p>
        </div>
        
        <div class="services">
            <h2>Our Services</h2>
            <p>✅ Startup Consultation</p>
            <p>✅ Business Strategy Development</p>
            <p>✅ Tech Innovation & AI Solutions</p>
            <p>✅ Networking & Partnerships</p>
        </div>

        <div class="feedback">
            <h2>Feedback & Support</h2>
            <p>We value your feedback! Let us know how we can improve.</p>
            <form>
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" required></textarea>
                <button type="submit" class="submit-btn">Submit Feedback</button>
            </form>
        </div>

        <div class="contact">
            <p>📧 Contact me: <a href="mailto:bhavani525762@gmail.com">bhavani525762@gmail.com</a></p>
            <button class="btn">Get in Touch</button>
        </div>
    </div>

</body>
</html>

