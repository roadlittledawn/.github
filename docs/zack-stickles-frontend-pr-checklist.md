1. Continuous Integration

- Have the required tests passed?
- Has the build completed successfully?
- Does the submitted code meet linting requirements?
- Have all the other required checks passed?

2. Code Style

- Are variables and function names consistent with the code base?
- Are variables and function names clear and accurate?
- Are the files located in a reasonable location?
- Are all the files related to the purpose of PR?
- Are the included libraries required?
- Are comments included when the code may not be clear?

3. CSS

- Does it render well in blink (Chrome)?
- Does it render well in gecko (Firefox)?
- Does it render well in webkit (Safari)?
- Does it render well on a mobile breakpoint?
- Does it render well on a mobile breakpoint?
- Does it render well on an android device?
- Does it render well on an iOS device?
- Do all the style rules used have good browser support?

4. Javascript

- Is the browser console clear of errors?
- Are all the network requests successful?
- Does that page load in a timely manner?
- Do all the APIs used have good browser support?
- Are all the network requests debounced as needed?
- Are there no duplicate network requests?
- Are there no duplicate function calls / unnecessary render calls?

5. Security

- Are there no secrets / sensitive information checked in?
- Are all the references to environmental variables set correctly?
- Are all the inputs safe from code injection?

6. Accessibility

- Are semantic tags used (where applicable)?
- Does the page structure make sense for screen readers (headings, sections, etc)?
- Are all the meaningful page elements represented in the HTML (as supposed to images)?
- Do all images have alt tags?
- Are tab-indexes included?
- Does the text have an appropriate amount of contrast?

7. Github

- Is the code branched off the correct base branch?
- Does the PR have a descriptive title?
- Does the PR include an informative description?
- Is the issue linked correctly?
- Are the applicable labels added?
