# Nightfall Arsenal

A nocturnal, PS1-style low-poly 3D arena survival game. Survive endless waves by scavenging enemy weapons.

## Run locally

**Prerequisite:** [Bun](https://bun.sh/)

```sh
bun install
bun run dev
```

Open the local URL printed by Vite.

## Publish on GitHub Pages

1. Create an empty GitHub repository, then connect and push this project (replace the URL with your repository's URL):

   ```sh
   git init -b main
   git add .
   git commit -m "Prepare Nightfall Arsenal for GitHub Pages"
   git remote add origin https://github.com/<owner>/<repository>.git
   git push -u origin main
   ```

2. In the repository, open **Settings → Pages** and set the build and deployment source to **GitHub Actions**.
3. The included workflow builds and deploys the game whenever you push to `main` or `master`. You can also start it manually from the **Actions** tab.
4. When the workflow finishes, open the Pages URL shown in the deployment. Project repositories are served at `https://<owner>.github.io/<repository>/`; a `<owner>.github.io` repository is served at the root domain.

The workflow builds the app with the correct asset path for either kind of Pages URL.
