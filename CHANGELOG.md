# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2025-11-25

### Added
- Markdown parsing library (marked.js) for proper rendering of analysis results
- DOMPurify library for secure HTML sanitization
- UTF-8 encoding support in DOCX exports via meta charset tag
- Enhanced UI styling with improved typography and spacing
- Myers-Briggs Type Indicator in candidate persona analysis

### Changed
- Improved markdown rendering from basic regex to proper parser
- Enhanced prompt engineering for more detailed jargon decoder (includes doublespeak detection)
- Refined interview preparation questions to focus on clarifying vague areas
- Updated candidate persona prompt to include psychological profiling
- Modernized UI with better contrast and readability

### Fixed
- Missing `exportDocx()` method declaration causing syntax errors
- Inconsistent markdown formatting in analysis output
- Character encoding issues in exported DOCX files

## [1.0.0] - 2025-11-21

### Added
- Initial release
- Standalone HTML tool with embedded CSS and JavaScript
- LM Studio integration for local AI analysis
- Six comprehensive analysis modules:
  - Core Competencies Breakdown
  - Ideal Candidate Persona
  - Corporate Jargon Decoder
  - Red Flags & Culture Check
  - Interview Preparation Generator
  - Seniority & Market Positioning
- User guide with carousel interface
- Export to DOCX functionality
- Copy to clipboard feature
- Real-time character counter
- Connection status indicators
- Model selection with auto-refresh
- MIT License

### Security
- 100% local processing - no external data transmission
- CORS-aware connection to LM Studio
