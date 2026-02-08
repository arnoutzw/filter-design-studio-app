# Filter Design Studio

A comprehensive web-based digital filter design tool for analyzing and implementing audio and signal processing filters.

## Features

- **Multiple Filter Types**:
  - Low-Pass (LP)
  - High-Pass (HP)
  - Band-Pass (BP)
  - Notch (Band-Stop)
  - Peaking EQ
  - Shelving (Low-Shelf, High-Shelf)
- **Analysis Tools**:
  - Magnitude response plots
  - Phase response visualization
  - Group delay analysis
  - Impulse response display
  - Pole-zero diagrams
- **Transfer Function Display**: View mathematical representation of your filter
- **Biquad Structure**: Optimized second-order section implementation
- **Bilinear Transform**: Advanced filter design technique support
- **Code Export**:
  - Generate C code for embedded systems
  - Export to MATLAB for further analysis
  - Ready-to-use filter coefficients
- **Real-time Visualization**: Instant plot updates as design parameters change
- **Frequency Response Analysis**: Interactive frequency domain exploration

## Tech Stack

- **HTML5** - Semantic markup
- **JavaScript** - Digital signal processing algorithms and computations
- **Canvas** - 2D visualization and plot rendering
- **PWA** - Progressive Web App capabilities

## Getting Started

### Online Demo
Visit the live application: [https://arnoutzw.github.io/filter-design-studio-app/](https://arnoutzw.github.io/filter-design-studio-app/)

### Local Installation
Simply open `index.html` in a modern web browser. No build tools or dependencies required.

### Usage
1. Open the application in your browser
2. Select a filter type (LP, HP, BP, Notch, Peaking, Shelving)
3. Adjust cutoff frequency, Q factor, and other parameters
4. View real-time frequency response, phase, and group delay plots
5. Examine pole-zero diagram for stability analysis
6. Export C code or MATLAB data for implementation
7. Analyze impulse response and transfer function

## Browser Support

Requires a modern browser with Canvas support (Chrome, Firefox, Edge, Safari)

## License

MIT License - See LICENSE file for details
