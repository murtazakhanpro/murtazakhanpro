# CSS Practice

A small, beginner-friendly repository for experimenting with CSS Grid and building confidence with responsive layouts.

## Current Example

The page contains a six-item CSS Grid example. The grid uses responsive columns, spacing, and a mobile breakpoint so it remains usable on narrow screens.

Open `index.html` directly in a browser to view it. No build tools or dependencies are required.

## Suggested First Contribution

Improve the grid with a small visual or usability enhancement, such as adding hover and focus states to the grid items. This is a good first contribution because it is contained in `style.css`, easy to preview, and introduces an important accessibility consideration.

Other useful contribution ideas:

- Improve styling and spacing
- Make the page responsive
- Add better accessibility
- Fix visual inconsistencies
- Add more practice sections or components

## Contribution Workflow

1. Fork the repository on GitHub.
2. Clone your fork:

	```bash
	git clone https://github.com/<your-username>/css-practice.git
	cd css-practice
	```

3. Create a branch:

	```bash
	git checkout -b improve-layout
	```

4. Make changes to `index.html` and/or `style.css`.
5. Preview the page locally by opening `index.html` in a browser.
6. Commit and push your branch:

	```bash
	git add .
	git commit -m "Improve CSS layout"
	git push origin improve-layout
	```

7. Open a pull request from your branch into the original repository.

## Review Notes

The original layout used fixed column widths that could overflow smaller screens and had little context for someone viewing the page. The current version addresses those issues with semantic structure, a page heading, responsive grid columns, consistent spacing, and a mobile breakpoint.

Future improvements could include:

- Adding visible keyboard focus and hover states
- Using descriptive labels if the grid items become interactive
- Adding separate practice sections for Flexbox, typography, and forms
- Adding a lightweight contribution checklist or screenshot examples
