* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Roboto', sans-serif;
    background-color: #1e1e2e;
    color: #fff;
    line-height: 1.6;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background: #121222;
}

.logo {
    font-size: 1.5rem;
    font-weight: 700;
    color: #00d9ff;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: 400;
    transition: color 0.3s ease;
}

nav ul li a:hover {
    color: #00d9ff;
}

.hero {
    height: 100vh;
    background: linear-gradient(135deg, #00d9ff, #007bff);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 30px;
}

.cta-btn {
    background: #00d9ff;
    color: #1e1e2e;
    padding: 15px 30px;
    text-decoration: none;
    font-weight: 700;
    border-radius: 30px;
    transition: background 0.3s ease;
}

.cta-btn:hover {
    background: #007bff;
}

.produtos {
    padding: 50px 20px;
    background: #121222;
}

.produtos h2 {
    text-align: center;
    margin-bottom: 40px;
    font-size: 2.5rem;
    color: #00d9ff;
}

.produtos-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
}

.produto {
    background: #1e1e2e;
    padding: 20px;
    border-radius: 10px;
    text-align: center;
}

.produto img {
    width: 100%;
    border-radius: 10px;
}

.produto h3 {
    margin: 20px 0;
    font-size: 1.5rem;
}

.produto p {
    margin-bottom: 20px;
}

.produto button {
    background: #00d9ff;
    color: #1e1e2e;
    padding: 10px 20px;
    border: none;
    border-radius: 30px;
    cursor: pointer;
    transition: background 0.3s ease;
}

.produto button:hover {
    background: #007bff;
}


