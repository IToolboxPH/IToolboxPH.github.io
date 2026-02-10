# IToolbox Assets Folder

This folder contains all visual assets for the IToolbox landing page.

## 📁 Recommended Structure

```
assets/
├── images/
│   ├── itoolbox_logo_ipo-approved.jpg  # Company logo (IPO-approved) ✅
│   ├── hero-background.jpg   # Hero section background (optional)
│   ├── og-image.png          # Social media preview (1200x630px)
│   └── team/                 # Team member photos (when hired)
│       └── ceo.jpg
│
├── icons/
│   ├── favicon.ico           # Browser tab icon (16x16, 32x32)
│   ├── apple-touch-icon.png  # iOS home screen (180x180px)
│   └── android-chrome-*.png  # Android icons
│
└── downloads/                # Optional: Brochures, pitch decks
    ├── company-brochure.pdf
    └── product-overview.pdf
```

## 🎨 Design Assets Needed

### High Priority
1. **Company Logo**
   - ✅ Logo file saved: `itoolbox_logo_ipo-approved.jpg`
   - ✅ Implemented in navigation and footer
   - Format: JPG (IPO-approved version)

2. **Favicon**
   - Format: ICO or PNG
   - Size: 16x16, 32x32, 64x64px
   - Tool: Use https://favicon.io to generate from logo
   - Status: ⏳ To be created

3. **Social Media Image**
   - Format: PNG or JPG
   - Size: 1200x630px
   - Use: Open Graph meta tags

### Medium Priority
4. **Product Screenshots**
   - BilMoko dashboard mockup
   - InForMa monitoring interface
   - DigiCool school portal

5. **Company Photos**
   - Office/workspace
   - Team photos (when hired)
   - Product demos

### Low Priority
6. **Marketing Materials**
   - Business cards design
   - Letterhead template
   - Email signature

---

## 🔧 How to Add Assets

### 1. Add Logo to Landing Page
✅ **Already implemented in index.html:**
```html
<div class="logo">
    <img src="assets/images/itoolbox_logo_ipo-approved.jpg" alt="IToolbox" height="45">
</div>
```

### 2. Add Favicon
```html
<!-- In index.html <head> section -->
<link rel="icon" type="image/x-icon" href="assets/icons/favicon.ico">
<link rel="apple-touch-icon" sizes="180x180" href="assets/icons/apple-touch-icon.png">
```

### 3. Add Open Graph Image
```html
<!-- In index.html <head> section -->
<meta property="og:image" content="assets/images/og-image.png">
<meta property="og:image:width" content="1200">
<meta property="og:image:height" content="630">
```

---

## 🎨 Brand Guidelines

### Colors (from CSS)
- **Primary:** #2563eb (Blue)
- **Secondary:** #7c3aed (Purple)
- **Accent:** #06b6d4 (Cyan)
- **Success:** #10b981 (Green)
- **Warning:** #f59e0b (Orange)

### Typography
- **Font:** Inter
- **Weights:** 300 (Light), 400 (Regular), 600 (Semibold), 700 (Bold), 900 (Black)

### Logo Design Suggestions
- Incorporate toolbox icon (🛠️)
- Modern, tech-forward aesthetic
- Works in light and dark backgrounds
- Scalable to small sizes

---

## 📐 Image Specifications

### Favicon
- **Size:** 16x16, 32x32, 48x48px
- **Format:** ICO or PNG
- **Background:** Transparent or brand color

### Logo
- **Horizontal:** 1024x256px minimum
- **Square/Icon:** 512x512px minimum
- **Format:** PNG with transparency
- **Background:** Transparent

### Open Graph
- **Size:** 1200x630px
- **Format:** PNG or JPG
- **Text:** Minimal, high contrast
- **File size:** < 1MB

### Product Screenshots
- **Size:** 1920x1080px recommended
- **Format:** PNG or JPG
- **Quality:** High quality, clear text
- **File size:** Optimize to < 500KB

---

## 🚀 Next Steps

1. **Design Logo:**
   - Use Canva, Figma, or hire designer
   - Follow brand colors
   - Get multiple variations

2. **Generate Favicon:**
   - Visit https://favicon.io
   - Upload logo
   - Download favicon package

3. **Create Social Media Assets:**
   - Open Graph image
   - LinkedIn banner
   - Twitter header

4. **Organize Files:**
   - Use consistent naming
   - Keep originals in separate folder
   - Version control for updates

---

## 📝 Naming Conventions

Use lowercase with hyphens:
- ✅ `itoolbox_logo_ipo-approved.jpg` (current logo file)
- ✅ `product-bilmoko-screenshot.png`
- ✅ `team-ceo-photo.jpg`
- ❌ `IToolbox_Logo.PNG`
- ❌ `ProductScreen1.jpg`

---

**Last Updated:** February 5, 2026  
**Maintained By:** Nico M., CEO
