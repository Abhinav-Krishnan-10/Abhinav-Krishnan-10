# Setup

1. Create a **public** repository named exactly:

   `Abhinav-Krishnan-10`

   under the account `Abhinav-Krishnan-10`.

2. Copy:
   - `README.md`
   - `.github/workflows/profile-3d.yml`
   - `.github/workflows/snake.yml`

3. Push everything to the repository.

4. Open **Actions** in GitHub and manually run:
   - `GitHub-Profile-3D-Contrib`
   - `Generate Contribution Snake`

5. Refresh the GitHub profile after the workflows finish.

The 3D workflow will create `profile-3d-contrib/` automatically.
The snake workflow publishes generated SVG files to an `output` branch.

## Optional avatar / 3D character

GitHub READMEs cannot run interactive Three.js/WebGL directly. For a true custom 3D-looking avatar,
render a looping transparent/WebP/GIF or animated SVG and store it at:

`assets/avatar-3d.gif`

Then add this near the top of README.md:

```html
<img src="./assets/avatar-3d.gif" width="320" alt="Abhinav 3D Avatar" />
```

For the cleanest result, use a dark background, cyan rim light, subtle floating motion, and a transparent
or near-black background.
