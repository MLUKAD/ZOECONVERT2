# Changelog

All notable changes to Java2Bedrock Converter will be documented in this file.

## [2.2.0] - 2024-12-19

### Added
- 🚀 **Full support for Minecraft Java Edition 1.22.0 (Latest)**
- 📱 **Complete support for Minecraft Bedrock/PE 1.22.0 (Latest)**
- 🎯 **Enhanced pack format validation (supports formats 1-255)**
- 🔍 **Advanced resource pack analysis with detailed statistics**
- 📊 **Model and texture count reporting during analysis**
- 🎮 **Comprehensive version compatibility checking**
- 📱 **Explicit PE (Pocket Edition) support documentation**

### Changed
- ⚡ **Improved pack format detection and validation**
- 🎨 **Enhanced user interface with better version information display**
- 📝 **Updated README with detailed version support information**
- 🔧 **Better error handling for unsupported pack formats**
- 📦 **Optimized compatibility checking for latest versions**

### Technical Improvements
- Extended pack format support to include all current Java Edition formats
- Enhanced resource pack analysis with detailed compatibility reporting
- Improved version detection and validation logic
- Better error messages for version compatibility issues
- Updated documentation to reflect latest version support

## [2.1.0] - 2024-12-19

### Added
- 🚀 Support for Minecraft Bedrock Edition 1.20.0 - 1.22.0
- 🎯 Enhanced dependency checking with version validation
- 🎨 Improved user interface with better status messages and progress indicators
- 📊 Conversion statistics display at the end of the process
- 🔍 Resource pack analysis before conversion starts
- 💾 Automatic backup creation of important files
- 🎨 New color scheme with additional status message types (warning, success)
- 📦 Updated all format versions to 1.20.0 for better compatibility

### Changed
- ⚡ Improved performance and error handling throughout the script
- 🔧 Updated GitHub Actions workflow to use Node.js 20 and latest dependencies
- 📝 Enhanced README with better documentation and version information
- 🎯 Better dependency validation with minimum version requirements
- 📦 Updated manifest files to use version 2.1.0 and min_engine_version 1.20.0

### Technical Improvements
- Updated geometry format version from 1.16.0 to 1.20.0
- Updated animation format version from 1.8.0 to 1.20.0
- Updated block/item format version from 1.16.100 to 1.20.0
- Updated attachable format version from 1.10.0 to 1.20.0
- Enhanced dependency checking with version validation
- Improved error messages and user feedback
- Added resource pack validation before processing

### Dependencies
- jq: 1.6+ (with version validation)
- sponge: Latest (from moreutils)
- spritesheet-js: Latest (via npm)
- ImageMagick: 6+ (optional but recommended)
- Node.js: 16+ (updated from previous requirements)

## [Previous Versions]

### [1.x.x] - Legacy versions
- Initial release with basic conversion functionality
- Support for Minecraft Bedrock 1.16.210.59+
- Basic dependency checking
- Standard conversion process

---

For more information about this project, visit the [GitHub repository](https://github.com/Kas-tle/java2bedrock.sh).
