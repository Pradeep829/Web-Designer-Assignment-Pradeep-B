# Web-Designer-Assignment-Pradeep-B

# React Product Showcase

A modern product showcase built with React.js. This project features a clean UI that displays a collection of products with names and prices. It includes sections like a hero banner and a dynamically rendered products grid.

## 🚀 Features

- Responsive layout with modular CSS
- Hero section with call-to-action
- Dynamic product listing from structured content data
- Easily extendable structure for categories and testimonials

## 🌐 Live Demo

Check out the live site here: [Netlify Deployment](https://cheerful-croissant-c0a9bc.netlify.app/)

## 💻 Repository

Source code available on GitHub: [Web Designer Assignment Repository](https://github.com/Pradeep829/Web-Designer-Assignment-Pradeep-B)

## 📁 Project Structure

```
myapp/
├── public/
├── src/
│   ├── assets/
│   │   └── images/         # Product images
│   ├── components/         # (if applicable)
│   ├── App.js              # Main component with hero + products section
│   ├── app.module.css      # Scoped styles
│   └── content.js          # Centralized content data
```

## 🛠️ Installation & Usage

```bash
npm install
npm start
```

The app will be served at `http://localhost:3000`.

## 📦 Build

```bash
npm run build
```

Generates an optimized production build.

## 📝 Content Sample

```js
const content = {
  products: [
    { id: 1, name: 'Altiplano Ultimate', price: '$29.99', imageUrl: 'altiplano.webp' },
    { id: 2, name: 'Product B', price: '$49.99', imageUrl: 'altiplano.webp' },
    { id: 3, name: 'Product C', price: '$19.99', imageUrl: 'altiplano.webp' },
    { id: 4, name: 'Product D', price: '$39.99', imageUrl: 'altiplano.webp' }
  ],
  hero: {
    title: 'Discover Our New Collection',
    subtitle: 'Elevate your style with our premium products.',
    buttonText: 'Shop Now',
  }
};
```

## 🧱 Tech Stack

- React.js
- CSS Modules
- Netlify (for deployment)
- Visual Studio Code

## ✨ Customization

You can easily add more products by updating the `content.js` file. To add a new image, place it in `src/assets/images` and reference it in the `imageUrl` of your product object.

## 📄 License

This project is intended for educational/demo purposes.

## 🙋‍♂️ Author

Developed by **Pradeep B**.

---

