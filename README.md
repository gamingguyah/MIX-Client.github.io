# MIX - Minecraft PVP Client Website

A sleek website for the MIX Minecraft PVP client, hosted on GitHub Pages.

## Setup Instructions

1. Create a new GitHub repository
2. Upload all these files to the repository
3. Go to repository Settings > Pages
4. Set source to "Deploy from a branch" and select "main" branch
5. Your site will be live at `https://yourusername.github.io/repository-name/`

## Adding the Client File

Place your MIX client JAR file in the `downloads/` folder and name it `MIX-Client-v1.0.0.jar`

## Files Structure

```
├── index.html          # Main webpage
├── style.css          # Stylesheet
├── 404.html          # Custom 404 page
├── .nojekyll         # Disables Jekyll processing
├── downloads/
│   └── MIX-Client-v1.0.0.jar    # Client file (add your own)
└── README.md         # This file
```

## Customization

- Edit `index.html` to update version numbers, features, or text
- Modify `style.css` to change colors, fonts, or layout
- Update the download links when you release new versions
