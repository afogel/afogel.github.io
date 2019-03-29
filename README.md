# Personal Site

This site was built using [Mitchell Hanberg's Jekyll-Tailwind starter](https://github.com/mhanberg/jekyll-tailwind-starter). Thanks!


## File Structure

```
+---_includes
    \---analytics.html // place your analytics tracking snippet in here
    \---components.css // Tailwind components CSS
    \---preflight.css // Tailwind preflight CSS
    \---syntax.css // Syntax highlighting CSS
    \---tailwind.js // Tailwind configuration. This is generated by bin/setup
+---_layouts
    \---default.html
    \---page.html
    \---post.html
+---_posts
+---_bin
    \---bootstrap // Install dependencies
    \---new // Create a new post and open it in your $EDITOR
    \---setup // Initial site setup
    \---start // Start the server with the livereload, incremental, drafts, and future flags on port 5000
+---_css
    \---site.css // Entry point stylesheet. You can write your styles here or import them from the _includes directory
+---index.index // Front page. This can be changed to an HTML file if desired.
+---404.html
+---_config.yml // Jekyll configuration
+---postcss.config.js // PostCSS configuration. All plugins should be registered here.
+---purgecss.config.js // Purgecss configuration
```

