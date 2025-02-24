# Fast React Pizza Co.

A responsive React-based pizza menu application that showcases a restaurant's pizza offerings. The app features a dynamic menu display with real-time availability status, pricing, and detailed descriptions of each pizza. It also includes a smart footer that automatically updates based on the restaurant's operating hours.

## Features
- Dynamic pizza menu with images and descriptions
- Real-time availability status for menu items
- Responsive design
- Automatic opening hours display
- Interactive ordering system

## Technologies
- React
- CSS
- JavaScript

App
├── Header
│   └── h1 "Fast React Pizza Co."
│
├── Menu
│   ├── h2 "Our Menu"
│   └── Pizza (mapped from pizzaData)
│       ├── img
│       └── div
│           ├── h3 (pizza name)
│           ├── p (ingredients)
│           └── span (price)
│
└── Footer
    └── Order (conditionally rendered)
        ├── p (opening hours message)
        └── button "Order"
