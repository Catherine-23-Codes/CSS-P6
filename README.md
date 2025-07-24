# 🌐 CSS Part 6 — Quick Revision Guide

## 🔳 CSS Grid Layout

| Property                     | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| `display: grid`             | Initiates grid layout on a container.                                       |
| `grid-template-rows/columns`| Defines layout structure in rows/columns (e.g., `1fr 2fr`).                 |
| `grid-gap` / `gap`          | Sets spacing between grid items.                                           |
| `grid-template-areas`       | Creates named layout zones for semantic clarity.                           |
| `grid-column` / `grid-row`  | Controls span and position of grid items.                                  |
| `place-items`               | Aligns content vertically and horizontally inside the grid.                |
| `justify-content`           | Aligns items horizontally in the grid container.                           |

> **Note:** Use fractional units (`fr`) for flexible and responsive layouts.

---

## 🌀 CSS Animations

| Property                   | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| `@keyframes`              | Defines stages of animation using percentage or `from/to`.                  |
| `animation-name`          | Refers to a defined keyframes block.                                        |
| `animation-duration`      | Specifies runtime of the animation (e.g., `2s`).                             |
| `animation-iteration-count`| Sets repetition (e.g., `infinite`).                                        |
| `animation` (shorthand)   | Combines name, duration, timing function, etc., in a single line.           |

> **Tip:** Use `ease-in-out` or `linear` for smoother transitions.

---

## 📱 Media Queries

| Type                          | Example                                      | Purpose                              |
|-------------------------------|----------------------------------------------|--------------------------------------|
| Max-width breakpoint          | `@media (max-width: 768px)`                 | Adjust styles for tablets/small screens |
| Orientation control           | `@media (orientation: portrait)`            | Modify layout based on screen rotation |
| Common breakpoints            | `480px`, `768px`, `1024px`, `1200px`        | For responsive layout targeting      |

> **Best Practice:** Test media queries on multiple devices to ensure consistency.

---

## 🐶 Pet Adoption Page Highlights

| Feature            | Application                                                       |
|--------------------|-------------------------------------------------------------------|
| Grid Layout         | Organized adoption cards and sections with named areas.           |
| Animations          | Smooth transitions and hover effects.                            |
| Media Queries       | Responsive views on mobile, tablet, and desktop.                 |
| `z-index`           | Layered modals and images effectively above other elements.      |

---
---





