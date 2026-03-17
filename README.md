# RS School JavaScript/Frontend 2025 Q3 - Portfolio Projects

This repository contains my portfolio projects completed during the **RS School JavaScript/Frontend 2025 Q3** course. The course is a comprehensive frontend development program that covers modern web technologies, responsive design, and interactive functionality implementation.

## About the Course

RS School is a free, community-based online education program run by The Rolling Scopes community. The JavaScript/Frontend course offers intensive training in modern frontend development.

## Projects

- **Portfolio Website** — [View Project](https://rolling-scopes-school.github.io/ulyana0siadziuk-JSFE2025Q3/portfolio/)
- **Virtual Music Kit** — [View Project](https://rolling-scopes-school.github.io/ulyana0siadziuk-JSFE2025Q3/virtual-music-kit/)
- **Museum Website (Louvre)** — [View Project](https://rolling-scopes-school.github.io/ulyana0siadziuk-JSFEPRESCHOOL2025Q2/museum/)

### 1. Portfolio Website

#### 🔗 Live Demo
[View Portfolio Project](https://rolling-scopes-school.github.io/ulyana0siadziuk-JSFE2025Q3/portfolio/)


A fully responsive photographer portfolio website with interactive features and modern UI/UX implementation.


<img width="500" height="350" alt="portfolio" src="https://github.com/user-attachments/assets/2c0a0573-ce53-4b6c-be33-cd7b51f51041" />


#### 📱 Responsive Design
- **Adaptive Layout**: Fully responsive design for desktop (1440px+), tablets (768px), and mobile devices (380px)
- **Fluid Scaling**: Smooth adaptation across all screen sizes without horizontal scroll
- **Centered Layout**: Content remains centered on wider screens while background colors stretch full width
- **Flexible Units**: Implementation using relative units (%, rem, vh) for true responsiveness

#### 🎨 Layout Implementation
The page consists of 7 main sections matching the Figma design:
- **Header**: Navigation with responsive behavior
- **Hero Section**: Engaging introduction with call-to-action
- **About Section**: Photographer's story and mission
- **Portfolio Section**: Gallery showcase
- **Price Section**: Packages and pricing cards
- **FAQ Section**: Interactive accordions
- **Footer**: Contact and additional information

#### 🍔 Burger Menu Functionality
- **Responsive Navigation**: Menu transforms into burger icon at 768px and below
- **Pure CSS Burger**: Icon created with HTML and CSS only (no images)
- **Smooth Animations**: 
  - Burger smoothly transforms into cross when opened
  - Menu slides from the right with smooth transitions
  - Cross transforms back to burger when closed
- **Enhanced UX**: 
  - Menu occupies full screen area below header
  - Page scrolling disabled when menu is open
  - Clicking any link closes menu and scrolls to section
  - Smooth anchor scrolling implemented

#### 🎯 Interactive Slider
- **Dual Control Systems**:
  - **Desktop**: Hover-based scrolling (left/right areas, ~30% screen width each)
  - **Mobile**: Touch-based scrolling with finger swipes
- **Smart Positioning**: 
  - Slider track horizontally centered
  - Inactive center area on desktop
  - End positions aligned with page content
  - Scrolling locked at boundaries

#### ❓ FAQ Accordions
- **Default State**: First accordion open by default
- **Interaction**: Click anywhere on header to open/close
- **Exclusive Opening**: Only one accordion open at a time
- **Persistence**: State preserved after page reload

#### 📱 Modal Windows
- **Trigger**: Click any "BOOK NOW" button in pricing cards
- **Visual Design**:
  - Darkened overlay outside modal
  - Centered modal with matching Figma layout
- **UX Features**:
  - Page scroll disabled when modal is open
  - Close by clicking outside, close button, or ESC key
  - Smooth transitions

#### 🖱️ Additional Features
- **Scroll Down Button**: Smooth scroll to About section
- **Interactive Elements**: 
  - Hover effects for links and buttons
  - Interactive package cards (border and button color change)
  - Accordion header hover effects
  - Smooth transitions without affecting adjacent elements
- **Device-Aware**: Hover effects active on desktop, disabled on mobile

#### ✅ Code Quality
- **Validation**: W3C Validator passed (no errors)
- **Semantic HTML**: Proper heading structure (single h1)
- **Favicon**: Custom favicon implemented
- **Clean Code**: No frameworks/libraries, pure HTML/CSS/JavaScript

#### 🛠️ Technologies Used
- HTML5
- CSS3 (Flexbox, Grid, Animations)
- JavaScript (ES6+)
- Git & GitHub Pages

---

### 2. Virtual Music Kit

#### 🔗 Live Demo
[View Virtual Music Kit](https://rolling-scopes-school.github.io/ulyana0siadziuk-JSFE2025Q3/virtual-music-kit/)


<img width="500" height="350" alt="virtual-music-kit" src="https://github.com/user-attachments/assets/2bd5ebf5-fc42-42ab-b156-5839f1aebe06" />


An interactive sound application that simulates a musical instrument (piano) where users can play sounds live.

#### 🎹 Concept & Visual Design
- **Instrument**: Piano simulator with 12 distinct notes (C, C#, D, D#, E, F, F#, G, G#, A, A#, B)
- **Visual Layout**: Creative piano-style interface with black and white keys
- **Responsive Design**: Fully adaptive for desktop (1440px+), tablet (768px-1440px), and mobile (360px-768px)

#### 🎼 Core Functionality
- **Sound Mapping**: Each of the 12 piano notes mapped to a unique English letter key:
  - **White keys**: C (A), D (S), E (D), F (F), G (G), A (H), B (J)
  - **Black keys**: C# (W), D# (E), F# (T), G# (Y), A# (U)
- **Visual Feedback**: Keys displayed on screen, clearly associated with their piano key
- **Trigger Methods**: 
  - Click on piano keys
  - Press assigned keyboard keys
- **Smart Input Handling**: 
  - Sounds play regardless of keyboard layout (RU/EN) or Caps Lock state
  - Only processes first key when multiple keys pressed simultaneously

#### 🔧 Key Remapping System
- **Edit Feature**: Edit button/icon next to each key
- **Input Interface**: 
  - Click edit → input field appears with current key pre-filled
  - Type new key → press Enter to confirm
  - Input disappears after confirmation
- **Conflict Prevention**: System prevents assigning same key to multiple sounds
- **Temporary Changes**: Remapping resets after page refresh

#### 🎨 Visual States
Each playable element has three distinct visual states:
- **Default**: Normal appearance
- **Hover**: Visual feedback when mouse hovers
- **Active**: Triggered state during sound playback (key press or click)

#### 🧩 DOM Implementation
- **Pure DOM Manipulation**: 
  - Initial `body` contains only script tag
  - All elements dynamically created and managed with `createElement()`, `appendChild()`, and other DOM methods
  - No HTML injection — complete separation of structure and content
- **Event Handling**:
  - Keyboard events for key presses (`keydown`)
  - Mouse events for clicks and hover states
  - Custom event management for application state

#### 🛠️ Technologies Used
- **DOM API**: Native document manipulation (`createElement`, `appendChild`, `querySelector`, etc.)
- HTML5
- CSS3 (Flexbox/Grid, animations)
- Vanilla JavaScript (ES6+)
- Web Audio API for sound generation



---
