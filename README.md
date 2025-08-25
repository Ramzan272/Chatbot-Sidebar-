README.md
# Chatbot Sidebar 

A clean, responsive, **single-file** HTML template for AI/chat apps and dashboards with a **collapsible sidebar**, **smooth micro-interactions**, **keyboard shortcuts**, and **mobile-first** behavior. Everything is self-contained: **HTML + CSS + JS in one file**.


## ✨ Highlights

- **Collapsible sidebar** — Compact/expanded on desktop; slides in/out on mobile.
- **Keyboard shortcut** — Press **Ctrl + B** to toggle the sidebar.
- **Mobile overlay** — Auto-collapses on small screens (≤ 820px) and shows an overlay.
- **Smooth interactions** — Ripple on clicks, hover states, and lazy load-in animations.
- **Accessible** — Visible focus outlines; ARIA attributes on key controls and panels.
- **No dependencies** — Pure HTML/CSS/JS; works offline.
- **Progressive enhancement** — Uses `IntersectionObserver` for card load-ins when available.
- **Demo chat** — Simple front-end chat flow with typing indicator (easy to replace).

## 🧩 What’s Inside

- **Sidebar navigation** with brand block and account section (shows “Ramzan Mustafa”).
- **Panels**:  
  - **Chat**: demo chat UI with quick prompt chips  
  - **Knowledge**: sample articles and highlights  
  - **Projects**: responsive card grid  
  - **Templates**: example template cards  
  - **Skills**: core skills + tools  
  - **About**: (placeholder—customize for your bio/mission)



## 🚀 Quick Start

1. Save the file as `chatbot-sidebar.html`.
2. Open it directly in any modern browser (Chrome, Edge, Firefox, Safari).
3. Press **Ctrl + B** to toggle the sidebar.
4. Resize to see mobile overlay behavior.
## ⌨️ Keyboard & Accessibility

- **Toggle sidebar**: `Ctrl + B`
- **Close on mobile**: `Esc` or tap outside (overlay)
- **Focus styles**: Visible with `:focus-visible`
- **ARIA**:  
  - `aria-label` on sidebar, nav, and panels  
  - `aria-live="polite"` on panel container to announce panel changes  
  - Toggle button keeps `aria-expanded` in sync


