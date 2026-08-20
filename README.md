# recipes


# 🍽️ Recipe App

A responsive recipe discovery web app built with vanilla JavaScript, Tailwind CSS, and the DummyJSON Recipes API.



📸 Demo(https:)




## ✨ Features

- Browse a collection of recipes with images
- Search recipes by name in real-time
- View full recipe details including:
  - Ingredients list
  - Step-by-step instructions
  - Prep & cook time
  - Servings & difficulty level
- Clean detail page with smooth show/hide transitions
- Fully responsive design

## 🛠️ Built With

- **HTML5**
- **Tailwind CSS** — utility-first styling
- **Vanilla JavaScript** — async/await, fetch API, DOM manipulation
- **DummyJSON API** — `https://dummyjson.com/recipes`

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/recipe-app.git
   ```

2. Install Tailwind CSS:
   ```bash
   npx @tailwindcss/cli -i ./src/stylesheet/master.css -o ./src/out.css --watch
   ```

3. Open `index.html` in your browser.



## 🔌 API Reference

This project uses [DummyJSON](https://dummyjson.com/docs/recipes) free recipes API.

| Endpoint | Description |
|----------|-------------|
| `GET /recipes?limit=12` | Fetch list of recipes |
| `GET /recipes/search?q={query}` | Search recipes by name |

Made with ZahraAzizi ❤️
