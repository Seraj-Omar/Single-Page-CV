# Single-Page-CV
https://roadmap.sh/projects/single-page-cv

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta property="og:title" content="CV" />
    <meta property="og:description" content="a single page CV of a frontend developer" />
    <meta property="og:type" content="website" />
    <meta property="og:site_name" content="CV" />
    <meta property="og:locale" content="en_US" />

    <title>CV</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
    <style>
        body{
            padding: 50px; 
            border: solid 3px black; 
            font-family: 'Roboto', sans-serif;
            width: 100%;
            max-width: 630px;
            margin: 0 auto;
        }
        h2{
            color: rgb(124,194,137);
        }
        address{
            font-size: larger;
        }
        .company{
            color: rgb(85,150,210);
            font-size: larger;
        }
        .personal-informations{
            line-height: 25px;
        }

    </style>
</head>
<body>
    <header>
        <hr style="border: 2px solid black;">
        <h1>Seraj Omar</h1>
        <h2>Junior Frontend Developer</h2>
    </header>
    <section class="personal-informations">
        <address>01 Baqa Al-Sharqiyah</address>
        <address>Tulkarem, ST 01</address>
        <a href="tel:+972568610919">(+972)56-761-0919</a>
        <br>
        <a href="mailto:srag20062017@gmail.com">srag20062017@gmail.com</a>
    </section>
    <section class="skills">
        <h2>Skills</h2>
        <p>C++, JAVA, HTML, CSS, JavaScript, Accessibility, Problem Solving.</p>
    </section>

    <section class="education">
        <h2>Education</h2>
        <p class="company">PTUK,Palestine - Bachelor in Computer Systems Engineering</p>
        <p>September 2023 to June 2028</p>
        <ul>
            <li>16th place in the PCPC</li>
            <li>6th place in the HCJ</li>
        </ul>
    </section>

    <section>
        <h2>Experience</h2>

        <p class="company">Company Name, Location - Job Title</p>
        <p>Month 20xx to Month 20xx</p>
        <ul>
            <li>Achievement</li>
            <li>Achievement</li>
            <li>Achievement</li>
        </ul>
        <p>Skills i Gained in That Company</p>

        <p class="company">Company Name, Location - Job Title</p>
        <p>Month 20xx to Month 20xx</p>
        <ul>
            <li>Achievement</li>
            <li>Achievement</li>
            <li>Achievement</li>
        </ul>
        <p>Skills i Gained in That Company</p>
    </section>
    <footer>
        <h2>Across Social Media</h2>
        <ul>
            <li><a href="https://github.com/Seraj-Omar" target="_blank">Github account</a></li>
            <li><a href="https://www.linkedin.com/in/seraj-omar-aa5946312/" target="_blank">Linkedin account</a></li>
        </ul>
    </footer>
</body>
</html>
