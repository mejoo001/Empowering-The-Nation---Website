# Empowering The Nation - Website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Empowering The Nation</title>

    <link rel="stylesheet" href="style.css">

    <link
        rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
    />
</head>
<body>

    <!-- ================= NAVIGATION BAR ================= -->

    <header>
        <nav class="navbar">

            <div class="logo">
                <h2>EMPOWERING THE NATION</h2>
            </div>

            <ul class="nav-links">
                <li><a href="index.html">Home</a></li>
                <li><a href="sixmonth.html">6-Month Courses</a></li>
                <li><a href="sixweek.html">6-Week Courses</a></li>
                <li><a href="fees.html">Calculate Fees</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>

            <button class="signup-btn">Sign Up</button>

        </nav>
    </header>

    <!-- ================= HERO SECTION ================= -->

    <section class="hero-section">

        <div class="hero-image">
            <img
                src="https://cdn-icons-png.flaticon.com/512/3209/3209265.png"
                alt="Hero Image"
            />
        </div>

        <div class="hero-content">

            <h1>EMPOWERING THE NATION</h1>

            <h3>Skills Training for a Better Tomorrow</h3>

            <p>
                Established in 2018, Empowering the Nation provides practical
                skills development programs and learnerships designed to help
                individuals become workplace ready while improving communities.
            </p>

            <div class="hero-buttons">

                <a href="sixmonth.html" class="main-btn">
                    6-Month Courses
                </a>

                <a href="sixweek.html" class="main-btn">
                    6-Week Courses
                </a>

            </div>

        </div>

    </section>

    <!-- ================= FEATURES SECTION ================= -->

    <section class="features-section">

        <div class="feature-card">
            <i class="fa-solid fa-screwdriver-wrench"></i>
            <p>
                Empower individuals through practical skills development.
            </p>
        </div>

        <div class="feature-card">
            <i class="fa-solid fa-school"></i>
            <p>
                Provide training opportunities for workplace readiness.
            </p>
        </div>

        <div class="feature-card">
            <i class="fa-solid fa-award"></i>
            <p>
                Deliver quality educational experiences and support.
            </p>
        </div>

        <div class="feature-card">
            <i class="fa-solid fa-users"></i>
            <p>
                Promote community empowerment and growth.
            </p>
        </div>

    </section>

    <!-- ================= FOOTER ================= -->

    <footer>

        <div class="footer-container">

            <div class="footer-column">
                <h3>Quick Links</h3>
                <a href="index.html">Home</a>
                <a href="sixmonth.html">Courses</a>
                <a href="fees.html">Calculate Fees</a>
                <a href="contact.html">Contact Us</a>
            </div>

            <div class="footer-column">
                <h3>Courses</h3>
                <a href="#">First Aid</a>
                <a href="#">Sewing</a>
                <a href="#">Landscaping</a>
                <a href="#">Cooking</a>
            </div>

            <div class="footer-column">
                <h3>Contact</h3>
                <p>011 123 4567</p>
                <p>info@empoweringthenation.co.za</p>
                <p>Mon - Fri: 08h00 - 16h30</p>
            </div>

        </div>

    </footer>

</body>
</html>
________________________________________
2. style.css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body {
    background-color: #f5f5f5;
    color: #222;
}

/* ================= NAVBAR ================= */

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 60px;
    background-color: white;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.logo h2 {
    font-size: 22px;
    color: #000;
}

.nav-links {
    display: flex;
    list-style: none;
    gap: 30px;
}

.nav-links a {
    text-decoration: none;
    color: #000;
    font-weight: 500;
    transition: 0.3s;
}

.nav-links a:hover {
    color: #65a88f;
}

.signup-btn {
    padding: 12px 22px;
    border: none;
    background-color: #9fd7c4;
    border-radius: 8px;
    cursor: pointer;
    font-weight: bold;
}

.signup-btn:hover {
    background-color: #65a88f;
    color: white;
}

/* ================= HERO SECTION ================= */

.hero-section {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 80px 60px;
}

.hero-image img {
    width: 350px;
}

.hero-content {
    width: 55%;
}

.hero-content h1 {
    font-size: 55px;
    margin-bottom: 20px;
}

.hero-content h3 {
    font-size: 28px;
    margin-bottom: 20px;
    color: #444;
}

.hero-content p {
    line-height: 32px;
    font-size: 18px;
    color: #555;
}

.hero-buttons {
    margin-top: 40px;
    display: flex;
    gap: 20px;
}

.main-btn {
    text-decoration: none;
    background-color: #9fd7c4;
    color: #000;
    padding: 16px 24px;
    border-radius: 8px;
    font-weight: bold;
    transition: 0.3s;
}

.main-btn:hover {
    background-color: #65a88f;
    color: white;
}

/* ================= FEATURES SECTION ================= */

.features-section {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
    padding: 50px 60px;
}

.feature-card {
    background-color: white;
    padding: 30px;
    border-radius: 12px;
    text-align: center;
    box-shadow: 0 2px 10px rgba(0,0,0,0.08);
}

.feature-card i {
    font-size: 40px;
    margin-bottom: 20px;
    color: #65a88f;
}

.feature-card p {
    line-height: 28px;
    color: #555;
}

/* ================= COURSE PAGE ================= */

.page-heading {
    text-align: center;
    margin-top: 50px;
    margin-bottom: 50px;
    font-size: 42px;
}

.course-container {
    width: 90%;
    margin: auto;
}

.course-card {
    display: flex;
    align-items: center;
    background-color: white;
    padding: 25px;
    margin-bottom: 30px;
    border-radius: 12px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.08);
}

.course-card img {
    width: 120px;
    margin-right: 30px;
}

.course-info h2 {
    margin-bottom: 10px;
}

.course-info p {
    margin-bottom: 10px;
    color: #555;
}

.course-btn {
    display: inline-block;
    margin-top: 10px;
    text-decoration: none;
    background-color: #9fd7c4;
    padding: 12px 20px;
    border-radius: 8px;
    color: black;
    font-weight: bold;
}

/* ================= FORM SECTION ================= */

.form-container {
    width: 60%;
    margin: 50px auto;
    background-color: white;
    padding: 40px;
    border-radius: 12px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.08);
}

.form-group {
    margin-bottom: 25px;
}

.form-group label {
    display: block;
    margin-bottom: 10px;
    font-weight: bold;
}

.form-group input {
    width: 100%;
    padding: 14px;
    border-radius: 8px;
    border: 1px solid #ccc;
}

.checkbox-group {
    margin-top: 20px;
}

.checkbox-group label {
    display: block;
    margin-bottom: 12px;
}

.calculate-btn {
    margin-top: 25px;
    width: 100%;
    padding: 16px;
    background-color: #9fd7c4;
    border: none;
    border-radius: 8px;
    font-size: 16px;
    font-weight: bold;
    cursor: pointer;
}

/* ================= CONTACT SECTION ================= */

.contact-container {
    width: 80%;
    margin: auto;
    padding-bottom: 60px;
}

.contact-card {
    display: flex;
    align-items: center;
    background-color: white;
    padding: 25px;
    margin-bottom: 20px;
    border-radius: 12px;
}

.contact-card i {
    font-size: 30px;
    margin-right: 20px;
    color: #65a88f;
}

/* ================= FOOTER ================= */

footer {
    background-color: white;
    padding: 60px;
    margin-top: 60px;
}

.footer-container {
    display: flex;
    justify-content: space-between;
}

.footer-column {
    display: flex;
    flex-direction: column;
}

.footer-column h3 {
    margin-bottom: 20px;
}

.footer-column a,
.footer-column p {
    margin-bottom: 12px;
    text-decoration: none;
    color: #555;
}

/* ================= RESPONSIVE DESIGN ================= */

@media(max-width: 992px) {

    .hero-section {
        flex-direction: column;
        text-align: center;
    }

    .hero-content {
        width: 100%;
        margin-top: 40px;
    }

    .hero-buttons {
        justify-content: center;
    }

    .features-section {
        grid-template-columns: repeat(2, 1fr);
    }

    .footer-container {
        flex-direction: column;
        gap: 40px;
    }
}

@media(max-width: 768px) {

    .navbar {
        flex-direction: column;
        gap: 20px;
    }

    .nav-links {
        flex-direction: column;
        align-items: center;
    }

    .hero-content h1 {
        font-size: 38px;
    }

    .features-section {
        grid-template-columns: 1fr;
    }

    .course-card {
        flex-direction: column;
        text-align: center;
    }

    .course-card img {
        margin-right: 0;
        margin-bottom: 20px;
    }

    .form-container {
        width: 90%;
    }
}
________________________________________
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>6-Month Courses</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <h1 class="page-heading">6-Month Courses</h1>

    <div class="course-container">

        <div class="course-card">
            <img
                src="https://cdn-icons-png.flaticon.com/512/2966/2966481.png"
                alt="First Aid"
            >

            <div class="course-info">
                <h2>First Aid</h2>
                <p>Course Fee: R1500</p>
                <p>
                    Learn emergency treatment and life-saving techniques.
                </p>
                <a href="fees.html" class="course-btn">Add to Quote</a>
            </div>
        </div>

        <div class="course-card">
            <img
                src="https://cdn-icons-png.flaticon.com/512/3082/3082037.png"
                alt="Sewing"
            >

            <div class="course-info">
                <h2>Sewing</h2>
                <p>Course Fee: R1500</p>
                <p>
                    Learn sewing techniques and garment alterations.
                </p>
                <a href="fees.html" class="course-btn">Add to Quote</a>
            </div>
        </div>

    </div>

</body>
</html>
________________________________________
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculate Fees</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <h1 class="page-heading">Calculate Fees</h1>

    <div class="form-container">

        <div class="form-group">
            <label>Full Name</label>
            <input type="text" placeholder="Enter your full name">
        </div>

        <div class="form-group">
            <label>Phone Number</label>
            <input type="text" placeholder="Enter your phone number">
        </div>

        <div class="form-group">
            <label>Email Address</label>
            <input type="email" placeholder="Enter your email address">
        </div>

        <div class="checkbox-group">
            <label><input type="checkbox"> First Aid</label>
            <label><input type="checkbox"> Sewing</label>
            <label><input type="checkbox"> Landscaping</label>
            <label><input type="checkbox"> Cooking</label>
        </div>

        <button class="calculate-btn">
            Calculate Quote
        </button>

    </div>

</body>
</html>
________________________________________
// FORM VALIDATION

const calculateButton = document.querySelector('.calculate-btn');

if (calculateButton) {
    calculateButton.addEventListener('click', function(event) {
        event.preventDefault();

        const fullName = document.querySelector('input[type="text"]');
        const phoneNumber = document.querySelectorAll('input[type="text"]')[1];
        const email = document.querySelector('input[type="email"]');
        const checkboxes = document.querySelectorAll('input[type="checkbox"]');

        let selectedCourse = false;

        if (fullName.value.trim() === '') {
            alert('Please enter your full name');
            return;
        }

        const phoneRegex = /^[0-9]{10}$/;

        if (!phoneRegex.test(phoneNumber.value)) {
            alert('Please enter a valid 10-digit phone number');
            return;
        }

        const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;

        if (!emailRegex.test(email.value)) {
            alert('Please enter a valid email address');
            return;
        }

        checkboxes.forEach(function(checkbox) {
            if (checkbox.checked) {
                selectedCourse = true;
            }
        });

        if (!selectedCourse) {
            alert('Please select at least one course');
            return;
        }

        alert('Quote calculated successfully!');

        window.location.href = 'quote.html';
    });
}

// CONTACT FORM ERROR HANDLING

const contactForm = document.querySelector('.contact-form');

if (contactForm) {
    contactForm.addEventListener('submit', function(event) {
        event.preventDefault();

        try {
            const inputs = contactForm.querySelectorAll('input, textarea');

            let isValid = true;

            inputs.forEach(function(input) {
                if (input.value.trim() === '') {
                    input.style.border = '2px solid red';
                    isValid = false;
                } else {
                    input.style.border = '1px solid #ccc';
                }
            });

            if (!isValid) {
                throw new Error('Please complete all fields');
            }

            alert('Message sent successfully!');

        } catch (error) {
            alert(error.message);
            console.log(error);
        }
    });
}

// PAGE ERROR HANDLING

window.addEventListener('error', function(event) {
    console.log('Page Error:', event.message);

    alert('Something went wrong. Please refresh the page.');
});

// NETWORK ERROR HANDLING

window.addEventListener('offline', function() {
    alert('No internet connection detected.');
});

window.addEventListener('online', function() {
    alert('Internet connection restored.');
});
// Structured Navigation SEO
<header>
<nav>
<ul>
<li><a href="index.html">Home</a></li>
<li><a href="sixmonth.html">6-Month Courses</a></li>
<li><a href="sixweek.html">6-Week Courses</a></li>
<li><a href="fees.html">Calculate Fees</a></li>
<li><a href="contact.html">Contact</a></li>
</ul>
</nav>
</header>
