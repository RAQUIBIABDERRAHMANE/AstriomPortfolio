# 👥 Astriom Team Instructions

These instructions define how our team will collaborate to build the **Astriom Portfolio Website** efficiently and consistently.

---

## 🧩 1. Project Overview

The portfolio website will include the following sections:

1. **Hero Section** – Introduction and main call-to-action  
2. **Our Services** – Presentation of services offered  
3. **Technologies** – Technologies we use  
4. **Projects** – Showcase of completed work  
5. **Reviews** – Client feedback and testimonials  
6. **Contact** – Contact form and social links  

Each section is stored in its **own folder** with its own HTML and CSS files.

---

## 🗂️ 2. Folder & File Structure

```
Astriom/
│
├── index.html
├── style.css
├── css/
│   └── global.css
├── Services/
│   ├── index.html
│   └── style.css
├── Technologies/
│   ├── index.html
│   └── style.css
├── Projects/
│   ├── index.html
│   └── style.css
├── Reviews/
│   ├── index.html
│   └── style.css
├── Contact/
│   ├── index.html
│   └── style.css
└── assets/
    ├── images/
    ├── icons/
    └── fonts/
```

---

## 👥 3. Team Roles

Each section is built by **two developers** — one focuses on HTML, and the other on CSS.  
In the next section, they **switch roles** to keep the work balanced.

| Section      | HTML         | CSS             | Notes             |
| ------------ | ------------ | -------         | ----------------- |
| Hero Section | Abderrahmane | Hasnae          | Primary devs      |
| Services     | Hasnae       | Ousama          | Rotate CSS/HTML   |
| Technologies | Ousama       | Yasmine         | Rotate CSS/HTML   |
| Projects     | Yasmine      | Salma           | Rotate CSS/HTML   |
| Reviews      | Salma        | Abderrahmane    | Rotate CSS/HTML   |
| Contact      | Ousama       | Hasnae          | Rotate CSS/HTML   |


---

## ⚙️ 4. Workflow

### 🪜 Step 1 — Clone the Repository

```bash
git clone https://repos.raquibi.com/Astriom/portfolio.git
cd portfolio
# or if already have it make :
git pull
```

### 🪜 Step 2 — Build Your Section

- Create your section's folder if it doesn't exist
- Add `index.html` and `style.css`
- Follow the design guidelines and global styles

### 🪜 Step 3 — Test Locally

- Open your section in a browser
- Check responsiveness and styling
- Ensure it matches the mockup/design

### 🪜 Step 4 — Commit & Push

```bash
git add .
git commit -m "Add [section-name] section"
git push origin main
```
---

## 🎨 5. Design Guidelines

### Color Palette

- **Primary:** `#1E3A8A` (Deep Blue)
- **Secondary:** `#3B82F6` (Bright Blue)
- **Accent:** `#F59E0B` (Orange)
- **Background:** `#F9FAFB` (Light Gray)
- **Text:** `#1F2937` (Dark Gray)

### Typography

- **Headings:** `'Poppins', sans-serif`
- **Body:** `'Inter', sans-serif`
- **Font Sizes:**
  - H1: `3rem`
  - H2: `2.5rem`
  - H3: `2rem`
  - Body: `1rem`

### Spacing

- Use consistent spacing: `8px, 16px, 24px, 32px, 48px, 64px`
- Container max-width: `1200px`
- Section padding: `64px 0`

---

## 📋 6. Coding Standards

### HTML Best Practices

- Use semantic HTML5 elements (`<header>`, `<section>`, `<article>`, etc.)
- Add meaningful `alt` attributes to images
- Use proper heading hierarchy (H1 → H2 → H3)
- Keep code clean and indented

### CSS Best Practices

- Use BEM naming convention: `.block__element--modifier`
- Mobile-first approach (start with mobile, then add media queries)
- Avoid `!important` unless absolutely necessary
- Group related styles together
- Comment complex CSS

### Example Structure

```html
<section class="services">
  <div class="services__container">
    <h2 class="services__title">Our Services</h2>
    <div class="services__grid">
      <div class="services__card">
        <!-- Content -->
      </div>
    </div>
  </div>
</section>
```

---

## 🔄 7. Git Best Practices

### Commit Messages

Use clear, descriptive commit messages:

```
✅ Good:
- "Add hero section with responsive layout"
- "Fix navigation menu mobile styling"
- "Update contact form validation"

❌ Bad:
- "Update"
- "Fix stuff"
- "Changes"
```


## 📱 8. Responsiveness

Ensure all sections work on:

- **Mobile:** 320px - 767px
- **Tablet:** 768px - 1023px
- **Desktop:** 1024px+

### Media Query Template

```css
/* Mobile First */
.element {
  /* Mobile styles */
}

/* Tablet */
@media (min-width: 768px) {
  .element {
    /* Tablet styles */
  }
}

/* Desktop */
@media (min-width: 1024px) {
  .element {
    /* Desktop styles */
  }
}
```

---

## ✅ 9. Checklist Before PR

- [ ] Code is clean and well-commented
- [ ] Responsive on all screen sizes
- [ ] No console errors
- [ ] Images are optimized
- [ ] Follows design guidelines
- [ ] Tested in multiple browsers
- [ ] Accessibility checked (contrast, alt text, keyboard navigation)

---


**Let's build something amazing together! 💪✨**