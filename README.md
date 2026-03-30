# NightShield Pest Control Website - Static HTML Version

## 📁 Complete Website Structure

This is a complete static HTML/CSS/JS conversion of the NightShield Pest Control website. All 20+ pages have been converted and are ready to use!

### ✅ Pages Included

**Core Pages:**
- `index.html` - Homepage with hero, services, features, blog preview
- `about.html` - Company information, story, values, certifications
- `contact.html` - Contact form and information
- `privacy.html` - Privacy policy
- `terms.html` - Terms and conditions

**Service Pages:**
- `termite-control.html` - Termite control services
- `bed-bug-treatment.html` - Bed bug treatment
- `rodent-control.html` - Rodent control
- `cockroach-control.html` - Cockroach extermination
- `mosquito-control.html` - Mosquito control programs

**Category Pages:**
- `residential.html` - Residential pest control with pricing plans
- `commercial.html` - Commercial pest control for businesses
- `emergency.html` - 24/7 emergency services

**Additional Pages:**
- `blog.html` - Blog listing page
- `blog-post.html` - Individual blog post template
- `faqs.html` - Frequently asked questions with accordion
- `testimonials.html` - Customer reviews and ratings
- `areas.html` - Service areas across the USA

### 📂 File Structure

```
/public/
├── index.html                 # Homepage
├── about.html                 # About us
├── contact.html               # Contact page
├── termite-control.html       # Termite service
├── bed-bug-treatment.html     # Bed bug service
├── rodent-control.html        # Rodent service
├── cockroach-control.html     # Cockroach service
├── mosquito-control.html      # Mosquito service
├── residential.html           # Residential services
├── commercial.html            # Commercial services
├── emergency.html             # Emergency services
├── blog.html                  # Blog listing
├── blog-post.html             # Blog post template
├── faqs.html                  # FAQs with accordion
├── testimonials.html          # Customer testimonials
├── areas.html                 # Service areas
├── privacy.html               # Privacy policy
├── terms.html                 # Terms & conditions
├── css/
│   └── style.css              # All website styles
├── js/
│   └── script.js              # JavaScript functionality
└── README.md                  # This file
```

## 🚀 How to Use

### Option 1: Open Directly in Browser
1. Navigate to the `/public/` folder
2. Double-click `index.html` to open in your browser
3. All links and navigation will work perfectly

### Option 2: Use a Local Server (Recommended)
```bash
# Using Python
cd public
python -m http.server 8000

# Using Node.js
npx serve public

# Using PHP
cd public
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

### Option 3: Deploy to Hosting
Upload the entire `/public/` folder to any web hosting service:
- **Netlify**: Drag and drop the folder
- **Vercel**: Deploy via CLI or GitHub
- **GitHub Pages**: Push to repository
- **Traditional hosting**: FTP upload to public_html

## 🎨 Features

### Design
- ✅ Dark theme (black/charcoal/deep gray)
- ✅ Yellow accent colors (#eab308)
- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Modern, professional design
- ✅ Trust-building elements

### Functionality
- ✅ Mobile menu with smooth toggle
- ✅ Dropdown navigation for services
- ✅ Smooth scroll for anchor links
- ✅ Form submission handling
- ✅ FAQ accordion functionality
- ✅ Hover effects and animations
- ✅ SVG icon system

### Contact Information
- Phone: +1-341-939-482
- Email: info@pestshield.in
- Service: 24/7 Emergency Available

## 🛠️ Customization

### Changing Colors
Edit `/public/css/style.css` and modify the CSS variables:
```css
:root {
  --color-yellow-500: #eab308;  /* Primary accent */
  --color-black: #000000;        /* Background */
  /* ... other colors */
}
```

### Updating Content
All content is in plain HTML - simply edit the text in any `.html` file.

### Adding Images
- Current images use Unsplash URLs
- Replace with your own images by updating `<img src="...">` tags
- Keep images in `/public/images/` folder (create if needed)

### Modifying Contact Details
Find and replace across all files:
- Phone: `+1-341-939-482`
- Email: `info@pestshield.in`

## 📱 Mobile Responsive

The website is fully responsive with breakpoints at:
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## 🌐 Browser Support

Works perfectly in all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Notes

- No build process required - pure HTML/CSS/JS
- No dependencies or frameworks
- Works offline after initial load
- SEO-friendly with proper meta tags
- Forms use JavaScript alert (integrate with backend as needed)
- All SVG icons are inline for performance

## 🔧 Form Integration

Currently, forms show an alert message. To integrate with a backend:

1. **Email Service (EmailJS, Formspree):**
   ```javascript
   // In script.js, replace the form handler
   form.addEventListener('submit', async function(e) {
     e.preventDefault();
     // Send to EmailJS or Formspree
   });
   ```

2. **Custom Backend:**
   ```javascript
   const formData = new FormData(form);
   await fetch('/api/contact', {
     method: 'POST',
     body: formData
   });
   ```

## 📄 License

All rights reserved © 2026 NightShield Pest Control

## 💡 Support

For questions or customization help, refer to the inline comments in:
- `/public/css/style.css` - Styling guide
- `/public/js/script.js` - JavaScript functionality

---

**Ready to deploy!** Just upload the `/public/` folder to your web server or hosting platform. No compilation or build steps needed! 🎉
