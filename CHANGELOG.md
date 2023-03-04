# Changelog

All notable changes to this project will be documented in this file.


## [Unreleased]

### Added 

- Added hashed passwords in auth.py
- Added premade SQL requests
- Added CSRF protection
- Added XSS prevention
- Added secure Session Cookie

### Fixed

- Fixed SQLi vulnerability
- Fixed Session Cookie that were without the "secure" attribute
- Fixed XSS vulnerability

### Removed

- f-strings for SQL requests removed to prevent SQLi vulnerabilities