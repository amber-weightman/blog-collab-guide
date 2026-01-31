# blog-collab-guide

A collaborative blog powered by Jekyll and GitHub Pages.

## Getting Started

### Prerequisites

- Ruby (installed)
- Bundler (installed)

### Testing Locally

To run the site locally and preview your changes:

```bash
cd docs
bundle exec jekyll serve
```

Your site will be available at `http://localhost:4000`. The site will automatically rebuild when you make changes to files.

To stop the server, press `Ctrl+C` in the terminal.

### Adding Content

#### Creating a New Post

1. Create a new file in `docs/_posts/` with the naming format: `YYYY-MM-DD-title.md`
2. Add front matter at the top of the file:
   ```yaml
   ---
   layout: post
   title: "Your Post Title"
   date: YYYY-MM-DD HH:MM:SS
   categories: [category1, category2]
   ---
   ```
3. Write your content below the front matter using Markdown
4. Save and preview locally before committing

#### Editing Pages

- Edit existing pages in the `docs/` directory
- The site will automatically rebuild when you save changes (if running locally)

### Publishing to GitHub Pages

1. Commit your changes: `git add . && git commit -m "Your message"`
2. Push to GitHub: `git push`
3. GitHub Pages will automatically build and deploy your site
4. Visit your site at: `https://amber-weightman.github.io/blog-collab-guide/`

## Configuration

Edit `docs/_config.yml` to customize your site settings like title, description, and theme options.