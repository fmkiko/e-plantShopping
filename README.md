# Paradise Nursery - E-Plant Shopping

A modern, responsive React web application for browsing and purchasing a variety of plants online. Built with Vite and Redux Toolkit, this project simulates an e-commerce experience focused on plant lovers.

## Features
- **Landing Page:** Welcoming introduction to Paradise Nursery.
- **Product Catalog:** Browse plants by categories such as Air Purifying, Aromatic, Insect Repellent, Medicinal, and Low Maintenance.
- **Add to Cart:** Easily add plants to your shopping cart.
- **Cart Management:** View, increment, decrement, or remove items from your cart. See the total cost in real time.
- **Responsive Design:** Works well on desktop and mobile devices.
- **About Us:** Learn more about Paradise Nursery and its mission.

## Demo
Live demo: [https://fmkiko.github.io/e-plantShopping/](https://fmkiko.github.io/e-plantShopping/)

## Getting Started

### Prerequisites
- Node.js (v16 or higher recommended)
- npm

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/fmkiko/e-plantShopping.git
   cd e-plantShopping
   ```
2. Install dependencies:
   ```sh
   npm install
   ```

### Running Locally
Start the development server:
```sh
npm run dev
```
Open [http://localhost:5173](http://localhost:5173) in your browser.

### Building for Production
To build the app for production:
```sh
npm run build
```
The output will be in the `dist` folder.

### Deploying to GitHub Pages
To deploy the latest build to GitHub Pages:
```sh
npm run deploy
```

## Project Structure
- `src/` - React components, Redux store, and styles
- `public/` - Static assets
- `index.html` - Main HTML file
- `vite.config.js` - Vite configuration (with correct `base` for GitHub Pages)

## Technologies Used
- [React](https://react.dev/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [Vite](https://vitejs.dev/)
- [gh-pages](https://www.npmjs.com/package/gh-pages)

## License
This project is licensed under the Apache 2.0 License.