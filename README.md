# Legal Document Block Editor

A proof-of-concept block editor designed specifically for creating structured legal documents with automatic hierarchical numbering and PDF export capabilities.

## Features

### Document Structure
- Hierarchical block-based editing system
- Three levels of document organization:
  - Level 0: Main headings (1., 2., 3., etc.)
  - Level 1: Sub-clauses (1.1, 1.2, etc.)
  - Level 2: Detailed points (a), b), c), etc.)
- Smart content blocks for body text (unnumbered)

### Editor Controls
- **Indentation Control**
  - Indent/Outdent buttons
  - Keyboard shortcuts: Tab/Shift+Tab
  - Automatic numbering updates
- **Block Management**
  - Add new blocks (Enter key or '+' button)
  - Remove empty blocks (Backspace)
  - Dynamic placeholder text based on block level

### Export and Preview
- PDF export with proper formatting
- Live preview mode
- Mobile-responsive design
- Loading indicator for export process

## Usage

### Basic Navigation
1. Start typing in any block to add content
2. Press Enter to create a new block
3. Use Tab/Shift+Tab to adjust indentation levels
4. Click the '+' button to add a new block at any position

### Creating Document Structure
1. Main headings (Level 0):
   - Use for primary sections
   - Automatically numbered (1., 2., 3.)

2. Sub-clauses (Level 1):
   - Indent once for subsections
   - Automatically numbered (1.1, 1.2, etc.)

3. Detailed points (Level 2):
   - Indent twice for detailed items
   - Automatically lettered (a), b), c))

### Exporting Documents
1. Click the PDF export button (document icon)
2. Wait for the loading indicator
3. PDF will automatically download
4. Exported document includes:
   - Proper formatting
   - Hierarchical structure
   - Date stamp
   - Consistent styling

## Technical Implementation

### Technologies Used
- Pure JavaScript (ES6+)
- HTML5
- CSS3
- html2pdf.js for PDF generation

### Key Components
- `BlockEditor` class for core functionality
- Responsive CSS layout system
- Mobile-optimized PDF generation
- Event-based user interaction handling

### Mobile Support
- Touch-friendly interface
- Responsive design
- Optimized PDF generation for mobile devices
- Loading indicators for slower connections

## Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome for Android)

## Limitations
- PDF export might take longer on mobile devices
- Complex formatting options not yet implemented
- Basic styling options only

## Future Enhancements
- Rich text formatting
- Document templates
- Collaborative editing
- Custom numbering schemes
- Document versioning
- Cloud storage integration

## Getting Started

1. Clone the repository
2. Open `index.html` in a modern web browser
3. Start creating your legal document

No build process or dependencies required for basic usage.

## Contributing

This is a proof-of-concept project. Feel free to fork and enhance based on your needs. Potential areas for contribution:
- Additional formatting options
- Template system
- Enhanced mobile support
- PDF styling options
- Document validation

## License

MIT License - Feel free to use and modify for your own projects.
