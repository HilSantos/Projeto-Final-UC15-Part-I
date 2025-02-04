# Cultura-Nordica-styles.css
Parte um da criação do Projeto Final UC15.

body {
    background-image: url('C:/users/hilton.lssantos/imagens/Ygg-dra-sil.jpg');
  background-size: cover;
  background-repeat: repeat;
  background-position: center;
  background: radial-gradient(circle, #6a11cb, #2575fc, #ff7e5f);
  margin-left: auto;
  margin-right: auto;
  height: 100vh;
  color: aliceblue;
}

header {
    background: rgba(0, 0, 0, 0.7);
  padding: 20px;
  text-align: center;
  border-bottom: 2px solid #ccc;
  color: #fff;
}

header h1 {
    font-size: 2.5em;
  margin: 0;
  background-color: #252323;
  height: 100px;
  width: 100%;
  color: white;
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

#Início a[href="index.html"],
#Mitologia a[href="mitologia.html"],
#Historia a[href="historia.html"],
#Tradições a[href="tradições.html"],
#Contato a[href="contato.html"] {
background-color: #ff7e5f;
}

#Início aside{
    width: 230px;
    float: left;
    margin-top: 30px;
}

#Início main{
    width: 490px;
    float: left;
    margin: 30px 25px 10px;
}

footer{
    clear: both;
    border-top: 7px solid #999;
    background-color: #000;
    color: #fff;
    text-align: center;
    padding: 10px;
}

footer p{
    margin: 0;
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
    color: gold;
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
