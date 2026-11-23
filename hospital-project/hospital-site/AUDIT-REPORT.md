# Before-and-After Accessibility Audit

Name: Devalla Revanth Krishna (2600080047)
Project: Hospital Patient Appointment Management Website
Tools: Lighthouse (Chrome DevTools), WAVE, Windows Narrator / NVDA

## 1. Audit scores

| Category | Before | After |
|---|---|---|
| Accessibility | __ / 100 | __ / 100 |
| Best Practices | __ / 100 | __ / 100 |
| SEO | __ / 100 | __ / 100 |
| WAVE errors | __ | __ |

## 2. Problems in the original page and how they were fixed

| Problem (before) | Fix (after) |
|---|---|
| No lang attribute, no title, no meta tags | Added lang="en", title, meta description and viewport |
| Whole page built with div elements | Replaced with header, nav, main, section, article, aside, footer |
| Headings were styled divs, no heading levels | Real h1, h2 and h3 in correct order |
| Form fields had only placeholders, no labels | Added label for each field linked with for and id |
| Phone, email and date used type="text" | Changed to type="tel", "email" and "date" |
| No validation | Added required, pattern and minlength |
| Radio buttons not grouped | Wrapped in fieldset with legend |
| "Book Now" was a div, not usable with keyboard | Replaced with a real button type="submit" |
| Low colour contrast (white on light blue) | Changed to dark blue with white text |
| No visible focus, no skip link | Added focus outline and skip link |

## 3. Screen reader testing

Tool: ____ (Narrator: Win + Ctrl + Enter)

| Check | Before | After |
|---|---|---|
| Page title announced | | |
| Landmarks (header, nav, main) found | | |
| Headings list makes sense | | |
| Form fields announced with their label | | |
| Radio group announced with "Gender" | | |
| Submit button announced as a button | | |

Notes: ____

## 4. Screenshots
Add before and after screenshots in a `screenshots/` folder.
