# IToolbox Logo Installation Instructions

## 📸 Extract Logo from Business Card

You have a business card image with the IToolbox logo. Follow these steps to extract and use it:

### Option 1: Extract Logo from Image (Recommended)

1. **Open the business card image** in an image editor (Photoshop, GIMP, Canva, etc.)

2. **Crop/Extract the logo**:
   - The logo is the red toolbox icon with "IT oolbox" text
   - Crop just the logo portion (approximately center-right of the card)

3. **Create transparent background**:
   - Remove the blue background
   - Save with transparency as PNG

4. **Logo file status**:
   - ✅ `itoolbox_logo_ipo-approved.jpg` (IPO-approved logo - saved!)
   - Additional formats can be added as needed

### Option 2: Use Online Tools

**Remove Background:**
1. Visit: https://remove.bg
2. Upload your business card image
3. Download the logo with transparent background
4. Crop to just the logo area

**Create Favicon:**
1. Visit: https://favicon.io
2. Upload your logo PNG
3. Download the favicon package
4. Extract to `assets/icons/` folder

### Option 3: Recreate Logo

If you have the original logo files:
1. Export as PNG with transparent background
2. Multiple sizes: 512x512, 256x256, 128x128, 64x64
3. Save to `assets/images/` folder

---

## 📁 File Structure

Place logo files in these locations:

```
assets/
├── images/
│   └── itoolbox_logo_ipo-approved.jpg  # ✅ Main logo (IPO-approved)
│
└── icons/
    ├── favicon.ico                  # 16x16, 32x32, 48x48
    ├── apple-touch-icon.png         # 180x180px
    ├── android-chrome-192x192.png
    └── android-chrome-512x512.png
```

---

## 🎨 Logo Specifications from Business Card

Based on your business card:

**Colors:**
- Primary Red: `#dc2626` ✅ (already updated in CSS)
- Secondary Red: `#b91c1c` ✅ (already updated in CSS)
- Red Accent: `#ef4444` ✅ (already updated in CSS)
- White/Light text: `#ffffff`

**Design Elements:**
- Red toolbox icon
- "IT oolbox" text (stylized)
- Network/connectivity theme (visible in card background)

---

## 🔧 After Saving Logo Files

### 1. Update HTML to use logo image

✅ **Already updated in `index.html`:**
```html
<div class="logo">
    <img src="assets/images/itoolbox_logo_ipo-approved.jpg" alt="IToolbox" height="45">
</div>
```

### 2. Add favicon to HTML

In `index.html` `<head>` section (around line 11), update:
```html
<!-- Favicon -->
<link rel="icon" type="image/x-icon" href="assets/icons/favicon.ico">
<link rel="icon" type="image/png" sizes="32x32" href="assets/icons/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="assets/icons/favicon-16x16.png">
<link rel="apple-touch-icon" sizes="180x180" href="assets/icons/apple-touch-icon.png">
```

### 3. Update footer logo

In `index.html` footer section (around line 350):
```html
<div class="logo">
    <img src="assets/images/itoolbox-icon.png" alt="IToolbox" height="30">
    <span>IToolbox</span>
</div>
```

---

## 🎯 Quick Start (If you already have the logo file)

```bash
# Navigate to assets folder
cd "/Users/nicomortel/Desktop/Nico M. Simulation Lab/itoolbox_lab/itoolbox_landing/landing_page/assets/images"

# Copy your logo file here
# Then refresh the browser to see changes
```

---

## ✅ Checklist

- [ ] Extract logo from business card image
- [ ] Remove background (make transparent)
- [ ] Save as PNG in multiple sizes
- [ ] Place in `assets/images/` folder
- [ ] Generate favicon using favicon.io
- [ ] Place favicons in `assets/icons/` folder
- [ ] Update HTML logo references
- [ ] Update HTML favicon links
- [ ] Test in browser
- [ ] Verify mobile display

---

## 🆘 Need Help?

If you need assistance extracting the logo:
1. I can guide you through using remove.bg
2. You can hire a designer on Fiverr (~$5-10)
3. Ask a friend with Photoshop/design skills

**Contact:** Nicole John A. Mortel
**Email:** itoolbox2019@gmail.com
**Phone:** +63 999 229 8724

---

**Note:** The red color scheme has already been applied to the website CSS to match your logo colors!
