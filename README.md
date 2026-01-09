# 🌿 GreenDen - Plant Shop Website

A beautiful, responsive plant shop website built with HTML and Tailwind CSS. GreenDen showcases a modern e-commerce design for a plant nursery business.

## ✨ Features

- **Responsive Design** - Fully responsive layout that works on desktop, tablet, and mobile devices
- **Modern UI** - Clean and contemporary design using Tailwind CSS utility classes
- **Product Showcase** - Beautiful product cards displaying plants with images and descriptions
- **Easy Navigation** - User-friendly navigation menu and smooth scrolling
- **Fast Loading** - Optimized HTML structure with CDN-based Tailwind CSS
- **Contact Form** - Functional contact section for customer inquiries
- **About Section** - Information about the business and services

## 🚀 Technologies Used

- **HTML5** - Semantic markup for better SEO and accessibility
- **Tailwind CSS** - Utility-first CSS framework for rapid UI development
- **Font Awesome** (optional) - Icons for enhanced visual appeal
- **Google Fonts** (optional) - Custom typography

## 📁 Project Structure

```
greenden-website/
│
├── index.html          # Main homepage
├── about.html          # About page (if separate)
├── products.html       # Products page (if separate)
├── contact.html        # Contact page (if separate)
├── assets/
│   ├── images/         # Product images and graphics
│   └── icons/          # Icon files
├── css/
│   └── custom.css      # Any custom CSS (optional)
└── README.md           # Project documentation
```

## 🛠️ Installation & Setup

1. **Clone the repository**
   ```bash
   https://github.com/theja1212-hub/Greenden-Tailwind-.git
   ```

2. **Navigate to project directory**
   ```bash
   cd greenden-website
   ```

3. **Open in browser**
   - Simply open `index.html` in your preferred web browser
   - Or use a local server:
   ```bash
 
   # Using Node.js (http-server)
   npx http-server
   ```



## 🎨 Tailwind CSS Setup

This project uses Tailwind CSS via CDN for simplicity:

```html
<script src="https://cdn.tailwindcss.com"></script>
```

### For Production (Optional)

For better performance in production, consider setting up Tailwind CLI:

1. **Install Tailwind CSS**
   ```bash
   npm install -D tailwindcss
   npx tailwindcss init
   ```

2. **Configure template paths** in `tailwind.config.js`
   ```javascript
   module.exports = {
     content: ["./**/*.html"],
     theme: {
       extend: {},
     },
     plugins: [],
   }
   ```

3. **Build CSS**
   ```bash
   npx tailwindcss -i ./src/input.css -o ./css/output.css --watch
   ```

## 📱 Responsive Breakpoints

The website is responsive across all devices using Tailwind's breakpoint system:

- **Mobile**: < 640px
- **Tablet**: 640px - 1024px
- **Desktop**: > 1024px

## 🌟 Key Sections

1. **Hero Section** - Eye-catching landing area with call-to-action
2. **Featured Products** - Showcase of popular plants
3. **About Us** - Company information and mission
4. **Services** - Plant care services offered
5. **Testimonials** - Customer reviews and feedback
6. **Contact** - Contact form and location information
7. **Footer** - Social links and additional navigation

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**THEJA NAVEEN S**
- GitHub: [theja-1212](https://github.com/theja1212-hub/Greenden-Tailwind-.git)
- Email: thejanaveen1212@gmail.com

## 🙏 Acknowledgments

- Tailwind CSS team for the amazing framework
- Plant images from [Unsplash](https://unsplash.com) or [Pexels](https://pexels.com)
- Inspiration from various plant shop websites


Check out the live demo: [GreenDen Website](https://yourusername.github.io/greenden-website)

---

⭐ Star this repository if you found it helpful!

🐛 Found a bug? [Report it here](https://github.com/yourusername/greenden-website/issues)
