# Foodie Hub - Korean Cuisine Website

A responsive, single-page website for Foodie Hub, a Korean cuisine food ordering platform. Built with Bootstrap 5 and custom CSS, featuring a Korean cuisine theme with authentic dishes and restaurants.

## 🍜 Features

### Core Functionality
- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Korean Cuisine Focus**: Specialized in authentic Korean dishes and restaurants
- **Canadian Korean Restaurants**: Real addresses and contact information for authentic Korean restaurants across Canada
- **No JavaScript Required**: Pure HTML and CSS implementation as per assignment requirements
- **Bootstrap 5**: Modern, mobile-first framework for consistent styling

### Website Sections

#### 1. Navigation Bar
- Responsive Bootstrap navbar with Foodie Hub logo
- Navigation links: Home, Restaurants, About, Contact
- Mobile hamburger menu for smaller screens
- Fixed positioning for easy navigation

#### 2. Hero Section
- Full-screen banner with Korean cuisine background image
- Centered overlay text welcoming users
- Call-to-action button to explore restaurants
- Responsive text sizing for different screen sizes

#### 3. Restaurants List
- 6 Korean restaurants with unique specialties:
  - **Seoul BBQ House**: Authentic Korean BBQ
  - **K-Chicken Palace**: Korean fried chicken
  - **Bibimbap Express**: Rice bowls and traditional dishes
  - **Hot Pot Korea**: Korean hot pot and stews
  - **Street Food Seoul**: Korean street food
  - **Sweet Seoul**: Traditional Korean desserts
- Responsive grid layout (4/2/1 cards per row)
- Hover effects with shadow and scale animations
- "View Menu" buttons linking to individual restaurant pages

#### 4. Individual Restaurant Menus
- Dedicated pages for each restaurant with detailed menus
- Korean dish names with English descriptions
- Pricing information
- Availability badges (Available/Unavailable)
- Responsive card layout
- Back navigation to main page

#### 5. Order Form
- Customer information fields (name, phone)
- Restaurant selection dropdown
- Menu items with quantity inputs
- Responsive form layout
- Form validation styling

#### 6. About Section
- Two-column layout on desktop
- Korean cuisine image and descriptive text
- Mobile-responsive stacking

#### 7. Canadian Korean Restaurants
- Real addresses and contact information for authentic Korean restaurants
- Coverage of major Canadian cities: Toronto, Vancouver, Calgary, Montreal, Edmonton, Ottawa
- Korea Town locations and popular restaurant names
- Responsive card layout showcasing Canadian Korean cuisine scene

#### 8. Contact/Footer
- Contact information (email, phone, address)
- Social media icons using Bootstrap Icons
- Responsive footer layout

## 🎨 Design Features

### Korean Theme
- Red and gold color scheme inspired by Korean culture
- Traditional Korean dish names and descriptions
- Authentic Korean cuisine focus

### Responsive Design
- **Desktop (1200px+)**: 4 restaurant cards per row, full navigation
- **Large Tablets (1024px-1199px)**: 3 restaurant cards per row, optimized spacing
- **Tablets (768px-1023px)**: 2 restaurant cards per row, collapsed navigation
- **Large Phones (576px-767px)**: 1 restaurant card per row, hamburger menu
- **Small Phones (480px-575px)**: Optimized for small screens
- **Extra Small Phones (360px-479px)**: Compact layout for very small screens

### Interactive Elements
- Smooth hover effects on cards and buttons
- CSS transitions for enhanced user experience
- Custom scrollbar styling
- Focus states for accessibility

### Typography & Spacing
- Responsive font sizes using CSS media queries
- Consistent spacing with Bootstrap utilities
- Korean-themed color palette

## 📁 File Structure

```
foodie-hub/
├── index.html              # Main homepage
├── menu-seoul-bbq.html     # Seoul BBQ House menu
├── menu-k-chicken.html     # K-Chicken Palace menu
├── menu-bibimbap.html      # Bibimbap Express menu
├── menu-hot-pot.html       # Hot Pot Korea menu
├── menu-street-food.html   # Street Food Seoul menu
├── menu-desserts.html      # Sweet Seoul menu
├── styles.css              # Custom CSS styles
└── README.md              # Project documentation
```

## 🍽️ Korean Cuisine Featured

### BBQ & Grilled Dishes
- Bulgogi (Korean BBQ Beef)
- Galbi (Beef Short Ribs)
- Samgyeopsal (Pork Belly)
- Dakgalbi (Spicy Chicken)

### Rice & Noodle Dishes
- Bibimbap (Mixed Rice Bowl)
- Japchae (Glass Noodles)
- Kimchi Fried Rice
- Kimbap (Korean Sushi)

### Hot Pot & Stews
- Kimchi Jjigae (Kimchi Stew)
- Doenjang Jjigae (Soybean Stew)
- Sundubu Jjigae (Soft Tofu Stew)
- Budae Jjigae (Army Stew)

### Street Food
- Tteokbokki (Spicy Rice Cakes)
- Hotteok (Sweet Pancakes)
- Bungeoppang (Fish Bread)
- Odeng (Fish Cake)

### Desserts
- Patbingsu (Red Bean Shaved Ice)
- Yakgwa (Honey Cookies)
- Sikhye (Sweet Rice Drink)
- Injeolmi (Rice Cake)

## 🚀 How to Use

1. **Open the Website**: Open `index.html` in any modern web browser
2. **Navigate**: Use the navigation menu to explore different sections
3. **Browse Restaurants**: Click on restaurant cards to view their menus
4. **View Menus**: Each restaurant has a dedicated menu page with detailed dishes
5. **Place Orders**: Use the order form on the main page to simulate ordering

## 🛠️ Technical Implementation

### Technologies Used
- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling and responsive design
- **Bootstrap 5**: Framework for responsive grid and components
- **Bootstrap Icons**: Icon library for UI elements

### CSS Features
- CSS Custom Properties (variables) for consistent theming
- CSS Grid and Flexbox for layouts
- CSS Transitions and Transforms for animations
- Media queries for responsive design
- Custom scrollbar styling

### Responsive Breakpoints
- **Large screens**: 4 columns, full navigation
- **Medium screens**: 2 columns, collapsed navigation
- **Small screens**: 1 column, hamburger menu

## 📱 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Assignment Requirements Met

✅ **Responsive Bootstrap navbar** with logo and navigation  
✅ **Hero section** with background image and overlay text  
✅ **Restaurant cards** (6 minimum) with responsive grid  
✅ **Menu sections** with availability badges  
✅ **Order form** with customer info and menu selection  
✅ **About section** with two-column layout  
✅ **Contact/Footer** with social media icons  
✅ **No JavaScript** - pure HTML/CSS implementation  
✅ **Bootstrap 5 CDN** integration  
✅ **Custom CSS** for responsive design and Korean theme  
✅ **Clean, well-structured code** with comments  
✅ **Smooth scroll** effect with CSS  
✅ **Hover effects** on cards and buttons  

## 🌟 Bonus Features Implemented

- **Multiple HTML pages** for individual restaurant menus
- **Korean cuisine focus** with authentic dish names
- **Availability badges** (green/red) for menu items
- **Custom color scheme** inspired by Korean culture
- **Smooth animations** and transitions
- **Accessibility features** with focus states
- **Professional typography** and spacing

## 📸 Screenshots

The website is fully responsive and should be tested on:
- **Desktop**: 1920x1080 and larger
- **Tablet**: 768px width
- **Mobile**: 375px width

## 🎨 Customization

To customize the website:
1. **Colors**: Modify CSS variables in `:root`
2. **Images**: Replace Unsplash URLs with your own images
3. **Content**: Update restaurant names, descriptions, and menu items
4. **Styling**: Modify `styles.css` for custom appearance

## 📞 Contact

For questions about this project or Korean cuisine recommendations, feel free to reach out!

---

*Built with ❤️ for Korean cuisine lovers everywhere* 