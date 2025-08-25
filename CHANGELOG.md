# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [7.0.0] - 2025-01-25

### Added
- ✨ **Support for Joi v18** - Full compatibility with the latest Joi version
- ✨ **Joi.link() support** - Handle recursive schemas for tree structures
- 📝 Comprehensive tests for recursive schema functionality
- 📝 Enhanced documentation with examples
- 🔧 GitHub Actions workflow for continuous testing

### Changed
- 📦 Forked from joi-to-swagger v6.2.0
- 📦 Updated package name to `@eval-pairs/joi-to-swagger`
- 📦 Updated peerDependencies to require Joi v18+
- 📦 Updated Node.js requirement to v20+ (from v14+)
- 🔧 Fixed ESLint issues throughout codebase
- 📝 Modernized README with better examples

### Fixed
- 🐛 Compatibility issues with Joi v18 schema parsing
- 🐛 Missing support for recursive schemas with Joi.link()

### Security
- 🔒 Updated all dependencies to latest secure versions
- 🔒 Added npm audit to CI pipeline

## Migration from Original Package

If you're migrating from the original `joi-to-swagger`:

1. **Install the fork:**
   ```bash
   npm uninstall joi-to-swagger
   npm install @eval-pairs/joi-to-swagger
   ```

2. **Update imports:**
   ```js
   // Before
   const j2s = require('joi-to-swagger');
   
   // After
   const j2s = require('@eval-pairs/joi-to-swagger');
   ```

3. **No other changes needed!** The API is 100% backward compatible.

## Original Package

For the changelog of the original package (up to v6.2.0), see the [original changelog](https://github.com/Twipped/joi-to-swagger/blob/master/CHANGELOG.md).

---

## Future Releases

### [Unreleased]
- Features and fixes will be documented here as they are developed

### Roadmap
- [ ] Support for Joi v19 when released
- [ ] Performance optimizations for large schemas
- [ ] Better TypeScript definitions
- [ ] Support for OpenAPI 3.1

## Contributing

We welcome contributions! Please see our [Contributing Guide](./CONTRIBUTING.md) for details.

## Support

- 🐛 **Issues:** [GitHub Issues](https://github.com/agent2-jifbrodeur/joi-to-swagger-v18/issues)
- 💬 **Discussions:** [GitHub Discussions](https://github.com/agent2-jifbrodeur/joi-to-swagger-v18/discussions)
- 📧 **Contact:** Open an issue for support

---

[7.0.0]: https://github.com/agent2-jifbrodeur/joi-to-swagger-v18/releases/tag/v7.0.0