<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>TechNova - Landing Page</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#0f172a;
    color:white;
}

/* Navbar */
nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 8%;
    position:fixed;
    width:100%;
    background:rgba(15,23,42,.9);
    backdrop-filter:blur(10px);
    z-index:1000;
}

.logo{
    font-size:30px;
    font-weight:bold;
    color:#06b6d4;
}

nav ul{
    display:flex;
    list-style:none;
    gap:30px;
}

nav a{
    text-decoration:none;
    color:white;
    transition:.3s;
}

nav a:hover{
    color:#06b6d4;
}

/* Hero */

.hero{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    flex-direction:column;
    text-align:center;
    padding:100px 20px;
    background:linear-gradient(135deg,#0f172a,#1e293b,#312e81);
}

.hero h1{
    font-size:65px;
    margin-bottom:20px;
}

.hero p{
    max-width:700px;
    line-height:1.8;
    color:#cbd5e1;
}

.btn{
    display:inline-block;
    margin:20px 10px;
    padding:14px 28px;
    background:#06b6d4;
    color:white;
    text-decoration:none;
    border-radius:10px;
    transition:.3s;
}

.btn:hover{
    transform:translateY(-5px);
}

/* Section */

section{
    padding:90px 8%;
}

.title{
    text-align:center;
    font-size:42px;
    color:#06b6d4;
    margin-bottom:50px;
}

/* Services */

.services{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:rgba(255,255,255,0.08);
    padding:35px;
    border-radius:15px;
    text-align:center;
    transition:.3s;
}

.card:hover{
    transform:translateY(-10px);
    background:#1e293b;
}

.card h3{
    margin-bottom:15px;
    color:#06b6d4;
}

/* About */

.about{
    text-align:center;
    line-height:1.8;
    color:#cbd5e1;
}

.stats{
    margin-top:40px;
    display:flex;
    justify-content:center;
    gap:50px;
    flex-wrap:wrap;
}

.stat{
    background:#1e293b;
    padding:25px;
    border-radius:12px;
    min-width:180px;
}

.stat h2{
    color:#06b6d4;
}

/* Testimonials */

.testimonials{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:20px;
}

.testimonial{
    background:#1e293b;
    padding:25px;
    border-radius:15px;
}

.testimonial h3{
    margin-bottom:10px;
    color:#06b6d4;
}

/* Contact */

.contact{
    text-align:center;
    line-height:2;
}

/* Footer */

footer{
    background:#020617;
    padding:25px;
    text-align:center;
    margin-top:30px;
}

/* Responsive */

@media(max-width:768px){

.hero h1{
    font-size:42px;
}

nav ul{
    gap:15px;
    font-size:14px;
}
}
</style>
</head>
<body>

<!-- Navbar -->

<nav>
    <div class="logo">TechNova</div>

    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<!-- Hero -->

<section class="hero" id="home">

    <h1>Build the Future with TechNova</h1>

    <p>
        We create modern websites, mobile applications,
        and digital experiences that help businesses grow
        and succeed in today's world.
    </p>

    <div>
        <a href="#" class="btn">Get Started</a>
        <a href="#about" class="btn">Learn More</a>
    </div>

</section>

<!-- Services -->

<section id="services">

    <h1 class="title">Our Services</h1>

    <div class="services">

        <div class="card">
            <h3>Web Development</h3>
            <p>Responsive and high-performance websites for businesses.</p>
        </div>

        <div class="card">
            <h3>UI/UX Design</h3>
            <p>Beautiful, modern and user-friendly digital experiences.</p>
        </div>

        <div class="card">
            <h3>App Development</h3>
            <p>Custom Android and iOS applications built for scalability.</p>
        </div>

    </div>

</section>

<!-- About -->

<section id="about">

    <h1 class="title">About Us</h1>

    <div class="about">

        <p>
            TechNova is a leading digital agency focused on innovation,
            creativity and technology. We have helped hundreds of
            businesses establish a strong online presence.
        </p>

        <div class="stats">

            <div class="stat">
                <h2>500+</h2>
                <p>Clients</p>
            </div>

            <div class="stat">
                <h2>1000+</h2>
                <p>Projects</p>
            </div>

            <div class="stat">
                <h2>5+</h2>
                <p>Years Experience</p>
            </div>

        </div>

    </div>

</section>

<!-- Testimonials -->

<section>

    <h1 class="title">Testimonials</h1>

    <div class="testimonials">

        <div class="testimonial">
            <h3>John Smith</h3>
            <p>"Excellent service and outstanding support!"</p>
        </div>

        <div class="testimonial">
            <h3>Sarah Johnson</h3>
            <p>"TechNova transformed our online presence."</p>
        </div>

        <div class="testimonial">
            <h3>Michael Brown</h3>
            <p>"Highly recommended for web development projects."</p>
        </div>

    </div>

</section>

<!-- Contact -->

<section id="contact">

    <h1 class="title">Contact Us</h1>

    <div class="contact">
        <p>📧 info@technova.com</p>
        <p>📞 +91 XXXXX XXXXX</p>
        <p>📍 Prayagraj, Uttar Pradesh, India</p>
    </div>

</section>

<!-- Footer -->

<footer>
    © 2026 TechNova. All Rights Reserved.
</footer>

</body>
</html>
