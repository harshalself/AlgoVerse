# AlgoVerse

## Description

AlgoVerse is a modern, responsive web platform that combines an elegant homepage with an interactive Dijkstra's algorithm visualizer. The platform features a clean, professional design with smooth animations and provides an intuitive interface for creating graphs and solving pathfinding problems using Dijkstra's algorithm. Perfect for students, educators, and developers learning about graph algorithms and pathfinding.

## Screenshots

**Home Page**
![Home Page](./Screenshot%201.png)

**Dijkstra Solver**
![Dijkstra Solver](./Screenshot%202.png)

## Tech Stack

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with CSS variables, Grid, Flexbox, and animations
- **JavaScript** - Interactive functionality and algorithm implementation
- **Bootstrap 4** - Grid system for responsive layout
- **Google Fonts** - Inter and Space Grotesk typography

## Project Structure

```
├── index.html              # Main landing page with hero, about, team, and footer sections
├── dijkstra-solver.html    # Interactive Dijkstra algorithm visualizer
├── css/
│   ├── style.css           # Main stylesheet with CSS variables
│   ├── responsive.css      # Mobile and tablet responsive styles
│   └── bootstrap.css       # Bootstrap framework (CSS only)
├── images/                 # Logo and UI images
├── js/
│   ├── jquery-3.4.1.min.js # jQuery library
│   └── script.js           # Dijkstra solver JavaScript
├── Figma/                  # Design mockups and prototypes
└── Project Report/         # Project documentation and reports
```

## Features

- **Modern Homepage**: Clean, responsive design with smooth animations
- **Interactive Navigation**: Mobile-friendly overlay menu
- **Dijkstra Visualizer**: Create graphs, add edges, and find shortest paths
- **Responsive Design**: Optimized for all screen sizes
- **Smooth Animations**: CSS transitions and Intersection Observer animations
- **Professional UI**: Modern color scheme and typography

## How to Run

### Local Development

1. Clone the repository
2. Open `index.html` in your browser or use a local server
3. Navigate to `dijkstra-solver.html` to use the algorithm visualizer

### Using Python Server

```bash
cd path/to/AlgoVerse
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Contributing

Contributions are welcome! If you have suggestions for improvements or want to add new features, feel free to fork the repository and submit a pull request. Please ensure your code follows the existing style and includes relevant documentation.
