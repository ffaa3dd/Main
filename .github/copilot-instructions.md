# Copilot Instructions

### Repository Overview
This repository contains a VuePress theme named 'Plume', a simple yet feature-rich template for documentation and blogging. It provides a functional and configurable framework to build beautiful static sites.
Homepage: [theme-plume.vuejs.press](https://theme-plume.vuejs.press)

- **Language:** TypeScript
- **Framework:** VuePress
- **License:** MIT

### Build and Validation Instructions

#### Prerequisites
- Node.js (v16 or higher)
- pnpm (v7 or higher): `npm install -g pnpm`

#### Steps
1. **Bootstrap**
   To set up the environment dependencies, run:
   ```bash
   pnpm install
   ```

2. **Build**
   To compile and build the documentation site:
   ```bash
   pnpm run build
   ```

3. **Test**
   To validate the changes:
   ```bash
   pnpm test
   ```

4. **Linting**
   To ensure code quality:
   ```bash
   pnpm run lint
   ```

### Layout Information

#### Key Directory Structure
- `.github/`: GitHub workflows and configurations.
- `docs/`: Main markdown source files for documentation.
- `plugins/`: Contains plugins to extend VuePress theme features.
- `theme/`: Consists of main components and layouts for the theme.
- `cli/`: Command-line interface scripts for theme operations.
- `preview/`: Preview builds for testing changes.

#### Configuration Files
- `pnpm-workspace.yaml`: Defines workspace for managing shared dependencies.
- `tsconfig.json`: TypeScript configuration file.
- `.markdownlint.json`: Linting rules for markdown files.
- `.stylelintignore`: Specifies files ignored for StyleLint.
- `.npmrc`: npm-related configurations.

### Additional Notes
- Always run `pnpm install` before starting any build or test processes.
- Keep node modules up-to-date to avoid dependency conflicts.
- You can reference the CONTRIBUTING.md and README.md for additional context.