# Blue Light Roleplay Community Website

A professional emergency services roleplay community website built for Blue Light Roleplay Community.

## Features
- Modern responsive design
- Professional application system with Discord integration
- Multiple service departments (Police Scotland, Scottish Ambulance Service, Scottish Fire and Rescue Service, Civilian)
- Comprehensive rules and privacy policy pages
- Dynamic scenario questions based on service choice

## GitHub Pages Setup

### Custom Domain Setup:
1. Go to your repository Settings
2. Scroll to "Pages" section
3. Under "Custom domain", enter your domain name
4. Enable "Enforce HTTPS"

### DNS Configuration:
For your domain provider, add these DNS records:
- **A Record**: Point your apex domain to GitHub Pages IPs:
  - 185.199.108.153
  - 185.199.109.153  
  - 185.199.110.153
  - 185.199.111.153
- **CNAME Record**: Point www subdomain to your-username.github.io

### Branch Configuration:
- Deploy from: `main` branch
- Folder: `/ (root)`

## Local Development
1. Clone the repository
2. Open `index.html` in your browser
3. For testing webhooks, update the webhook URL in `application.html`

## File Structure
```
/
├── index.html          # Homepage
├── about.html          # About page
├── get-involved.html   # Services and application info
├── application.html    # Application form
├── rules.html          # Community rules
├── privacy.html        # Privacy policy
├── assets/
│   ├── css/
│   │   └── custom.css  # Custom styling
│   └── js/
│       └── webhook-config.js  # Webhook configuration
└── CNAME              # Custom domain configuration
```

## Security
- Discord webhook URL is obfuscated for public repository security
- All sensitive information is encoded using base64

## Support
Join our Discord: https://discord.gg/gUKKXsaNt3