# Virtual Show Production Rework Demo

Install & Launch Dev Server
```cmd
git clone https://github.com/Ashrilys/vsp-demo
cd vsp-demo
npm i
npm run dev
```

[![Open in StackBlitz](https://github.com/Ashrilys/vsp-demo/blob/main/r.md_assets/launch/stackblitz.svg?raw=true)](https://stackblitz.com/github/Ashrilys/vsp-demo/tree/latest/examples/basics)
[![Open with CodeSandbox](https://github.com/Ashrilys/vsp-demo/blob/main/r.md_assets/launch/codesandbox.svg?raw=true)](https://codesandbox.io/p/sandbox/Ashrilys/withastro/vsp-demo/tree/latest/examples/basics)
[![Open in GitHub Codespaces](https://github.com/Ashrilys/vsp-demo/blob/main/r.md_assets/launch/github-codespaces.svg?raw=true)](https://codespaces.new/Ashrilys/vsp-demo?devcontainer_path=.devcontainer/basics/devcontainer.json)

> 🧑‍🚀 **Why Rework?** A breath of fresh air for the VSP! [Watch the comparison](https://github.com/Ashrilys/vsp-demo/blob/main/r.md_assets/vsp-compare/)

![new-homepage](https://github.com/Ashrilys/vsp-demo/blob/main/r.md_assets/vsp-compare/rework-by-me/vsp-demo-2023-09-20-20_50_35.png?raw=true)

## 🚀 Project Structure

Inside of my Astro project for VSP, you'll see the following folders and files:

```
/
├── public/
│   ├── assets/
│   │    └── img/
│   │        ├── FavEmission/ # Link to FavEmission Component
│   │        │   └── *.png-jpg 
│   │        ├── HeadImage/ # Link to HeadImage Component
│   │        │   └── *.png-jpg 
│   │        ├── JoinSocial/ # Link to JoinSocial Component
│   │        │   └── *.png-jpg 
│   │        ├── LastPost/ # Link to LastPost Component
│   │        │   └── *.png-jpg 
│   │        ├── Partner/ # Link to Partner Component
│   │        │   └── *.png-jpg
│   │        └── Staff/ # Link to Staff Component
│   │        └── *.webp
│   ├── fakeAPI/ # Fake API for LastPost Component
│   │   └── lastPost.json 
│   └── favicon.svg
├── src/
│   ├── assets/
│   │    └── js/*.js
│   ├── components/
│   │    ├── Emissions/
│   │    │    ├── Head.astro
│   │    │    └── Video.astro
│   │    ├── LastPost/ # Link to LastPost Component
│   │    │    └── Card.astro
│   │    ├── AboutVSP.astro
│   │    ├── FavEmission.astro
│   │    ├── Footer.astro
│   │    ├── HeadImage.astro
│   │    ├── LastPost.astro 
│   │    ├── Navbar.astro
│   │    ├── Partner.astro
│   │   └── StaffCard.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│    ├── emission/
│    │  ├── kus-talk-show.astro
│    │  ├── personal-journey.astro
│       │  └── reportages.astro
│       ├── film/
│       │   ├── lost-in-the-metaverse.astro
│       │   └── wrong-person-bad-job.astro
│       ├── participer/
│       │   └── personal-journey.astro
│       ├── a-propos.astro
│       ├── contact.astro
│       └── index.astro
├── astro.config.mjs
├── tailwind.config.cjs
└── package.json
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:3000`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [Astro documentation](https://docs.astro.build) or contact me for help.
