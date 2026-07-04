# SEPER DIGITAL Git Workflow

## Philosophy

Git is more than version control—it is the history of a project.

Every commit should represent meaningful progress and make it easy to understand how the project evolved.

---

# Repository Standards

Every repository should include:

- README.md
- .gitignore
- LICENSE (when appropriate)
- Clear folder structure
- Meaningful commit history

---

# Branch Strategy

## Main

The `main` branch should always contain stable, production-ready code.

---

## Feature Branches

Whenever possible, develop new features on separate branches.

Example:

feature/login-page

feature/mobile-ui

feature/pdf-export

bugfix/navbar-overflow

---

# Commit Messages

Commit messages should clearly describe the change.

Good examples:

Add invoice PDF export

Fix mobile navigation layout

Improve score calculation

Refactor dashboard rendering

Avoid vague commits such as:

update

changes

fix stuff

final

---

# Commit Frequency

Commit:

- After completing a feature
- After fixing a bug
- Before major refactoring
- Before merging

Avoid making one massive commit after several hours of work.

---

# Pull Requests

Before merging:

- Review your own code.
- Test the feature.
- Check mobile responsiveness.
- Verify there are no console errors.
- Update documentation if necessary.

---

# Code Reviews

Every code review should consider:

- Readability
- Maintainability
- Performance
- Accessibility
- Security
- User experience

The goal is improving the software, not criticizing the developer.

---

# Versioning

Use semantic versioning whenever appropriate.

Examples:

v1.0.0

v1.1.0

v2.0.0

---

# Releases

Major releases should include:

- Release notes
- Bug fixes
- New features
- Known issues
- Upgrade instructions (if applicable)

---

# Security

Never commit:

- API keys
- Passwords
- Secrets
- Tokens
- Personal information

Use environment variables whenever possible.

---

# Documentation

Major architectural changes should be documented.

Documentation is part of the project—not an afterthought.

---

# Continuous Improvement

Every project should become easier to maintain over time.

Small, consistent improvements create better software than occasional large rewrites.
