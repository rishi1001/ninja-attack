# Jailbreaking in the Haystack - NINJA Attack Website

This is the project website for the paper "Jailbreaking in the Haystack" by Rishi Shah, Chen Wu, Shashwat Saxena, Ziqian Zhong, Alexander Robey, and Aditi Raghunathan from Carnegie Mellon University.

## About NINJA Attack

NINJA (Needle-in-Haystack Jailbreak Attack) is a simple yet highly effective method for jailbreaking aligned language models by embedding harmful goals within benign long contexts.

## Local Development

To preview the website locally, simply open `index.html` in your web browser:

```bash
open index.html  # macOS
# or
python -m http.server 8000  # then visit http://localhost:8000
```

## Deployment

This is a static website that can be deployed to:

### GitHub Pages
1. Create a new repository or use an existing one
2. Copy all files to the repository
3. Enable GitHub Pages in repository settings
4. Your site will be available at `https://[username].github.io/[repo-name]/`

### Netlify/Vercel
1. Drag and drop the entire `temp_nerfies` folder to Netlify or Vercel
2. Your site will be automatically deployed

## Structure

- `index.html` - Main website file
- `static/` - Contains all CSS, JavaScript, images, and other assets
  - `css/` - Stylesheets
  - `js/` - JavaScript files for interactive elements
  - `images/` - Figures and images from the paper
- `15865_Jailbreaking_in_the_Hays.pdf` - The paper PDF

## Credits

Website template adapted from [Nerfies](https://github.com/nerfies/nerfies.github.io).

## License

This website is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
