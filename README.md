# ✦ BENTO UI DESIGN SYSTEM
### Modern Bento-Box Design System & Component Library

<p align="center">
  <strong>Design with Purpose. Build with Consistency. Create with Style.</strong>
</p>

<p align="center">
  A modern, responsive UI design system featuring asymmetric Bento layouts, reusable CSS components, glassmorphism, interactive controls, and advanced responsive design techniques.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/Responsive-Design-7055F5?style=for-the-badge" alt="Responsive Design">
  <img src="https://img.shields.io/badge/Container-Queries-8B6CFF?style=for-the-badge" alt="Container Queries">
  <img src="https://img.shields.io/badge/JavaScript-Not_Required-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="No JavaScript">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT License">
</p>

---

## 01. Project Overview

**Bento UI Design System** is a modern front-end component library and design showcase built around the Bento-box layout philosophy.

The project combines asymmetric CSS Grid layouts, glassmorphic surfaces, reusable interface components, and CSS-powered interactions to create a polished digital design environment.

It demonstrates how HTML5 and modern CSS3 can be used to build sophisticated, responsive user interfaces without depending on JavaScript frameworks or external component libraries.

Bento UI is designed to demonstrate three important principles:

- **Visual consistency:** Reusable components and centralised design tokens.
- **Layout flexibility:** Modular Bento grids that adapt across different screen sizes.
- **Interaction design:** Accessible controls with carefully considered hover, focus, active, and disabled states.

## 02. Key Features

### A. Asymmetric Bento Dashboard

A modular dashboard composed of cards with different dimensions and content structures.

The dashboard includes:

- Weather overview widget.
- Weekly activity analytics.
- Music player interface preview.
- Storage utilisation indicator.
- Daily activity heatmap.
- Design system performance metrics.

The layout uses CSS Grid template areas to create an asymmetric visual structure.

### B. Component Sandbox

A dedicated component showcase featuring reusable interface elements.

**Included components:**

| Component | Functionality |
|---|---|
| Buttons | Primary, secondary, outline and disabled states |
| Badges | Status and category indicators |
| Switches | CSS-powered checkbox toggles |
| Range Sliders | Custom-styled native range inputs |
| Accordions | Expandable native HTML sections |
| Skeletons | Animated loading placeholders |
| Form Controls | Customised native form elements |
| State Matrix | Default, hover, focus and disabled states |

### C. Glassmorphism Design

The interface uses modern glass-inspired styling, including:

- Semi-transparent card surfaces.
- Backdrop blur effects.
- Layered shadows.
- Soft gradient backgrounds.
- Subtle borders.
- Radial gradient highlights.
- Rounded component surfaces.

### D. Design Token System

Centralised CSS custom properties provide a consistent foundation for the interface.

The design system includes:

- Primary and secondary colours.
- Background and surface colours.
- Typography conventions.
- Border radius values.
- Shadow definitions.
- Reusable spacing conventions.

### E. Responsive Layout

The platform adapts to desktop, tablet and mobile devices through:

- CSS Grid.
- Flexbox.
- Media queries.
- Fluid typography.
- CSS container queries.
- Flexible component dimensions.

### F. Accessible Component States

Components demonstrate different interaction states:

- Default.
- Hover.
- Focus-visible.
- Active.
- Disabled.

Native HTML controls are retained wherever possible to preserve browser accessibility and keyboard interaction.

---

## 03. Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Semantic page structure |
| CSS3 | Visual styling and component design |
| CSS Grid | Asymmetric Bento layouts |
| Flexbox | Component alignment |
| CSS Variables | Centralised design tokens |
| Container Queries | Component-level responsive behaviour |
| Media Queries | Device responsiveness |
| Backdrop Filter | Glassmorphism effects |
| CSS Animations | Loading skeleton effects |
| Native HTML Controls | Interactive form components |

**Architecture:** HTML5 + CSS3.

No JavaScript framework, external component library, or build system is required.

---

## 04. Advanced CSS Techniques

Bento UI demonstrates practical application of modern CSS concepts.

**1. CSS Grid Template Areas**

Creates structured and asymmetric dashboard layouts using named grid areas and variable column spans.

**2. CSS Container Queries**

Uses container-based styling to adapt component presentation according to available component space rather than relying exclusively on viewport dimensions.

**3. Glassmorphism**

Combines transparent backgrounds, backdrop filters, layered shadows and subtle gradients to produce depth.

**4. CSS Custom Properties**

Provides a centralised design system for colours, borders, shadows and reusable styling values.

**5. CSS Pseudo-classes**

Uses `:hover`, `:focus-visible`, `:active`, `:checked` and `:disabled` to control interface states.

**6. Native Interactive Elements**

Uses HTML checkboxes, radio inputs, range controls, select elements and `<details>` for browser-native interactions.

**7. Responsive Engineering**

Combines media queries, Grid, Flexbox and fluid typography for different device sizes.

**8. Accessibility and Reduced Motion**

Uses semantic markup, visible keyboard focus indicators and `prefers-reduced-motion` styling.

---

## 05. Project Structure

```text
bento-ui-design-system/
│
├── index.html
│   └── Main dashboard and component showcase.
│
├── style.css
│   └── Complete design system, layouts,
│       component styling and responsive rules.
│
└── README.md
    └── Project documentation.
```

---

## 06. Getting Started

### Prerequisites

- Visual Studio Code or another code editor.
- Git installed locally.
- A modern web browser.

### Clone the repository

```bash
git clone https://github.com/Regalson001/bento-ui-design-system.git
```

### Open the project directory

```bash
cd bento-ui-design-system
```

### Open in Visual Studio Code

```bash
code .
```

### Run the project

Open `index.html` directly in your browser or use the Visual Studio Code Live Server extension.

No additional installation or dependency configuration is required.

---

## 07. Design Philosophy

Bento UI follows a minimal, modular and component-driven approach to interface design.

The visual system prioritises:

- Clear information hierarchy.
- Consistent spacing and alignment.
- Reusable interface patterns.
- Subtle visual depth.
- Intuitive interactions.
- Responsive component behaviour.
- Maintainable CSS architecture.

The objective is to demonstrate that professional interface design is not only about appearance, but also about structure, usability and consistency.

---

## 08. Current Implementation & Limitations

Bento UI is a static front-end design system.

The following elements are implemented:

- Responsive Bento dashboard.
- CSS-based component showcase.
- Native accordion interactions.
- Native switch and form controls.
- Styled range inputs.
- Animated skeleton placeholders.
- CSS-based component state demonstrations.
- Responsive container and viewport layouts.

Some widgets are visual demonstrations rather than connected applications.

For example:

- Weather values are sample data, not live weather information.
- Analytics figures are illustrative.
- The music player is a visual preview and does not play audio.
- Storage information is not connected to an actual storage service.
- Form submission and persistent settings are not implemented.
- The component state matrix provides visual examples; it is not an automated testing system.

---

## 09. Future Enhancements

Potential improvements for future versions include:

| Feature | Enhancement |
|---|---|
| Theme Management | Functional dark and light mode |
| Interactive Dashboard | Dynamic analytics and widget data |
| Music Player | Real audio playback and controls |
| Component Documentation | Dedicated component API pages |
| Design Tokens | Exportable CSS variables and themes |
| Accessibility | Expanded keyboard and screen-reader testing |
| Component Testing | Automated interaction and visual tests |
| Documentation Search | Searchable component catalogue |
| Framework Integration | React component implementation |

---

## 10. Author

**Stephen Oyugi**

Front-End Developer | AI Automation Engineer | Machine Learning Practitioner

Focused on developing modern web interfaces, reusable UI systems, responsive applications and practical software solutions.

- GitHub: [@Regalson001](https://github.com/Regalson001)
- LinkedIn: [Stephen Oyugi](https://linkedin.com/in/stephenoyugi001)

---

## 11. License

This project is distributed under the MIT License.

You are welcome to explore, modify and extend the project in accordance with the licence terms.

---

<p align="center">
  <strong>BENTO UI DESIGN SYSTEM</strong>
  <br>
  <em>Design with Purpose. Build with Consistency. Create with Style.</em>
  <br><br>
  Built with HTML5 and CSS3.
  <br>
  © 2026 Stephen Oyugi.
</p>
