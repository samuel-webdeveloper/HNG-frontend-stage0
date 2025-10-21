# Frontend Stage 0

Simple accessible profile card built with HTML, CSS, and vanilla JavaScript.

## Live demo
https://stage0-profilecard.netlify.app/

## How to run locally
1. Clone the repo.
2. Open `index.html` in a browser.

## What it includes
- Required `data-testid` attributes:
  - test-profile-card
  - test-user-name
  - test-user-bio
  - test-user-time
  - test-user-avatar
  - test-user-social-links (and per-link testids)
  - test-user-hobbies
  - test-user-dislikes
- `Date.now()` shown in milliseconds and updated every second.
- Avatar upload converts chosen file to a data URL and displays it.

## Notes
- All interactive links open in a new tab with `rel="noopener noreferrer"`.
- Focus styles are present for keyboard accessibility.
