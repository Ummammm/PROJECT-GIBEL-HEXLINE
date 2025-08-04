# 🚀 PROJECT GIBEL - HEXLINE

A cyberpunk-themed e-commerce platform built with HTML, CSS, JavaScript, and Tailwind CSS. Experience the future of online shopping with a dark, neon-accented interface that transports users to a dystopian digital marketplace.


## 🌟 Features

### 🎨 **Visual Design**
- **Cyberpunk Aesthetic**: Dark theme with neon green (#00FFAA) and pink (#FF2C79) accents
- **Responsive Design**: Fully responsive across all device sizes
- **Smooth Animations**: Fade-in effects, hover animations, and interactive elements
- **Custom Typography**: IBM Plex Sans font family for a modern, tech-focused look

### 🛒 **E-commerce Functionality**
- **Shopping Cart System**: Add items to stash with quantity management
- **Product Categories**: Multiple product types with filtering capabilities
- **Payment Integration**: Complete checkout flow with shipping information
- **Inventory Management**: Real-time stock tracking and availability

### 🔧 **Technical Features**
- **Local Storage**: Persistent cart data across browser sessions
- **Dynamic Content**: JSON-based product data management
- **Modal Systems**: Interactive product details and payment confirmation
- **Form Validation**: Comprehensive input validation and user feedback

## 📁 Project Structure

```
PROJECT GIBEL - HEXLINE/
├── 📄 HTML Pages
│   ├── index.html              # Landing page
│   ├── main.html               # Stockpile (main product catalog)
│   ├── mostwanted.html         # Most wanted items
│   ├── justsmuggled.html       # Recently added items
│   ├── loadbayxiii.html        # Weapons and equipment
│   ├── dropcrates.html         # Bundle packages
│   ├── stash.html              # Shopping cart
│   ├── payment.html            # Checkout and payment
│   └── linkin.html             # Login page
├── 📊 Data Files
│   ├── stockpile.json          # Main product catalog
│   ├── mostwanted.json         # Featured items
│   ├── weapons.json            # Weapons and equipment
│   ├── dropcrates.json         # Bundle packages
│   └── justsmuggled.json       # Recent additions
├── 🎨 Assets
│   ├── placeholder/            # Background images
│   ├── products/               # Product images
│   └── [other asset folders]
└── 📖 README.md               # This file
```

## 🎯 Pages Overview

### 🏠 **Index Page** (`index.html`)
- Landing page with project introduction
- Navigation to all major sections
- Cyberpunk aesthetic showcase

### 📦 **Stockpile** (`main.html`)
- **Main product catalog** with comprehensive filtering
- **Categories**: Neurotech, Occult-tech, Stealth-gear, Biochem/Serum, Glitchware & Scripts, Fragments & Relics
- **Filters**: By category, price, rating, and type
- **Product Cards**: Rating, score, price, and "PUT TO STASH" functionality
- **Modal Popups**: Detailed product information and quick add to cart

### ⭐ **Most Wanted** (`mostwanted.html`)
- **Featured items** with high ratings
- **Signature weapons** carousel display
- **Stockpile items** grid layout
- **Advanced filtering** by weapon type, price, and ratings
- **Interactive detail panels** for item information

### 🆕 **Just Smuggled** (`justsmuggled.html`)
- **Recently added items** to the catalog
- **Grid layout** with availability status
- **Modal system** for detailed product views
- **Real-time availability** tracking

### 🔫 **Loadbay XIII** (`loadbayxiii.html`)
- **Weapons and equipment** specialized section
- **Signature weapons** carousel with 3-item slides
- **Stockpile weapons** grid display
- **Comprehensive filtering** by weapon type, price, and ratings
- **Interactive tooltips** with product descriptions

### 📦 **Dropcrates** (`dropcrates.html`)
- **Bundle packages** and special offers
- **Modal system** showing bundle contents
- **Rating and stock** information
- **Bundle-specific** cart functionality

### 🛍️ **Stash** (`stash.html`)
- **Shopping cart** management
- **Quantity controls** (increase/decrease/remove)
- **Bundle support** for special items
- **Grand total** calculation
- **Clear stash** functionality
- **Proceed to checkout** integration

### 💳 **Payment** (`payment.html`)
- **Two-panel layout**: Shipping information and cart review
- **Delivery options**: Delivery vs Pick-up
- **Form validation** for shipping details
- **Terms and conditions** acceptance
- **Payment processing** simulation
- **Success modal** with confirmation

### 🔐 **Link In** (`linkin.html`)
- **Login page** with cyberpunk styling
- **Form validation** for credentials
- **Interactive background** elements
- **Success feedback** and redirect

## 🛠️ Technical Implementation

### **Frontend Technologies**
- **HTML5**: Semantic markup and structure
- **CSS3**: Custom styling with Tailwind CSS framework
- **JavaScript (ES6+)**: Dynamic functionality and interactivity
- **Tailwind CSS**: Utility-first CSS framework for rapid development

### **Key JavaScript Features**
- **Local Storage Management**: Persistent cart data
- **Event Delegation**: Efficient event handling
- **Dynamic Content Loading**: JSON-based product data
- **Modal Systems**: Interactive overlays
- **Form Validation**: Client-side input validation
- **Animation Systems**: Smooth transitions and effects

### **Data Management**
- **JSON Files**: Structured product data
- **Local Storage**: Browser-based data persistence
- **Dynamic Rendering**: Real-time content updates

## 🚀 Getting Started

### **Prerequisites**
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (for development)

### **Installation**
1. **Clone or download** the project files
2. **Navigate** to the project directory
3. **Start a local server** (recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```
4. **Open** `http://localhost:8000` in your browser

### **File Structure Setup**
Ensure all files are in the correct directory structure as shown above. The project uses relative paths for assets and data files.

## 🎮 Usage Guide

### **Shopping Flow**
1. **Browse Products**: Navigate through different sections (Stockpile, Most Wanted, etc.)
2. **Add to Stash**: Click "PUT TO STASH" buttons to add items to cart
3. **Manage Cart**: Visit the Stash page to adjust quantities or remove items
4. **Checkout**: Click "PROCEED →" to go to payment page
5. **Complete Purchase**: Fill shipping information and complete payment

### **Navigation**
- **Navbar**: Consistent navigation across all pages
- **Stash Counter**: Real-time cart item count
- **Active Page**: Visual indication of current section

### **Filtering and Search**
- **Category Filters**: Filter by product categories
- **Price Sorting**: Sort by lowest or highest price
- **Rating Filters**: Filter by star ratings
- **Type Selection**: Choose between bundle and individual items

## 🎨 Customization

### **Colors**
The project uses a consistent color scheme defined in Tailwind config:
- **Neon Green**: `#00FFAA` - Primary accent color
- **Cyber Pink**: `#FF2C79` - Secondary accent color
- **Cyber Black**: `#0a0a0a` - Background color
- **Glow White**: `#f0f0f0` - Text color

### **Styling**
- **Tailwind Classes**: Utility-first approach for rapid styling
- **Custom CSS**: Additional styles in `<style>` tags
- **Animations**: CSS keyframes for smooth transitions

### **Content Management**
- **JSON Files**: Easy product data management
- **Image Assets**: Organized in asset folders
- **Text Content**: Directly editable in HTML files

## 🔧 Development

### **Adding New Products**
1. **Update JSON files** in the `data/` directory
2. **Add product images** to appropriate asset folders
3. **Test functionality** across all pages

### **Modifying Styles**
1. **Tailwind Classes**: Use utility classes for quick styling
2. **Custom CSS**: Add styles in `<style>` tags
3. **Responsive Design**: Test across different screen sizes

### **Extending Functionality**
1. **JavaScript Functions**: Add new features in script tags
2. **Event Listeners**: Use event delegation for dynamic content
3. **Local Storage**: Extend data persistence as needed

## 🌐 Browser Compatibility

- **Chrome**: 80+
- **Firefox**: 75+
- **Safari**: 13+
- **Edge**: 80+

## 📱 Responsive Design

The project is fully responsive and optimized for:
- **Desktop**: 1920px and above
- **Laptop**: 1024px - 1919px
- **Tablet**: 768px - 1023px
- **Mobile**: 320px - 767px

## 🎯 Future Enhancements

### **Planned Features**
- **User Authentication**: Real login system
- **Payment Gateway**: Actual payment processing
- **Search Functionality**: Product search and filtering
- **User Profiles**: Account management
- **Order History**: Purchase tracking
- **Wishlist**: Save items for later

### **Technical Improvements**
- **Backend Integration**: Server-side functionality
- **Database**: Persistent data storage
- **API Integration**: External service connections
- **Performance Optimization**: Code splitting and lazy loading

## 🤝 Contributing

1. **Fork** the project
2. **Create** a feature branch
3. **Make** your changes
4. **Test** thoroughly
5. **Submit** a pull request

## 📄 License

This project is open source for learning purposes

## 👨‍💻 Author

**PROJECT GIBEL - HEXLINE**
- A cyberpunk-themed e-commerce experience
- Built with modern web technologies
- Focus on user experience and visual appeal

## 🙏 Acknowledgments

- **Tailwind CSS** for the utility-first framework
- **IBM Plex Sans** for the typography
- **Cyberpunk aesthetic** inspiration from various sources
- **Modern web development** best practices

---

**Experience the future of e-commerce with HEXLINE - where cyberpunk meets convenience!** 🚀 
