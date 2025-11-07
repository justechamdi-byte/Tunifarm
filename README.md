# TuniFarm - Tunisian Agriculture Marketplace

A complete mobile-first web application for Tunisia's agricultural marketplace, connecting farmers, vendors, and transporters.

## 🌾 Project Overview

TuniFarm is a comprehensive agricultural marketplace platform designed specifically for Tunisia's farming community. The application facilitates direct connections between farmers, vendors, and transporters, streamlining the agricultural supply chain.

## 📱 Features

### For Farmers
- **Product Management**: Add, edit, and manage agricultural products
- **Order Tracking**: Monitor incoming orders and their status
- **Analytics Dashboard**: View sales statistics and performance metrics
- **Notifications**: Real-time updates on orders and messages

### For Vendors
- **Product Discovery**: Browse and search through available products
- **Advanced Filtering**: Filter by category, location, price, and more
- **Order Management**: Place orders and track delivery status
- **Wishlist**: Save favorite products for later

### For Transporters
- **Delivery Management**: Accept and manage delivery requests
- **Route Optimization**: View delivery routes and optimize paths
- **Earnings Tracking**: Monitor income and performance metrics
- **Real-time Updates**: Live status updates for deliveries

### For Administrators
- **User Management**: Oversee all platform users
- **Product Approval**: Review and approve product listings
- **Analytics Dashboard**: Comprehensive platform insights
- **System Settings**: Configure platform parameters

## 🎨 Design System

The application uses a comprehensive design system with:

### Color Palette
- **Primary**: #4CAF50 (Green)
- **Secondary**: #8BC34A (Light Green)
- **Accent**: #F9A825 (Amber)
- **Background**: #F5F5F5 (Light Gray)
- **Surface**: #FFFFFF (White)

### Typography
- **Font Family**: Poppins (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700

### Spacing System
- **xs**: 4px
- **sm**: 8px
- **md**: 16px
- **lg**: 24px
- **xl**: 32px

## 📁 Project Structure

```
Tunifarm/
├── index.html              # Landing page
├── farmer.html             # Farmer dashboard
├── vendor.html            # Vendor dashboard
├── transporter.html        # Transporter dashboard
├── admin.html              # Admin dashboard
├── profile.html            # Profile & settings
├── css/
│   ├── root.css           # CSS variables and base styles
│   ├── utilities.css      # Utility classes
│   └── style.css          # Component styles
├── assets/
│   └── images/            # Image assets
└── README.md              # Project documentation
```

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Tunifarm
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - No build process or dependencies required

3. **Development**
   - All files are ready to use
   - CSS is modular and well-organized
   - JavaScript is minimal and focused on UI interactions

## 📱 Mobile-First Design

The application is designed with a mobile-first approach:

- **Responsive Grid System**: Adapts to different screen sizes
- **Touch-Friendly Interface**: Optimized for mobile interactions
- **Progressive Enhancement**: Works on all devices
- **Fast Loading**: Optimized for mobile networks

## 🎯 Key Components

### Navigation
- **Header**: Logo and user actions
- **Footer Navigation**: Primary app navigation
- **Breadcrumbs**: Contextual navigation

### Cards & Content
- **Product Cards**: Showcase agricultural products
- **Order Cards**: Display order information
- **Stats Cards**: Show key metrics
- **User Cards**: Display user information

### Forms & Inputs
- **Search Bars**: Product and content search
- **Filter Chips**: Category and attribute filtering
- **Form Inputs**: User data collection
- **Toggle Switches**: Settings and preferences

### Modals & Overlays
- **Product Details**: Full product information
- **Order Forms**: Order placement and management
- **Settings Panels**: User preferences
- **Confirmation Dialogs**: Action confirmations

## 🌍 Internationalization

The application supports multiple languages:
- **English** (Default)
- **Français** (French)
- **العربية** (Arabic)

## 🔧 Customization

### CSS Variables
All design tokens are defined in `css/root.css`:
```css
:root {
  --color-primary: #4CAF50;
  --color-secondary: #8BC34A;
  --spacing-md: 16px;
  --font-primary: 'Poppins', sans-serif;
}
```

### Utility Classes
Common patterns are available as utility classes in `css/utilities.css`:
```css
.flex { display: flex; }
.text-center { text-align: center; }
.btn-primary { background: var(--color-primary); }
```

## 📊 Browser Support

- **Modern Browsers**: Chrome, Firefox, Safari, Edge
- **Mobile Browsers**: iOS Safari, Chrome Mobile
- **Progressive Enhancement**: Graceful degradation for older browsers

## 🚀 Performance

- **Optimized Images**: Efficient image handling
- **Minimal JavaScript**: Fast loading and execution
- **CSS Optimization**: Modular and efficient styles
- **Mobile Performance**: Optimized for mobile devices

## 📝 License

This project is created for educational and demonstration purposes.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

For questions or support, please contact the development team.

---

**TuniFarm** - Connecting Tunisia's Agricultural Community 🌾
