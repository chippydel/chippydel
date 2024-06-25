- 👋 Hi, I’m @chippydel
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
chippydel/chippydel is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
westend-windows/
├── index.html
└── styles.css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #004080;
    color: white;
    padding: 20px 0;
}

.header-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

.logo img {
    max-height: 50px;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    gap: 20px;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.contact-info p {
    margin: 0;
}

.main-banner {
    background-image: url('banner-image.jpg');
    background-size: cover;
    background-position: center;
    color: white;
    text-align: center;
    padding: 100px 20px;
}

.banner-content h1 {
    margin: 0;
    font-size: 3em;
}

.intro, .product-highlights, .call-to-action {
    max-width: 1200px;
    margin: 40px auto;
    padding: 0 20px;
    text-align: center;
}

.product-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
}

.product-item {
    flex: 1 1 calc(33.333% - 20px);
    background-color: #f5f5f5;
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

.product-item img {
    max-width: 100%;
    height: auto;
    margin-bottom: 10px;
}

.call-to-action .cta-button {
    display: inline-block;
    margin: 20px 10px;
    padding: 15px 30px;
    background-color: #004080;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

footer {
    background-color: #333;
    color: white;
    padding: 20px 0;
    text-align: center;
}

.footer-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
    display: flex;
    justify-content: space
