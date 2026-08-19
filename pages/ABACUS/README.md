# ABACUS Project Website

## Overview

This directory contains the project website for **ABACUS: Adapting Unified Foundation Model for Bridging Image Count Understanding and Generation**.

## Project Details

- **Title:** ABACUS: Adapting Unified Foundation Model for Bridging Image Count Understanding and Generation
- **Authors:** 
  - Anindya Mondal (University of Surrey)*
  - Sauradip Nag (Simon Fraser University)*
  - Anjan Dutta (University of Surrey)
  - (*) Equal contribution

- **Conference:** NeurIPS 2026
- **Project Page:** https://mondalanindya.github.io/abacus/
- **GitHub Repository:** https://github.com/mondalanindya/ABACUS_NeurIPS_26

## About ABACUS

ABACUS is a unified vision-language model that handles:
- Object counting
- Crowd counting
- Referring-expression counting
- Count-faithful image generation

All without any benchmark-specific training required!

### Key Innovations

1. **Density-Aware Adaptive Zooming** with objectness maps for spatial grounding
2. **Boundary-Aware Count Policy** via GRPO to eliminate crop-boundary errors
3. **Cycle-Consistent GRPO Strategy** where the understanding branch self-critiques generated outputs

## Website Structure

```
docs/
├── index.html          # Main project webpage
├── README.md           # This file
├── .nojekyll           # GitHub Pages configuration
├── favicon.ico         # Website favicon
├── static/             # Static assets (images, etc.)
└── assets/             # Additional resources
```

## Building and Deploying

The website is designed to be served by GitHub Pages. To deploy:

1. Push the `docs/` folder to your GitHub repository
2. Go to repository Settings → Pages
3. Select "Deploy from a branch"
4. Choose the branch and set folder to `/docs`
5. The site will be available at `https://username.github.io/repository-name/`

## Customization

To customize the website:

- Update `index.html` with project-specific content
- Add images/logos to `docs/static/`
- Update author information and links
- Modify colors and styling in the `<style>` section

## Resources

- **Paper:** Coming soon
- **GitHub:** https://github.com/mondalanindya/ABACUS_NeurIPS_26
- **Citation:** Coming soon

---

For questions or suggestions, please open an issue on the GitHub repository.
