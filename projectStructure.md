# React Space Place Planning - Project Structure

react-space-place/
├── .github/ # GitHub specific files
├── public/ # Static files
├── src/ # Source files
│ ├── assets/ # Static assets
│ │ ├── images/ # Image assets
│ ├── components/ # React components
│ │ ├── Header.jsx
│ │ ├── Footer.jsx
│ │ ├── MainViewer.jsx
│ │ ├── NavBar.jsx
│ │ ├── HomeButton.jsx
│ │ ├── CollapsedNavBar.jsx
│ │ ├── NavCard.jsx
│ │ ├── NavCardImg.jsx
│ │ ├── NavCardText.jsx
│ │ ├── NavCardTitle.jsx
│ │ ├── ISSFeed.jsx
│ │ ├── ISSTracker.jsx
│ │ ├── Loading.jsx
│ │ ├── LoadingSpinner.jsx
│ │ ├── Modal.jsx
│ │ ├── ModalContent.jsx
│ │ ├── ModalHeader.jsx
│ │ ├── ISSTrackerHeading.jsx
│ │ ├── ISSTrackerTimes.jsx
│ │ ├── IODNavBar.jsx
│ │ ├── IODPauseButton.jsx
│ │ ├── IODPlayButton.jsx
│ │ ├── IODBackButton.jsx
│ ├── layout/ # React layout
│ │ ├── Layout.jsx
│ ├── pages/ # React pages
│ │ ├── LandingPage.jsx
│ │ ├── SpaceNewsPage.jsx
│ │ ├── NasaIODPage.jsx
│ │ ├── ISSPage.jsx
│ │ ├── SolSysModelPage.jsx
│ ├── store/ # Zustand store
│ │ ├── useStore.js # Main store file
│ ├── styles/ # stylesheets
│ │ ├── index.css # Global styles + Tailwind imports
│ │ ├── App.css
│ │ ├── components/ # Component styles
│ │ │ ├── Header.css
│ │ │ ├── Footer.css
│ │ │ ├── MainViewer.css
│ │ │ ├── NavBar.css
│ │ │ ├── HomeButton.css
│ │ │ ├── CollapsedNavBar.css
│ │ │ ├── NavCard.css
│ │ │ ├── NavCardImg.css
│ │ │ ├── NavCardText.css
│ │ │ ├── NavCardTitle.css
│ │ │ ├── ISSFeed.css
│ │ │ ├── ISSTracker.css
│ │ │ ├── Loading.css
│ │ │ ├── LoadingSpinner.css
│ │ │ ├── Modal.css
│ │ │ ├── ModalContent.css
│ │ │ ├── ModalHeader.css
│ │ │ ├── ISSTrackerHeading.css
│ │ │ ├── ISSTrackerTimes.css
│ │ │ ├── IODNavBar.css
│ │ │ ├── IODPauseButton.css
│ │ │ ├── IODPlayButton.css
│ │ │ ├── IODBackButton.css
│ │ ├── emotion/ # Emotion styled-components
│ │ │ ├── common/ # Reusable styled components
│ │ │ │ ├── buttons.js
│ │ │ │ ├── containers.js
│ │ │ │ ├── typography.js
│ │ │ │ ├── theme.js # Emotion theme configuration
│ │ ├── animations/ # Framer Motion animations
│ │ │ ├── variants/ # Animation variants
│ │ │ │ ├── fadeAnimations.js
│ │ │ │ ├── slideAnimations.js
│ │ │ │ ├── pageAnimations.js
│ │ │ ├── transitions.js # Common transition presets
│ │ ├── App.jsx
│ ├── main.jsx # Entry point
│ ├── api/ # API related files
│ │ ├── axios.js # Axios instance and interceptors
│ │ │ ├── endpoints.js # API endpoints constants
│ │ │ ├── services/ # API service modules
│ │ │ │ ├── issService.js # ISS API related calls
│ │ │ │ ├── nasaService.js # NASA API related calls
│ │ │ │ ├── spaceNewsService.js # Space News API related calls
├── android/ # Capacitor Android platform
├── ios/ # Capacitor iOS platform
├── .env # Environment variables
├── .gitignore
├── capacitor.config.ts # Capacitor configuration
├── index.html # Entry HTML file
├── package.json # Dependencies and scripts
├── tailwind.config.js # Tailwind configuration
├── postcss.config.js # PostCSS configuration for Tailwind
├── vite.config.js # Vite configuration (changed from .ts)
├── routes.js # Route configurations (changed from .tsx)
└── README.md

### Updated Proposed Dependencies:

{
"dependencies": {
"@emotion/react": "^11.11.x",
"@emotion/styled": "^11.11.x",
"axios": "^1.6.x",
"framer-motion": "^10.16.x",
"react": "^18.2.x",
"react-dom": "^18.2.x",
"react-router-dom": "^6.22.x",
"swiper": "^11.0.x",
"zustand": "^4.5.x"
},
"devDependencies": {
"@capacitor/android": "^5.7.x",
"@capacitor/cli": "^5.7.x",
"@capacitor/core": "^5.7.x",
"@capacitor/ios": "^5.7.x",
"@emotion/babel-plugin": "^11.11.x",
"@types/react": "^18.2.x",
"@types/react-dom": "^18.2.x",
"@vitejs/plugin-react": "^4.2.x",
"autoprefixer": "^10.4.x",
"postcss": "^8.4.x",
"tailwindcss": "^3.4.x",
"vite": "^5.1.x"
}
}

<!-- Removed MUI and Three.js for now -->
