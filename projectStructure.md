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
│ ├── App.jsx
│ ├── main.jsx # Entry point
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
