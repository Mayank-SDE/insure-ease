# insure-ease 
## Project Frontend Structure
├── public
│   └── index.html
├── src
│   ├── assets
│   │   └── images
│   ├── components
│   │   ├── common
│   │   │   ├── Header.jsx
│   │   │   ├── Footer.jsx
│   │   │   └── ProtectedRoute.jsx
│   │   ├── client
│   │   │   ├── PolicyList.jsx
│   │   │   ├── PolicyDetails.jsx
│   │   │   ├── PremiumCalculator.jsx
│   │   │   ├── Profile.jsx
│   │   │   └── PurchaseHistory.jsx
│   │   └── admin
│   │       ├── Dashboard.jsx
│   │       ├── ManagePolicies.jsx
│   │       ├── ManageClaims.jsx
│   │       └── CustomerCRUD.jsx
│   ├── pages
│   │   ├── Home.jsx
│   │   ├── Login.jsx
│   │   ├── Register.jsx
│   │   ├── ClientDashboard.jsx
│   │   └── AdminDashboard.jsx
│   ├── redux
│   │   ├── store.js
│   │   ├── slices
│   │   │   ├── authSlice.js
│   │   │   ├── policySlice.js
│   │   │   ├── profileSlice.js
│   │   │   └── adminSlice.js
│   ├── services
│   │   ├── api.js
│   │   ├── authService.js
│   │   ├── policyService.js
│   │   └── paymentService.js
│   ├── utils
│   │   ├── constants.js
│   │   ├── helpers.js
│   │   └── validation.js
│   ├── App.js
│   ├── index.js
│   ├── routes.js
│   └── styles
│       ├── main.css
│       └── theme.css
├── .env
├── .gitignore
├── package.json
└── README.md