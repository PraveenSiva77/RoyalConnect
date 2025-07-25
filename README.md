# RoyalConnect 2k24 - Rotaract Club Website

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![React](https://img.shields.io/badge/React-18.3.1-blue.svg)](https://reactjs.org/)
[![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub%20Pages-orange.svg)](https://sibisiddharth8.github.io/RoyalConnect2k24)

A modern, responsive website for the Rotaract Club of Coimbatore Royals, showcasing the club's legacy, activities, and community engagement. Built with React and featuring a clean, professional design optimized for all devices.

![RoyalConnect Screenshot](src/assets/Nav_Logo.svg)

## ✨ Features

### 🌐 Modern Web Experience

- **Responsive Design** - Seamlessly adapts to desktop, tablet, and mobile devices
- **Single Page Application** - Smooth navigation with React Router
- **Interactive Components** - Engaging user interface with modern animations
- **Professional Layout** - Clean and organized presentation of club information

### 🏢 Club Showcase

- **Club Information** - Comprehensive details about Rotaract Club of Coimbatore Royals
- **Legacy & History** - Rich heritage from R.I District 3200 to 3201 since 2007
- **Mission Statement** - "Self-development and fellowship through service"
- **Leadership Information** - Current and past leadership details

### 👥 Member Management

- **Member Profiles** - Interactive member showcase with carousel display
- **Social Integration** - WhatsApp and LinkedIn profile links
- **Dynamic Gallery** - Swiper-based member carousel with autoplay
- **Contact Information** - Easy access to member contact details

### 📱 Interactive Sections

- **Hero Section** - Engaging landing area with call-to-action buttons
- **About Section** - Detailed club information and mission
- **Members Section** - Interactive member profiles carousel
- **Releases Section** - Latest updates and announcements
- **Contact Section** - Easy communication channels
- **Footer** - Quick links and additional information

### 🎨 Technical Features

- **Font Awesome Icons** - Professional iconography throughout the site
- **React Icons** - Additional icon library for enhanced UI
- **Slick Carousel** - Smooth carousel functionality
- **Swiper Integration** - Modern touch-enabled carousels
- **CSS Animations** - Smooth transitions and hover effects

## 🛠️ Tech Stack

### Frontend

- **React 18.3.1** - Modern React with latest features and hooks
- **React Router DOM 6.24.1** - Client-side routing for seamless navigation
- **React Icons 5.2.1** - Comprehensive icon library
- **Font Awesome 6.5.2** - Professional iconography
- **Swiper 11.1.4** - Modern carousel and slider functionality
- **React Slick 0.30.2** - Additional carousel components
- **Slick Carousel 1.8.1** - Carousel base library

### Development Tools

- **Create React App 5.0.1** - React development environment
- **React Testing Library** - Comprehensive testing utilities
- **Web Vitals** - Performance monitoring
- **GitHub Pages** - Static site deployment

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager
- Git

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/PraveenSiva77/RoyalConnect.git
   cd RoyalConnect
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start development server**

   ```bash
   npm start
   ```

   Application will be available at `http://localhost:3000`

### 🏗️ Building for Production

1. **Create production build**

   ```bash
   npm run build
   ```

2. **Deploy to GitHub Pages**

   ```bash
   npm run deploy
   ```

   The site will be deployed to: `https://sibisiddharth8.github.io/RoyalConnect2k24`

## 🌐 Live Demo

Visit the live website: [RoyalConnect 2k24](https://sibisiddharth8.github.io/RoyalConnect2k24)

## 📱 Responsive Design

The website is fully responsive and optimized for:

- **Desktop** - Full-featured experience with hover effects
- **Tablet** - Touch-optimized interface with adapted layouts
- **Mobile** - Mobile-first design with optimized performance

## 🗂️ Project Structure

```text
RoyalConnect/
├── public/
│   ├── favicon.ico           # Site favicon
│   ├── index.html           # Main HTML template
│   ├── logo192.png          # PWA icon (192x192)
│   ├── logo512.png          # PWA icon (512x512)
│   ├── manifest.json        # PWA manifest
│   └── robots.txt           # SEO robots file
│
├── src/
│   ├── assets/              # Static assets
│   │   ├── About_Img.png    # About section image
│   │   ├── Home_Image.png   # Hero section image
│   │   ├── Member_Pic.png   # Default member picture
│   │   ├── Nav_Logo.svg     # Navigation logo
│   │   └── *.svg            # Various SVG icons
│   │
│   ├── components/
│   │   ├── about/
│   │   │   ├── About.jsx    # About section component
│   │   │   └── about.css    # About section styles
│   │   ├── contactus/
│   │   │   ├── Contactus.jsx # Contact section component
│   │   │   └── contactus.css # Contact section styles
│   │   ├── footer/
│   │   │   ├── Footer.jsx   # Footer component
│   │   │   └── footer.css   # Footer styles
│   │   ├── getintouch/
│   │   │   ├── Getintouch.jsx # Get in touch component
│   │   │   └── getintouch.css # Get in touch styles
│   │   ├── home/
│   │   │   ├── Home.jsx     # Hero section component
│   │   │   └── home.css     # Hero section styles
│   │   ├── members/
│   │   │   ├── Members.jsx  # Members carousel component
│   │   │   └── members.css  # Members section styles
│   │   ├── navbar/
│   │   │   ├── Navbar.jsx   # Navigation component
│   │   │   └── navbar.css   # Navigation styles
│   │   └── releases/
│   │       ├── Releases.jsx # Releases section component
│   │       └── releases.css # Releases section styles
│   │
│   ├── App.js               # Main application component
│   ├── App.css              # Global application styles
│   ├── index.js             # React application entry point
│   ├── index.css            # Global CSS styles
│   └── reportWebVitals.js   # Performance monitoring
│
├── package.json             # Project dependencies and scripts
├── README.md               # Project documentation
└── LICENSE                 # MIT License
```

## 🎯 Usage

### Navigation

- **Home** - Club introduction and call-to-action
- **About** - Detailed club information and mission
- **Members** - Interactive member profiles carousel
- **Releases** - Latest club updates and announcements
- **Get in Touch** - Contact information and communication channels

### Interactive Features

- **Member Carousel** - Swipe through member profiles
- **Social Links** - Direct access to WhatsApp and LinkedIn
- **Responsive Menu** - Mobile-friendly navigation
- **Smooth Scrolling** - Seamless section transitions

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🏛️ About Rotaract Club of Coimbatore Royals

The Rotaract Club of Coimbatore Royals has a rich legacy from R.I District 3200 to 3201, established in 2007 with the motto of "self-development and fellowship through service." The club was chartered on 29th October 2008, sponsored by the Rotary Club of Coimbatore Texcity.

### Key Highlights

- **Established**: 2007
- **Chartered**: October 29, 2008
- **Sponsor**: Rotary Club of Coimbatore Texcity
- **Current President**: Rtr. P. Malchielraj
- **Motto**: "Self-development and fellowship through service"

## 👨‍💻 Contributors

### Praveenkumar S

- **Role**: Frontend Developer
- **GitHub**: [@PraveenSiva77](https://github.com/PraveenSiva77)

### Sibi Siddharth S

- **Role**: Frontend  Developer
- **GitHub**: [@sibisiddharth8](https://github.com/sibisiddharth8)

## 🙏 Acknowledgments

- React team for the powerful frontend framework
- Create React App for the development environment
- Swiper.js for the beautiful carousel components
- Font Awesome for the professional icons
- GitHub Pages for free hosting
- Rotaract International for the community and service opportunities

## 📞 Contact

For any queries regarding the website or the Rotaract Club:

- **Website**: [RoyalConnect 2k24](https://praveensiva77.github.io/RoyalConnect2k24)
- **GitHub**: [RoyalConnect Repository](https://github.com/PraveenSiva77/RoyalConnect)

---

Made with ❤️ for the Rotaract Club of Coimbatore Royals