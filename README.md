# IPHONE

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 1rem;
}

nav a {
    color: white;
    text-decoration: none;
}

main {
    padding: 2rem;
}

.product-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    justify-content: center;
}

.product {
    background: white;
    border: 1px solid #ddd;
    padding: 1rem;
    text-align: center;
    width: 200px;
}

.product img {
    max-width: 100%;
}

button {
    background-color: #28a745;
    color: white;
    border: none;
    padding: 0.5rem 1rem;
    cursor: pointer;
}

button:hover {
    background-color: #218838;
}

#cart {
    margin-top: 2rem;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem;
    position: fixed;
    width: 100%;
    bottom: 0;
}
