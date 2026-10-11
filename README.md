# Tromsø Community Museum - Semester Project 1

A website for a fictional science museum, designed and developed for Semester Project 1 at Noroff

[View the live website](https://tommyaarstein.github.io/community-science-museum/)

## Description

Tromsø Community Science Museum presents exhibitions and practical information for people planning a museum visit.

The project focuses on creating a responsive website with clear navigation, readable content and accessible HMTL and CSS.

I designed and developed the website myself.

The website includes five pages:

- Home - an introduction and quick links to the main section.
- Exhibitions - information about anatomy, fossils and insects.
- Explore - an introduction to exploring the museum.
- Visit - location, an embedded map and opening hours.
- Contact - frequently asked questions and a demonstration contact form.

Features include:

- Responsive layouts for desktop and mobile.
- a CSS-only mobile navigation menu
- Expandable FAQ sections using HTML details and summary elements
- A skip-to-content link.
- Contact form fields with labels and native HTML validation.

## Built with

- HTML5
- CSS3
- CSS Grid
- Flexbox

## Getting started

### Installing

Clone the repository:

```bash
git clone https://github.com/tommyaarstein/community-science-museum.git
```

Open the project folder:

```bash
cd community-science-museum
```

There are no packages to install and no build step.

### Running locally

Open the project in VS Code and use the Live Server extension to serve `index.html`.

Then you can also visit the page in your preferred browser using:

```text
http://localhost:3000
```

An internet connection is required to load the embedded map.

## Usage

Use the navigation menu or homepage links to explore the museum website.

Visit the Exhibitions page to read about displays or open the Visit page to find opening hours and location.

The Contact page includes expandable answers to frequently asked questions. The contact form demostrates the layout and validation but does not send messages.

## Improvements for Portfolio 1

This assignment does not show as delivered in moodle so i do not have access to any feedback.

I improved the keyboard navigation in the shared header stylesheet.

Previously the visually hidden checkbox used to open the mobile menu could recive keyboard focus without a visible indicator on the menu icon.

I added a focus indicator to the visible menu label when checkbox recieves keyboard focus.

I also hid the checkbox with `display: none` at desktop widths, removing uneccessary hidden stop from the keyboard tab order.

These changes apply to all five pages through the shared stylesheet.

## Contributing

This is an individual school assignment, so I am completing the implementation myself.

Feedback and suggestions are welcome through GitHub issues. Please describe the issue and include steps to reproduce it, along with your browser and screen size where relevant.

## Author

**Tommy Aarstein**

Front-end development student at Noroff, based in Tromsø, Norway.

- [Github](https://github.com/tommyaarstein)
- [Email](mailto:tommy@aarstein.no)

## Acknowledgements

- [Icons8](https://icons8.com/) for interface icons.