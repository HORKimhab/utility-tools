# utility-tools

`utility-tools` is a small collection of lightweight browser-based utilities.

The goal of this repository is to keep simple, practical tools in one place without adding unnecessary build steps or backend services.

## Current Contents

At the moment, the repository includes:

- `password-generator` - a local password generator built with plain HTML, CSS, and JavaScript
<!-- Pull latest main in the submodule -->
- git submodule update --remote --merge password-generator

## Repository Structure

```text
utility-tools/
├── README.md
└── password-generator/
    ├── index.html
    ├── styles.css
    └── app.js
```

## Usage

Each tool is self-contained inside its own folder. Open the relevant folder and run or preview the tool directly in your browser.

## Development

- No build system is required right now
- No external dependencies are required right now
- Tools in this repository are intended to stay simple and easy to maintain

## Notes

This README describes the repository as a whole. Individual tools can have their own README files later if they need separate setup or documentation.


## TODO

- [ ] Term and privacy of password generaator 
- [ ] Notify user "Add your random password more after generate password" 
- [ ] Short url 
- [ ] Generate hacker names
- [ ] Text to pdf (Support Khmer font) 


