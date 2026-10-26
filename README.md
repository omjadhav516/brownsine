# 🌌 SAYALI — A UNIVERSE MADE FOR YOU ✨

> *"Every star in this universe shines a little brighter because you exist."*

A complete, premium, multi-page birthday website built as a private cinematic experience — dedicated to Sayali, My Prettiest Bebe.

---

## 📁 Project Structure

```
BIRTHDAY FILE/
├── index.html          ← Cinematic Welcome (Page 1)
├── birthday.html       ← Birthday Home (Page 2)
├── our-story.html      ← Our Story Timeline (Page 3)
├── memories.html       ← Memory Museum Gallery (Page 4)
├── gifts.html          ← Magical Gift Room (Page 5)
├── letter.html         ← Love Letter (Page 6)
├── our-song.html       ← Our Song Player (Page 7)
├── wishes.html         ← Wishing Galaxy (Page 8)
├── forever.html        ← Grand Finale (Page 9)
├── css/
│   └── styles.css      ← Master design system
├── js/
│   └── main.js         ← Shared animations & interactions
└── assets/
    ├── images/         ← All personal photographs (14 images)
    └── audio/          ← Place your song file here
```

---

## 🚀 How to Open (No Installation Required)

This is a pure HTML/CSS/JavaScript website — **no Node.js, npm, or build step needed**.

### Option 1 — Double-click (Quickest)
1. Navigate to the `BIRTHDAY FILE` folder
2. Double-click `index.html`
3. It opens directly in your browser ✨

### Option 2 — Local server (Recommended for best experience)

If you have Python installed:
```bash
# Python 3
python -m http.server 8080

# Then open: http://localhost:8080
```

If you have VS Code with Live Server extension:
- Right-click `index.html` → "Open with Live Server"

---

## 🎵 Adding Your Song

To enable the music player on the **Our Song** page:

1. Copy your music file to: `assets/audio/our-song.mp3`
   - Supported formats: `.mp3`, `.ogg`, `.wav`, `.m4a`
2. Open `our-song.html` and update the song configuration at the bottom:
   ```js
   const SONG_FILE   = 'assets/audio/our-song.mp3'; // your file
   const SONG_TITLE  = 'Our Song';                   // song name
   const SONG_ARTIST = 'For Sayali, with love ❤️';   // subtitle
   ```

---

## ✏️ Personalizing Content

### Update the "Days Together" counter
In `birthday.html`, find this line and update the start date:
```js
const startDate = new Date('2023-01-01'); // ← Change to your anniversary
```

### Edit the Love Letter
Open `letter.html` — the letter text is in the `.letter-paper` section. Every paragraph is clearly marked and editable.

### Edit the "Reasons You Are Special"
In `gifts.html`, find the `const reasons = [...]` array and replace the items with your personal reasons.

### Edit "Our Future Dreams"
In `gifts.html`, find the `<div id="future-dreams">` section and update the coupon text.

### Edit "Our Story" Timeline
In `our-story.html`, update each `.tl-card` with your real story details.

---

## 📸 Photographs Used

All 14 personal photographs are in `assets/images/` with friendly names:

| File | Description |
|------|-------------|
| `sayali-star-queen.jpg` | Solo portrait in black outfit |
| `sayali-solo-black-dress.jpg` | Solo portrait — black embroidered outfit |
| `sayali-solo-garden-pose.jpg` | Solo in garden |
| `sayali-solo-pout-trail.jpg` | Solo on a scenic trail |
| `sayali-star-queen.jpg` | Purple saree portrait |
| `sayali-couple-embrace.jpg` | Together — light/white tones |
| `sayali-couple-yellow-love.jpg` | Together — yellow outfits |
| `sayali-couple-arms-around.jpg` | Together — plaid outfits |
| `sayali-couple-happylife.jpg` | Together — pink stripe outfit |
| `sayali-couple-nature-portrait.jpg` | Nature outing portrait |
| `sayali-couple-nature-full.jpg` | Full nature outing shot |
| `sayali-kiss-cheek.jpg` | Sayali kissing cheek |
| `husband-kiss-sayali.jpg` | Husband kissing Sayali |
| `sayali-playful-poke.jpg` | Playful together photo |
| `sayali-sweet-duo.jpg` | Sweet selfie together |

---

## 🌐 Publishing Online

### Free hosting with Netlify Drop (Easiest)
1. Go to **https://app.netlify.com/drop**
2. Drag and drop the entire `BIRTHDAY FILE` folder
3. Get a live URL in seconds (e.g., `https://random-name.netlify.app`)
4. Share the link with Sayali!

> ⚠️ **Privacy Note:** A publicly hosted website is accessible to anyone with the URL. If you prefer privacy, share it locally by opening `index.html` directly on your device, or use a password-protected service.

### Other free options
- **GitHub Pages** — Free, requires GitHub account
- **Vercel** — Free, very fast
- **Surge.sh** — Simple CLI deployment

---

## 🎨 Nine Pages Overview

| # | Page | File | Highlight |
|---|------|------|-----------|
| 1 | Cinematic Welcome | `index.html` | Star sequence, heart constellation, galaxy zoom |
| 2 | Birthday Home | `birthday.html` | Hero photo, interactive cake with candles |
| 3 | Our Story | `our-story.html` | Animated timeline with real photos |
| 4 | Memory Museum | `memories.html` | Masonry gallery, filters, lightbox, polaroids |
| 5 | Magical Gift Room | `gifts.html` | 6 interactive gifts with animations |
| 6 | Love Letter | `letter.html` | Animated envelope, paper-textured letter |
| 7 | Our Song | `our-song.html` | Vinyl player, equalizer, full controls |
| 8 | Wishing Galaxy | `wishes.html` | Click-to-plant stars, wish reveals |
| 9 | Grand Finale | `forever.html` | Cinematic sequence, confetti, collage |

---

## 💖 Made With Love

Built by her husband for **Sayali — My Prettiest Bebe.**  
Happy Birthday. May this little universe bring you as much joy as you bring to mine.

*— Your Husband ❤️*
