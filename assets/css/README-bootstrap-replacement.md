# Custom Bootstrap Replacement Framework

This project replaces Bootstrap with a custom CSS and JavaScript framework tailored for the Rivoni Vila Recruitment website. The goal is to maintain the original design and interactivity while removing all Bootstrap dependencies.

---

## 1. CSS Structure

- **File:** `assets/css/bootstrap-replacement.css`
- **Purpose:** Replaces Bootstrap's grid, utility, button, and form classes with custom styles.

### Key Features
- **Grid System:** `.container`, `.row`, `.col-*`, `.col-md-*`, `.col-lg-*` (Flexbox-based, responsive)
- **Flex Utilities:** `.d-flex`, `.flex-column`, `.flex-row`, `.flex-wrap`, `.align-items-center`, `.justify-content-center`, `.justify-content-between`
- **Spacing Utilities:** `.mb-*`, `.mt-*`, `.pt-*`, `.py-*`, `.gap-*`, `.gy-*`
- **Typography & Color:** `.text-center`, `.text-warning`, `.text-light`, `.text-muted`, `.fw-bold`, `.fw-600`, `.fw-800`, `.display-3`
- **Buttons:** `.btn`, `.btn-primary`, `.cta-btn`, `.cta-btn2` (custom gold and white styles)
- **Forms:** `.form-label`, `.form-control`, `.form-text`, `.php-email-form` (styled for accessibility and clarity)
- **Navbar Mobile Toggle:** Responsive menu with `.navmenu-open` and `.mobile-nav-toggle` classes
- **Other Utilities:** `.rounded`, `.shadow`, `.position-relative`, `.fixed-top`, `.border-top`, `.border-secondary`, `.ratio`, `.ratio-21x9`, `.active`, `.visually-hidden`

### How to Use
- Use the same class names as in Bootstrap for layout and utilities.
- For new components, follow the established class naming conventions.
- Add or modify classes in `bootstrap-replacement.css` as needed for new features.

---

## 2. JavaScript Structure

- **File:** `assets/js/main.js`
- **Purpose:** Replaces Bootstrap's JS for navbar toggling and carousel functionality.

### Key Features
- **Navbar Mobile Toggle:** Handles opening/closing the mobile menu by toggling `.navmenu-open` on `#navmenu` and `.open` on the toggle icon.
- **Testimonials Carousel:** Vanilla JS slider for `.carousel` in the testimonials section, supporting next/prev navigation and looping.

### How to Use
- No dependencies required—just vanilla JS.
- Add new interactive components by following the structure in `main.js`.

---

## 3. Maintenance Notes

- **Extending the Framework:**
  - Add new utility classes to `bootstrap-replacement.css` as needed.
  - For new JS components, keep code modular and well-commented in `main.js`.
- **Testing:**
  - Always test changes on both desktop and mobile.
  - Check for cross-browser compatibility.
- **Performance:**
  - Minify CSS/JS for production.
  - Remove unused classes and scripts regularly.

---

## 4. Credits

- Original design inspired by Bootstrap.
- Custom framework by [Your Name/Team].

---

For questions or updates, contact the site maintainer. 