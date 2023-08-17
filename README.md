# A Modrinth App (Minecraft Launcher)
I forked this because I want to fix some bugs and problems which currently exist in the original version. I will also add some features which I think are useful.

# Installation to build your own
### Preqrequisites
- Node.js (vite, vue, tauri)
- Rust (Install it carefully)
- VSCode (Recommended)
- Intellij IDEA (Need Ultimate Edition to work with Node.js)
- Git

## Steps
1. Clone this repository
2. Open the repo  in VSCode or Intellij IDEA


3. VSCode should install the recommended extensions
    - ESLint
    - Prettier
    - Rust Analyzer
    - CSS variables autocomplete
    - Stylelint
    - Svetle Auto Import
    - Svelte for VS Code
    - Svelte Intellisense
    - Tauri
    - Vue Language Features
    - IntelliCode (Most important)
3. Intellij IDEA must install Rust plugin from JetBrains Official and enable JavaScript and TypeScript support
4. Open folder `theseus_gui` and install necessary packages from NPM
5. Build the `theseus` package from Rust first
5. Run `npm run dev` in `theseus_gui` to build stage 1
6. Run `npm run tauri dev` in `theseus_gui` to build stage 2

Now the build should be ready in `target/release` folder

## Notes
If you got into error `linker.exe` not found, you need to install Visual Studio Build Tools. [Read more here](https://code.visualstudio.com/docs/languages/rust#_common-questions)