[English](README.md) | [简体中文](README.zh-CN.md)

# LiteMesh Project Homepage

This repository contains the source code for the LiteMesh project homepage, presenting the research abstract, method overview, and experimental results.

**LiteMesh: An Efficient Quality-Aware Algorithm for Feature-Preserving Triangle Mesh Simplification**

## Project Links

- Project homepage: https://longwuya.github.io/LiteMesh-homepage/
- Algorithm code: https://github.com/longwuya/LiteMesh
- Homepage source code: https://github.com/longwuya/LiteMesh-homepage

## Page Contents

- Abstract: Research abstract.
- Introduction: Method overview and demonstration video.
- Results: Experimental results and comparisons with other methods.
- Citation: Paper citation information.

## Local Preview

Run the following command from the repository directory:

```sh
python -m http.server 8010 --bind 127.0.0.1
```

Local preview URL: http://127.0.0.1:8010/

## Deployment and Maintenance

The website uses static HTML, CSS, and JavaScript and is hosted on GitHub Pages. It does not require running the LiteMesh algorithm or configuring a backend service.

- Publishing branch: `main`.
- Publishing directory: Repository root.
- Updates: GitHub Pages deploys automatically after page changes are committed and pushed.

Keep author information, affiliations, research text, and experimental figure captions consistent with the project paper materials. Figures and demonstration videos are stored in the repository and deployed with the website.

## Repository Structure

```text
index.html   Page content
style.css    Page styles
page.js      Navigation and interactions
images/      Experimental figures
icon/        Institution logos
fonts/       Local fonts and licenses
video.mp4    Method demonstration video
```
