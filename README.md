# Projeto-Final-UC15-Part-I
Desenvolver um site com HTML e CSS, com os conceitos que aprendemos.

body {
    background-image: url('yggdrasil.jpg') no-repeat center center fixed;
    background-size: cover;
    font-family: 'Arial', sans-serif;
    color: #fff;
    margin: 0;
    padding: 0;
}

header {
    background: rgba(0, 0, 0, 0.7);
    padding: 20px;
    text-align: center;
    border-bottom: 2px solid #ccc;
}

header h1 {
    font-size: 2.5em;
    margin: 0;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 20px 0 0;
    display: flex;
    justify-content: center;
    gap: 15px;
}

nav ul li {
    display: inline;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    padding: 10px 20px;
    border: 1px solid #fff;
    border-radius: 5px;
    transition: background-color 0.3s, color 0.3s;
}

nav ul li a:hover {
    background-color: #fff;
    color: #000;
}

main {
    padding: 20px;
    background: rgba(0, 0, 0, 0.8);
    margin: 20px auto;
    max-width: 800px;
    border-radius: 10px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
}

main p, main strong {
    font-size: 1.2em;
    line-height: 1.6;
}

hr {
    border: none;
    border-top: 2px solid #ccc;
    margin: 20px 0;
}

footer {
    text-align: center;
    padding: 10px;
    background: rgba(0, 0, 0, 0.7);
    border-top: 2px solid #ccc;
}

footer p {
    margin: 0;
    font-size: 0.9em;
}
