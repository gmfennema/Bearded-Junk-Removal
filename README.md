# Bearded Junk Removal

## Local Development

To run the site locally:

1.  **Install Dependencies**:
    ```bash
    bundle install
    ```

2.  **Run the Server**:
    ```bash
    bundle exec jekyll serve --config _config.yml,_config_development.yml
    ```

3.  **View the Site**:
    Open [http://localhost:4000](http://localhost:4000) in your browser.

Using `_config_development.yml` ensures that the site uses `localhost` instead of the production domain, so CSS and JS load correctly.
