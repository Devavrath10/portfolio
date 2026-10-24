# Devavrath Vadanya — Portfolio

Latest source: light-blue styling, green animated text, Nextstep-AI project, Gmail compose button, GitHub and LinkedIn links, and updated footer.

## Run on your Mac
1. Extract the ZIP.
2. In VS Code choose File > Open Folder and open this folder (the one containing package.json).
3. Open Terminal > New Terminal. Use Node.js 22.12 or newer (`node -v` to check).
4. Run one command at a time:

```bash
npx pnpm@11.2.2 install
npx pnpm@11.2.2 dev
```

Open the Local URL printed in the terminal, normally http://localhost:4321.
Save edits with Command+S; the browser updates automatically. Stop with Control+C.
If package.json is not found, type `cd ` in Terminal, drag this extracted folder into Terminal, and press Enter.

## Edit guide
| Content | File |
| --- | --- |
| Name, bio, education, email, social links | src/data/profile.ts |
| Projects, skills, section text | src/pages/index.astro |
| Colors, spacing, responsive layout | src/styles/portfolio.css |
| Animated text effect | src/React/LetterGlitch.tsx |
| Page metadata | src/layouts/Layout.astro |
| Images and icons | public/ |

The Gmail button opens a compose window addressed to your profile email. It does not send an email automatically.

## Build
```bash
npx pnpm@11.2.2 build
npx pnpm@11.2.2 preview
```

Use the Astro development command above, rather than Live Server.
Local edits do not automatically update your published portfolio. Upload your edited source ZIP in this conversation and ask to update the existing site. Exclude node_modules, dist, .astro, and .git when zipping.

Original template license is retained in LICENSE.
