# ZaysSkinCare.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zay's Skincare Routine Blog</title>
</head>
<body>
    <header>
        <h1>Zay's Skincare Routine</h1>
        <nav>
            <ul>
                <li><a href="#cleansing">Cleansing</a></li>
                <li><a href="#exfoliating">Exfoliating</a></li>
                <li><a href="#moisturizing">Moisturizing</a></li>
                <li><a href="#sun-protection">Sun Protection</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="cleansing">
            <h2>Step 1: Cleansing</h2>
            <p> Cleansing is very important and I highly recommend using the Kale Cleanser from Free People!</p>
        </section>
        <section id="exfoliating">
            <h2>Step 2: Exfoliating</h2>
            <p> I personally think exfoliating is really important after shaving or you should exfoliate 3 times per week. It helps prevent cystic acne and overall neutralizes blemishes. I like Paulas choice! </p>
        </section>
        <section id="moisturizing">
            <h2>Step 3: Moisturizing</h2>
            <p> moisturizing is very important since you just stripped your face of its natural oils. I highly recommend the khiels moisturizer.</p>
        </section>
        <section id="sun-protection">
            <h2>Step 4: Sun Protection</h2>
            <p> Sun screen is sometimes overlooked but is very important. If you don’t apply an ample amount of sunscreen your pimples can scar from the sun. And overall your skin will lose its healthy appearance! </p>
        </section>
    </main>
    <footer>
        <p> Zay's Skincare Routine Blog</p>
    </footer>
</body>
</html>


//css file for my skin care blog

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #f5f5f5;
    padding: 20px;
    text-align: center;
}

h1 {
    color: #333;
}

article {
    margin: 20px;
}

section {
    margin-bottom: 40px;
}

h2 {
    color: #555;
}

p {
    line-height: 1.5;
}

footer {
    background-color: #f5f5f5;
    padding: 20px;
    text-align: center;
    font-size: 14px;
    color: #888;
}


// JavaScript for the skincare blog

// change the background color of the header function 
changeHeaderColor() {
    var header = document.querySelector('header');
    header.style.backgroundColor = '#ffcc00';
}

// show alert when the footer is clicked
function showAlert() {
    alert('Thanks for taking my skincare tips!!’);
}

// trigger the functions
document.addEventListener('DOMContentLoaded', changeHeaderColor);
document.querySelector('footer').addEventListener('click', showAlert);
