/* RESET E FONTES */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body {
    background-color: #f4f8f4;
    color: #333;
}

/* HEADER */
header {
    background: linear-gradient(90deg, #2e7d32, #66bb6a);
    color: white;
    padding: 20px;
    text-align: center;
}

header h1 {
    font-size: 2.2rem;
}

/* NAV */
nav {
    background-color: #1b5e20;
    padding: 10px;
    text-align: center;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
    transition: 0.3s;
}

nav a:hover {
    color: #c8e6c9;
}

/* SECTIONS */
section {
    padding: 50px 20px;
    max-width: 1100px;
    margin: auto;
}

.section-title {
    text-align: center;
    margin-bottom: 30px;
    color: #2e7d32;
}

.center-text {
    text-align: center;
}

/* CARDS */
.cards {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
}

.card {
    background: white;
    padding: 20px;
    width: 300px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-5px);
}

/* BUTTON */
button {
    background-color: #2e7d32;
    color: white;
    padding: 10px 15px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    margin-top: 10px;
    transition: 0.3s;
}

button:hover {
    background-color: #1b5e20;
}

/* MENSAGEM */
#mensagem {
    margin-top: 15px;
    font-weight: bold;
    color: #2e7d32;
}

/* FOOTER */
footer {
    background-color: #1b5e20;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 30px;
}
