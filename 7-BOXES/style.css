/* ================================
   7 BOXES — LEVEL 1
   Main Styles
================================ */


/* ---------- Reset ---------- */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


html {
    scroll-behavior: smooth;
}


body {
    font-family: Arial, Helvetica, sans-serif;
    background: #050508;
    color: #ffffff;
    min-height: 100vh;
    overflow-x: hidden;
}


/* ---------- Background ---------- */

#background {
    position: fixed;
    inset: 0;
    z-index: -1;

    background:
        radial-gradient(
            circle at 20% 20%,
            rgba(90, 70, 255, 0.18),
            transparent 35%
        ),
        radial-gradient(
            circle at 80% 70%,
            rgba(0, 200, 255, 0.12),
            transparent 35%
        ),
        #050508;
}


/* ---------- Navigation ---------- */

.navbar {
    position: fixed;

    top: 0;
    left: 0;

    width: 100%;

    display: flex;
    align-items: center;
    justify-content: space-between;

    padding: 20px 6%;

    background: rgba(5, 5, 8, 0.65);

    backdrop-filter: blur(16px);

    border-bottom: 1px solid rgba(255, 255, 255, 0.08);

    z-index: 100;
}


.logo {
    color: white;

    text-decoration: none;

    font-size: 1.3rem;

    font-weight: 800;

    letter-spacing: 3px;
}


.navbar nav {
    display: flex;

    gap: 30px;
}


.navbar nav a {
    color: rgba(255, 255, 255, 0.75);

    text-decoration: none;

    font-size: 0.95rem;

    transition: 0.3s;
}


.navbar nav a:hover {
    color: white;
}


/* ---------- Hero ---------- */

.hero {
    min-height: 100vh;

    display: flex;
    align-items: center;
    justify-content: center;

    text-align: center;

    padding: 120px 6% 80px;
}


.hero-content {
    max-width: 900px;
}


.eyebrow {
    font-size: 0.75rem;

    letter-spacing: 4px;

    font-weight: 700;

    opacity: 0.55;

    margin-bottom: 20px;
}


.hero h1 {
    font-size: clamp(3rem, 8vw, 7rem);

    line-height: 0.95;

    letter-spacing: -4px;

    margin-bottom: 30px;
}


.hero h1 span {
    display: block;

    background: linear-gradient(
        90deg,
        #ffffff,
        #8ea2ff,
        #72e8ff
    );

    -webkit-background-clip: text;
    background-clip: text;

    color: transparent;
}


.hero-text {
    max-width: 650px;

    margin: 0 auto 35px;

    font-size: 1.1rem;

    line-height: 1.7;

    color: rgba(255, 255, 255, 0.65);
}


.hero-button {
    display: inline-block;

    padding: 15px 25px;

    border: 1px solid rgba(255, 255, 255, 0.2);

    border-radius: 50px;

    color: white;

    text-decoration: none;

    background: rgba(255, 255, 255, 0.07);

    backdrop-filter: blur(10px);

    transition: 0.3s;
}


.hero-button:hover {
    transform: translateY(-3px);

    background: rgba(255, 255, 255, 0.13);
}


/* ---------- Boxes ---------- */

.boxes-section {
    padding: 120px 6%;
}


.section-heading {
    text-align: center;

    margin-bottom: 60px;
}


.section-heading h2 {
    font-size: clamp(2.5rem, 5vw, 4.5rem);

    margin-bottom: 15px;
}


.section-heading > p:last-child {
    color: rgba(255, 255, 255, 0.55);

    line-height: 1.6;
}


/* ---------- Grid ---------- */

.boxes-grid {
    max-width: 1200px;

    margin: auto;

    display: grid;

    grid-template-columns:
        repeat(3, 1fr);

    gap: 20px;
}


/* ---------- Cards ---------- */

.box-card {
    position: relative;

    min-height: 260px;

    padding: 30px;

    border-radius: 24px;

    background: rgba(255, 255, 255, 0.045);

    border: 1px solid rgba(255, 255, 255, 0.09);

    backdrop-filter: blur(12px);

    overflow: hidden;

    transition:
        transform 0.4s ease,
        border-color 0.4s ease,
        background 0.4s ease;
}


.box-card:hover {
    transform: translateY(-8px);

    border-color:
        rgba(255, 255, 255, 0.22);

    background:
        rgba(255, 255, 255, 0.075);
}


.box-number {
    position: absolute;

    top: 20px;
    right: 25px;

    font-size: 0.75rem;

    opacity: 0.3;

    letter-spacing: 2px;
}


.box-icon {
    font-size: 2.3rem;

    margin-bottom: 30px;
}


.box-card h3 {
    font-size: 1.5rem;

    margin-bottom: 12px;
}


.box-card p {
    color: rgba(255, 255, 255, 0.55);

    line-height: 1.6;
}


/* ---------- Footer ---------- */

footer {
    text-align: center;

    padding: 80px 6% 40px;

    border-top:
        1px solid rgba(255, 255, 255, 0.08);
}


.footer-logo {
    font-weight: 800;

    letter-spacing: 4px;

    margin-bottom: 15px;
}


footer p {
    color: rgba(255, 255, 255, 0.5);

    margin-bottom: 10px;
}


footer .copyright {
    font-size: 0.8rem;

    opacity: 0.4;

    margin-top: 30px;
}


/* ---------- Mobile ---------- */

@media (max-width: 800px) {

    .navbar {
        padding: 18px 5%;
    }


    .navbar nav {
        gap: 15px;
    }


    .navbar nav a {
        font-size: 0.8rem;
    }


    .hero h1 {
        letter-spacing: -2px;
    }


    .boxes-grid {
        grid-template-columns: 1fr;
    }


    .box-card {
        min-height: 220px;
    }

}
