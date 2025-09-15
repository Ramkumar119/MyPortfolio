# Portfolio — Ram Kumar

A small personal portfolio built with Vite + React. This repository contains the source for a responsive single-page portfolio that showcases projects, skills, and contact information.

## Features

- Built with Vite (fast dev server and build)
- React functional components
- Responsive layout and simple animations
- Ready for deployment to Vercel (static build)

## Quick start (local)

1. Clone the repository

   git clone https://github.com/<your-username>/MyPortfolio.git
   cd MyPortfolio

2. Install dependencies

   npm install

3. Start development server

   npm run dev

4. Open in your browser

   http://localhost:5173 (or the port shown in the terminal)

## Build for production

To create an optimized production build run:

npm run build

The compiled static assets will be placed in the `dist/` folder.

You can preview the production build locally with:

npm run preview

or using a simple static server:

npx serve dist

## Deploying to Vercel (recommended)

This project is configured to deploy as a static site on Vercel. Follow these steps:

1. Push your repository to GitHub

   git add .
   git commit -m "Prepare for Vercel deployment"
   git push origin main

2. Go to https://vercel.com and import your GitHub repository.

3. During import set the following (if Vercel doesn't detect automatically):

- Build Command: `npm run build`
- Output Directory: `dist`

4. Deploy. Vercel will run build and serve the static site from the `dist` folder.

Notes

- If you use environment variables, add them in the Vercel dashboard or a `.env.production` file and configure `.vercelignore` appropriately.
- Ensure your `package.json` has the scripts `dev`, `build`, and `preview`.
- If your project lives in a subfolder of the repository, set the Root Directory when importing on Vercel.

## Troubleshooting

- Build errors: run `npm run build` locally to reproduce errors and fix missing or incompatible dependencies.
- Node version: Vercel runs recent Node versions by default; if you need a minimum, add an `engines.node` field to `package.json` (for example `"node": ">=18"`).

## Contributing

If you'd like to contribute, please open an issue or submit a pull request. Small fixes, accessibility improvements, and content updates are welcome.

## License

This repository currently has no license file. Add a `LICENSE` file if you want to make the project open-source under a specific license.

## Contact

If you need help deploying or updating this project, open an issue or contact the repository owner.

---

Happy coding!
