# Ranga Kulathunga — Academic Website

A modular, data-driven Jekyll website. Most updates require editing only YAML files in `_data/`; the HTML templates and CSS control presentation separately.

## 1. Run locally on Windows

This project is configured for Jekyll 3.10.

1. Extract this ZIP.
2. Open the extracted project folder in VS Code (the folder containing `Gemfile` and `_config.yml`).
3. Open **Terminal → New Terminal**.
4. Run:

   ```bash
   bundle install
   bundle exec jekyll serve --livereload --force_polling
   ```

5. Open <http://127.0.0.1:4000/>.

Keep the terminal running while previewing. Press `Ctrl+C` to stop the server.

If Bundler reports that Ruby cannot find a dependency, run `bundle install` again and read the exact missing gem in the terminal. Do not switch to a different Ruby installation while installing and running.

## 2. Edit information

## 3. Publish with GitHub Pages
