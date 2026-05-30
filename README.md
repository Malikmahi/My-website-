# My-website-<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Al Ahmad Homeopathic Clinic</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    line-height:1.6;
    color:#333;
}

header{
    background:linear-gradient(135deg,#2e8b57,#66cdaa);
    color:white;
    text-align:center;
    padding:80px 20px;
}

header h1{
    font-size:3rem;
    margin-bottom:10px;
}

header p{
    font-size:1.2rem;
    margin-bottom:20px;
}

.btn{
    display:inline-block;
    background:white;
    color:#2e8b57;
    padding:12px 25px;
    border-radius:30px;
    text-decoration:none;
    font-weight:bold;
}

section{
    padding:60px 10%;
}

h2{
    color:#2e8b57;
    margin-bottom:20px;
}

.services{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:#f7f7f7;
    padding:25px;
    border-radius:10px;
    box-shadow:0 2px 8px rgba(0,0,0,0.1);
}

.testimonials{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:20px;
}

.testimonial{
    background:#f7f7f7;
    padding:20px;
    border-left:5px solid #2e8b57;
}

.contact-form{
    max-width:600px;
    margin:auto;
}

.contact-form input,
.contact-form textarea{
    width:100%;
    padding:12px;
    margin:10px 0;
    border:1px solid #ccc;
    border-radius:5px;
}

.contact-form button{
    background:#2e8b57;
    color:white;
    border:none;
    padding:12px 25px;
    border-radius:5px;
    cursor:pointer;
}

footer{
    background:#2e8b57;
    color:white;
    text-align:center;
    padding:20px;
}
</style>
</head>

<body>

<header>
    <h1>Al Ahmad Homeopathic Clinic</h1>
    <p>Natural Healing • Personalized Care • Better Health</p>
    <a href="#contact" class="btn">Book Appointment</a>
</header>

<section id="about">
    <h2>About Us</h2>
    <p>
        We provide safe, natural, and personalized homeopathic treatment
        for patients of all ages. Our goal is to identify the root cause
        of illness and support long-term wellness.
    </p>
</section>

<section id="services">
    <h2>Our Services</h2>

    <div class="services">

        <div class="card">
            <h3>Gastric Problems</h3>
            <p>Acidity, gastritis, bloating, indigestion, and stomach burning.</p>
        </div>

        <div class="card">
            <h3>Skin Disorders</h3>
            <p>Acne, eczema, psoriasis, allergies, and dermatitis.</p>
        </div>

        <div class="card">
            <h3>Respiratory Diseases</h3>
            <p>Asthma, sinusitis, allergic rhinitis, and chronic cough.</p>
        </div>

        <div class="card">
            <h3>Women's Health</h3>
            <p>PCOS, menstrual disorders, hormonal imbalances, and menopause care.</p>
        </div>

    </div>
</section>

<section id="doctor">
    <h2>Our Doctor</h2>
    <p>
        <strong>Dr. Altaf Hussain</strong><br>
        Homeopathic Consultant<br><br>
        Dedicated to providing individualized homeopathic care with a holistic approach.
    </p>
</section>

<section id="testimonials">
    <h2>Patient Testimonials</h2>

    <div class="testimonials">
        <div class="testimonial">
            ⭐⭐⭐⭐⭐
            <p>Excellent treatment for my digestive issues. Highly recommended.</p>
        </div>

        <div class="testimonial">
            ⭐⭐⭐⭐⭐
            <p>Very professional and caring doctor. Great experience.</p>
        </div>

        <div class="testimonial">
            ⭐⭐⭐⭐⭐
            <p>Natural treatment that helped improve my overall health.</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Book an Appointment</h2>

    <form class="contact-form">
        <input type="text" placeholder="Full Name" required>
        <input type="tel" placeholder="Phone Number" required>
        <input type="email" placeholder="Email Address">
        <textarea rows="5" placeholder="Describe Your Health Concern"></textarea>
        <button type="submit">Submit</button>
    </form>
</section>

<footer>
    <p>© 2026 Al Ahmad Homeopathic Clinic. All Rights Reserved.</p>
</footer>

</body>
</html>
