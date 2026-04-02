# 🎂 Happy Birthday Umang — Birthday Website

A beautiful, emotional, and visually stunning single-page birthday website for Umang, crafted with love.

---

## ✅ Completed Features

### 🌸 Intro Animation
- Full-screen overlay with animated "Happy Birthday, Umang ❤️" text
- Fades out after ~3 seconds to reveal the main page

### 🦋 Hero Section
- Animated gradient background (pink → lavender → peach, cycling)
- Floating hearts & particle canvas animation in the background
- Big title: *"Happy Birthday to the Most Special Girl 💖"*
- Gradient name display: **Umang**
- Glowing "Start the Surprise ✨" scroll button

### 🎉 Confetti
- Canvas-confetti burst fires on page load (two waves)
- Additional confetti burst when surprise modal opens

### 📸 Photo Gallery
- Responsive grid of 8 photos with captions
- Hover effects (scale, glow, shadow)
- Click-to-open lightbox for full-size preview
- Keyboard/Escape support to close lightbox
- Section title: *"Moments That Make My Heart Smile 📸"*

### 💌 Birthday Message
- Typewriter animation triggers when section scrolls into view
- Long, emotional message with a handwriting-style font (Dancing Script)
- Glassmorphism card with decorative quote marks

### ✨ Compliments Section
- 8 pastel compliment cards in a responsive grid
- Top gradient accent bar on each card
- Slide-up animation on scroll using Intersection Observer

### 🎁 Final Surprise
- Bouncing gift icon animation
- Glowing gradient "Click for a Surprise 🎁" button
- Opens animated modal popup with:
  - Multi-burst confetti from both sides
  - Pulsing hearts
  - Heartfelt personal message
  - Close button

### 🎵 Background Music
- Floating music button (top-right)
- Auto-attempts to play on first user interaction
- Toggle between play/pause

### ✨ Extra Details
- Custom sparkle cursor trail (desktop)
- Scroll-triggered reveal animations (fade-in + slide-up)
- Scroll-to-top button
- Fully mobile responsive

---

## 📁 File Structure

```
index.html    — Main (and only) file — all HTML, CSS & JS embedded
README.md     — Project documentation
```

---

## 🔗 Entry Points

| Path        | Description             |
|-------------|-------------------------|
| `/`         | Main birthday page      |
| `/#gallery` | Photo gallery section   |
| `/#message` | Heartfelt message       |
| `/#surprise`| Final surprise section  |

---

## 🛠️ Tech Stack

- **HTML5 / CSS3 / Vanilla JavaScript**
- **Google Fonts**: Dancing Script, Poppins
- **Font Awesome 6** (CDN)
- **canvas-confetti** (CDN) for confetti animations
- Intersection Observer API for scroll animations
- Canvas API for particle effects

---

## 🎨 Color Palette

| Name        | Hex       |
|-------------|-----------|
| Rose Pink   | `#ff6b9d` |
| Lavender    | `#c084fc` |
| Light Pink  | `#f9a8d4` |
| Deep Purple | `#4a1942` |
| Body Text   | `#6b4c6e` |

---

## 📌 Notes / Next Steps

- Replace the background music URL with a preferred royalty-free track if needed
- Photos are loaded directly from provided URLs
- All animations work on modern browsers (Chrome, Firefox, Safari, Edge)

---

*Made with 💖 especially for Umang*
