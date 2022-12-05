# Brickerz PHP template

This publication describes a standard structure suitable for all PHP projects.

## Summary

### **Root-level directories:**

This are recommended directory names for each purpose. 

The project may contain other root-level directories for purposes not described in this publication.

| Directory                  | Purpose / Description                           |
| -------------------------- | ----------------------------------------------- |
| `bin/`                     | Command-line executables                        |
| `config/`                  | Configuration files                             |
| `docs/`                    | Documentation files                             |
| `public/`                  | Web server files, this directory may be intended as a web server document root. Alternatively, it may be that the files will be served dynamically via other code, copied or symlinked to the "real" document root, or otherwise managed so that they become publicly available on the web.  |
| `vendor/`                  | 3rd party code                                  |
| `src/`                     | PHP source code                                 |
| `tests/`                   | Test code                                       |

#
### **Root-level files:**

These are recommended files for providing information about the project, such as release notes, licenses and copyrights, guidelines for contributors, and more.

The project may contain other root-level files for purposes not described in this publication.

| File                       | Purpose / Description                           |
| -------------------------- | ----------------------------------------------- |
| `README(.*)`               | General information about the project, installation, requirements, etc. |
| `CHANGELOG(.*)`            | A log of changes between releases               |
| `CONTRIBUTING(.*)`         | Guidelines for contributors                     |
| `LICENSE(.*)`              | Licensing information                           |

<!-- # -->
<!-- ### **Source code structure:** -->

### **Source code:**
#

This post does not indicate any rules to structure your code, but here are some recommendations...

- Use an autoloader
- Use object oriented programming
- Use MVC (Model - View - Controller) design pattern.
- If you are developing the backend and frontend of a project, here are two ways to go about it:
    
    - One approach is to make the front pages in the Views folder, this way the backend and frontend are dependent on each other, it's much harder to switch technologies in the future.

    - The other approach is to make a backend API that will be consumed by the frontend, this last option is more flexible, because your frontend and backend are not dependent on each other.
