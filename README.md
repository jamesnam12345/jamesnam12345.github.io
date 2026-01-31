# Personal Website (James Nam)

This is the source code for my personal website, hosted at [jamesnam12345.github.io](https://jamesnam12345.github.io/).

## Tech Stack
- **Engine:** Jekyll
- **Theme:** Minima (Customized)
- **Hosting:** GitHub Pages

## Local Development

To run this website locally on your machine:

1. **Install Dependencies:**
   Make sure you have Ruby and Bundler installed.
   ```bash
   cd docs
   bundle install
   ```

2. **Start the Server:**
   ```bash
   bundle exec jekyll serve
   ```

3. **View the Site:**
   Open your browser and navigate to `http://localhost:4000`.

## Project Structure
- `docs/`: The root directory for the GitHub Pages site (configured in repo settings).
- `docs/_config.yml`: Main site configuration.
- `docs/index.md`: The landing page content.
- `docs/ai-projects.md`: The AI Projects portfolio page.
- `docs/assets/css/style.scss`: Custom styling overrides.
