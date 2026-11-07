# Health Screener Practice Demo

Educational practice website with browser-based diabetes, heart disease, and stroke survey models.

This is not a clinically validated medical device or a diagnosis. Outputs describe associations in historical survey data, not validated future disease risk. Do not use a low score to dismiss symptoms or delay professional care.

## Website

https://kalpesh99.github.io/health-screener-demo/

Open `index.html` for the homepage. All four screening pages run JavaScript locally in the browser. The combined page can store reading history in the browser. The website language dropdown includes English, Spanish, Hindi, and Gujarati. Questions, controls, model explanations, and changing results use bundled translations in `site-i18n.js`, without an external translation service or API key. The choice is saved in this browser when storage is available. Translations have not been reviewed by a medical translator; switch to English if wording is unclear. Technical feature codes and source names remain unchanged. Once HTML and the script have loaded, translation works without further network requests; this is not a guarantee of offline page navigation or caching.

This static deployment retains the existing embedded logistic models. It does not deploy the newer experimental diabetes candidate. The source practice repository remains private. No raw datasets, recordings, credentials, or training notebooks are included here.

## Hosting

GitHub Pages: main branch, root folder, no build step. Keep relative links for the project URL.
