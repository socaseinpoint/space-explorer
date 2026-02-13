# Changelog

All notable changes to Space Explorer will be documented in this file.

## [v0.2.0] - 2026-02-13

### Changed
- Stars now pass by the camera (fly past you) instead of coming at you
- Reduced star size to small dots (0.05 radius)
- Added motion trails behind each star for speed effect
- Increased speed to 2 units for better motion feel
- Stars positioned in cylinder around camera path (radius 10-50)

### Technical
- 1000 stars with individual trail lines
- Each star has a dedicated Line geometry for trail
- Trail opacity: 0.3 for subtle effect

## [v0.1.0] - 2026-02-13

### Added
- Initial minimal space explorer
- Basic forward movement through space
- 2000 white star points
- Simple infinite loop (stars reset when passing camera)
- Black space background

### Technical
- Three.js r160
- Point cloud for stars
- Speed: 0.5 units per frame
