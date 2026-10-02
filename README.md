# Shoe Store (React + useState)

An online shoe store built with React. Browse shoes on the left, add them to a shopping cart on the right, change quantities, and see the running total. Cart state is managed with the `useState` hook.

## Features

- **Display shoes**: each shoe shows an image, name and price.
- **Add to Cart**: adds the shoe, or increases its quantity if it is already in the cart.
- **Remove from Cart**: the `−` button decreases the quantity; the item is removed when it reaches 0.
- **Cart total**: the total cost of all items updates automatically.

## Tech Stack

- React (hooks: `useState`)
- Vite
- Plain CSS

## Project Structure

```
shoe-store/
├── public/
│   └── images/
│       ├── shoe.avif
│       ├── shoe1.avif
│       ├── shoe2.jpg
│       ├── shoe3.avif
│       ├── shoe4.avif
│       └── shoe5.jpg
├── src/
│   ├── App.jsx
│   ├── App.css
│   └── main.jsx
├── package.json
└── README.md
```

## Available Scripts

| Command | What it does |
| --- | --- |
| `npm run dev` | Starts the development server |
| `npm run build` | Creates a production build in `dist/` |
| `npm run preview` | Previews the production build locally |

how to run: 
open the files and run command in terminal
npm run dev

Open the URL shown in the terminal 
