
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/jpg" href="image/icons.jpg">
    <link rel="stylesheet" href="style.css">
    <title>Product Layout</title>
</head>
<body>
    <h1 style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; font-style:italic; text-align:center;">Product Layout</h1>
    <div class="product-container">
        <div class="product-card">
            <img src="image/airf1.jfif" alt="Product 1">
            <h2>Nike Air Force 1</h2>
            <p>₱2,680.00</p>
            <button style="background-color:rgb(107, 212, 107); font-family:monospace">Add to Cart</button>
        </div>
        <div class="product-card">
            <img src="image/nike pre-5.jfif" alt="Product 2">
            <h2>Nike Precision 5</h2>
            <p>₱2,985.00</p>
            <button style="background-color:rgb(107, 212, 107); font-family:monospace">Add to Cart</button>
        </div>
        <div class="product-card">
            <img src="image/Zoom1.avif" alt="Product 3">
            <h2>Nike Alphafly Next    2</h2>
            <p>₱2,795.00</p>
            <button style="background-color:rgb(107, 212, 107); font-family:monospace">Add to Cart</button>
        </div>
        <div class="product-card">
            <img src="image/img4.jpg" alt="Product 4">
            <h2>Jordan 1 Retro High</h2>
            <p>₱2,895.00</p>
            <button style="background-color:rgb(107, 212, 107); font-family:monospace">Add to Cart</button>
        </div>
        <div class="product-card">
            <img src="image/img5.jfif" alt="Product 5">
            <h2>Nike SB Dunk Low</h2>
            <p>₱2.855.00</p>
            <button style="background-color:rgb(107, 212, 107); font-family:monospace">Add to Cart</button>
        </div>
    </div>
    <h1 style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; font-style:italic; text-align:center">Employee Cards</h1>
    <div class="employee-container">
        <div class="employee-card">
            <img src="imag-person/p1.jfif">
            <h2>John Doe S.</h2>
            <p>Position: Developer</p>
        </div>
        <div class="employee-card">
            <img src="imag-person/p4.jfif">
            <h2>Jerson D.</h2>
            <p>Position: Designer</p>
        </div>
        <div class="employee-card">
            <img src="imag-person/p3.jfif">
            <h2>Loid G.</h2>
            <p>Position: Manager</p>
        </div>
        <div class="employee-card">
            <img src="imag-person/p2.jpg">
            <h2>Jessy A.</h2>
            <p>Position: HR</p>
        </div>
        <div class="employee-card">
            <img src="imag-person/p5.1.jpg">
            <h2>Morgana T.</h2>
            <p>Position: Sales</p>
        </div>
    </div>
    <h1 style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; font-style:italic;text-align:center">Student Profiles</h1>
    <div class="student-container">
        <div class="student-card">
            <img src="imag-person/s1.jpeg">
            <h2>Tanggol D.</h2>
            <p>Grade: A</p>
        </div>
        <div class="student-card">
            <img src="imag-person/s2.jfif">
            <h2>Regor C.</h2>
            <p>Grade: B</p>
        </div>
        <div class="student-card">
            <img src="imag-person/s3.png">
            <h2>Santino C.</h2>
            <p>Grade: A+</p>
        </div>
        <div class="student-card">
            <img src="imag-person/s4.jfif">
            <h2>Larry S.</h2>
            <p>Grade: C</p>
        </div>
        <div class="student-card">
            <img src="imag-person/s5.jfif">
            <h2>Kier P.</h2>
            <p>Grade: B+</p>
        </div>
    </div>
    <h1 style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; font-style:italic; text-align:center">Image Gallery</h1>
    <div class="gallery-container">
        <div class="gallery-item">
            <img src="bg-view/v1.jfif" alt="Gallery 1">
        </div>
        <div class="gallery-item">
            <img src="bg-view/v2.jfif" alt="Gallery 2">
        </div>
        <div class="gallery-item">
            <img src="bg-view/v3.webp" alt="Gallery 3">
        </div>
        <div class="gallery-item">
            <img src="bg-view/v4.jfif" alt="Gallery 4">
        </div>
        <div class="gallery-item">
            <img src="bg-view/v5.jpg" alt="Gallery 5">
        </div>
    </div>
    <h1 style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; font-style:italic; text-align:center">Testimonials</h1>
    <div class="testimonial-container">
        <div class="testimonial-card">
            <p>"Great service!"</p>
            <h3>- Customer 1</h3>
        </div>
        <div class="testimonial-card">
            <p>"I love this product!"</p>
            <h3>- Customer 2</h3>
        </div>
        <div class="testimonial-card">
            <p>"Highly recommend this!"</p>
            <h3>- Customer 3</h3>
        </div>
        <div class="testimonial-card">
            <p>"Will buy again!"</p>
            <h3>- Customer 4</h3>
        </div>
        <div class="testimonial-card">
            <p>"Excellent quality!"</p>
            <h3>- Customer 5</h3>
        </div>
    </div>
</body>
</html>

/* This is for CSS */

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

.product-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 20px;
}

.product-card {
    background: white;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
    margin: 10px;
    padding: 15px;
    flex: 0 1 calc(20% - 20px);
    text-align: center;
}

.product-card img {
    max-width: 100%;
    height: auto;
}
.student-container, .employee-container, .gallery-container, .testimonial-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 20px;
}

.student-card, .employee-card, .gallery-item, .testimonial-card {
    background: white;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
    margin: 10px;
    padding: 15px;
    flex: 0 1 calc(20% - 20px);
    text-align: center;
}

.student-card img, .employee-card img, .gallery-item img {
    max-width: 100%;
    height: auto;
}
