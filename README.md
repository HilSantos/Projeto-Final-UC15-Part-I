# Cultura-Nordica-styles.css
Parte um da criação do Projeto Final UC15.

/* Reset básico */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Merriweather', serif;
  background-color: #0f0f0f;
  color: #e0e0e0;
  line-height: 1.6;
  padding-top: 80px; /* espaço para o menu fixo */
}

/* Cabeçalho fixo */
header {
  position: fixed;
  top: 0;
  width: 100%;
  background-color: #1e1e1e;
  padding: 20px 0;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.8);
  z-index: 1000;
}

nav ul {
  display: flex;
  justify-content: center;
  list-style: none;
  gap: 30px;
}

nav a {
  color: #e0e0e0;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s;
}

nav a:hover {
  color: #bfa76f;
}

/* Seções */
section {
  max-width: 900px;
  margin: 40px auto;
  padding: 20px;
  background-color: #1c1c1c;
  border-left: 5px solid #bfa76f;
  border-radius: 8px;
  box-shadow: 0 0 10px #00000088;
}

/* Títulos */
h1, h2 {
  color: #bfa76f;
  margin-bottom: 10px;
}

/* Listas */
ul {
  padding-left: 20px;
}

li {
  margin-bottom: 8px;
}

/* Rodapé */
footer {
  text-align: center;
  padding: 20px;
  background-color: #1e1e1e;
  color: #888;
  margin-top: 40px;
}

/* Responsivo */
@media (max-width: 600px) {
  nav ul {
    flex-direction: column;
    gap: 15px;
  }

  section {
    margin: 20px;
  }
}
