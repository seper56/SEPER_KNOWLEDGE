# SEPER DIGITAL Coding Standards

## Philosophy

Code should be written for people first and computers second.

Readable, maintainable code is always preferred over clever or overly complex solutions.

Every commit should improve the project.

---

# General Principles

- Keep solutions simple.
- Avoid unnecessary complexity.
- Write code that is easy to understand.
- Prefer maintainability over shortcuts.
- Follow consistent naming conventions.
- Comment why something exists, not what obvious code does.

---

# HTML

- Use semantic HTML whenever possible.
- Maintain proper heading hierarchy.
- Every form must have labels.
- Images require descriptive alt text.
- Avoid unnecessary div nesting.
- Keep HTML clean and organized.

---

# CSS

- Mobile-first development.
- Use consistent spacing throughout the project.
- Group related styles together.
- Avoid duplicate CSS.
- Prefer reusable utility classes when appropriate.
- Keep selectors simple.
- Avoid !important unless absolutely necessary.

---

# JavaScript

- Use const by default.
- Use let only when values change.
- Avoid var.
- Keep functions focused on one responsibility.
- Break large functions into smaller reusable functions.
- Handle errors gracefully.
- Validate user input.
- Avoid duplicate logic.

---

# File Organization

- Separate HTML, CSS, and JavaScript.
- Keep assets organized.
- Remove unused files.
- Keep naming consistent across the project.

---

# Naming Conventions

Variables:
camelCase

Functions:
camelCase

Classes:
PascalCase

Files:
kebab-case whenever possible

Constants:
UPPER_CASE

---

# Performance

- Optimize images.
- Minimize unnecessary DOM updates.
- Reduce repeated calculations.
- Load only what is necessary.
- Keep page load times fast.

---

# Accessibility

Every project should:

- Be keyboard accessible.
- Use sufficient color contrast.
- Include proper labels.
- Use semantic HTML.
- Support screen readers where practical.

Accessibility is a requirement—not an optional feature.

---

# Git

- Make small, meaningful commits.
- Write clear commit messages.
- Never commit secrets or API keys.
- Keep the main branch stable.
- Test before pushing changes.

---

# Quality Checklist

Before every commit:

- Code is readable.
- No obvious duplicate logic.
- Mobile layout tested.
- Console errors resolved.
- Accessibility reviewed.
- Performance considered.
- Project builds successfully.

---

# The SEPER Standard

Every project should leave the codebase in a better state than it was found.

Clean code builds trust.

Consistency builds quality.

Quality builds reputation.
