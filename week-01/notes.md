# 5 Rules of Good HTML

## 1. Use Semantic Elements
Choose HTML tags that describe the meaning of content, not just how it looks. Use `<nav>` for navigation, `<article>` for self-contained content, `<aside>` for sidebars. This helps screen readers, search engines, and other developers understand your structure.

## 2. Always Provide Alternative Text for Images
Every `<img>` must have an `alt` attribute. If the image is decorative, use `alt=""`. If it conveys information, describe it briefly. This is essential for users who cannot see the image and for SEO.

## 3. Structure Forms with Labels and Fieldsets
Every form field needs a visible `<label>` linked by `for` and `id`. Group related fields (like radio buttons) with `<fieldset>` and `<legend>`. This makes forms accessible and easier to use for everyone.

## 4. Keep Tables for Tabular Data Only
Use `<table>` only for data that naturally fits rows and columns (schedules, statistics). Never use tables for page layout. Always include `<caption>`, `<thead>`, and `<th scope="col">` for proper structure.

## 5. Validate and Test Your HTML
Run your code through the W3C validator to catch errors. Test with keyboard navigation (Tab/Enter/Space) to ensure accessibility. Check contrast ratios and screen reader compatibility. Good HTML works for all users, not just those with mice and perfect vision.