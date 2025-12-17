[README.md](https://github.com/user-attachments/files/24221516/README.md)
# TWF Gemach Website

A professional, modern landing page for TWF Gemach - an interest-free loan service for the NW London Orthodox Jewish community.

## 📁 Files Included

- **index.html** - Main landing page
- **privacy.html** - Privacy policy page
- **README.md** - This file with setup instructions

## 🎨 Design Features

- **Modern & Clean**: Uncluttered design with generous white space
- **Brand Consistent**: Uses TWF Gemach's teal color (#0D5750) throughout
- **Fully Responsive**: Works perfectly on mobile, tablet, and desktop
- **Professional Typography**: Serif and sans-serif fonts matching your letterhead
- **Accessible**: Follows web accessibility best practices
- **Fast Loading**: Uses Tailwind CSS via CDN for optimal performance

## ⚙️ Setup Instructions

### Before Publishing

You need to make ONE important change in `index.html`:

**Line 200** - Replace the placeholder Google Form URL:
```html
<a href="YOUR_GOOGLE_FORM_URL_HERE" 
```

Change `YOUR_GOOGLE_FORM_URL_HERE` to your actual Google Form URL.

### How to Get Your Google Form URL

1. Create your application form in Google Forms
2. Click "Send" in the top right
3. Copy the link provided
4. Paste it in place of `YOUR_GOOGLE_FORM_URL_HERE`

Example:
```html
<a href="https://forms.google.com/your-actual-form-link-here" 
```

## 🚀 Deployment Options

### Option 1: Basic Web Hosting (Recommended for beginners)

Many web hosting providers offer simple upload options:

1. **Fasthosts, 123-reg, or similar UK providers**
   - Log into your hosting control panel
   - Find "File Manager" or "Upload Files"
   - Upload both `index.html` and `privacy.html`
   - Your site will be live at your domain

2. **Cost**: Typically £3-10/month for basic hosting

### Option 2: GitHub Pages (Free)

If you're comfortable with GitHub:

1. Create a GitHub account (free)
2. Create a new repository
3. Upload both HTML files
4. Enable GitHub Pages in repository settings
5. Your site will be live at `yourusername.github.io/repository-name`

### Option 3: Netlify or Vercel (Free)

Modern hosting platforms with drag-and-drop:

1. Create an account on Netlify.com or Vercel.com
2. Drag and drop your HTML files
3. Your site goes live immediately with HTTPS
4. Can connect a custom domain

## 📝 Customization Guide

### Changing Colors

All colors are defined in the Tailwind config at the top of each HTML file:

```javascript
colors: {
    'twf-teal': '#0D5750',        // Main teal color
    'twf-teal-light': '#156B63',  // Lighter teal
    'twf-teal-dark': '#083D38',   // Darker teal
}
```

### Updating Content

All text content is clearly structured in semantic HTML sections. Simply find the section you want to edit and modify the text.

### Adding Your Logo as an Image (Optional)

Currently, the logo is recreated in text. If you prefer to use your actual logo image:

1. Save your logo as `logo.png` in the same folder as the HTML files
2. Replace the header section (around line 30) with:
```html
<img src="logo.png" alt="TWF Gemach" class="h-16 sm:h-20">
```

## 🔒 Security & Privacy

- The privacy policy is comprehensive and GDPR-compliant
- All sensitive information is collected via Google Forms (not stored on your website)
- The website itself doesn't collect or store any user data
- Make sure your Google Form is properly configured with data protection in mind

## 📱 Mobile Optimization

The site is fully responsive and looks great on:
- Smartphones (iPhone, Android)
- Tablets (iPad, etc.)
- Desktop computers
- Large displays

## ✅ Testing Checklist

Before going live, please check:

- [ ] Google Form URL is updated and working
- [ ] All links work correctly (especially email links)
- [ ] Privacy policy link works from main page
- [ ] Site looks good on mobile (test on your phone)
- [ ] Email address is correct in all locations
- [ ] Charity number is correct (1165689)
- [ ] Test the "Apply" button leads to your form
- [ ] Test the "Contact Us About Donating" link

## 🆘 Support

If you need any modifications or have questions:
- Review the code comments in the HTML files
- Most text can be edited directly without coding knowledge
- For design changes, modify the Tailwind classes

## 📄 Browser Compatibility

Works perfectly in:
- Chrome, Firefox, Safari, Edge (all modern versions)
- iOS Safari, Chrome Mobile
- No need for Internet Explorer support (outdated)

## 🎯 Next Steps After Launch

1. Submit your website to Google Search Console for SEO
2. Consider setting up Google Analytics to track visitors (optional)
3. Share your website URL in community WhatsApp groups
4. Include the URL in any printed materials or email signatures
5. Consider basic SEO (meta descriptions are already included)

## 📞 Contact for Applicants

Reminder: The website intentionally does NOT include phone numbers to encourage form submissions and reduce administrative time.

---

**Built with care for the TWF Gemach community** 🌟

Last updated: December 2024
