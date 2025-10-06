# Security Policy

## Supported Versions

This project is a demonstration/educational tool. We support the latest version with security updates as needed.

| Version | Supported          |
| ------- | ------------------ |
| 1.x.x   | :white_check_mark: |

## Reporting a Vulnerability

This is a client-side only application with no server components or data storage. However, if you discover any security concerns:

1. **For dependency vulnerabilities**: Please report issues with the Leaflet.js library to their maintainers
2. **For code vulnerabilities**: Open an issue in this repository
3. **For general security concerns**: Contact through GitHub issues

## Security Considerations

- **External Dependencies**: This project loads Leaflet.js from unpkg.com CDN
- **Data Privacy**: No user data is collected or transmitted
- **Client-Side Only**: All code runs in the browser, no server-side components
- **HTTPS**: When hosting, always use HTTPS to protect against man-in-the-middle attacks

## Best Practices for Users

- Always host this application over HTTPS in production
- Verify CDN integrity if modifying the Leaflet.js version
- Be cautious when adding external data sources or APIs
- Validate any user input if extending the functionality