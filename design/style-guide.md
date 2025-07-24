# 📘 FEELDX UI Style Guide

---

## Fonts

- **Heading Font**: `Poppins`, sans-serif  
  Used for all headings (`h1`–`h6`)
- **Body Font**: `Roboto`, sans-serif  
  Used for paragraphs, default text, and navigation

---

## Colors

| Variable                          | Description                   | Hex Code  |
| --------------------------------- | ----------------------------- | --------- |
| `--background-color`              | Page background               | `#ffffff` |
| `--default-color`                 | Body text                     | `#3c442d` |
| `--heading-color`                 | Headings                      | `#3c442d` |
| `--accent-color`                  | Primary accent (buttons etc.) | `#6c7651` |
| `--accent-hover-color`            | Accent hover                  | `#6f7754` |
| `--surface-color`                 | Card/box background           | `#e8ece3` |
| `--contrast-color`                | Light text for dark BG        | `#ffffff` |
| `--nav-background-color`          | Nav bar background            | `#3c442d` |
| `--nav-hover-color`               | Nav item hover                | `#6c7651` |
| `--nav-dropdown-background-color` | Dropdown menu background      | `#ffffff` |
| `--section-bg-color`              | Section alternate background  | `#f0f8ff` |
| `--header-bg-color`               | Header when scrolled          | `#242424` |

---

## Spacing & Layout

- **Global Section Padding**: `60px 0`
- **Hero Section Height**: `100vh` (Full viewport)
- **Section Overlay Opacity**: `0.75`
- **Container Padding (Hero)**: `50px` bottom
- **Responsive Scroll Margin**: `88px` desktop / `66px` mobile

---

## Typography Guidelines

| Element             | Font    | Size   | Weight | Style          |
| ------------------- | ------- | ------ | ------ | -------------- |
| `h1`                | Poppins | `48px` | 700    | Uppercase      |
| `h2`                | Poppins | `32px` | 700    | Uppercase      |
| `.hero p`           | Roboto  | `22px` | 600    | Subheading     |
| `.section-title h2` | Poppins | `32px` | 700    | With underline |
| `.about p`          | Roboto  | `16px` | 400    | Default text   |

---

## Responsive Breakpoints

| Device       | Max Width |
| ------------ | --------- |
| Mobile       | `640px`   |
| Tablet       | `991px`   |
| Small Laptop | `1199px`  |
| Desktop      | `1200px+` |

---

## Components Overview

### Navigation

- Sticky top nav
- Desktop & mobile variants
- Dropdown with hover and mobile slide toggle

### Hero

- Full-screen background video (`.custom-video`)
- Main heading, subheading, two CTA buttons

### Buttons

- `.btn-getstarted`, `.btn-learn-more`, `.cta-btn`
- Rounded pill shape
- Hover & focus transitions
- Accent background with white or transparent base

### Sections

- `.section`, `.section-padding`, `.section-title`
- Consistent spacing
- Section overlays and color sections supported

### Cards & Services

- `.service-item`, `.post-item`, `.our-works-item`
- Box-shadow and hover transforms
- Image + title + description layout

### Footer

- Dark background
- Multi-column layout
- Social links with hover effect
