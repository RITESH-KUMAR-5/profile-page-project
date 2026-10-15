# Personal Profile Page

A responsive profile page built with semantic HTML5 and CSS. It includes a header/navigation, About section, Skills list, Contact form, and footer.

## Features

- Semantic page structure: `header`, `nav`, `main`, `section`, `form`, and `footer`
- Responsive layout for mobile and desktop screen sizes
- Accessible form labels, useful input types, required-field validation, and visible keyboard focus
- No build tools or third-party dependencies required

## Project files

```text
profile-page/
├── index.html
├── styles.css
└── README.md
```

## Run locally

1. Download or clone this repository.
2. Open the project folder in VS Code.
3. Open `index.html` in a browser. Alternatively, use the VS Code Live Server extension.
4. Resize the browser or use Developer Tools' device toolbar to test a phone-sized and desktop-sized layout.

## What is semantic HTML?

Semantic HTML means choosing elements that describe the purpose of their content rather than using generic containers for everything.

- `<header>` contains the introductory banner and site navigation.
- `<nav>` identifies a group of navigation links.
- `<main>` wraps the page's primary content.
- `<section>` groups related content under a heading.
- `<form>`, `<label>`, `<input>`, and `<textarea>` provide meaningful, accessible form controls.
- `<footer>` contains closing information and a back-to-top link.

Semantic elements improve document structure, accessibility for assistive technology, and maintainability. They do not automatically make a site accessible; good labels, keyboard focus, contrast, and sensible heading order still matter.

## Contact form note

The contact form currently demonstrates browser-side required-field and email-format validation. Because no backend or form service is configured, it does **not** send or store messages. To receive messages, connect the form to a server or a trusted form-handling service and update the `action` attribute.

## Git workflow: submit with a Pull Request

The commands below assume the project is in a Git repository and that you have permission to push a branch to the remote repository. Replace the remote URL and branch names to match your assignment.

### 1. Open a terminal in the project folder

```bash
cd path/to/profile-page
git status
```

If this folder is not yet a Git repository and your instructor expects you to create one, run `git init`. If the assignment repository already exists, do not initialize a nested repository.

### 2. Create a feature branch

```bash
git switch -c feature/profile-page
```

### 3. Stage and commit your work

```bash
git add index.html styles.css README.md
git commit -m "Build responsive semantic profile page"
```

If Git asks you to set your identity, configure the name and email you use for your repository account:

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

Then repeat the commit command.

### 4. Push your branch

```bash
git push -u origin feature/profile-page
```

### 5. Open a Pull Request (PR)

1. Open your repository in your Git hosting service, such as Azure DevOps or GitHub.
2. Choose **New pull request** (Azure DevOps) or **Compare & pull request** (GitHub).
3. Set the **source** branch to `feature/profile-page`.
4. Set the **target** branch to the assignment's required branch, commonly `main`.
5. Add a clear title such as `Build responsive semantic profile page`.
6. Describe the page sections and note that the contact form is a front-end demo only.
7. Add the required reviewer(s), if your assignment asks for them.
8. Review the changed files and create the PR. Do not complete/merge it unless the assignment instructions say to do so.

### If you already have an assignment repository

Clone that repository first, then put these three files in its expected assignment folder. Do not create a separate repository inside it. Follow the repository's required source and target branch names if they differ from the example above.
