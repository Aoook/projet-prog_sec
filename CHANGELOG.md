# Changelog

All notable changes to this project will be documented in this file.


## [Unreleased]

### Added 

- Added hashed passwords 
- Added premade SQL requests
- Added CSRF protection
- Added XSS prevention

### Fixed

- Fixed SQLi vulnerability
- Fixed Session Cookie that were without the "secure" attribute
- Fixed XSS vulnerability

### Removed

- f-strings for SQL requests removed to prevent SQLi vulnerabilities
