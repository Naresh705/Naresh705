* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
}

header {
    background: #222;
    color: #fff;
    padding: 1.5rem;
    text-align: center;
}

header nav ul {
    list-style: none;
    padding: 0;
    display: flex;
    justify-content: center;
    gap: 1rem;
}

header nav ul li {
    margin: 0;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

.hero {
    background: url('https://via.placeholder.com/1200x600') no-repeat center center/cover;
    color: white;
    height: 60vh;
    display: flex;
    align-items: center;
    justify-content: center;
}

.hero-text {
    text-align: center;
}

.hero-text .btn {
    background: #007bff;
    color: #fff;
    padding: 0.5rem 1.5rem;
    border-radius: 5px;
    text-decoration: none;
}

section {
    padding: 2rem;
}

#services .service-cards {
    display: flex;
    gap: 1rem;
    justify-content: space-around;
}

.service-cards .card {
    background: #f4f4f4;
    padding: 1rem;
    border-radius: 8px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    transition: transform 0.3s;
}

.service-cards .card:hover {
    transform: translateY(-5px);
}

.service-cards .card i {
    font-size: 2rem;
    color: #007bff;
}

footer {
    background: #222;
    color: #fff;
    text-align: center;
    padding: 1rem;
}

footer .social-icons a {
    color: #fff;
    margin: 0 0.5rem;
    text-decoration: none;
    font-size: 1.2rem;
}
