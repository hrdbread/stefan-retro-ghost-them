# Stefan's Retro Ghost Theme

A dark mode retro portfolio theme for Ghost CMS featuring neon pink accents, animated elements, and 90s-inspired design.

![Theme Preview](https://via.placeholder.com/800x400/000000/ff1493?text=Stefan's+Retro+Theme)

## 🌟 Features

- **Dark Mode Design** - Sleek black background with neon pink accents
- **Retro Typography** - Custom Google Fonts (Chewy, Bungee, Press Start 2P)
- **Animated Elements** - Floating dots, marquee text, and pulse effects
- **Responsive Layout** - Looks great on all devices
- **Accessibility** - WCAG compliant with reduced motion support
- **Ghost CMS Integration** - Full Ghost v5+ compatibility
- **SEO Optimized** - Structured data and meta tags
- **Custom Pages** - Special styling for About and Contact pages

## 🎨 Design Elements

- Starfield background with pink and white stars
- Neon glowing borders and effects
- Retro visitor counter
- Animated marquee banner
- Glassmorphism header effects
- Custom skill bars and mission sections

## 📦 Installation

### Method 1: Download Release
1. Go to [Releases](../../releases)
2. Download the latest `stefan-retro-theme.zip`
3. Upload to Ghost Admin → Design → Upload Theme

### Method 2: Clone Repository
```bash
cd /var/www/ghost/content/themes
git clone https://github.com/YOUR_USERNAME/stefan-retro-ghost-theme.git
cd stefan-retro-ghost-theme
zip -r stefan-retro-theme.zip . -x "*.git*" "*.DS_Store*" "README.md"
```

### Method 3: Manual Download
1. Click "Code" → "Download ZIP"
2. Extract and upload to Ghost

## 🛠️ Setup

1. **Install Theme** in Ghost Admin
2. **Activate Theme** in Design settings
3. **Create Required Pages:**
   - About page with slug: `about`
   - Contact page with slug: `contact` 
   - Archive page with slug: `archive`
4. **Customize** navigation in Ghost Admin
5. **Add your content** and enjoy!

## 📄 Required Pages

The theme includes special styling for these pages:

### About Page (`/about/`)
- Displays skills with animated progress bars
- Mission statement section with icons
- Custom retro styling

### Contact Page (`/contact/`)
- Contact information section
- Contact form (requires Ghost Pro or custom setup)
- Web ring links section

### Archive Page (`/archive/`)
- Lists all blog posts
- Grid layout with featured images
- Pagination support

## 🎯 Customization

### Colors
Edit `assets/css/style.css` to change the color scheme:
```css
/* Primary neon pink */
#ff1493

/* Secondary pink */
#ff69b4

/* Background */
#000000

/* Cards */
#111827
```

### Fonts
The theme uses Google Fonts loaded in `default.hbs`:
- **Chewy** - Main headings and buttons
- **Bungee** - Section headers and navigation
- **Press Start 2P** - Retro elements like visitor counter

### Site Information
Update these in Ghost Admin → Settings → General:
- Site title (appears in header)
- Site description (appears under title)
- Navigation (customize menu items)

## 🔧 Development

### File Structure
```
stefan-retro-ghost-theme/
├── package.json          # Theme configuration
├── default.hbs           # Main layout template
├── index.hbs            # Homepage template
├── post.hbs             # Individual post template
├── page.hbs             # Static pages template
├── archive.hbs          # All posts archive
├── tag.hbs              # Tag archive template
├── error.hbs            # 404 error page
├── partials/
│   └── pagination.hbs   # Pagination component
└── assets/
    └── css/
        └── style.css    # All theme styles
```

### Local Development
1. Clone the repository
2. Symlink to Ghost themes folder:
   ```bash
   ln -s /path/to/stefan-retro-ghost-theme /var/www/ghost/content/themes/
   ```
3. Restart Ghost and activate theme
4. Make changes and refresh to see updates

## 🌐 Browser Support

- Chrome/Chromium 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## ♿ Accessibility

- Semantic HTML5 structure
- ARIA labels and roles
- Keyboard navigation support
- Respects `prefers-reduced-motion`
- High contrast color combinations
- Focus indicators

## 📱 Responsive Design

- Mobile-first approach
- Responsive grid layouts
- Touch-friendly navigation
- Optimized images
- Readable typography on all screens

## 🚀 Performance

- Optimized CSS (no unused styles)
- Minimal JavaScript
- Efficient animations
- Compressed images
- Fast loading fonts

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 Changelog

### v1.0.0 (2025-01-XX)
- Initial release
- Dark mode design with neon pink accents
- Retro typography and animations
- Full Ghost v5+ compatibility
- Responsive design
- Accessibility features

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Stefan Twerdochlib**
- Website: [twerdochlib.com](https://twerdochlib.com)
- Email: stefan@twerdochlib.com
- Design Lead at Wolt

## 🙏 Acknowledgments

- Ghost CMS team for the excellent platform
- Google Fonts for the retro typography
- 90s web design for inspiration
- Geocities for the nostalgic vibes

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Issues](../../issues) page
2. Search for existing solutions
3. Create a new issue with details
4. Email: stefan@twerdochlib.com

---

**⭐ Star this repository if you find it useful!**
