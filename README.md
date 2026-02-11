# Mich Random Port - VPN & CDN Port Generator

![Mich Random Port Preview](https://img.shields.io/badge/Mich-Random%20Port-blue)
![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)
![HTML CSS JavaScript](https://img.shields.io/badge/HTML-CSS-JavaScript-yellow)
![Single File](https://img.shields.io/badge/Single-File%20Application-green)

A modern, single-file web application for generating random ports optimized for VPN, HTTP, HTTPS, and CDN/proxy services like Cloudflare, Fastly, and G-Core.

## 🌐 Live Demo
[[Demo]](https://m1chtv.github.io/mich-ports/)

## 📋 Features

### 🛡️ VPN Port Generation
- Generate random ports for VPN connections
- Options to prefer UDP-friendly ports
- Avoid common VPN ports (1194, 1723, etc.)
- Prefer high-range ports (above 30000)

### ☁️ CDN/Proxy Port Generation
- Generate ports for popular CDN/proxy services:
  - **Cloudflare** - 80, 443, 2053, 2083, 2087, 2096, 8443
  - **Fastly** - 80, 443, 8080, 8443
  - **G-Core** - 80, 443, 8080, 8443
  - **Akamai** - 80, 443, 8080, 8443
  - **CloudFront** - 80, 443, 8080, 8443
  - **Bunny CDN** - 80, 443, 8080, 8443

### 🔧 Advanced Options
- Prefer common CDN ports
- Avoid standard 80/443 ports
- Include alternative ports
- Use any available port (1024-65535)
- Copy to clipboard functionality
- Port history tracking with localStorage

### 🎨 User Interface
- Modern dark theme with gradient accents
- Fully responsive design for all devices
- Visual port status indicators with badges
- Animated port generation effects
- History of recently generated ports
- Clean, intuitive controls
