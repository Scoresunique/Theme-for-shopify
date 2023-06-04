/* Global Styles */

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

/* Header */

header {
  background-color: #333;
  color: #fff;
  padding: 20px;
}

header h1 {
  margin: 0;
  font-size: 28px;
}

/* Navigation */

nav {
  background-color: #666;
  padding: 10px;
}

nav ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 10px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  padding: 5px;
}

/* Main Content */

main {
  padding: 20px 0;
}

.product {
  display: flex;
  margin-bottom: 20px;
}

.product img {
  width: 200px;
  height: 200px;
  object-fit: cover;
  margin-right: 20px;
}

.product-info {
  flex: 1;
}

.product-title {
  font-size: 24px;
  margin: 0 0 10px;
}

.product-description {
  margin-bottom: 10px;
}

.product-price {
  font-weight: bold;
  font-size: 18px;
}

.product-button {
  background-color: #666;
  color: #fff;
  padding: 5px 10px;
  border: none;
  cursor: pointer;
}

.product-button:hover {
  background-color: #333;
}

/* Footer */

footer {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}

