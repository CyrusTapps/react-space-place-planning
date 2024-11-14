# React Space Place - Project Structure V2

react-space-place/
├── src/
│   ├── components/
│   │   ├── common/
│   │   │   ├── IconButton/
│   │   │   │   ├── IconButton.jsx        # Reusable icon button wrapper
│   │   │   │   └── IconButton.css
│   │   │   ├── Navigation/
│   │   │   │   ├── Drawer/
│   │   │   │   │   ├── Drawer.jsx
│   │   │   │   │   └── Drawer.css
│   │   │   │   ├── NavBar.jsx
│   │   │   │   └── NavBar.css
│   │   │   ├── Card/
│   │   │   │   ├── NavCard.jsx           # Card component with image/text areas
│   │   │   │   └── NavCard.css
│   │   │   ├── Loading/
│   │   │   │   ├── Loading.jsx
│   │   │   │   └── Loading.css
│   │   │   └── Modal/
│   │   │       ├── Modal.jsx
│   │   │       └── Modal.css
│   │   ├── features/
│   │   │   ├── SpaceNews/
│   │   │   │   ├── NewsCard.jsx
│   │   │   │   ├── NewsCard.css
│   │   │   │   ├── NewsList.jsx
│   │   │   │   └── NewsList.css
│   │   │   ├── NASA/
│   │   │   │   ├── ImageViewer.jsx       # Main image display component
│   │   │   │   ├── ImageViewer.css
│   │   │   │   ├── IODNavBar.jsx         # Navigation controls using IconButton
│   │   │   │   └── IODNavBar.css
│   │   │   ├── ISS/
│   │   │   │   ├── ISSFeed.jsx           # Live feed component
│   │   │   │   ├── ISSFeed.css
│   │   │   │   ├── ISSTracker.jsx        # Location tracking component
│   │   │   │   └── ISSTracker.css
│   │   │   └── SolarSystem/
│   │   │       ├── ModelViewer.jsx
│   │   │       └── ModelViewer.css
│   ├── layouts/
│   │   ├── MainLayout.jsx                 # Main app layout wrapper
│   │   └── MainLayout.css
│   ├── pages/
│   │   ├── Landing/
│   │   │   ├── LandingPage.jsx
│   │   │   └── LandingPage.css
│   │   ├── SpaceNews/
│   │   │   ├── SpaceNewsPage.jsx
│   │   │   └── SpaceNewsPage.css
│   │   ├── NasaImage/
│   │   │   ├── NasaImagePage.jsx
│   │   │   └── NasaImagePage.css
│   │   ├── ISS/
│   │   │   ├── ISSPage.jsx
│   │   │   └── ISSPage.css
│   │   └── SolarSystem/
│   │       ├── SolarSystemPage.jsx
│   │       └── SolarSystemPage.css
│   ├── styles/
│   │   ├── base/
│   │   │   ├── reset.css                  # CSS reset
│   │   │   ├── variables.css              # CSS custom properties
│   │   │   ├── typography.css             # Typography styles
│   │   │   └── animations.css             # Common animations
│   │   ├── utils/
│   │   │   ├── spacing.css                # Spacing utilities
│   │   │   ├── flexbox.css                # Flexbox utilities
│   │   │   └── grid.css                   # Grid utilities
│   │   └── index.css                      # Main stylesheet
│   ├── services/
│   │   ├── api/
│   │   │   ├── axios.js                   # Axios instance
│   │   │   └── endpoints.js               # API endpoints
│   │   ├── spaceNews.js                   # Space news API service
│   │   ├── nasa.js                        # NASA API service
│   │   └── iss.js                         # ISS tracking API service
│   ├── store/
│   │   ├── slices/
│   │   │   ├── navigationSlice.js         # Navigation state
│   │   │   ├── newsSlice.js              # News data state
│   │   │   └── imageSlice.js             # Image viewer state
│   │   └── index.js                       # Zustand store setup
│   ├── utils/
│   │   ├── formatters.js                  # Data formatting utilities
│   │   └── constants.js                   # App constants
│   ├── App.jsx
│   ├── App.css
│   ├── main.jsx
│   └── routes.jsx                         # Route definitions with explicit imports
├── public/
│   └── assets/
│       └── images/
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
└── README.md

## Dependencies
