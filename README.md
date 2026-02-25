# Lost After the Crash – CSS Ricing Edition

## Description

This project is an interactive survival story developed for the Web Systems and Technologies course.

The original HTML narrative has been enhanced using modern CSS techniques, focusing on UI/UX principles, responsive design, visual consistency, and CSS animations.

No JavaScript was used in this project.

---

## Concept

The player survives a plane crash and must make decisions that lead to different outcomes.  
The visual experience is divided into three thematic states:

- Start (hope and clarity)
- Decision (tension and uncertainty)
- Ending (dramatic resolution)

Each state has its own visual identity defined through CSS.

---

## Technologies Used

- HTML5  
- CSS3 (Variables, Grid, Animations, Transitions)  
- Google Fonts  
- NGINX  
- Git  

---

## Project Structure
Web_Lab3/
│
├── index.html
├── pages/
├── css/
│ ├── story-theme.css
│ ├── base.css
│ ├── layouts.css
│ ├── components.css
│ └── animations.css
└── assets/


---

## CSS Architecture

- **story-theme.css** → Design tokens, color palette, theme states, typography  
- **base.css** → Reset and global styles  
- **layouts.css** → CSS Grid structure and responsive layout  
- **components.css** → Interactive button component (default, hover, active, focus-visible)  
- **animations.css** → Keyframe animations and microinteractions  

---

## Features Implemented

- 3 distinct visual theme states  
- CSS Grid layout (no floats used)  
- Responsive design using relative units (rem, %, vh)  
- Interactive RPG-style buttons  
- 4 CSS animations using @keyframes  
- Smooth transitions  
- Accessibility support (:focus-visible)  
- No JavaScript  

---

## How to Run (NGINX)

1. Create project directory:
/var/www/html/adventure

2. Copy project files:
sudo cp -r ~/Web_Lab3/* /var/www/html/adventure/


3. Set permissions:
sudo chmod -R 755 /var/www/html/adventure

4. Open in browser:
http://localhost/adventure/


---

## Remote Deployment

Available at:
http://chicharronconpelos.shop/24336/LAB3/


---

## Author

Diego Alejandro Quan Castillo  
Universidad del Valle de Guatemala  
Laboratorio CSS – RICING
