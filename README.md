# From the Point

**[Explore the live experience](https://jameel7007.github.io/from-the-point-site/)**

A scroll-driven drawing of Islamic geometric patterns. The sequence begins with a point, then develops a circle, vesica, sixfold rose, eightfold *khātam*, tenfold rosette, and twelvefold pattern before returning to the point. The site's colophon credits Keith Critchlow's *Islamic Patterns* as an inspiration.

## What this repository contains

This is the **published GitHub Pages output**: `index.html`, generated JavaScript and CSS in `assets/`, and `.nojekyll`. The original, editable source project is private and is **not included here**. Generated bundles are not a useful substitute for the original modules, build configuration, or tests, so this repository currently demonstrates the deployed result rather than the implementation.

The page's HTML describes the drawing as a sequence constructed from a shared radius using compass and straightedge relationships. The generated files are committed here for hosting; changes to the original experience should be made in the source project and redeployed.

## Preview the deployed files

The built page loads files from `/from-the-point-site/assets/`. From a directory **containing** this repository as `from-the-point-site/`, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/from-the-point-site/`. Opening `index.html` directly from the file system will not reproduce the deployed asset paths.

## For a reviewable source repository

Publish the original source files and their build instructions in a public repository, then link to it here. Keeping this deployment repository separate is fine as long as reviewers can follow that link to the actual source. Do not treat the generated files in `assets/` as the authored source.
