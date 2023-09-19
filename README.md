# Curio Open Dag - Software Developer Opleiding

Dit project is speciaal gemaakt voor de open dag van Curio, ter promotie van onze Software Developer-opleiding.

## Doel

Het hoofddoel van deze website is om informatie te verstrekken aan potentiële studenten en andere geïnteresseerden die de open dag bijwonen. We willen een overzicht bieden van wat onze opleiding te bieden heeft.

## Gebruik

- **Navigatie**: Ga naar de website om meer te ontdekken over onze opleiding en de open dag.
- **Informatie**: Vind hier details over ons curriculum, docenten, locatie en meer.
- **Contact**: Neem contact met ons op voor vragen of om deel te nemen aan de open dag.

Dank je wel voor je interesse in onze Software Developer-opleiding. We hopen je te verwelkomen op onze open dag!

![Curio Logo](curiologo.png)



# Web Development Conventions

This document outlines coding and project management conventions to ensure consistency and maintainability in web development projects.

## Table of Contents

1. [Coding Conventions](#coding-conventions)
   - [HTML](#html)
   - [CSS](#css)
   - [JavaScript](#javascript)
   - [Naming Conventions](#naming-conventions)

### HTML conventions

- Specify the document type with `<!DOCTYPE html>` at the beginning of HTML files.
- Use consistent and meaningful indentation (e.g., 2 spaces or 4 spaces).
- Organize HTML elements logically, following a clear structure.
- Use semantic HTML elements whenever possible (e.g., `<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`).
- Include comments to explain complex or non-obvious code.
- Use lowercase letters for HTML tags and attributes.
- Provide alternative text for images using the `alt` attribute.
- Keep the use of inline styles and inline JavaScript to a minimum.

### CSS conventions

- Use meaningful and descriptive class and ID names for CSS selectors.
- Maintain a consistent indentation and formatting style.
- Use external CSS files for styles, and link them in the HTML with the `<link>` tag.
- Group related CSS rules together for better readability.
- Avoid using `!important` unless absolutely necessary.
- Use CSS preprocessors like SASS or LESS for more maintainable stylesheets if appropriate.
- Implement responsive design techniques for cross-device compatibility.
- Comment your CSS to explain the purpose of specific styles or sections.

### JavaScript conventions

- Use consistent and meaningful variable and function names.
- Follow the appropriate coding style (e.g., camelCase, snake_case) for variable and function naming.
- Use `const` or `let` to declare variables and avoid using `var`.
- Use strict mode by adding `"use strict";` at the beginning of JavaScript files.
- Organize code into functions or modules with clear responsibilities.
- Avoid global variables whenever possible.
- Handle errors and exceptions gracefully using try-catch blocks.
- Use meaningful comments to explain complex algorithms or logic.
- Minimize the use of synchronous operations to avoid blocking the main thread.

### Naming Conventions

- Follow a consistent naming convention for files and directories (e.g., kebab-case, snake_case, or camelCase).
- Choose descriptive and meaningful names for variables, functions, classes, and identifiers.
- Use clear and concise names to improve code readability and understanding.
- Use prefixes or namespaces when necessary to avoid naming conflicts.
- Document naming conventions in the project's documentation for team members to follow.
