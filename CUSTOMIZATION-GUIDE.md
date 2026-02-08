# 🎨 CRUNCH Customization Guide

Complete guide to customize fonts, logos, colors, and branding for your marketplace.

## 📍 Where to Edit

All customization settings are at the **TOP** of `index.html` in the `BRAND_CONFIG` object (around line 17).

---

## 🏷️ Brand Name

Change your marketplace name:

```javascript
name: "CRUNCH", // Change to your brand name
```

**Examples:**
- `"ServiceHub"`
- `"HomeConnect"`
- `"FixIt Pro"`

---

## 🎨 Logo Options

You have **3 logo types** to choose from:

### Option 1: Text Logo (Default)
```javascript
logo: {
    type: "text",
    text: "C", // Your letter/initials
    size: "40px"
}
```

### Option 2: Emoji Logo
```javascript
logo: {
    type: "emoji",
    emoji: "🏠", // Any emoji
    size: "40px"
}
```

**Popular emojis for service marketplaces:**
- 🏠 Home
- 🔧 Tools
- ⚡ Electric/Fast
- 🛠️ Repair
- 💼 Professional
- 🌟 Premium
- 🏆 Quality

### Option 3: Custom Image Logo
```javascript
logo: {
    type: "image",
    imageUrl: "https://yoursite.com/logo.png", // Your logo URL
    size: "40px"
}
```

**To use your own logo:**
1. Upload your logo to a hosting service (Imgur, Cloudinary, etc.)
2. Copy the direct image URL
3. Paste it in `imageUrl`

---

## 🌈 Colors

Customize your brand colors using hex codes:

```javascript
colors: {
    primary: "#2563eb",   // Main brand color (buttons, links)
    secondary: "#7c3aed", // Secondary color (gradients)
    accent: "#10b981",    // Success/verified badges
    danger: "#ef4444"     // Delete/warning buttons
}
```

### Color Palette Examples:

**Professional Blue (Default)**
```javascript
primary: "#2563eb"
secondary: "#7c3aed"
```

**Fresh Green**
```javascript
primary: "#10b981"
secondary: "#059669"
```

**Modern Purple**
```javascript
primary: "#8b5cf6"
secondary: "#6d28d9"
```

**Bold Orange**
```javascript
primary: "#f97316"
secondary: "#ea580c"
```

**Elegant Navy**
```javascript
primary: "#1e40af"
secondary: "#1e3a8a"
```

**Need help choosing colors?** Visit:
- [Coolors.co](https://coolors.co) - Color palette generator
- [Adobe Color](https://color.adobe.com)
- [Material Design Colors](https://materialui.co/colors)

---

## 🔤 Fonts

### Change Font Family

```javascript
fonts: {
    main: "Inter",     // Body text font
    heading: "Inter",  // Headings font (can be different)
    googleFonts: "URL_HERE"
}
```

### Popular Google Fonts:

**Modern & Clean:**
```javascript
main: "Poppins"
heading: "Poppins"
googleFonts: "https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap"
```

**Professional:**
```javascript
main: "Roboto"
heading: "Roboto"
googleFonts: "https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700;900&display=swap"
```

**Bold & Impactful:**
```javascript
main: "Montserrat"
heading: "Montserrat"
googleFonts: "https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700;800&display=swap"
```

**Elegant:**
```javascript
main: "Playfair Display"
heading: "Playfair Display"
googleFonts: "https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700;800&display=swap"
```

**Friendly & Rounded:**
```javascript
main: "Nunito"
heading: "Nunito"
googleFonts: "https://fonts.googleapis.com/css2?family=Nunito:wght@300;400;500;600;700;800&display=swap"
```

**Tech/Startup:**
```javascript
main: "Work Sans"
heading: "Work Sans"
googleFonts: "https://fonts.googleapis.com/css2?family=Work+Sans:wght@300;400;500;600;700;800&display=swap"
```

**Want more fonts?**
1. Visit [Google Fonts](https://fonts.google.com)
2. Select your font
3. Click "Select styles" (choose weights: 300, 400, 500, 600, 700, 800)
4. Copy the `<link>` URL
5. Paste in `googleFonts`

**Mix & Match Example:**
```javascript
main: "Open Sans"        // Clean body text
heading: "Montserrat"    // Bold headings
googleFonts: "https://fonts.googleapis.com/css2?family=Montserrat:wght@600;700;800&family=Open+Sans:wght@300;400;500&display=swap"
```

---

## 📝 Taglines & Copy

```javascript
tagline: "Home Services, Simplified"
subtitle: "Connect with trusted local professionals for all your home needs"
```

**Examples:**

For a cleaning marketplace:
```javascript
tagline: "Spotless Homes, Trusted Cleaners"
subtitle: "Book professional cleaning services in minutes"
```

For handyman services:
```javascript
tagline: "Fix Anything, Anytime"
subtitle: "Expert handymen ready to help with all your home repairs"
```

For general services:
```javascript
tagline: "Your Home, Our Experts"
subtitle: "Professional services at your fingertips"
```

---

## 🚀 Quick Customization Examples

### Example 1: "HomeHub" - Green Theme

```javascript
const BRAND_CONFIG = {
    name: "HomeHub",
    logo: {
        type: "emoji",
        emoji: "🏠",
        size: "40px"
    },
    colors: {
        primary: "#10b981",
        secondary: "#059669",
        accent: "#3b82f6",
        danger: "#ef4444"
    },
    fonts: {
        main: "Poppins",
        heading: "Poppins",
        googleFonts: "https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap"
    },
    tagline: "Home Services Made Easy",
    subtitle: "Professional help when you need it most"
};
```

### Example 2: "FixPro" - Orange & Bold

```javascript
const BRAND_CONFIG = {
    name: "FixPro",
    logo: {
        type: "text",
        text: "FP",
        size: "40px"
    },
    colors: {
        primary: "#f97316",
        secondary: "#ea580c",
        accent: "#10b981",
        danger: "#ef4444"
    },
    fonts: {
        main: "Roboto",
        heading: "Montserrat",
        googleFonts: "https://fonts.googleapis.com/css2?family=Montserrat:wght@600;700;800&family=Roboto:wght@300;400;500&display=swap"
    },
    tagline: "Expert Repairs, Every Time",
    subtitle: "Skilled professionals for all your home projects"
};
```

### Example 3: "Luxe Services" - Purple & Elegant

```javascript
const BRAND_CONFIG = {
    name: "Luxe",
    logo: {
        type: "text",
        text: "L",
        size: "40px"
    },
    colors: {
        primary: "#8b5cf6",
        secondary: "#6d28d9",
        accent: "#10b981",
        danger: "#ef4444"
    },
    fonts: {
        main: "Poppins",
        heading: "Playfair Display",
        googleFonts: "https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700;800&family=Poppins:wght@300;400;500&display=swap"
    },
    tagline: "Premium Home Services",
    subtitle: "Exceptional quality, delivered with care"
};
```

---

## 📋 Step-by-Step Customization

1. **Open `index.html`** in a text editor (VS Code, Notepad++, Sublime)

2. **Find the BRAND_CONFIG** (around line 17)

3. **Edit the values** following the examples above

4. **Save the file**

5. **Test locally:**
   - Open `index.html` in your browser
   - Refresh to see changes

6. **Deploy to Vercel:**
   - Push changes to your Vercel project
   - Changes will be live instantly

---

## 🎯 Pro Tips

✅ **Keep it consistent** - Use 2-3 main colors throughout
✅ **Test readability** - Make sure text is readable on all backgrounds
✅ **Mobile-friendly fonts** - Stick to clean, legible fonts
✅ **Brand personality** - Choose colors/fonts that match your service type
✅ **Save backups** - Keep the original file before making big changes

---

## 🆘 Troubleshooting

**Fonts not loading?**
- Check the Google Fonts URL is correct
- Make sure font name matches exactly (case-sensitive)

**Colors not changing?**
- Use proper hex format: `#2563eb` not `2563eb`
- Clear browser cache

**Logo not showing?**
- For images, make sure URL is direct link to image
- Test URL in a new browser tab first

---

## 🌟 Need Inspiration?

Check out these marketplaces for design ideas:
- TaskRabbit
- Thumbtack
- Handy
- Angi (formerly Angie's List)
- HomeAdvisor

---

**Your marketplace, your brand!** 🚀
