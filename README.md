# Baltic Technology Solution - EV Charging Website

Professional website for Baltic Technology Solution's EV charging installation services.

## 🚀 Live Website
- **Domain**: https://b-techs.com
- **GitHub Pages**: https://[your-username].github.io/b-techs-website

## 📁 Files
- `index.html` - Main homepage with embedded CSS/JS
- `Logo.png` - Company logo
- `README.md` - This documentation

## 🛠️ Features
- Responsive design (mobile, tablet, desktop)
- Contact form with validation
- WhatsApp and phone integration (+971581014496)
- Professional EV charging business layout
- Construction banner (remove when site is complete)

## 📧 Contact
- **Email**: inal.k@b-techs.com
- **Phone**: +971 58 101 4496
- **WhatsApp**: +971 58 101 4496

## 🔧 Setup Instructions

### 1. GitHub Repository Setup
1. Create new repository: `b-techs-website`
2. Upload `index.html` and `Logo.png`
3. Go to Settings → Pages
4. Source: Deploy from a branch → main → root
5. Custom domain: `b-techs.com`

### 2. GoDaddy DNS Configuration
Add these DNS records in GoDaddy:

**For GitHub Pages:**
```
Type: A
Name: @
Value: 185.199.108.153

Type: A  
Name: @
Value: 185.199.109.153

Type: A
Name: @  
Value: 185.199.110.153

Type: A
Name: @
Value: 185.199.111.153

Type: CNAME
Name: www
Value: [your-github-username].github.io
```

**For Zoho Email:**
```
Type: MX
Name: @
Value: mx.zoho.com
Priority: 10

Type: MX
Name: @  
Value: mx2.zoho.com
Priority: 20

Type: TXT
Name: @
Value: v=spf1 include:zoho.com ~all

Type: CNAME
Name: zb[random-code]
Value: zmverify.zoho.com
```

### 3. Zoho Email Setup
1. Go to https://zoho.com/mail
2. Sign up for free plan
3. Add domain: b-techs.com
4. Create user: inal.k@b-techs.com
5. Verify domain with TXT record
6. Configure MX records

### 4. Form Setup (Formspree)
1. Go to https://formspree.io
2. Create account and form
3. Replace form action in HTML:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

## 📱 Contact Integration
- Phone links: `tel:+971581014496`
- WhatsApp links: `https://wa.me/971581014496`
- Email links: `mailto:inal.k@b-techs.com`

## 🎨 Customization
- Hero background: Aqua blue gradient
- Logo size: 80px height
- WhatsApp buttons: Official green (#25d366)
- Construction banner: Orange gradient with animation

## 📝 Content Sections
1. Hero: "Ready to Electrify your Parkings?"
2. Value Pillars: 4 key benefits
3. Install Service: End-to-end process
4. Target Markets: 5 sectors served
5. Social Proof: Trust indicators
6. Tech Features: OCPP, payments, etc.
7. Contact Form: Full validation
8. FAQ: 3 common questions

## 🚧 Development Notes
- Remove construction banner when site is live
- Update contact form endpoint
- Add analytics (Google Analytics)
- Consider adding chat widget
- SEO optimization for local search

---
**© 2024 Baltic Technology Solution - Future-ready EV charging solutions**