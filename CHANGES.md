# CHANGES.md

## Major Issues Identified
- Monolithic code structure
- No password hashing
- Poor input validation and error handling

## Changes Made
- Modular structure with separate folders
- Added bcrypt password hashing
- Marshmallow validation
- Proper JSON responses and status codes

## Trade-offs
- SQLite retained for simplicity
- No JWT added due to scope

## AI Usage
- Used ChatGPT for structuring and scaffolding base templates
