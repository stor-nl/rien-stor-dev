# Jekyll Blog

A simple Jekyll blog ready for GitHub Pages deployment.

## Getting Started

1. **Install dependencies:**
   ```bash
   bundle install
   ```

2. **Run the development server:**
   ```bash
   bundle exec jekyll serve
   ```

3. **View your site:**
   Open [http://localhost:4000](http://localhost:4000) in your browser.

## Customization

### Site Configuration
Edit `_config.yml` to customize your site's title, description, and other settings.

### Adding Posts
Create new blog posts in the `_posts` directory following the naming convention:
```
YYYY-MM-DD-title-of-your-post.md
```

### Styling
The main stylesheet is located at `assets/css/main.css`. You can customize the appearance by modifying this file.

### Themes
This setup uses a custom layout, but you can easily switch to a Jekyll theme by:
1. Adding the theme gem to your `Gemfile`
2. Updating the `theme` setting in `_config.yml`
3. Removing or overriding the custom layouts in `_layouts/`

## GitHub Pages Deployment

This repository is configured to automatically deploy to GitHub Pages when you push to the main branch. The deployment workflow is defined in `.github/workflows/pages.yml`.

## File Structure

```
├── _config.yml          # Site configuration
├── _layouts/            # Layout templates
│   ├── default.html     # Default layout
│   └── post.html        # Blog post layout
├── _posts/              # Blog posts
├── assets/              # Static assets
│   └── css/
│       └── main.css     # Main stylesheet
├── .github/
│   └── workflows/
│       └── pages.yml    # GitHub Pages deployment
├── Gemfile              # Ruby dependencies
├── index.html           # Homepage
└── README.md            # This file
```

## Next Steps

1. Customize the site title and description in `_config.yml`
2. Add your own blog posts to the `_posts` directory
3. Customize the styling in `assets/css/main.css`
4. Consider adding a theme for more advanced styling options
