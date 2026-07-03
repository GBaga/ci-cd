### CI/CD Setup
- Configured branch name validation for `feature/*`.
- Configured CI validations (lint, test, build) on push and pull requests.
- Configured GitHub Pages deployment to trigger when the PR is updated.

### Accessibility (A11y) Improvements
- Fixed HTML semantics (`<header>`, `<main>`, `<button>`).
- Improved text contrast for `.header`.
- Added missing `alt` text to the hero image.
*(Please attach before-and-after Lighthouse A11y screenshots here)*

### Performance Optimization
- Added `width` and `height` to the hero image to fix Cumulative Layout Shift (CLS).
- Deferred the jQuery script and added `preconnect` to optimize First Contentful Paint (FCP) and eliminate render-blocking resources.
- Removed the synchronous JavaScript loop, significantly improving Time to Interactive (TTI).
*(Please attach before-and-after Lighthouse Performance screenshots here)*
