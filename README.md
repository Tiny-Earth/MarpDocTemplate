# MarpDocTemplate

Usage:

1. [Use this template](https://github.com/new?template_name=MarpDocTemplate&template_owner=Tiny-Earth)
2. In your new repo, go to `Settings / Pages`. Make sure `Source` is set to `GitHub Actions`
3. Go to `Settings / Environments / github-pages`. Press `Add deployment branch or tag rule`. Set `Ref type` to `Tag` and `name pattern` to `v*`
4. Go to `Code / Releases` (right sidebar). Click `Draft a new release`. Set `Choose a tag` to `v0.1` and `Release title` also to `v0.1`
5. Go to `Code` and click the gear symbol by `About`. Check `Use your GitHub Pages website`
6. To confirm that everything worked, click the link that appeared under `Code / About`. If it errors, check `Actions` to see if it failed to build the webpage or if it is still working on it.

Once everything works, edit the following files as necessary:

- `md/index.md`, the content of the document in [CommonMark](https://commonmark.org/help/)
- `public/style.css`, the style of the document in [CSS](https://www.w3schools.com/css/)
- `public/script.js`, additional logic for the document in [JavaScript](https://www.w3schools.com/js/)

If you have images for the webpage, put them under `public/`.

Once you are happy with edits, repeat step 4 above, using the next appropriate [version number](https://nesbitt.io/2024/06/24/from-zerover-to-semver-a-comprehensive-list-of-versioning-schemes-in-open-source.html).
