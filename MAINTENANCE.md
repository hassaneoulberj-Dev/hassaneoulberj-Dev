# Profile maintenance

## Update personal information

Edit `README.md` to update your degree, contact details and projects. Check every repository link and only list skills and achievements you want to represent publicly. Keep the image descriptions readable when an external badge service is unavailable.

## Contribution animation

The Pac-Man animation is configured in `.github/workflows/pacman.yml`. After updating that file, inspect the corresponding run in the repository’s Actions tab. The README references generated SVGs on the `output` branch.

If the animation is missing, check the generation and publication steps separately. Confirm that both SVG filenames match the README links. A successful local commit does not mean the remote workflow has completed.

## Preview and publish

Preview the README on GitHub and check both light and dark appearance. Verify the header, typing animation, contribution graph, badges and contact links. Commit the intended files explicitly, then push the profile repository’s `main` branch.

The old `assets/learning-flow.gif` and its preview are unused by the current README. They do not need to be added to Git to update the profile.
