# beesuiteDocs

Documentation for beeSuite, an HR software suite (Employee Lifecycle Suite) that provides tools for employee management, login, administration, and location tracking.

## Overview

This repository contains the Sphinx-based documentation for beesuite, covering user workflows including:

- First-time login and authentication
- Password management (reset, forgot password)
- Administration features (announcements, leave setup, calendar profiles)
- Employee management
- Location tracking (beewhere)
- Legal pages (Terms & Conditions, Privacy Policy)

## Installation

### Prerequisites

- Python 3.8 or higher
- Git

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/zencomputersystems/beesuiteDocs.git
   cd beesuiteDocs
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Building the Documentation

1. Navigate to the docs directory:
   ```bash
   cd docs
   ```

2. Build the HTML documentation:
   ```bash
   make html
   ```

3. For a clean build:
   ```bash
   make clean html
   ```

## Viewing the Documentation

After building, open `docs/build/html/index.html` in your web browser to view the documentation.

## Project Structure

```
beesuiteDocs/
├── docs/
│   ├── source/          # RST source files
│   │   ├── _static/     # Static assets
│   │   ├── images/      # Documentation images
│   │   ├── conf.py      # Sphinx configuration
│   │   ├── index.rst    # Main table of contents
│   │   └── *.rst        # Individual documentation pages
│   ├── build/           # Generated HTML output
│   ├── Makefile         # Build automation
│   └── make.bat         # Windows build script
├── .github/
│   └── copilot-instructions.md  # AI assistant guidelines
├── requirements.txt     # Python dependencies
└── README.md           # This file
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test the build: `cd docs && make html`
5. Commit your changes
6. Push to your fork
7. Create a pull request

## Technologies Used

- **Sphinx**: Documentation generator
- **Read the Docs Theme**: Documentation theme
- **reStructuredText**: Markup language for documentation

## License

[Add license information here]

## Contact

For questions or support, please contact admin@beesuite.app.
