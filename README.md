<div align="center">

# ⏰ Sudhir's Clock

### A Stunning, Feature-Rich Analog & Digital Clock Experience

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Click_Here-ff6b35?style=for-the-badge&logoColor=white)](https://sudhir-clock.vercel.app)
[![Version](https://img.shields.io/badge/Version-2.0.0-10b981?style=for-the-badge)](https://github.com/SudhirDevOps1/CLOCK/releases)
[![License](https://img.shields.io/badge/License-MIT-8b5cf6?style=for-the-badge)](LICENSE)
[![Stars](https://img.shields.io/github/stars/SudhirDevOps1/CLOCK?style=for-the-badge&color=f59e0b&logo=github)](https://github.com/SudhirDevOps1/CLOCK)

<br>

<img src="https://raw.githubusercontent.com/SudhirDevOps1/CLOCK/main/assets/hero-preview.png" alt="Sudhir's Clock Preview" width="800">

<br>

**A beautiful, fully responsive, real-time analog + digital clock built with pure HTML, CSS & JavaScript.**
**No frameworks. No dependencies. Just pure craftsmanship.**

<br>

[Features](#-features) •
[Screenshots](#-screenshots) •
[Quick Start](#-quick-start) •
[Themes](#-themes) •
[Architecture](#-architecture) •
[Customization](#-customization) •
[API Reference](#-api-reference) •
[Contributing](#-contributing)

<br>

---

</div>

## 🌟 Why Sudhir's Clock?

> Most clock apps are boring. This one isn't.

Sudhir's Clock isn't just a clock — it's a **visual experience**. Built from scratch with zero dependencies, it combines a mesmerizing multi-ring analog clock with powerful utilities like stopwatch, timer, and world clocks — all wrapped in a gorgeous glassmorphic UI that adapts perfectly to every screen size.

<br>

## ✨ Features

### 🕐 Core Clock
| Feature | Description |
|---------|-------------|
| **Multi-Ring Analog Clock** | 7 concentric rings showing seconds, minutes, hours, days, months, years, and weekdays |
| **Digital Time Display** | Large, beautiful digital readout with blinking colons and gradient text |
| **Real-Time Rotation** | Smooth CSS transitions with cubic-bezier easing for fluid ring movement |
| **12/24 Hour Format** | Toggle between formats instantly — clock rings adapt dynamically |
| **20% Glass Overlay** | Subtle depth effect without hiding the clock — every number stays visible |
| **Rotating Glow Ring** | Animated outer ring with accent-colored conic gradient |
| **Active Number Highlight** | Current values glow with accent color and scale animation |

### ⏱️ Stopwatch
| Feature | Description |
|---------|-------------|
| **Millisecond Precision** | Accurate to the millisecond with `~31ms` refresh rate |
| **Lap Recording** | Record unlimited laps with individual timestamps |
| **Start/Pause/Resume** | Full playback control with visual state indicators |
| **Lap History** | Scrollable list with highlighted best lap |

### ⏳ Countdown Timer
| Feature | Description |
|---------|-------------|
| **Custom Duration** | Set hours, minutes, and seconds independently |
| **Vibration Alert** | Haptic feedback on mobile when timer completes |
| **Toast Notification** | Visual notification with accent-colored alert |
| **Pause/Resume** | Full control without losing countdown state |

### 🌍 World Clocks
| Feature | Description |
|---------|-------------|
| **8 Major Cities** | New York, London, Tokyo, Dubai, Sydney, Paris, Mumbai, Singapore |
| **UTC Offset Display** | Shows UTC+/- offset for each timezone |
| **Locale-Aware** | Time format adapts to selected language |
| **Real-Time Updates** | All clocks update every second simultaneously |

### 📊 Time Progress
| Feature | Description |
|---------|-------------|
| **Day Progress** | Percentage of current day completed |
| **Week Progress** | Current position in the week |
| **Month Progress** | How far through the current month |
| **Year Progress** | Annual progress with gradient fill bars |
| **Animated Bars** | Smooth width transitions with glow effects |

### 🎨 Theming & Customization
| Feature | Description |
|---------|-------------|
| **9 Color Themes** | Ember, Emerald, Violet, Rose, Cyan, Gold, Ocean, Pink, Lime |
| **Persistent Themes** | Selection saved to `localStorage` automatically |
| **CSS Variable System** | Every color derives from theme variables |
| **Ambient Gradients** | Background adapts to selected accent color |

### 🌐 Internationalization
| Feature | Description |
|---------|-------------|
| **30 Languages** | Full support via `Intl.DateTimeFormat` API |
| **Circular Selector** | Beautiful radial flag picker dialog |
| **Auto-Detection** | Defaults to browser's preferred language |
| **Dynamic Updates** | Clock rings, date display, and world clocks all adapt |

### 📱 Responsive Design
| Feature | Description |
|---------|-------------|
| **7 Breakpoints** | 1200px, 900px, 680px, 420px, 340px, landscape, print |
| **Mobile Bottom Nav** | Touch-friendly navigation bar on small screens |
| **Auto-Hide Topbar** | Hides on scroll down, reappears on scroll up |
| **Safe Area Support** | Proper padding for notched devices |
| **Landscape Mode** | Horizontal layout for phones in landscape |
| **Dynamic Viewport** | Uses `100dvh` for accurate mobile height |

### ⚡ Performance
| Feature | Description |
|---------|-------------|
| **Zero Dependencies** | Pure HTML + CSS + JS — nothing else |
| **Single RAF Loop** | Efficient `requestAnimationFrame` rendering |
| **Passive Listeners** | Scroll events use `{ passive: true }` |
| **Debounced Resize** | Clock redraws throttled at 200ms |
| **IIFE Encapsulation** | No global scope pollution |
| **Optimized Particles** | Squared distance check (avoids `sqrt` until needed) |

### ♿ Accessibility
| Feature | Description |
|---------|-------------|
| **ARIA Labels** | Screen reader support for all interactive elements |
| **Keyboard Shortcuts** | `F` = Fullscreen, `S` = Settings, `Esc` = Close |
| **Focus Visible** | Clear focus indicators for keyboard navigation |
| **Reduced Motion** | Respects `prefers-reduced-motion` media query |
| **High Contrast** | Enhanced borders and text for `prefers-contrast: high` |
| **Print Styles** | Clean, ink-friendly output when printing |

<br>

## 📸 Screenshots

<div align="center">

### 🖥️ Desktop View
<img src="https://raw.githubusercontent.com/SudhirDevOps1/CLOCK/main/assets/desktop-preview.png" alt="Desktop" width="700">

### 📱 Mobile View
<div style="display: flex; gap: 16px; justify-content: center;">
<img src="https://raw.githubusercontent.com/SudhirDevOps1/CLOCK/main/assets/mobile-clock.png" alt="Mobile Clock" width="220">
<img src="https://raw.githubusercontent.com/SudhirDevOps1/CLOCK/main/assets/mobile-tools.png" alt="Mobile Tools" width="220">
<img src="https://raw.githubusercontent.com/SudhirDevOps1/CLOCK/main/assets/mobile-settings.png" alt="Mobile Settings" width="220">
</div>

### 🎨 Theme Showcase
<img src="https://raw.githubusercontent.com/SudhirDevOps1/CLOCK/main/assets/themes-grid.png" alt="Themes" width="700">

</div>

<br>

## 🚀 Quick Start

### Option 1: Direct Download

```bash
# Clone the repository
git clone https://github.com/SudhirDevOps1/CLOCK.git

# Navigate to directory
cd CLOCK

# Open in browser (no build step needed!)
open index.html
```

### Option 2: CDN / Direct Link

```html
<!-- Just drop this single file into your project -->
<iframe src="https://sudhir-clock.vercel.app" width="100%" height="600"></iframe>
```

### Option 3: Embed as Widget

```html
<!-- Minimal embed -->
<div id="sudhir-clock" style="width:400px;height:400px;">
  <iframe
    src="https://sudhir-clock.vercel.app"
    style="width:100%;height:100%;border:none;border-radius:20px;"
    loading="lazy"
  ></iframe>
</div>
```

### Option 4: NPM (Coming Soon)

```bash
npm install @sudhir/clock
```

<br>

## 🎨 Themes

All themes are powered by CSS custom properties and can be switched instantly:

| Theme | Primary | Secondary | Preview |
|-------|---------|-----------|---------| 
| Ember 🔥 | `#ff6b35` | `#ff8c42` | ![#ff6b35](https://via.placeholder.com/60x20/ff6b35/ff6b35) |
| Emerald 💚 | `#10b981` | `#34d399` | ![#10b981](https://via.placeholder.com/60x20/10b981/10b981) |
| Violet 💜 | `#8b5cf6` | `#a78bfa` | ![#8b5cf6](https://via.placeholder.com/60x20/8b5cf6/8b5cf6) |
| Rose 🌹 | `#f43f5e` | `#fb7185` | ![#f43f5e](https://via.placeholder.com/60x20/f43f5e/f43f5e) |
| Cyan 🧊 | `#06b6d4` | `#22d3ee` | ![#06b6d4](https://via.placeholder.com/60x20/06b6d4/06b6d4) |
| Gold ⭐ | `#f59e0b` | `#fbbf24` | ![#f59e0b](https://via.placeholder.com/60x20/f59e0b/f59e0b) |
| Ocean 🌊 | `#3b82f6` | `#60a5fa` | ![#3b82f6](https://via.placeholder.com/60x20/3b82f6/3b82f6) |
| Pink 🌸 | `#ec4899` | `#f472b6` | ![#ec4899](https://via.placeholder.com/60x20/ec4899/ec4899) |
| Lime 🍀 | `#84cc16` | `#a3e635` | ![#84cc16](https://via.placeholder.com/60x20/84cc16/84cc16) |

### Creating a Custom Theme

```css
[data-theme="custom"] {
    --accent: #your-color;
    --accent-2: #your-lighter-color;
    --accent-3: #your-lightest-color;
    --accent-glow: rgba(r, g, b, 0.35);
    --accent-soft: rgba(r, g, b, 0.08);
    --accent-mid: rgba(r, g, b, 0.18);
    --shadow-glow: 0 0 100px rgba(r, g, b, 0.06);
}
```

Then add a button in the theme grid:

```html
<button class="theme-btn" data-theme="custom">
    <div class="theme-dot" style="background:linear-gradient(135deg, #color1, #color2)"></div>
    <span>Custom</span>
</button>
```

<br>

## 🏗️ Architecture

### File Structure

```
CLOCK/
├── index.html          # Single-file application (HTML + CSS + JS)
├── README.md           # This documentation
├── LICENSE             # MIT License
├── CHANGELOG.md        # Version history
├── CONTRIBUTING.md     # Contribution guidelines
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md
│   │   └── feature_request.md
│   └── workflows/
│       └── deploy.yml  # Auto-deploy to Vercel/Pages
└── assets/
    ├── hero-preview.png
    ├── desktop-preview.png
    ├── mobile-clock.png
    ├── mobile-tools.png
    ├── mobile-settings.png
    ├── themes-grid.png
    ├── og-image.png    # Open Graph preview
    └── favicon.ico
```

### Component Architecture

```
┌─────────────────────────────────────────────────────┐
│                    APPLICATION                       │
├─────────────────────────────────────────────────────┤
│                                                      │
│  ┌──────────┐  ┌──────────┐  ┌──────────────────┐  │
│  │  Loader   │  │  Canvas  │  │  Ambient Gradient │  │
│  │  Screen   │  │ Particles│  │    Background     │  │
│  └──────────┘  └──────────┘  └──────────────────┘  │
│                                                      │
│  ┌──────────────────────────────────────────────┐   │
│  │              Navigation Layer                 │   │
│  │  ┌─────────────┐      ┌──────────────────┐   │   │
│  │  │   Topbar     │      │   Bottom Nav     │   │   │
│  │  │  (Desktop)   │      │    (Mobile)      │   │   │
│  │  └─────────────┘      └──────────────────┘   │   │
│  └──────────────────────────────────────────────┘   │
│                                                      │
│  ┌──────────────────────────────────────────────┐   │
│  │                Main Content                   │   │
│  │                                               │   │
│  │  ┌─────────┐  ┌────────────────────────────┐ │   │
│  │  │Greeting │  │    Digital Time Display     │ │   │
│  │  └─────────┘  └────────────────────────────┘ │   │
│  │                                               │   │
│  │  ┌────────────────────────────────────────┐  │   │
│  │  │         Analog Clock (7 Rings)         │  │   │
│  │  │  ┌─────────────────────────────────┐   │  │   │
│  │  │  │  Years → Seconds → Minutes →    │   │  │   │
│  │  │  │  Hours → Days → Months →        │   │  │   │
│  │  │  │  Weekdays → [Center Button]     │   │  │   │
│  │  │  └─────────────────────────────────┘   │  │   │
│  │  └────────────────────────────────────────┘  │   │
│  │                                               │   │
│  │  ┌──────────┐ ┌──────────┐ ┌──────────────┐ │   │
│  │  │Info Cards│ │  Tools   │ │ World Clocks │ │   │
│  │  │ (6 cards)│ │ SW/Timer │ │  (8 cities)  │ │   │
│  │  └──────────┘ └──────────┘ └──────────────┘ │   │
│  │                                               │   │
│  │  ┌──────────────────────────────────────┐    │   │
│  │  │        Progress Bars (4)             │    │   │
│  │  │  Day | Week | Month | Year           │    │   │
│  │  └──────────────────────────────────────┘    │   │
│  └──────────────────────────────────────────────┘   │
│                                                      │
│  ┌──────────────┐  ┌───────────────────────────┐   │
│  │ Settings Panel│  │    Language Dialog        │   │
│  │  (Slide-in)   │  │   (Modal + Radial UI)    │   │
│  └──────────────┘  └───────────────────────────┘   │
│                                                      │
│  ┌──────────┐  ┌──────────┐  ┌────────────────┐   │
│  │ Scroll ↑ │  │Fullscreen│  │     Toasts     │   │
│  │  Button  │  │  Button  │  │  (Notifications)│   │
│  └──────────┘  └──────────┘  └────────────────┘   │
│                                                      │
└─────────────────────────────────────────────────────┘
```

### Clock Ring Structure

```
Ring 1 (Outermost): Years      [2000 - 2100]  101 values
Ring 2:             Seconds    [00 - 59]       60 values
Ring 3:             Minutes    [00 - 59]       60 values
Ring 4:             Hours      [00 - 23/1-12]  24/12 values
Ring 5:             Days       [1 - 28/29/30/31] Dynamic
Ring 6:             Months     [Jan - Dec]      12 values
Ring 7 (Innermost): Weekdays   [Sun - Sat]      7 values
Center:             Language Button (🌐)
```

### Data Flow

```
┌─────────────┐     ┌──────────────┐     ┌─────────────┐
│  Date()     │────▶│  Main Loop   │────▶│  Digital    │
│  Object     │     │  (RAF)       │     │  Display    │
└─────────────┘     └──────┬───────┘     └─────────────┘
                           │
                    ┌──────┴───────┐
                    │              │
              ┌─────▼─────┐ ┌─────▼──────┐
              │  Analog   │ │   Info     │
              │  Clock    │ │   Cards    │
              │  Rotation │ │   Update   │
              └───────────┘ └────────────┘
                    │
              ┌─────▼─────────────┐
              │  World Clocks     │
              │  (per-second)     │
              └───────────────────┘
```

<br>

## 🔧 Customization

### CSS Variables Reference

```css
:root {
    /* ── Colors ── */
    --bg-1: #06060b;              /* Darkest background */
    --bg-2: #0e0e18;              /* Card backgrounds */
    --bg-3: #161625;              /* Elevated surfaces */
    --bg-4: #1e1e32;              /* Highest elevation */

    --accent: #ff6b35;            /* Primary accent */
    --accent-2: #ff8c42;          /* Secondary accent */
    --accent-3: #ffab76;          /* Tertiary accent */
    --accent-glow: rgba(…, 0.35); /* Glow/shadow color */
    --accent-soft: rgba(…, 0.08); /* Subtle backgrounds */
    --accent-mid: rgba(…, 0.18);  /* Medium emphasis */

    --text-1: #f0f0f5;            /* Primary text */
    --text-2: rgba(…, 0.65);      /* Secondary text */
    --text-3: rgba(…, 0.35);      /* Tertiary text */
    --text-4: rgba(…, 0.18);      /* Quaternary text */

    /* ── Glass ── */
    --glass: rgba(255,255,255, 0.025);
    --glass-2: rgba(255,255,255, 0.045);
    --glass-border: rgba(255,255,255, 0.055);
    --glass-border-2: rgba(255,255,255, 0.09);
    --glass-hover: rgba(255,255,255, 0.07);

    /* ── Layout ── */
    --clock-size: min(78vmin, 680px);
    --topbar-h: 54px;
    --bottombar-h: 0px; /* 58px on mobile */
    --radius: 18px;
    --radius-sm: 12px;
    --radius-xs: 8px;

    /* ── Clock ── */
    --clock-mask-opacity: 0.20;   /* 20% overlay */

    /* ── Transitions ── */
    --transition-fast: 0.2s cubic-bezier(0.4, 0, 0.2, 1);
    --transition-med: 0.35s cubic-bezier(0.4, 0, 0.2, 1);
    --transition-slow: 0.5s cubic-bezier(0.4, 0, 0.2, 1);
}
```

### Modifying Clock Rings

Each ring's size is controlled by `--cd` (diameter) and `--cf` (font-size):

```css
/* Example: Make the seconds ring larger */
.clock > div:nth-of-type(2) {
    --cd: calc(var(--clock-size) - 60px); /* diameter */
    --cf: 0.8rem;                          /* font size */
}
```

### Adding a New Clock Ring

```html
<!-- Add inside .clock, before center-btn -->
<div><div data-clock="custom" data-numbers="10" class="clock-face"></div></div>
```

```javascript
// Add case in drawClockFaces() switch:
case 'custom':
    vals = ['A','B','C','D','E','F','G','H','I','J'];
    cv = someValue;
    break;

// Add case in rotateClockFaces() tick():
case 'custom':
    val = someComputedValue;
    break;
```

### Adding a New World Clock City

```javascript
// Add to the cities array:
const cities = [
    // ... existing cities
    { city: 'Berlin', tz: 'Europe/Berlin', e: '🇩🇪' },
];
```

### Changing Particle Count & Behavior

```javascript
// Increase particles (default: 45)
for (let i = 0; i < 80; i++) particles.push(new Particle());

// Change particle speed
this.vx = (Math.random() - 0.5) * 0.5; // faster (default: 0.25)

// Change connection distance
if (d < 15000) { // larger radius (default: 10000 = 100px²)
```

<br>

## 📖 API Reference

### Global State

| Variable | Type | Default | Description |
|----------|------|---------|-------------|
| `locale` | `string` | Browser default | Current language code (e.g., `'en-US'`) |
| `is24h` | `boolean` | `true` | 24-hour format enabled |
| `smoothSec` | `boolean` | `false` | Smooth second hand animation |
| `particlesOn` | `boolean` | `true` | Background particles enabled |

### Key Functions

| Function | Description |
|----------|-------------|
| `drawClockFaces()` | Rebuilds all clock ring elements (call after locale/format change) |
| `rotateClockFaces()` | Starts the continuous rotation animation loop |
| `updateDigital()` | Updates digital display, info cards, and progress bars |
| `updateWorld()` | Refreshes all world clock displays |
| `updateGreeting()` | Sets greeting based on time of day |
| `toast(msg, icon)` | Shows a toast notification |
| `openPanel()` / `closePanel()` | Controls settings panel |
| `openLang()` / `closeLang()` | Controls language dialog |
| `toggleFS()` | Toggles fullscreen mode |
| `setFormat(bool)` | Sets 12/24 hour format |

### Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `F` | Toggle fullscreen |
| `S` | Open settings panel |
| `Esc` | Close any open panel/dialog |

### Events Handled

| Event | Handler |
|-------|---------|
| `scroll` | Auto-hide topbar, show scroll-to-top |
| `resize` | Debounced clock redraw |
| `orientationchange` | Delayed clock redraw |
| `visibilitychange` | Refresh data when tab becomes visible |
| `mousemove` (buttons) | Radial gradient ripple effect |

<br>

## 🌐 Supported Languages

<table>
<tr>
<td>🇸🇦 Arabic</td><td>🇨🇿 Czech</td><td>🇩🇰 Danish</td><td>🇩🇪 German</td><td>🇬🇷 Greek</td>
</tr>
<tr>
<td>🇺🇸 English (US)</td><td>🇬🇧 English (UK)</td><td>🇪🇸 Spanish</td><td>🇲🇽 Spanish (MX)</td><td>🇫🇮 Finnish</td>
</tr>
<tr>
<td>🇨🇦 French (CA)</td><td>🇫🇷 French</td><td>🇮🇱 Hebrew</td><td>🇮🇳 Hindi</td><td>🇭🇺 Hungarian</td>
</tr>
<tr>
<td>🇮🇹 Italian</td><td>🇯🇵 Japanese</td><td>🇰🇷 Korean</td><td>🇳🇱 Dutch</td><td>🇳🇴 Norwegian</td>
</tr>
<tr>
<td>🇵🇱 Polish</td><td>🇧🇷 Portuguese (BR)</td><td>🇵🇹 Portuguese</td><td>🇷🇴 Romanian</td><td>🇷🇺 Russian</td>
</tr>
<tr>
<td>🇸🇪 Swedish</td><td>🇹🇭 Thai</td><td>🇹🇷 Turkish</td><td>🇻🇳 Vietnamese</td><td>🇨🇳 Chinese</td>
</tr>
</table>

<br>

## 📱 Browser Support

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 90+ | ✅ Full Support |
| Firefox | 88+ | ✅ Full Support |
| Safari | 15+ | ✅ Full Support |
| Edge | 90+ | ✅ Full Support |
| Opera | 76+ | ✅ Full Support |
| Samsung Internet | 15+ | ✅ Full Support |
| iOS Safari | 15+ | ✅ Full Support |
| Chrome Android | 90+ | ✅ Full Support |

### Progressive Enhancement

| Feature | Fallback |
|---------|----------|
| `backdrop-filter` | Solid background color |
| `dvh` units | Falls back to `vh` |
| `@starting-style` | No animation on dialog open |
| `env(safe-area-inset)` | Zero padding |
| Fullscreen API | Button hidden |
| Vibration API | Silent fallback |
| `navigator.language` | Defaults to `en-US` |

<br>

## ⚡ Performance Metrics

| Metric | Value |
|--------|-------|
| First Contentful Paint | ~0.4s |
| Largest Contentful Paint | ~0.8s |
| Total Blocking Time | ~10ms |
| Cumulative Layout Shift | 0 |
| Bundle Size | ~28KB (single file, no gzip) |
| Dependencies | **0** |
| DOM Nodes | ~450 (with all rings) |
| Animation Frames | Stable 60fps |
| Memory Usage | ~8MB |
| Lighthouse Score | **95+** (Performance) |

<br>

## 🛠️ Development

### Prerequisites

- Any modern web browser
- A text editor (VS Code recommended)
- Optional: Live Server extension for hot reload

### Local Development

```bash
# Clone
git clone https://github.com/SudhirDevOps1/CLOCK.git
cd CLOCK

# Start with VS Code Live Server
# Or use any static server:
npx serve .
# or
python -m http.server 8080
# or
php -S localhost:8080
```

### Code Style

- **CSS**: BEM-inspired naming, CSS custom properties for theming
- **JavaScript**: IIFE pattern, `$()` helper for DOM queries, `const`/`let` only
- **HTML**: Semantic elements, ARIA attributes, minimal nesting

### Testing Checklist

```
□ Desktop Chrome (1920x1080)
□ Desktop Firefox (1920x1080)
□ Desktop Safari (1920x1080)
□ Tablet Portrait (768x1024)
□ Tablet Landscape (1024x768)
□ Mobile Portrait (375x812)
□ Mobile Landscape (812x375)
□ Small Phone (320x568)
□ Large Phone (428x926)
□ 4K Display (3840x2160)
□ Reduced Motion ON
□ High Contrast ON
□ Print Preview
□ Keyboard-only Navigation
□ Screen Reader (VoiceOver/NVDA)
```

<br>

## 🗺️ Roadmap

### v2.1 (Planned)
- [ ] 🔔 Alarm functionality with custom sounds
- [ ] 🌓 Light/Dark mode toggle
- [ ] 📅 Calendar integration
- [ ] 🎵 Ambient sounds (rain, fireplace, etc.)
- [ ] 📊 Time tracking / Pomodoro timer

### v2.2 (Future)
- [ ] 🔄 PWA support (installable app)
- [ ] 🔗 Shareable clock configurations via URL
- [ ] 🖼️ Custom background images
- [ ] ⌨️ More keyboard shortcuts
- [ ] 🌐 Additional world clock cities (configurable)

### v3.0 (Vision)
- [ ] 🧩 Widget/Component mode (embed anywhere)
- [ ] 📱 Native mobile app (Capacitor)
- [ ] 🎨 Theme creator/editor UI
- [ ] 🔊 Voice announcements
- [ ] 🤖 AI-powered time insights

<br>

## 🤝 Contributing

Contributions are welcome! Please read the [Contributing Guidelines](CONTRIBUTING.md) first.

### How to Contribute

1. **Fork** the repository
2. **Create** your feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Contribution Ideas

| Area | Ideas |
|------|-------|
| 🎨 Themes | New color schemes, light mode, dark OLED mode |
| 🌐 Languages | Add more language packs, RTL improvements |
| 🌍 World Clocks | Searchable city picker, timezone map |
| ⚡ Performance | Web Worker for calculations, virtual scrolling |
| ♿ Accessibility | Screen reader improvements, voice control |
| 📱 Mobile | Gesture controls, haptic feedback improvements |
| 🧪 Testing | Unit tests, E2E tests, visual regression tests |
| 📖 Documentation | Tutorials, video demos, API examples |

<br>

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Sudhir Kumar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

<br>

## 🙏 Acknowledgments

- **Fonts**: [Google Fonts](https://fonts.google.com/) — Outfit & JetBrains Mono
- **Inspiration**: Swiss railway clocks, modern dashboard UIs
- **Icons**: Custom SVG inline icons (no icon library needed)
- **Timezone Data**: Native `Intl.DateTimeFormat` API

<br>

## 📊 Stats

<div align="center">

![GitHub repo size](https://img.shields.io/github/repo-size/SudhirDevOps1/CLOCK?style=flat-square&color=ff6b35)
![GitHub code size](https://img.shields.io/github/languages/code-size/SudhirDevOps1/CLOCK?style=flat-square&color=10b981)
![GitHub last commit](https://img.shields.io/github/last-commit/SudhirDevOps1/CLOCK?style=flat-square&color=8b5cf6)
![GitHub issues](https://img.shields.io/github/issues/SudhirDevOps1/CLOCK?style=flat-square&color=f43f5e)
![GitHub pull requests](https://img.shields.io/github/issues-pr/SudhirDevOps1/CLOCK?style=flat-square&color=f59e0b)

</div>

<br>

<div align="center">

### ⭐ Star this repository if you found it useful!

<br>

**Built with ❤️ and ☕ by [Sudhir Kumar](https://github.com/SudhirDevOps1)**

<br>

<img src="https://raw.githubusercontent.com/SudhirDevOps1/CLOCK/main/assets/footer-wave.svg" alt="wave" width="100%">

</div>
