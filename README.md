# E-Cart Store - React Demo Website

A modern, responsive e-commerce website built with React and Vite, featuring reusable components and beautiful UI design.

## Project Structure

```
myport/
├── src/
│   ├── components/
│   │   ├── Header.jsx          # Reusable header component
│   │   └── Footer.jsx          # Reusable footer component
│   ├── styles/
│   │   ├── Header.css          # Header component styles
│   │   ├── Footer.css          # Footer component styles
│   │   └── App.css             # Main app styles
│   ├── App.jsx                 # Main app component with hero, products, about, contact sections
│   ├── main.jsx                # Entry point
│   └── index.css               # Global styles
├── public/
│   └── index.html              # HTML template
├── package.json                # Project dependencies
├── vite.config.js              # Vite configuration
└── README.md                   # This file
```

## Features

### 1. **Header Component** (Reusable)
- Logo with emoji icon (🛒)
- E-Cart Store branding
- Navigation menu with links
- Sticky positioning
- Responsive design

### 2. **Hero Section**
- Eye-catching gradient background
- Welcome message and tagline
- Centered typography

### 3. **Products Section**
- Grid layout displaying 6 featured products
- Each product card includes:
  - Product emoji icon
  - Product name
  - Price
  - "Add to Cart" button
- Hover effects and smooth transitions
- Responsive grid that adapts to screen size

### 4. **About Us Section**
- Company information
- Clean, readable layout
- White background with subtle shadow

### 5. **Contact Section**
- Three contact cards (Phone, Email, Address)
- Professional layout
- Easy-to-read contact information
- Contact: +1 (800) 123-4567 / support@ecartstore.com

### 6. **Footer Component** (Reusable)
- Company name and description
- Contact information
- Social media links
- Copyright information
- Responsive grid layout

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Navigate to the project folder:
```bash
cd myport
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:3000`

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the project for production
- `npm run preview` - Preview the production build

## Design Highlights

- **Gradient Colors**: Uses modern gradient backgrounds (purple to pink)
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Card Layout**: Product cards with hover effects and shadows
- **Typography**: Clear hierarchy with different font sizes for sections
- **Spacing**: Consistent padding and margins throughout
- **Color Scheme**: Professional purple and white color palette
- **Interactive Elements**: Buttons with hover and active states

## Component Architecture

### Header Component (`Header.jsx`)
```jsx
- Logo and brand name
- Navigation menu
- Styled with Header.css
```

### Footer Component (`Footer.jsx`)
```jsx
- Company info section
- Contact section
- Social media links
- Footer bottom with copyright
- Styled with Footer.css
```

### App Component (`App.jsx`)
- Hero section
- Products grid with 6 items
- About us section
- Contact section
- Imports and uses Header and Footer components

## Product Data

The website features 6 sample products:
1. Wireless Headphones - $79.99 (🎧)
2. Smart Watch - $199.99 (⌚)
3. Laptop Backpack - $49.99 (🎒)
4. Portable Charger - $34.99 (🔋)
5. Phone Case - $19.99 (📱)
6. Camera - $299.99 (📷)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Future Enhancements

- Shopping cart functionality
- Product detail pages
- Search and filter functionality
- User authentication
- Payment integration
- Product reviews and ratings

## Technologies Used

- React 18.2.0
- Vite 5.0.8
- CSS3 (Flexbox, Grid, Gradients)
- ES6+ JavaScript

## Author

E-Cart Store Demo

## License

MIT
