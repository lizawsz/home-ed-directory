# Mayo & Connacht Home Education Directory

A comprehensive, searchable directory of home education resources, support groups, and activities for families in Mayo and the wider Connacht region of Ireland.

## 🎯 Project Overview

This directory helps home educating families find:
- Local support groups and communities
- Educational activities and venues
- Museums, nature centers, and cultural sites
- Home education meetups and events
- Resources organized by county

## ✨ Features

### Current Features (v1.0)
- ✅ **Searchable directory** - Real-time search across all listings with highlighted results
- ✅ **Mobile responsive** - Card layout on mobile devices for easy browsing
- ✅ **Tabbed navigation** - Organized by region and category
- ✅ **Keyboard accessible** - Full keyboard navigation support (Arrow keys, Home, End)
- ✅ **ARIA compliant** - Screen reader friendly with proper semantic HTML
- ✅ **LocalStorage** - Remembers your last viewed tab
- ✅ **8 main sections** covering 150+ venues and activities

### Content Sections
1. **Welcome** - Introduction and overview
2. **Groups & Support** - HEN Ireland, Facebook groups, national organizations
3. **Home Ed Meetups** - Regular meetups and social gatherings
4. **Mayo Activities** - Comprehensive Mayo county listings
5. **Galway Activities** - Galway region activities and venues
6. **Sligo Activities** - Sligo county resources
7. **Roscommon & Leitrim** - Eastern Connacht listings
8. **Quick Reference** - Top picks by category

## 📁 Project Structure

```
home-ed-directory/
├── index.html              # Main directory (single-page HTML)
├── README.md               # This file
├── MONETIZATION.md         # Revenue strategies and implementation
├── ROADMAP.md             # Future features and development plan
├── DISTRIBUTION.md        # How to reach home ed families
└── docs/
    └── pitch-template.md  # Template for approaching venues
```

## 🚀 Getting Started

### View Locally
1. Clone or download this repository
2. Open `index.html` in any web browser
3. No build process or dependencies needed - it's a single HTML file!

### Host Online (Free Options)

**GitHub Pages**
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/home-ed-directory.git
git push -u origin main
# Enable GitHub Pages in repo settings
```

**Netlify** (Easiest)
1. Go to netlify.com
2. Drag and drop the `index.html` file
3. Get instant URL: `yoursite.netlify.app`

**Cloudflare Pages**
1. Sign up at pages.cloudflare.com
2. Upload project folder
3. Free hosting with custom domain support

## 💰 Monetization Strategy

See [MONETIZATION.md](MONETIZATION.md) for detailed revenue strategies including:
- Sponsored listings (€25-50/month per venue)
- Premium memberships for families
- Google AdSense integration
- Affiliate partnerships
- Event promotion services

**Projected Income:**
- Year 1: €1,750-2,150
- Year 2: €9,400+

## 📢 Distribution Channels

See [DISTRIBUTION.md](DISTRIBUTION.md) for complete distribution strategy.

**Key channels:**
- Mayo Sligo Home Educators Facebook group
- HEN Ireland local contacts
- 17 Mayo library branches
- 29 Galway library branches
- Activity venues listed in directory
- QR codes at community centers

## 🛠️ Technical Details

**Built with:**
- Vanilla HTML, CSS, JavaScript
- No frameworks or dependencies
- Works offline once loaded
- ~535 lines of code
- Fully self-contained

**Browser Support:**
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Degrades gracefully on older browsers

**Performance:**
- Loads in <1 second
- No external dependencies
- No tracking (unless you add AdSense)
- Accessibility score: AAA compliant

## 📝 Content Updates

### How to Update Content

1. Open `index.html` in a text editor
2. Find the relevant `<table>` section
3. Add/edit rows following the existing format
4. Save and reload in browser

### Table Structure Example
```html
<tr>
  <td>Venue Name</td>
  <td>Category</td>
  <td>Location</td>
  <td>Description</td>
  <td>Best For</td>
  <td><a href="https://..." target="_blank">website.com</a></td>
</tr>
```

### Adding New Venues
1. Identify the correct section (Mayo, Galway, etc.)
2. Copy an existing row as a template
3. Update all cells with new information
4. Ensure links open in new tab: `target="_blank"`

## 🤝 Contributing

Want to improve the directory? Here's how:

1. **Report Issues**: Found incorrect info? Open an issue
2. **Suggest Venues**: Know a great home ed resource? Add it!
3. **Improve Features**: Submit pull requests for enhancements
4. **Share Feedback**: Contact via [method TBD]

## 📋 Future Enhancements

See [ROADMAP.md](ROADMAP.md) for full development plan.

**Phase 2 Features:**
- Event calendar integration
- User reviews and ratings
- Photo galleries for venues
- Google Maps integration
- Email newsletter signup
- Print-friendly PDF export

**Phase 3 Features:**
- Mobile app (PWA)
- User-submitted listings
- Admin dashboard
- Automated link checking
- Multi-language support (Irish/English)

## 📄 License

[Choose appropriate license - MIT, Creative Commons, etc.]

## 📞 Contact

For updates, corrections, or partnership inquiries:
- Email: [to be added]
- Facebook: [to be added]
- Website: [to be added]

## 🙏 Acknowledgments

Content compiled from:
- HEN Ireland (henireland.org)
- Mayo Sligo Home Educators Facebook group
- Galway Home Ed communities
- Local home educating families
- Venue websites and public information

---

**Last Updated:** February 2026
**Version:** 1.0
**Coverage:** Mayo, Galway, Sligo, Roscommon, Leitrim
