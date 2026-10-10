Readme document for Stella (Yuxuan) Jiang, jyxsju@gmail.com

1. How many assignment points do you believe you completed?

10/10
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 2/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features
- Images: the original system-signal.svg illustration and Stella's orange pixel-cat mascot appear in index.html with descriptive alternative text.
- Headings and text: both pages use a logical h1-h3 hierarchy, paragraphs, and lists.
- External links: the Contact section links to LinkedIn and GitHub and includes an email link.
- Multiple pages: index.html and projects.html use consistent navigation in both directions.
- Semantic HTML: header, nav, main, section, article, figure, details, and footer organize the content.
- Custom icons: Google Material Icons identify the email, LinkedIn, GitHub, and About actions while remaining hidden from screen readers so the adjacent text supplies each accessible name.

This completes all six listed basic HTML options and exceeds the three-feature requirement.

(b) CSS features
- Custom colors, typography, spacing, borders, shadows, and rounded shapes. Padding and margins create readable visual grouping throughout both pages.
- CSS Grid and Flexbox for the navigation, hero, project cards, process, skill groups, and footer.
- Responsive breakpoints for tablet and mobile layouts.
- Visible keyboard focus styles, hover states, and high-contrast buttons.

This directly satisfies the listed spacing and custom-color options, in addition to the responsive layout work.

(c) Advanced features
- A multi-column project evidence table in projects.html with a caption, scoped row and column headers, and explicit header relationships for screen-reader navigation.
- Complex layouts built with navigation, CSS Grid, Flexbox, and nested selectors; these adapt across desktop, tablet, and phone widths.
- A native interactive details/summary component in the About section.
- A reduced-motion media query and a keyboard-accessible skip link.
- An original scalable SVG graphic stored locally, so the page does not rely on external assets.
- A personal pixel-art cat mascot, optimized as a transparent local PNG and styled responsively in the About section.

3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern?

AChecker reported 0 Known Problems and 0 Likely Problems for both HTML pages under WCAG 2.0 Level AA. It listed 47 Potential Problems for index.html and 38 for projects.html; these are prompts for human review rather than confirmed failures. I manually checked the logical heading order, semantic landmarks, descriptive link text, image alternative text, keyboard focus indicators, table header relationships, and color contrast. Lighthouse also gave the main page an accessibility score of 100. The decorative project numbers and visual status dot are hidden from assistive technology where appropriate.

The W3C CSS validator reported 0 errors and a small set of diagnostic warnings at its standard warning levels. The warnings concern the system-font fallback stack, CSS variables that the validator cannot evaluate statically, and foreground or background colors inherited from parent elements. More sensitive warning settings may repeat the inheritance checks across additional selectors. These choices are intentional: each component inherits a defined readable color combination, and the rendered pages were manually reviewed at desktop, tablet, and mobile sizes. No CSS warning indicates an invalid rule.

4. How long, in hours, did it take you to complete this assignment?

Approximately 4 hours for planning, implementation, responsive testing, validation, and documentation.

5. What online resources did you consult when completing this assignment?

- MDN responsive design overview: https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design
- MDN CSS Grid guide: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout
- MDN details element reference: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details
- Google Material Icons: https://fonts.google.com/icons
- W3C HTML validator: https://validator.w3.org/
- W3C CSS validator: https://jigsaw.w3.org/css-validator/
- AChecker accessibility checker: https://achecks.org/achecker/
- Chrome Lighthouse accessibility audit.
- The instructor-provided starter repository and assignment instructions.
- Openai helped me to review the code, understand rubrics and use rubrics to help me review and improve. I independently completed the initial code construction and subsequent improvement.

6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?

I did not consult classmates or other individuals for this assignment.

7. Is there anything special we need to know in order to run your code?

No installation or build step is required. Unzip the submission and open index.html directly in a modern browser. All styles and visual assets use relative local paths.

Validation evidence is included as separate image files:
- valid-html-index.jpg and valid-accessibility-achecker.jpg document index.html.
- valid-html-projects.jpg and valid-accessibility-projects-achecker.jpg document projects.html.
- valid-css-styles.jpg documents the shared styles.css file used by both pages.
- valid-accessibility-lighthouse.jpg is an additional accessibility audit for the main page.
