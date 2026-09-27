# CSK UI/UX Design Track — Session 1

> **Computer Society of Kirinyaga (CSK)**
> Facilitator: Morris | UI/UX Track Lead
> Track: UI/UX Design
> Session: 1 of the ongoing series

---

## Overview

This repository documents the content, resources, and exercises covered during **Session 1** of the CSK UI/UX Design Track. The session built on foundational Figma skills introduced in Session 1 and dived deeper into visual design techniques used in modern, professional UI design.

By the end of this session, students were able to:
- Apply the glassmorphism (glass effect) technique in Figma
- Install, manage and use icon libraries within Figma projects
- Import and work with images inside Figma frames
- Design and structure frames for desktop applications
- Apply layout principles specific to desktop UI design

---

## Table of Contents

- [Session Topics](#-session-topics)
  - [1. Glass Effect (Glassmorphism)](#1-glass-effect-glassmorphism)
  - [2. Using & Installing Icons](#2-using--installing-icons)
  - [3. Importing Images into Figma](#3-importing-images-into-figma)
  - [4. Designing Frames for Desktop Applications](#4-designing-frames-for-desktop-applications)
  - [5. Additional Concepts](#5-additional-concepts)
- [Tools & Resources](#-tools--resources)
- [Practice Exercises](#-practice-exercises)
- [Key Takeaways](#-key-takeaways)
- [Next Session Preview](#-next-session-preview)
- [Contributing](#-contributing)

---

## Session Topics

### 1. Glass Effect (Glassmorphism)

Glassmorphism is a modern UI design trend that creates a frosted-glass visual effect. It is widely used in dashboards, cards, and modal components in modern applications.

**What we covered:**
- What glassmorphism is and where it's used in real-world apps
- How to apply **background blur** in Figma (`Effects > Background Blur`)
- Setting the correct **fill opacity** on a rectangle to simulate glass transparency
- Adding a **subtle border** using stroke with low opacity to define the glass edge
- Layering elements behind the glass to make the blur visible and realistic
- Choosing the right **background gradient or image** to complement the glass card

**Step-by-step recap:**
1. Add a rectangle or frame over a colorful/image background
2. Set the fill color to white or a light tint at ~10–20% opacity
3. Add a Background Blur effect (value: 10–20px works well)
4. Add a 1px stroke at white ~30% opacity for the glass border
5. Add a subtle drop shadow for depth
6. Place your UI content (text, icons) inside the glass card

**Best practices:**
- Always test glassmorphism against a colorful or gradient background — it won't show on plain white
- Don't overuse it; reserve it for key UI elements like cards and modals
- Ensure enough contrast between text and the glass background for accessibility

---

### 2. Using & Installing Icons

Icons are a critical part of any UI design. They improve usability, reduce the need for text labels, and give your interface a polished, professional feel.

**What we covered:**
- The role of icons in UI design (clarity, navigation, aesthetics)
- How to access the **Figma Community** to find and install icon plugins
- Installing and using popular icon libraries:
  - **Iconify** — thousands of free open-source icons
  - **Material Design Icons** — Google's icon system
  - **Feather Icons** — minimal and clean icon set
- How to search, insert, and resize icons from a plugin
- Converting icons to frames/components for reuse
- Changing icon color and size while maintaining consistency

**How to install a plugin in Figma:**
1. Open Figma and go to the **Community** tab (or `Main Menu > Plugins > Browse plugins`)
2. Search for the icon plugin (e.g., "Iconify")
3. Click **Install**
4. Open it from `Main Menu > Plugins > [Plugin Name]`
5. Search for your icon, select it and click **Insert**

**Tips:**
- Stick to one icon style throughout a project (don't mix filled and outlined icons)
- Use a standard size (e.g., 24×24px) and scale up/down consistently
- Group related icons and store them in a shared component library

---

### 3. Importing Images into Figma

Images play a huge role in making designs feel real and presentable. Figma offers several ways to bring images into your design file.

**What we covered:**
- Drag and drop images directly onto the Figma canvas
- Using **Place Image** (`Ctrl/Cmd + Shift + K`) to place images into existing shapes or frames
- Filling a shape with an image via the **Fill panel** (click the fill color > switch to Image)
- Adjusting image fit options: **Fill**, **Fit**, **Crop**, and **Tile**
- Cropping images inside frames using the double-click method
- Using images as background fills for frames and components
- Sourcing free, high-quality images from:
  - [Unsplash](https://unsplash.com)
  - [Pexels](https://pexels.com)
  - [Pixabay](https://pixabay.com)

**Best practices:**
- Always use high-resolution images (at least 1920px wide for desktop designs)
- Use the **Crop** mode to focus on the most important part of an image
- Compress images before exporting to keep file sizes manageable
- Maintain consistent image aspect ratios across similar components (e.g., all profile pictures should be square)

---

### 4. Designing Frames for Desktop Applications

Frames are the foundation of every design in Figma. Understanding how to set up and structure frames for desktop applications is essential before building any UI.

**What we covered:**
- The difference between frames and groups in Figma
- How to create a frame using the **Frame tool (F)** and selecting a preset
- Standard desktop screen sizes:
  - **1440 × 900px** — common laptop screen
  - **1920 × 1080px** — full HD desktop
  - **1280 × 800px** — older laptops and smaller screens
- Setting up frames with the correct dimensions for desktop layouts
- Understanding **layout grids** for desktop design:
  - 12-column grid system
  - Gutter and margin settings for desktop (e.g., 24px gutters, 80px margins)
- Desktop vs mobile layout differences:
  - Desktop has more horizontal space — use multi-column layouts
  - Navigation is typically a top navbar or a left sidebar on desktop
  - More content can be displayed above the fold on desktop
- Grouping and organizing layers inside a frame for cleaner file structure
- Naming frames and layers descriptively for team collaboration

**Common desktop UI components we designed:**
- Navigation bar (top navbar with logo, links, CTA)
- Hero section with image and text layout
- Card grid layout (3–4 columns)
- Sidebar navigation layout
- Desktop form layout

**Tips:**
- Always start with a frame, not a blank canvas
- Use **Auto Layout** to make your frames responsive and easier to manage
- Name all your frames and layers — messy layers slow down collaboration
- Use a grid to align elements consistently

---

### 5. Additional Concepts

Beyond the main topics, we also touched on the following:

- **Color styles** — saving brand colors as reusable styles in Figma
- **Text styles** — setting up a type scale (H1, H2, Body, Caption) for consistency
- **Component basics** — turning repeated elements into components for reuse
- **Alignment & spacing** — using Figma's smart guides and alignment tools
- **Design hierarchy** — using size, weight, and color to guide the user's eye
- **Keyboard shortcuts** — key Figma shortcuts to speed up your workflow:

| Action | Shortcut (Mac) | Shortcut (Windows) |
|---|---|---|
| Frame tool | `F` | `F` |
| Rectangle | `R` | `R` |
| Text tool | `T` | `T` |
| Zoom to fit | `Shift + 1` | `Shift + 1` |
| Group | `Cmd + G` | `Ctrl + G` |
| Component | `Cmd + Alt + K` | `Ctrl + Alt + K` |
| Place image | `Cmd + Shift + K` | `Ctrl + Shift + K` |

---

## Tools & Resources

| Resource | Link | Purpose |
|---|---|---|
| Figma (Web) | [figma.com](https://figma.com) | Main design tool |
| Iconify Plugin | [iconify.design](https://iconify.design) | Icon library |
| Unsplash | [unsplash.com](https://unsplash.com) | Free images |
| Pexels | [pexels.com](https://pexels.com) | Free images & videos |
| Google Fonts | [fonts.google.com](https://fonts.google.com) | Free typography |
| Figma Community | [figma.com/community](https://figma.com/community) | Templates & plugins |
| Coolors | [coolors.co](https://coolors.co) | Color palette generator |
| CSS Glass | [css.glass](https://css.glass) | Glassmorphism reference |

---

##  Practice Exercises

Try these exercises on your own before the next session:

1. **Glassmorphism card** — Design a profile card using the glass effect over a gradient background. Include a profile image, name, role, and a follow button.

2. **Icon exploration** — Install the Iconify plugin and design a simple icon-based navigation bar for a mobile or desktop app.

3. **Desktop hero section** — Create a 1440×900px frame and design a hero section for an imaginary app. Include a navbar, headline, subtext, CTA button, and a hero image.

4. **Image gallery** — Design a 3-column image grid for a desktop app using images imported from Unsplash. Ensure all images are consistently cropped.

5. **Full desktop screen** — Combine everything: glassmorphism card, icons, imported images, and a well-structured desktop frame to create one complete desktop UI screen of your choice.

---

## Key Takeaways

- Glassmorphism creates depth and modern aesthetics — use it deliberately
- Icons should be consistent in style and size throughout a project
- Images should be high quality and properly cropped/fitted inside frames
- Desktop design requires wider, multi-column thinking compared to mobile
- Good layer naming and file organization are professional habits to build early
- Consistency in color, type, and spacing is what separates good design from great design

---

##  Next Session Preview

In **Session 3**, we will cover:
- Introduction to Auto Layout in Figma
- Building responsive components
- Prototyping and adding interactions
- Designing a complete mobile app screen from scratch

Make sure you have Figma open and your Session 2 practice exercises ready to review!

---

##  Contributing

This repository is maintained by the **CSK UI/UX Design Track**.

If you're a student and want to share your practice work:
1. Fork this repository
2. Add your design screenshots or notes inside a `/students/your-name/` folder
3. Open a Pull Request with a short description of what you designed

All contributions are welcome! Let's learn and grow together.

---

<div align="center">

**Computer Society of Kirinyaga (CSK)**
UI/UX Design Track · Session 
Facilitator: Morris muiruri

*Designing the future, one frame at a time.*

</div>
