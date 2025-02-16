<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #000;
            color: #fff;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: #111;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(255,255,255,0.1);
            text-align: left;
        }
        h1, h2, h3 {
            color: #fff;
            text-align: center;
        }
        .portfolio-item, .service-item, .review-item, .pricing-item {
            margin: 20px 0;
            padding: 10px;
            border: 1px solid #444;
            border-radius: 5px;
            background: #222;
            text-align: center;
        }
        .expertise {
            text-align: left;
        }
        .contact-info {
            margin-top: 20px;
        }
        .contact-info p {
            margin: 5px 0;
        }
        .consultation-form {
            margin-top: 20px;
            text-align: center;
        }
        .consultation-form input, .consultation-form textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #444;
            border-radius: 5px;
            background: #333;
            color: #fff;
        }
        .consultation-form button {
            background: #fff;
            color: #000;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            display: block;
            margin: 0 auto;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Valeriia Tereshchenko</h1>
        <p>Experienced SMM specialist and digital marketing expert with a passion for creating engaging digital content. With 1 year of experience, I help businesses grow their online presence through strategic content planning, data-driven ad campaigns, and audience engagement.</p>
        
        <h2>My Expertise</h2>
        <div class="expertise">
            <ul>
                <li>Social media management & content creation</li>
                <li>Targeted advertising (Meta Ads, TikTok Ads)</li>
                <li>Google Ads & contextual advertising</li>
                <li>Content strategy & branding</li>
                <li>Audience growth & engagement</li>
                <li>Analytics & performance tracking</li>
            </ul>
        </div>

        <h2>My Works</h2>
        <div id="portfolio"></div>

        <h2>Services</h2>
        <div class="service-item">✅ Social Media Management & Content Creation</div>
        <div class="service-item">✅ Targeted Advertising (Meta Ads, TikTok Ads)</div>
        <div class="service-item">✅ Google Ads & Contextual Advertising</div>
        <div class="service-item">✅ Content Strategy & Branding</div>
        <div class="service-item">✅ Audience Growth & Engagement</div>
        <div class="service-item">✅ Analytics & Performance Reports</div>
        
        <h2>Pricing</h2>
        <div class="pricing-item"><b>💰:</b> Available upon request / Custom pricing based on your needs.</div>

        <h2>Contact Information</h2>
        <div class="contact-info">
            <p>📧 Email: <a href="mailto:odesa.vt@gmail.com" style="color: #fff;">odesa.vt@gmail.com</a></p>
            <p>🔗 LinkedIn: <a href="#" style="color: #fff;">Valeriia Tereshchenko</a></p>
            <p>💬 WhatsApp: <a href="https://wa.me/14373323428" style="color: #fff;">+1 437 332 3428</a></p>
        </div>

        <h2>Book a Consultation</h2>
        <div class="consultation-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Describe your request" rows="4" required></textarea>
            <button type="submit">Submit Request</button>
        </div>

        <h2>Client Reviews</h2>
        <div id="reviews">
            <div class="review-item">⭐ "Valeriia helped us boost engagement by 200%! Highly recommend."</div>
            <div class="review-item">⭐ "Professional and result-oriented. A great experience!"</div>
        </div>
    </div>
</body>
</html>
