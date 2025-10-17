# Tron Ares Theme

A dark VS Code theme inspired by the aesthetic of Tron: Ares movie, featuring a red and dark color scheme that creates an immersive coding experience.

## Features

- Dark theme optimized for long coding sessions
- Comprehensive syntax highlighting for multiple programming languages
- Red accent colors with dark backgrounds
- Semantic highlighting support
- Customized UI elements for a cohesive look

## Installation

1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X)
3. Search for "Tron: Ares"
4. Click Install

## Usage

1. Open VS Code
2. Press Ctrl+Shift+P (Cmd+Shift+P on macOS)
3. Type "Preferences: Color Theme"
4. Select "Tron: Ares" from the list

## Publication Procedure

### Prerequisites
- Install `vsce` globally: `npm install -g vsce`
- Ensure you're logged in to the Visual Studio Marketplace: `vsce login`

### Publishing Steps

1. **Update version** (if needed):
   ```bash
   # Update version in package.json
   npm version patch  # or minor, major
   ```

2. **Package the extension**:
   ```bash
   vsce package
   ```

3. **Publish to Marketplace**:
   ```bash
   vsce publish
   ```

4. **Update documentation**:
   - Update CHANGELOG.md with new version
   - Add any new features or changes
   - Update this README if needed

### Pre-publication Checklist

- [ ] Version numbers are consistent across all files
- [ ] Theme file is complete and tested
- [ ] README.md is updated with current information
- [ ] CHANGELOG.md reflects the new version
- [ ] Extension has been tested locally
- [ ] All required files are present and properly configured

### File Structure
```
tron-ares/
├── package.json                    # Extension manifest
├── themes/
│   └── tron-ares-color-theme.json  # Theme definition
├── README.md                       # This file
├── CHANGELOG.md                    # Version history
├── .vscodeignore                   # Files to exclude from package
└── .gitignore                      # Git ignore rules
```

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the [MIT License](LICENSE).
