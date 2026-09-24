# Youth360

A youth-facing mobile prototype made with HTML, CSS and vanilla JavaScript. No framework, backend, database or external assets are required.

## Open the prototype

From this folder run `python -m http.server 8080 --bind 127.0.0.1`, then visit http://127.0.0.1:8080. After onboarding, select **Explore the demo**, or create an account using made-up details. Localhost or HTTPS is required for password hashing.

The requested source files are `index.html`, `styles.css`, `app.js` and `assets/illustrations/student.svg`. `dist/` is an identical static publishing copy.

## Included

- Splash and four-page onboarding with swipe controls.
- Validated local demo signup, login, password visibility and logout.
- Home search, six feature areas, bottom navigation and Quick Actions sheet.
- Four courses, 24 lesson previews, notes, activities, completion and progress.
- Wellbeing categories, six tools, breathing exercise, check-ins and history.
- Community discussions, polls, local responses, ideas and support reactions.
- Informational support screens and distinct urgent-support guidance.
- Six clearly fictional South African opportunity examples with saved listings.
- Personal goals, achievements, profile editing and settings.
- Per-account localStorage state, simulated downloads and offline settings.

## Prototype boundaries

Video, offline downloads, notifications and counselling are simulations. No applications or messages are sent. English is the available language. All sample opportunities are fictional. Demo authentication is not production security; do not enter real passwords or sensitive personal information. Clearing this browser's site data removes local demo accounts and their progress.

## Validation

JavaScript syntax and every screen renderer were checked in a JavaScript VM, including all 72 course lesson/tab combinations. Interaction checks covered idempotent lesson completion, saved courses/resources/opportunities, downloads, poll votes, idea support, check-ins, goals, replies, profile edits, logout/session restoration and localStorage serialization. Signup/login validation was also exercised.

Browser automation was unavailable in this environment. Visual review at 390px, real DOM interaction, mobile scrolling and screen-reader behavior remain unverified. CSS includes a 420px desktop shell, full-width mobile layout, fixed-navigation clearance, visible focus styles and reduced-motion support.


## September visual refinement

The app now uses a full-height flex shell: the main content scrolls independently above an opaque, bottom-docked navigation bar. Home, Learn, Quick Actions, Wellbeing, Community and Profile each occupy their own grid column. Safe-area padding is included in the bar. New reference-inspired student artwork replaces the SVG placeholder in onboarding, home, lessons and profile. Home and Learning Hub use more compact layouts. User-facing demo labels have been replaced with product wording, while unavailable services and illustrative opportunities remain explicitly described.

Validation: JavaScript syntax, 90 rendered screen/tab states, six navigation controls, artwork references and absence of demo/prototype labels in rendered main screens passed. Browser visual QA remains unavailable in this environment.
