# Prefix Codex Calculator - Huffman Coding Visualizer

## Overview

The Prefix Codex Calculator is an interactive web application that demonstrates Huffman coding, a lossless data compression algorithm. It allows users to:

- Analyze text input to calculate character frequencies
- Generate optimal prefix codes using Huffman coding
- Visualize the Huffman tree structure
- Encode text using the generated codes
- Decode binary strings back to the original text
- View detailed statistics and frequency charts

## Features

### Core Functionality
- **Frequency Analysis**: Calculates and displays character frequencies in input text
- **Huffman Tree Generation**: Builds an optimal prefix code tree based on character frequencies
- **Encoding/Decoding**: Converts text to binary codes and vice versa using the generated Huffman codes

### Visualization
- **Interactive Tree Diagram**: Dynamic 2D visualization of the Huffman tree with zoom/pan controls
- **Frequency Chart**: Bar chart showing character frequency distribution
- **Downloadable Tree**: Export the Huffman tree visualization as a PNG image

### User Experience
- **Responsive Design**: Works on desktop and mobile devices
- **Modern UI**: Clean, intuitive interface with smooth animations
- **Sample Text**: Quick-load sample text for demonstration
- **Copy Functionality**: One-click copy for encoded/decoded results

## How to Use

1. **Enter Text**:
   - Type or paste text into the input area
   - Or click "Load Sample" to use example text

2. **Analyze**:
   - Click "Analyze Text" to calculate frequencies and build the Huffman tree

3. **Explore Results**:
   - View character frequencies in the table and chart
   - Examine the generated Huffman codes
   - Interact with the visual Huffman tree (hover for details)

4. **Encode/Decode**:
   - Encode your text to binary using the generated codes
   - Decode binary strings back to text

5. **Download**:
   - Save the Huffman tree visualization as an image

## Technical Details

### Technologies Used
- **Frontend**: HTML5, CSS3, JavaScript (ES6)
- **Libraries**: 
  - [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
  - [D3.js](https://d3js.org/) - Data visualization library
  - [SweetAlert2](https://sweetalert2.github.io/) - Beautiful alert dialogs
  - [html2canvas](https://html2canvas.hertzen.com/) - HTML to image conversion

### Algorithms Implemented
- Huffman coding algorithm for prefix code generation
- Frequency analysis and probability calculation
- Tree traversal for code assignment

## Installation

No installation required! The application runs directly in modern web browsers.

To run locally:
1. Download all files
2. Open `index.html` in any modern browser

## Browser Support

The application is tested and works on:
- Chrome (latest)
- Firefox (latest)
- Edge (latest)
- Safari (latest)

## License

This project is open-source and available under the MIT License.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements.

## Author

Developed by [Bilol Kobilov](https://github.com/bilolkobilov)

---

**Note**: This is a client-side application. All processing happens in the browser - no data is sent to any server.