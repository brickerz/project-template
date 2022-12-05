# Brickerz PHP template

This publication describes a standard structure suitable for all PHP projects.

Command-line tools for `validating` or `generating` PDS conform projects which are included with this standard are documented [here](./docs/tools.md).

## Summary
#

### **Root-level directories:**

This are recommended directory names for each purpose. 

The project may contain other root-level directories for purposes not described in this publication.

| Directory                  | Purpose / Description                           |
| -------------------------- | ----------------------------------------------- |
| `bin/`                     | Command-line executables                        |
| `config/`                  | Configuration files                             |
| `docs/`                    | Documentation files                             |
| `public/`                  | Web server files, This directory may be intended as a web server document root. Alternatively, it may be that the files will be served dynamically via other code, copied or symlinked to the "real" document root, or otherwise managed so that they become publicly available on the web.  |
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
