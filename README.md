<header>
    <nav class="navbar">
        <img src="logo-loja.png" alt="Logo Loja Delicada" class="logo-img" />
        <ul>
            <li><a href="#inicio">Início</a></li>
            <li><a href="#servicos">Serviço</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>
</header>


/* Fonte elegante */
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap');

body {
    margin: 0;
    font-family: 'Playfair Display', serif;
    background-color: #fff0f5;
    color: #4b2e2e;
}

/* Logo */
.logo {
    height: 100px;
    display: block;
    margin: 0 auto;
    padding: 1rem 0;
}

/* Navbar */
.navbar {
    background-color: #ffc0cb;
    display: flex;
    justify-content: space-between;
    padding: 1rem 2rem;
    align-items: center;
    position: sticky;
    top: 0;
    z-index: 1000;
}

.navbar .logo-text {
    font-size: 1.5rem;
    color: #4b2e2e;
    font-weight: bold;
    font-family: 'Playfair Display', serif;
}

.navbar ul {
    list-style: none;
    display: flex;
    gap: 1rem;
}

.navbar a {
    color: #4b2e2e;
    text-decoration: none;
    font-weight: bold;
}

.hero {
    padding: 4rem 2rem;
    text-align: center;
}

.hero img {
    margin-top: 1rem;
    border-radius: 12px;
    max-width: 100%;
    height: auto;
}

.servicos {
    background-color: #ffe4e1;
    padding: 3rem 2rem;
    text-align: center;
}

.servicos ul {
    list-style: none;
    padding: 0;
}

.servicos li {
    margin: 1rem 0;
    font-size: 1.1rem;
}

.contato {
    padding: 3rem 2rem;
    background-color: #fffafc;
    text-align: center;
}

form {
    display: flex;
    flex-direction: column;
    max-width: 400px;
    margin: auto;
    gap: 1rem;
}

input, textarea {
    padding: 0.75rem;
    border-radius: 6px;
    border: 1px solid #ddd;
    font-family: 'Segoe UI', sans-serif;
}

button {
    background-color: #eac9c1;
    color: #4b2e2e;
    border: none;
    padding: 0.75rem;
    border-radius: 30px;
    font-weight: bold;
    cursor: pointer;
    transition: background-color 0.3s;
}

button:hover {
    background-color: #f5dcd4;
}

footer {
    background-color: #ffc0cb;
    text-align: center;
    padding: 1rem;
    color: #4b2e2e;
    font-family: 'Segoe UI', sans-serif;
}

.whatsapp {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: #25d366;
    color: white;
    font-size: 1.8rem;
    padding: 0.75rem 1rem;
    border-radius: 50px;
    text-decoration: none;
    box-shadow: 0 4px 6px rgba(0,0,0,0.2);
}