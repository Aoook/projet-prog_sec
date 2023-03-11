# Changelog

All notable changes to this project will be documented in this file.


## [Unreleased]

### Added 

- Added hashed passwords 
- Added premade SQL requests
- Added CSRF protection
- Added XSS prevention
- Added securization to Cookies

### Fixed

- Fixed SQLi vulnerability
- Fixed Cookies that were vulnerable to JavaScript cookie gathering scripts and Man in the middle attacks
- Fixed XSS vulnerability

### Removed

- f-strings for SQL requests removed to prevent SQLi vulnerabilities
