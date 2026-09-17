# Assignment 1 - Digital Business Card

A Hebrew-language website for Noam Levi, a fictional professional. Built with HTML and CSS only, with no JavaScript, libraries, or installation required. Includes a local profile image, About section, contact information, Skills, Projects, responsive layouts, and light/dark modes.

## File Structure

```text
digital-business-card/
├── index.html
├── assets/
│   ├── css/style.css
│   └── images/profile.png
├── README.md
└── .gitignore
```

## How It Works

A keyboard-accessible checkbox is activated through the theme toggle label (displayed in Hebrew as "Dark mode"). The `#dark-mode:checked ~ .page` selector switches color variables in the external CSS file. Clicking again restores light mode. The preference is not permanently saved between visits. Project details expand using native HTML `details` and `summary` elements. On mobile screens, the main content switches to a single-column layout.

## Sample Information

The name, experience, and first two projects are fictional, as permitted by the assignment. The GitHub and LinkedIn URLs are fictional profile addresses that can be replaced in `index.html`; they are not guaranteed to work. The email address and phone number are also for demonstration. No messages were sent and no calls were made. Before publishing, replacing at least the two profile links with your own is recommended. The profile image was generated using the built-in ImageGen tool and depicts a fictional person.

Image generation description: a square professional portrait of a fictional 28-year-old software developer with short dark hair, light stubble, a navy shirt, and a pale blue studio background, with no text or logos.