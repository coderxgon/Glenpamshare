# SpamShare CLI Tool

## Overview
This is a Python CLI application called "SpamShare" that automates Facebook post sharing. The application was successfully imported from GitHub and configured to run in the Replit environment.

## Project Structure
- `spamshare.py` - Main Python application file
- `requirements.txt` - Python dependencies (requests, aiohttp, rich)
- `README.md` - Original project documentation

## Dependencies
- **Python 3.11** - Programming language runtime
- **requests** - HTTP library for API calls
- **aiohttp** - Async HTTP client library
- **rich** - Library for rich text and beautiful formatting in terminals

## Configuration
- **Workflow**: "SpamShare CLI" configured to run `python spamshare.py`
- **Output Type**: Console (CLI application)
- **Environment**: Linux/NixOS with Python 3.11

## Setup Completed
1. ✅ Installed Python 3.11 module
2. ✅ Created requirements.txt with necessary dependencies
3. ✅ Installed Python packages (requests, aiohttp, rich)
4. ✅ Fixed code syntax errors (f-string nesting, async task variable reference)
5. ✅ Fixed potential runtime errors (regex error handling)
6. ✅ Configured workflow for console output
7. ✅ Verified application runs successfully

## Recent Changes
- **2025-09-20**: Initial GitHub import and environment setup
- Fixed syntax error in line 119 (nested f-string issue)
- Fixed async task gathering in line 147 (variable reference issue)
- Added error handling for regex pattern matching
- Application successfully starts and displays banner with input prompts

## Usage
The application prompts for:
1. Facebook cookie
2. Post link
3. Share count

It then performs automated Facebook post sharing using the provided credentials.

## Project Status
✅ **Ready for use** - All dependencies installed and application running successfully