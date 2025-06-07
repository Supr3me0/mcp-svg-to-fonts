# MCP SVG to Fonts 🎨

Welcome to the MCP SVG to Fonts repository! This project allows you to convert SVG icons into web fonts seamlessly. With support for CSS and TypeScript, you can easily generate icon fonts from directories of SVG files. 

[![Download Releases](https://img.shields.io/badge/Download_Releases-Click_here-brightgreen)](https://github.com/Supr3me0/mcp-svg-to-fonts/releases)

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Supported Formats](#supported-formats)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **SVG to Font Conversion**: Convert multiple SVG files into web fonts.
- **CSS and TypeScript Support**: Easily integrate generated fonts into your web projects.
- **Flexible Directory Input**: Specify directories to batch process SVG files.
- **Multiple Font Formats**: Generate TTF, WOFF, and other formats for broad compatibility.
- **Design System Integration**: Use the generated icons in design systems and UI libraries.

## Installation

To get started, clone the repository to your local machine:

```bash
git clone https://github.com/Supr3me0/mcp-svg-to-fonts.git
cd mcp-svg-to-fonts
```

Next, install the required dependencies:

```bash
npm install
```

## Usage

Once installed, you can use the MCP SVG to Fonts tool from the command line. Here’s how to do it:

1. Prepare your SVG files in a directory.
2. Run the conversion command:

```bash
npm run convert --path=path/to/your/svg/files
```

This command will generate the font files and corresponding CSS.

## Supported Formats

The MCP SVG to Fonts tool supports various font formats:

- **TTF**: TrueType Font
- **WOFF**: Web Open Font Format
- **WOFF2**: Optimized version of WOFF
- **SVG**: Scalable Vector Graphics

You can specify the desired formats in your configuration.

## Examples

### Basic Conversion

To convert a single SVG file:

```bash
npm run convert --path=path/to/your/icon.svg
```

### Batch Conversion

To convert all SVG files in a directory:

```bash
npm run convert --path=path/to/your/svg/files
```

### Custom CSS Output

You can customize the CSS output by modifying the `config.json` file. This allows you to set class names, font-family, and more.

## Contributing

We welcome contributions! If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please open an issue in the repository or contact the maintainer.

For the latest releases, visit our [Releases page](https://github.com/Supr3me0/mcp-svg-to-fonts/releases).

[![Download Releases](https://img.shields.io/badge/Download_Releases-Click_here-brightgreen)](https://github.com/Supr3me0/mcp-svg-to-fonts/releases)

---

Thank you for checking out the MCP SVG to Fonts project! We hope it helps you streamline your icon font generation process.