# Contributing to D-Bus City

Thank you for your interest in contributing to the D-Bus City project.

This document provides basic guidelines for contributing to the project, including reporting issues, suggesting improvements, and submitting changes.

---

## How to Contribute

### 1. Reporting Issues

If you find a bug or unexpected behavior, please create an issue in the repository and include:

* a clear description of the problem;
* steps to reproduce;
* expected and actual behavior;
* screenshots (if applicable);
* device and OS version.

---

### 2. Suggesting Features

Feature requests are welcome. Please describe:

* the proposed feature;
* why it would be useful;
* possible implementation ideas (if any).

---

### 3. Development Workflow

To contribute code changes:

1. Fork the repository.
2. Create a new branch for your feature or fix:

   ```
   feature/your-feature-name
   ```
3. Make your changes in the Godot project.
4. Test the project locally on Godot Engine 4.4 and Aurora OS build environment.
5. Commit your changes with clear messages.
6. Push to your fork.
7. Create a Pull Request.

---

## Code Style Guidelines

* Use clear and readable GDScript code.
* Follow Godot Engine recommended naming conventions.
* Keep scenes modular and reusable.
* Avoid hardcoded values when possible.

---

## Project Structure Notes

* `/scenes` — game scenes
* `/scripts` — GDScript logic
* `/assets` — images, sounds, UI elements
* `/screenshots` — project screenshots (documentation only)
* `/doc` — project documentation

---

## Testing Requirements

Before submitting changes, ensure:

* the project runs without errors in Godot 4.4;
* no crashes occur on Aurora OS build;
* UI works in portrait orientation;
* all scenes load correctly.

---

## Pull Request Guidelines

Please ensure your Pull Request:

* has a clear description of changes;
* is focused on a single feature or fix;
* does not include unrelated modifications;
* includes screenshots if UI is affected.

---

## License

By contributing to this project, you agree that your contributions will be licensed under the same license as the project (see `LICENSE.md`).
