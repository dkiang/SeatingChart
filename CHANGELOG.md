# Changelog

All notable changes to the Student Seating Chart Generator will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.0] - 2024-03-21

### Added
- New grouping strategy options:
  - "Maximum Same-Size Groups" for balanced group distribution
  - "Maximum N-Sized Groups" for exact group size prioritization
- Modern UI redesign:
  - Added Inter font family
  - Implemented CSS variables for consistent theming
  - Responsive grid layout for group display
  - Card-based design with hover effects
  - Improved form layout and input styling
  - Mobile-responsive design
- Improved accessibility features:
  - Better color contrast
  - Proper focus states
  - Improved form label associations
  - Enhanced interactive element visibility

### Changed
- Updated group distribution algorithm to create more balanced groups
- Improved layout and spacing throughout the application
- Enhanced button and input styling
- Reorganized controls into distinct sections
- Made the interface more intuitive and user-friendly

### Fixed
- Group distribution now properly handles remainder students
- Improved handling of edge cases in group generation

## [1.0.0] - 2024-03-21

### Added
- Basic student list management:
  - Save and load student lists
  - Local storage for persistent data
- Group generation functionality:
  - Configurable group sizes
  - Random student distribution
  - Group display
- Simple, functional interface

### Changed
- Initial release with core functionality

## Versioning Guidelines

### Version Format
- MAJOR version for incompatible API changes
- MINOR version for backwards-compatible functionality
- PATCH version for backwards-compatible bug fixes

### Change Categories
- **Added** for new features
- **Changed** for changes in existing functionality
- **Deprecated** for soon-to-be removed features
- **Removed** for now removed features
- **Fixed** for any bug fixes
- **Security** for vulnerability fixes

## How to Update This Changelog

1. Add new entries under the [Unreleased] section
2. When releasing a new version:
   - Create a new version section with the current date
   - Move all unreleased changes to the new version section
   - Update the version number according to semantic versioning
3. Keep the most recent changes at the top of each section
4. Include the date of the change in the version header
5. Link to relevant issues or pull requests when applicable 