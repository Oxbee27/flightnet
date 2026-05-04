# FlightNet ✈️

A modern, responsive airline booking and travel platform with a clean, user-friendly interface built with HTML, CSS, and Tailwind CSS.

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Installation & Setup](#installation--setup)
- [Development](#development)
- [File Structure](#file-structure)
- [Key Sections](#key-sections)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Project Overview

FlightNet is a comprehensive travel platform designed to simplify flight bookings and travel planning. The platform prioritizes operational clarity and credibility, functioning as a transparent digital hub where users can easily discover destinations, book flights, and manage their travel arrangements.

The project is built as a single-page website with multiple sections showcasing services, popular destinations, testimonials, and subscription options.

## ✨ Features

- **Responsive Design**: Fully responsive layout using Tailwind CSS that works on all devices
- **Navigation Menu**: Intuitive header navigation with destinations, hotels, flights, bookings, and login options
- **Hero Section**: Compelling hero section with call-to-action buttons
- **Service Cards**: Grid-based service showcase with icons and descriptions
  - Calculated Weather
  - Best Flight Options
  - Local Events
  - Customization Services
- **Destination Showcase**: Featured destinations with beautiful imagery and cards
- **Booking Process**: Clear 3-step booking flow visualization
- **Trip Cards**: Current and upcoming trip information with progress tracking
- **Testimonials**: Customer reviews and feedback section
- **Social Links**: Partner logos and social media integration
- **Newsletter Subscription**: Email subscription section with call-to-action
- **Footer**: Comprehensive footer with company info, links, and app store downloads

## 🛠 Tech Stack

- **HTML5**: Semantic markup and structure
- **CSS3**: Styling and layout (compiled from Tailwind)
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development
- **Boxicons**: Icon library for UI elements

## 📁 Project Structure

```
flightnet/
├── index.html              # Main HTML file (landing page)
├── package.json            # Project dependencies and scripts
├── package-lock.json       # Locked dependency versions
├── README.md               # This file
├── .gitignore              # Git ignore rules
├── src/
│   ├── input.css           # Tailwind CSS input file
│   └── output.css          # Compiled CSS output
└── img/                    # Image assets directory
    ├── Logo.png
    ├── plane.png
    ├── card[n].png
    ├── destination-images/
    └── [other assets]
```

## 🚀 Installation & Setup

### Prerequisites

- Node.js (v14 or higher)
- npm (comes with Node.js)

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Oxbee27/flightnet.git
   cd flightnet
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```
   This command watches for changes in `src/input.css` and compiles to `src/output.css`

4. **Open in browser**
   - Simply open `index.html` in your preferred web browser
   - For live reload functionality, use a tool like Live Server (VS Code extension recommended)

## 👨‍💻 Development

### Tailwind CSS Workflow

The project uses Tailwind CSS CLI for development. The setup includes:

- **Input file**: `src/input.css` - Your custom CSS and Tailwind directives
- **Output file**: `src/output.css` - Compiled CSS used by `index.html`

### Watch Mode

Run the development script to automatically recompile CSS on changes:

```bash
npm run dev
```

### Building for Production

To build optimized CSS for production (with purging unused styles):

```bash
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css
```

## 🏗 File Structure Details

### HTML Structure (`index.html`)

The main page is divided into logical sections:

1. **Header** - Navigation bar with logo, menu links, and authentication options
2. **Hero Section** - Main headline and call-to-action with imagery
3. **Services Section** - Grid of 4 service cards highlighting key offerings
4. **Destinations Section** - Featured travel destinations with cards
5. **Booking Process** - Step-by-step guide for booking trips
6. **Trip Cards** - Display of current and upcoming trips with progress indicators
7. **Testimonials** - Customer reviews and social proof
8. **Partners** - Logos of partner companies
9. **Newsletter** - Subscription section for updates
10. **Footer** - Company information, links, and app store buttons

## 📑 Key Sections

### Services Offered

- ✈️ **Best Flight Options** - Premium flight selection and comparison
- 🌤️ **Calculated Weather** - Real-time weather information for destinations
- 🎉 **Local Events** - Discover activities and events at your destination
- 🎨 **Customization** - Personalized travel packages and options

### Destination Showcase

The platform features beautiful destination cards with:
- High-quality destination imagery
- Trip metadata and organizer information
- Interactive icons for location, amenities, and sharing

### Booking Workflow

Three simple steps to book your next trip:
1. Choose your destination
2. Make payment
3. Reach airport on your selected date

## 🎨 Design Features

- **Color Scheme**: Modern palette with accent colors (amber/red accents)
- **Typography**: Multiple font families for hierarchy and visual interest
- **Spacing**: Generous padding and margins for breathing room
- **Icons**: Boxicons library for consistent, scalable vector icons
- **Images**: Optimized images in `img/` directory for various sections
- **Responsive Grid**: Tailwind's grid system adapts to different screen sizes

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the ISC License - see the LICENSE file for details.

## 📞 Contact & Support

For questions, issues, or suggestions:
- Open an issue on the GitHub repository
- Check existing documentation and guides
- Review the FAQ section in the footer

## 🔮 Future Enhancements

Potential improvements for future versions:
- Backend API integration for real booking functionality
- User authentication system
- Dynamic destination database
- Real-time flight search and pricing
- Payment gateway integration
- User account dashboard
- Mobile app version
- Multi-language support

---

**Last Updated**: May 2026  
**Version**: 1.0.0  
**Author**: Oxbee27

Made with ❤️ for seamless travel experiences
