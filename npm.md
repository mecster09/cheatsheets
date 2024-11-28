# npm Commands Cheatsheet

## **npm Commands**

### **Basic npm Commands**
| **Command**                    | **Description**                                 |
|--------------------------------|------------------------------------------------|
| `npm init`                     | Create a new `package.json` file interactively. |
| `npm init -y`                  | Create a default `package.json` file without prompts. |
| `npm install <package>`        | Install a package locally in the `node_modules` folder. |
| `npm install -g <package>`     | Install a package globally (accessible anywhere). |
| `npm uninstall <package>`      | Remove a package from your project. |
| `npm update <package>`         | Update a package to the latest version. |
| `npm outdated`                 | List packages that are outdated. |
| `npm run <script>`             | Run a custom script defined in `package.json`. |

---

### **Managing Dependencies**
| **Command**                          | **Description**                                 |
|--------------------------------------|------------------------------------------------|
| `npm install`                        | Install all dependencies from `package.json`. |
| `npm install <package> --save`       | Add a package as a dependency (default for npm v6). |
| `npm install <package> --save-dev`   | Add a package as a development dependency. |
| `npm install <package>@<version>`    | Install a specific version of a package. |
| `npm ci`                             | Install dependencies from `package-lock.json` (clean install). |

---

### **Information and Troubleshooting**
| **Command**                    | **Description**                                 |
|--------------------------------|------------------------------------------------|
| `npm list`                     | List all installed packages in the project. |
| `npm list -g`                  | List globally installed packages. |
| `npm config list`              | View npm configurations. |
| `npm audit`                    | Analyze your dependencies for vulnerabilities. |
| `npm audit fix`                | Automatically fix security vulnerabilities if possible. |
| `npm cache clean --force`      | Clear the npm cache. |

---

