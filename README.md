# mateen  
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset"UTF-8">
    <meta ADHAM REALESTATE="viewport" content="width=device-width, initial-scale=1.0">
    <title>Real Estate listings</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Dream Homes Realty</h1>
        <nav>
            <a herf="#">Home</a>
            <a herf="#">Listings</a>
            <a herf="#">contact</a>
        </nav>
    </header>

    <main>
        <section class="property-list">
            <article class="property">
                <img src="file:///C:/Users/ALIENWARE/Downloads/Adham%20Real%20Estate_files/adh.jpg/300x200" alt="Property Image">
                <h2>Modern Family Home</h2>
                <p>$450,000 · 3 Bed · 2 Bath · 1,800 sqft</p>
                <a href="#" class="btn">View Details</a>
            </article>
            <article class="property">
                <img src="https://via.placeholder.com/300x200" alt="Property Image">
                <h2>Luxury Condo Downtown</h2>
                <p>$850,000 · 2 Bed · 2 Bath · 1,200 sqft</p>
                <a href="#" class="btn">View Details</a>
            </article>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Dream Homes Realty</p>
    </footer>
</body>

</html> 
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}
header {
    background: #003366;
    color: white;
    padding: 20px 0;
    text-align: center;
}
nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
}
main {
    padding: 20px;
}
.property-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
}
.property {
    background: white;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    padding: 15px;
    text-align: center;
}
.property img {
    width: 100%;
    border-radius: 5px;
}
.btn {
    display: inline-block;
    margin-top: 10px;
    padding: 10px 15px;
    background: #003366;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}
footer {
    text-align: center;
    padding: 20px;
    background: #333;
    color: white;
}
