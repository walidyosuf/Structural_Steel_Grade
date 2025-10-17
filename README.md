# Steel Specification Checker - Multi-Standard

A comprehensive web application for checking steel specifications against multiple international standards including DIN 17100, EN 10025, ASTM, and JIS. The application supports both mechanical testing and chemical analysis with sample analysis capabilities.

![Steel Specification Checker](https://img.shields.io/badge/Steel-Specification%20Checker-blue)
![Multi-Standard](https://img.shields.io/badge/Multi--Standard-Supported-green)
![Bilingual](https://img.shields.io/badge/Bilingual-EN%2FAR-orange)

## 🌟 Features

### Multi-Standard Support
- **DIN 17100**: ST37, ST44, ST52
- **EN 10025**: S235JR, S275JR, S355JR
- **ASTM**: A36, A572 Grade 50
- **JIS**: SS400, SS540

### Testing Capabilities
- **Mechanical Testing**: Yield strength, tensile strength, elongation
- **Chemical Analysis**: Complete elemental analysis with 10 elements
- **Sample Analysis**: Specifically designed for sample analysis rather than ladle analysis

### User Experience
- 🌙 Dark/Light mode toggle
- 🌐 Bilingual support (English/Arabic)
- 📱 Responsive design
- 📊 Real-time compliance checking
- 📋 Detailed standard specifications viewer

### Export Functionality
- 📄 Export to Excel with formatted tables
- 📊 Comprehensive report generation
- 🎨 Professional table formatting

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server requirements - runs entirely in browser

### Installation
1. Clone the repository:
```bash
git clone https://github.com/your-username/steel-specification-checker.git
```

2. Navigate to the project directory:
```bash
cd steel-specification-checker
```

3. Open `index.html` in your web browser:
```bash
# On Windows
start index.html

# On macOS
open index.html

# On Linux
xdg-open index.html
```

## 📖 How to Use

### Basic Usage
1. **Select Standard**: Choose from DIN 17100, EN 10025, ASTM, or JIS
2. **Choose Steel Type**: Available options update based on selected standard
3. **Specify Thickness**: Select product thickness range
4. **Select Test Type**: Choose between Mechanical Test or Chemical Analysis
5. **Enter Results**: Input your test values
6. **Check Compliance**: Click "Check Compliance" to validate against standards

### Advanced Features

#### Chemical Analysis
- Carbon (C), Silicon (Si), Manganese (Mn)
- Phosphorus (P), Sulfur (S), Nitrogen (N)
- Aluminum (Al), Chromium (Cr), Nickel (Ni), Copper (Cu)
- Each element includes information about its effect on steel properties

#### Mechanical Testing
- Yield Strength (N/mm²)
- Tensile Strength (N/mm²)
- Elongation (%)

#### Exporting Results
- Click "Export to Excel" to generate comprehensive reports
- Reports include all test data, compliance status, and reasons for non-compliance
- Formatted as professional tables

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Charts**: No external dependencies
- **Export**: SheetJS (xlsx.js) for Excel export
- **Styling**: Pure CSS with CSS Variables for theming
- **Icons**: Unicode symbols

## 📁 Project Structure

```
steel-specification-checker/
│
├── index.html              # Main application file
├── README.md               # Project documentation
├── assets/                 # Static assets (if any)
│   ├── images/            # Screenshots and logos
│   └── docs/              # Additional documentation
└── LICENSE                 # Project license
```

## 🌍 Language Support

The application fully supports:
- **English** (Default)
- **Arabic** (Right-to-left layout)

Toggle between languages using the language button in the header.

## 🎨 Themes

- **Light Theme**: Clean, professional appearance
- **Dark Theme**: Reduced eye strain for extended use

Toggle between themes using the dark mode switch.

## 📊 Supported Standards Details

### DIN 17100
- General structural steels
- Sample analysis requirements
- Comprehensive chemical composition limits

### EN 10025
- European standard for hot-rolled products
- JR quality classes
- Standardized mechanical properties

### ASTM
- American Society for Testing and Materials
- A36 and A572 Grade 50
- US standard specifications

### JIS
- Japanese Industrial Standards
- SS400 and SS540 grades
- Japanese manufacturing requirements

## 🔧 Development

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Local Development
The application requires no build process. Simply edit the `index.html` file and refresh your browser.

### Adding New Standards
To add a new standard:

1. Update the `translations` object with new standard names
2. Add steel types to the `steelOptions` object
3. Define specifications in the `standards` object
4. Update the standard selection dropdown

## 🤝 Contributing

We welcome contributions! Please feel free to submit pull requests or open issues for:

- New steel standards
- Additional language support
- UI/UX improvements
- Bug fixes
- Documentation enhancements

### Contribution Guidelines
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Bug Reports

If you encounter any issues, please [open an issue](https://github.com/your-username/steel-specification-checker/issues) with:

1. Description of the problem
2. Steps to reproduce
3. Expected behavior
4. Actual behavior
5. Browser and version information

## 📞 Support

For support and questions:
- Open an [issue](https://github.com/your-username/steel-specification-checker/issues)
- Check the [documentation](#)
- Contact the maintainers

## 🙏 Acknowledgments

- International standards organizations (DIN, EN, ASTM, JIS)
- SheetJS library for Excel export functionality
- Contributors and testers

---

**Note**: This application is designed for educational and professional use. Always verify critical specifications with official standard documents and qualified materials engineers.

---

<div align="center">

**Made with ❤️ for the materials engineering community**

[⭐ Star this repo](https://github.com/your-username/steel-specification-checker) if you find it helpful!

</div>
