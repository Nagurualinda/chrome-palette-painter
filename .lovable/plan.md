

# Chrome Theme Customizer Extension

A minimal, modern Chrome extension that lets users fully customize their browser's appearance with colors, backgrounds, and pre-made themes—all stored locally.

---

## Overview

This Chrome extension will give users complete control over Chrome's visual appearance. The extension will feature an intuitive popup interface where users can customize colors, select backgrounds, and preview changes in real-time.

---

## Core Features

### 1. Color Picker for Browser Elements
- **Toolbar color** customization
- **Tab strip** color options  
- **Frame/window border** colors
- **Text color** adjustments for readability
- Interactive color wheel + hex/RGB input

### 2. Custom Background Images
- **Upload your own images** for the new tab page
- **Built-in image gallery** with curated backgrounds
- **Solid color option** for minimalists
- Image positioning controls (fill, fit, center, tile)

### 3. Pre-Made Theme Templates
Includes starter themes ready to apply with one click:
- **Dark Mode** - Sleek dark grays and blacks
- **Light Mode** - Clean whites and soft grays  
- **Forest** - Deep greens and earthy browns
- **Ocean** - Calming blues and seafoam
- **Meadow** - Fresh greens and natural tones

### 4. Live Preview
- Real-time preview panel showing how changes will look
- Toggle between preview and current theme
- Undo/reset options before applying

### 5. Local Theme Storage
- Save unlimited custom themes to browser storage
- Name and organize your saved themes
- Import/export themes as JSON files
- No account or sign-in required

---

## Extension UI Design

### Popup Interface (Minimal & Modern)
- Clean, card-based layout
- Sidebar navigation with sections:
  - **Colors** - All color customization tools
  - **Background** - Image and background options
  - **Templates** - Pre-made theme gallery
  - **My Themes** - Saved custom themes
- Floating action button to apply changes
- Dark mode support for the extension UI itself

### New Tab Override
- Beautiful new tab page that showcases the custom theme
- Optional widgets (clock, quick links, search bar)
- Respects the user's background image choice

---

## Technical Approach

The extension will include:
- **manifest.json** - Extension configuration for Chrome
- **Popup HTML/CSS/JS** - The settings interface
- **New Tab page** - Custom new tab with theme applied
- **Background script** - Handles theme application and storage
- **Chrome Theme API** integration for native browser styling

---

## How You'll Use It

1. Download the extension files from Lovable
2. Go to `chrome://extensions` in Chrome
3. Enable "Developer mode"
4. Click "Load unpacked" and select the folder
5. Click the extension icon to start customizing!

