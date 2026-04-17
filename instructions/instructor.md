# Ms. N – Integration Lead & Project Manager

You are responsible for the overall structure, coordination, and final quality of the Magical Forest project.

Your role is to ensure that all parts of the project:
- Work together correctly
- Follow a consistent structure
- Meet the final project requirements

---

# Core Responsibilities

## 1. Homepage Development

- Build and maintain the main entry point (`index.html`)
- Create the interactive forest interface
- Ensure all creature links (Dragon, Unicorn, Elf) function correctly

---

## 2. Integration of Components

- Combine work from all team members into a single system
- Ensure:
  - Navigation links work across folders
  - Pages are properly connected
  - No broken paths or missing files

---

## 3. Code Consistency

- Ensure consistent:
  - File structure
  - Naming conventions
  - Layout patterns

- Standardize:
  - Navigation bars
  - Page structure
  - Shared components

---

## 4. Debugging & Issue Resolution

- Identify and fix:
  - Broken links
  - JavaScript errors
  - Layout inconsistencies

- Use browser developer tools to inspect issues

---

## 5. Version Control Oversight

- Monitor commits and pushes on GitHub
- Ensure students:
  - Pull before starting work
  - Use meaningful commit messages
  - Avoid overwriting others’ work

- Resolve merge conflicts if necessary

---

## 6. Final Review & Testing

Before deployment, verify:

- All pages load correctly
- Navigation works across all sections
- Games function as expected
- Styling is consistent across pages

---

# Core Concepts

## 1. System Integration

Combining multiple independent components into one functional system.

Key considerations:
- Compatibility between files
- Consistent linking
- Unified structure

---

## 2. Relative File Paths

Understanding how files connect across folders:

- Same folder:
```html
<a href="game.html">
````

* Parent folder:

```html
<a href="../index.html">
```

---

## 3. Debugging Workflow

Steps:

1. Identify the issue
2. Locate the source file
3. Test changes locally
4. Re-test after fixing

---

## 4. Testing Strategy

* Test navigation from every page
* Check all links manually
* Verify game functionality multiple times

---

# Tools

## Development Tools

* Visual Studio Code
* GitHub Desktop

## Browser Tools

* Chrome DevTools:

  * Inspect elements
  * Console for JavaScript errors
  * Network tab for missing files

---

# Project Structure Oversight

Ensure the project follows this structure:

```
index.html

dragon/
  index.html
  game.html
  info.html

elf/
  index.html
  game.html
  info.html

unicorn/
  index.html
  game.html
  info.html

css/
  style.css
```

---

# Coordination

* Review student progress regularly
* Provide guidance when needed
* Ensure collaboration between:

  * UI (structure)
  * Styling (visuals)
  * Games (logic)

---

# Final Checklist

* Homepage links to all creature pages
* Each creature has:

  * Gallery page
  * Game page
  * Info page
* Navigation is consistent across all pages
* No broken links
* No major bugs
