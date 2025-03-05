# Metro Route Optimization System

A web-based metro route optimization system that helps users find the best routes between stations, including fare calculation and alternative paths.

## Features

- Interactive metro station network visualization
- Shortest path finding using Dijkstra's algorithm
- Alternative route suggestions
- Real-time fare calculation with student and senior citizen discounts
- Responsive design for all devices
- Interactive route selection and highlighting
- Distance-based zone fare system

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- vis.js Network for graph visualization

## Getting Started

1. Clone the repository

```bash
git clone [your-repository-url]
```

2. Open `index.html` in your web browser

## Usage

1. Click "Get Started" and enter your details
2. Select your starting and destination stations
3. View the suggested routes with:
   - Distance information
   - Fare calculation
   - Alternative paths
4. Click on any route to highlight it on the map

## Project Structure

```
metro-route-optimization/
│
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js          # Main JavaScript file
└── README.md          # Project documentation
```

## Features in Detail

### Route Finding

- Implements Dijkstra's algorithm for shortest path
- Provides alternative routes using DFS
- Shows multiple path options with different colors

### Fare Calculation

- Zone-based pricing system
- Special discounts for students (50%) and senior citizens (40%)
- Dynamic fare updates based on distance

### Interactive Visualization

- Click-to-highlight routes
- Smooth animations
- Responsive station network display
- Clear station labeling

## Contributing

Feel free to fork this project and submit pull requests for any improvements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
