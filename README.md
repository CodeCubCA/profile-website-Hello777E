# Eric's Personal Portfolio Website

A stunning interactive portfolio featuring glassmorphism design with a vibrant purple gradient theme. This single-page application showcases personal information, projects, and includes three custom-built browser games with real-time gameplay and smooth animations.

## Live Demo

**Website**: [https://eric.codecub.org](https://eric.codecub.org)

**Repository**: [https://github.com/CodeCubCA/profile-website-Hello777E](https://github.com/CodeCubCA/profile-website-Hello777E)

---

## Table of Contents

- [Features](#features)
- [Sections](#sections)
- [Projects Showcase](#projects-showcase)
- [Interactive Games](#interactive-games)
- [Technologies Used](#technologies-used)
- [Design Highlights](#design-highlights)
- [File Structure](#file-structure)
- [Getting Started](#getting-started)
- [Browser Compatibility](#browser-compatibility)
- [License](#license)

---

## Features

### Core Features
- **Modern Glassmorphism Design** - Frosted glass effects with backdrop blur and semi-transparent overlays
- **Fully Responsive** - Optimized for desktop, tablet, and mobile devices
- **Interactive Games** - Three custom-built browser games with full gameplay mechanics
- **Smooth Animations** - CSS keyframe animations with cubic-bezier easing
- **No Dependencies** - Pure HTML5, CSS3, and Vanilla JavaScript
- **Single Page Application** - All content in one optimized file
- **Touch Support** - Virtual joystick and touch controls for mobile gaming
- **Data Persistence** - Local storage for game progress
- **Accessibility** - Keyboard navigation and clear visual feedback

### Interactive Elements
- Games menu modal with selection interface
- Hover effects on all interactive elements
- Click animations and transitions
- Escape key modal dismissal
- Responsive grid layouts
- Real-time game statistics tracking

---

## Sections

### 1. Header
- Clean, minimal header with name display
- Games menu button with hover effects
- Responsive navigation

### 2. About Me
- Personal information (age, school)
- Engaging personal description
- Gold accent highlights

### 3. My Hobbies
- Coding and building apps
- Reading tech books and fiction
- Playing strategy and indie games
- Listening to music and discovering new artists

### 4. My Projects
Showcases two major projects with:
- Project screenshots with gradient backgrounds
- Detailed descriptions
- Technology stack badges
- GitHub repository links
- Live demo links

### 5. Interactive Games
Three fully-functional browser games:
- Memory Match Game
- Diamond Clicker Game
- Island Adventure Game

### 6. Footer
- Thank you message
- Creative attribution

---

## Projects Showcase

### 1. Personal Portfolio Website
**Description**: A stunning interactive portfolio featuring glassmorphism design with a vibrant purple gradient theme. Showcases personal information, hobbies, and includes three custom-built browser games: Memory Match, Diamond Clicker, and Island Adventure with real-time gameplay and smooth animations.

**Tech Stack**:
- HTML5
- CSS3
- JavaScript
- Glassmorphism
- Responsive Design
- Git

**Links**:
- [Repository](https://github.com/CodeCubCA/profile-website-Hello777E)
- [Live Demo](https://eric.codecub.org)

---

### 2. AI ChatBox
**Description**: An intelligent AI-powered chatbot built with Streamlit and Google Gemini API. Features real-time conversation, context awareness, and deployed to the cloud with CI/CD. Perfect for students seeking instant help with homework, explanations, and learning support across various subjects.

**Tech Stack**:
- Python
- Streamlit
- Gemini 2.5 Flash API
- Git
- Streamlit Cloud

**Links**:
- [Repository](https://github.com/CodeCubCA/ai-chatbox-Hello777E)
- [Live Demo](https://ai-chatbox-eric-codecub.streamlit.app)

---

## Interactive Games

### 1. Memory Match Game 🧠

**Description**: Test your memory skills by finding matching pairs of cards. Challenge yourself with this classic brain training game!

**Features**:
- 4x3 grid with 6 pairs of emoji cards
- Move counter
- Timer (MM:SS format)
- Match tracking
- Win modal with final statistics
- Card flip animations
- Start/Restart functionality

**Gameplay**: Click cards to reveal symbols. Find all 6 matching pairs to win!

**Cards**: ⭐ Star, 🎈 Balloon, 🎯 Target, 🎨 Palette, 🌈 Rainbow, 🎪 Circus Tent

---

### 2. Diamond Clicker Game 💎

**Description**: Click diamonds to collect gems and unlock powerful upgrades. Build your mining empire in this addictive clicker game!

**Features**:
- Large clickable diamond with animations
- Per-click value display
- 5 upgrade tiers with increasing costs
- Auto-save to local storage (every 5 seconds)
- Floating number particles on clicks
- Number formatting (K, M, B, T)
- Reset functionality

**Upgrades**:
1. **Better Pick** ⛏️ - Cost: 25 → +1 per click
2. **Diamond Drill** 🔧 - Cost: 150 → +2 per click
3. **Mining Robot** 🤖 - Cost: 750 → +5 per click
4. **Diamond Factory** 🏭 - Cost: 5,000 → +10 per click
5. **Quantum Miner** ⚡ - Cost: 25,000 → +25 per click

**Mechanics**: Each upgrade purchase increases cost by 1.5x

---

### 3. Island Adventure 🏝️

**Description**: Sail the high seas, explore mysterious islands, and fight zombies with your sword in this 3D-style adventure game!

**Features**:
- Canvas-based 2D graphics with camera system
- Two game modes: Sailing Mode and Island Mode
- Player health system (0-100 HP)
- Score tracking
- 5 explorable islands
- Zombie AI and combat
- Minimap navigation
- Touch controls with virtual joystick
- Pause/Resume functionality
- Real-time statistics

**Gameplay**:
- **Sailing Mode**: Navigate your boat across a 2000x2000 world to discover islands
- **Island Mode**: Dock at islands to explore and fight 6-14 spawned zombies
- **Combat**: Swing your sword to eliminate zombies (+10 points each)
- **Health**: Zombies deal 10 damage per attack; game over at 0 HP

**Controls**:
- **Desktop**: WASD/Arrow Keys (move), Space/Click (attack)
- **Mobile**: Virtual joystick (move), Action buttons (attack/dock)
- **Other**: Dock button (toggle island mode), Pause, Help, Reset

**Game Elements**:
- **Player**: Red circle with sword attack animation
- **Boat**: Brown rectangle with sail, rotates with movement
- **Islands**: Brown circles with tree decorations
- **Zombies**: Green circles with red eyes, chase and attack player
- **Minimap**: Real-time overview of world and positions

---

## Technologies Used

### Core Technologies
- **HTML5** - Semantic markup and Canvas API
- **CSS3** - Advanced styling with modern features
- **JavaScript (Vanilla)** - No external frameworks

### CSS Techniques
- **Glassmorphism** - Frosted glass effect with `backdrop-filter: blur()`
- **CSS Variables** - Custom properties for consistent theming
- **CSS Grid** - Responsive layouts for projects and games
- **Flexbox** - Flexible arrangements for buttons and controls
- **Linear Gradients** - Purple-to-violet theme and tech badges
- **Radial Gradients** - Pulse effects and ambient lighting
- **Keyframe Animations** - 15+ custom animations with smooth easing
- **Media Queries** - Responsive breakpoints at 768px and 480px
- **Transform & Transition** - Smooth animations with cubic-bezier
- **Box Shadow** - Multi-layer depth effects
- **Text Shadow** - Enhanced readability

### JavaScript Features
- **Object-Oriented Programming** - Class-based game architecture
- **DOM Manipulation** - Dynamic content rendering
- **Event Listeners** - Mouse, keyboard, and touch handlers
- **Local Storage** - Game progress persistence
- **Canvas API** - 2D graphics rendering
- **Request Animation Frame** - 60fps game loop
- **Touch Support** - Virtual joystick for mobile
- **Math Functions** - Trigonometry and distance calculations

---

## Design Highlights

### Color Scheme
- **Primary Gradient**: `#667eea` → `#764ba2` (Purple to Violet)
- **Accent Color**: `#ffd700` (Gold)
- **Text Colors**: White with varying opacity (100%, 85%, 70%)
- **Glass Effects**: Semi-transparent white overlays

### Tech Badge Gradients
- **HTML5**: Orange (`#e34c26` → `#f06529`)
- **CSS3**: Blue (`#264de4` → `#2965f1`)
- **JavaScript**: Yellow (`#f0db4f` → `#f7df1e`)
- **Python**: Blue-Yellow (`#3776ab` → `#ffd343`)
- **Streamlit**: Red (`#ff4b4b` → `#ff6b6b`)
- **Gemini API**: Purple (`#8b5cf6` → `#a78bfa`)
- **Git**: Red-Orange (`#f05032` → `#e84e31`)
- **Cloud**: Pink (`#ec4899` → `#f472b6`)
- **Responsive**: Cyan (`#61dafb` → `#21a1c4`)
- **Glassmorphism**: Translucent white with blur

### Spacing System
- **XS**: 0.5rem
- **SM**: 1rem
- **MD**: 1.5rem
- **LG**: 2rem
- **XL**: 3rem

### Border Radius
- **Small**: 8px
- **Medium**: 12px
- **Large**: 20px

### Typography
- **Font Stack**: System fonts for optimal performance
- **H1**: 2.5-4rem, ultra-light (200), 4px letter-spacing
- **Section Headings**: 2.25rem, light (200)
- **Body**: 1rem, line-height 1.6

### Animations
- Fade-in-up for sections (staggered delay)
- Pulse effect for project images
- Bounce animation for modal icons
- Shine effect on diamond button
- Floating particles on clicks
- Sword swing and zombie hit animations
- Damage flash effect

---

## File Structure

```
profile-website/
├── index.html              # Main SPA (3776 lines)
├── README.md               # This file
├── .gitignore              # Git ignore rules
└── img/
    ├── profile.png         # Portfolio website screenshot
    └── chatbox.png         # AI ChatBox screenshot
```

**Note**: This is a single-page application with all HTML, CSS, and JavaScript embedded in one optimized file. No build process or external dependencies required.

---

## Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No installation or build tools required

### Running Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/CodeCubCA/profile-website-Hello777E.git
   cd profile-website-Hello777E
   ```

2. **Open in browser**:
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Python 3
     python -m http.server 8000

     # Python 2
     python -m SimpleHTTPServer 8000

     # Node.js (with npx)
     npx http-server
     ```

3. **View the website**:
   - Navigate to `http://localhost:8000` (if using a server)
   - Or directly open the `index.html` file

### Deployment

This website can be deployed to any static hosting service:
- **GitHub Pages**: Push to `gh-pages` branch
- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your GitHub repository
- **Cloudflare Pages**: Deploy from Git

---

## Browser Compatibility

### Supported Browsers
- ✅ Chrome 90+ (recommended)
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+

### Required Features
- CSS Grid and Flexbox
- CSS Custom Properties (Variables)
- Backdrop Filter (for glassmorphism)
- Canvas API (for Island Adventure game)
- Local Storage (for game saves)
- Touch Events (for mobile controls)

### Mobile Support
- ✅ iOS Safari 14+
- ✅ Chrome Mobile 90+
- ✅ Samsung Internet 14+
- ✅ Firefox Mobile 88+

**Note**: The website is fully responsive with touch controls for mobile gaming.

---

## Performance Features

- **No External Dependencies** - Zero HTTP requests for libraries
- **Single File Architecture** - Minimal HTTP requests
- **Optimized Animations** - GPU-accelerated transforms
- **Efficient Canvas Rendering** - 60fps game loop with RAF
- **Lazy Game Loading** - Games initialize only when opened
- **Local Storage Caching** - Persistent game progress

---

## Key Technical Implementations

### Glassmorphism Effect
```css
backdrop-filter: blur(20px) saturate(1.8);
background: rgba(255, 255, 255, 0.08);
border: 1px solid rgba(255, 255, 255, 0.18);
box-shadow: 0 8px 32px rgba(0, 0, 0, 0.12);
```

### Game Architecture
- Class-based design for each game
- State management (menu, sailing, island, paused)
- Event listener cleanup on destroy
- 60fps canvas rendering with requestAnimationFrame

### Responsive Canvas
- Dynamic sizing based on viewport
- Touch controls for mobile devices
- Minimap scaling
- Adaptive UI elements

### Data Persistence
- Auto-save every 5 seconds (Diamond Clicker)
- localStorage with JSON serialization
- Graceful fallback if unavailable

---

## Development

### Project Structure
- **Lines of Code**: 3776 lines in single HTML file
- **CSS Classes**: 100+ custom classes
- **JavaScript Classes**: 4 game/menu classes
- **Animations**: 15+ keyframe animations
- **Media Queries**: 2 responsive breakpoints

### Code Organization
1. **CSS Variables** (lines 8-27) - Theme configuration
2. **Global Styles** (lines 29-161) - Base styling
3. **Section Styles** (lines 162-267) - Content sections
4. **Projects Styles** (lines 267-467) - Project cards
5. **Game Styles** (lines 468-1600) - All game styling
6. **Responsive Styles** (lines 1601-1720) - Media queries
7. **HTML Content** (lines 1721-2070) - Markup
8. **JavaScript** (lines 2071-3776) - Interactivity and games

---

## Credits

**Developer**: Eric

**Age**: 13 years old

**Skills Demonstrated**:
- Advanced CSS (Glassmorphism, Animations, Grid/Flexbox)
- Vanilla JavaScript (OOP, Canvas API, Game Development)
- Responsive Web Design
- UI/UX Design
- Game Development
- Version Control (Git)

---

## License

This project is open source and available for educational purposes.

---

## Contact

- **Portfolio**: [https://eric.codecub.org](https://eric.codecub.org)
- **GitHub**: [CodeCubCA](https://github.com/CodeCubCA)

---

**Made with passion for coding and creativity** ⭐

---

## Acknowledgments

- Thanks to all the open-source projects that inspired this work
- Special thanks to the web development community for their resources and tutorials
- GitHub Classroom for the assignment framework

---

*Last Updated: October 2024*
