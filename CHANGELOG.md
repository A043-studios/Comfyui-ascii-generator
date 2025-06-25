# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2025-06-25

### Added
- Initial release of ComfyUI ASCII Generator Node
- Multi-language character set support (8 languages)
- Dual output format (ASCII image + text)
- Configurable parameters:
  - Column count (10-500)
  - Character sets (simple, complex, english, chinese, korean, japanese, russian, german)
  - Background color (black/white)
  - Font size (6-48)
- ComfyUI tensor compatibility
- Batch processing support
- Error handling and fallbacks
- Brightness-based character mapping
- Automatic character density sorting
- Example workflows
- Comprehensive documentation
- Test suite

### Technical Details
- Based on vietnh1009/ASCII-generator algorithm
- Pure Python implementation with PIL and NumPy
- Compatible with ComfyUI's image tensor format
- Optimized for performance and memory usage

### Character Sets
- **Simple**: Basic ASCII characters for clean output
- **Complex**: Full ASCII symbol set for detailed art
- **English**: Alphabetic characters for text-like effects
- **Chinese**: Chinese characters for unique artistic style
- **Korean**: Hangul characters for Korean aesthetic
- **Japanese**: Hiragana characters for Japanese style
- **Russian**: Cyrillic alphabet for Russian text effects
- **German**: German alphabet with umlauts

### Files Added
- `ascii_generator_node.py` - Main node implementation
- `__init__.py` - Package initialization
- `requirements.txt` - Dependencies
- `README.md` - Documentation
- `LICENSE` - MIT license
- `examples/` - Example workflows
- `test_node.py` - Test suite

## [Unreleased]

### Planned Features
- Video to ASCII animation support
- Color ASCII art generation
- Custom character set import
- Performance optimizations
- Additional font support
- Batch processing improvements
