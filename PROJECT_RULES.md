# Space Explorer - Project Rules

## Versioning & Changelog

1. **Version Format**: `vX.Y.Z`
   - X = Major (breaking changes, complete redesigns)
   - Y = Minor (new features, significant changes)
   - Z = Patch (bug fixes, tiny tweaks)

2. **CHANGELOG.md is mandatory**
   - Every change must be documented
   - Include date in format: YYYY-MM-DD
   - Categories: Added, Changed, Removed, Fixed, Technical

3. **Version Snapshots**
   - Each significant version saved in `/versions/` folder
   - Named as: `v0.1.0.html`, `v0.2.0.html`, etc.
   - Allows easy rollback and comparison

## Development Principles

1. **Keep it Simple**
   - Start with minimal version
   - Add features incrementally
   - Each change should have clear purpose

2. **Performance First**
   - Test on mobile devices
   - Optimize before adding more features
   - Keep frame rate smooth (60fps target)

3. **No Libraries Unless Necessary**
   - Use vanilla Three.js when possible
   - Avoid heavy dependencies
   - Prefer simple solutions

## Git Workflow

1. Commit message format: `[vX.Y.Z] Short description`
2. Always update CHANGELOG.md before commit
3. Create version snapshot before major changes
4. Deploy to production after testing locally

## Current Version

**v0.2.0** - Stars with motion trails passing by camera
