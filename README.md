
# CyberNeuroRT Documentation Setup

Use mkdocs library to generate documentation quickly

## Install mkdocs:

```
pip install mkdocs
```

## Build the Site Locally:

Run the following command in your terminal inside your project directory:

```
mkdocs build
```

Check the site/ Folder

After running mkdocs build, navigate to the site/ directory in your project. You should see an index.html file and other HTML files corresponding to your Markdown documentation files.

## Test Locally

You can test the generated documentation locally by running:

```mkdocs serve```

This will start a local web server at http://127.0.0.1:8000 where you can preview your generated site, including index.html.

## Deploying to GitHub Pages

 - Use mkdocs gh-deploy:
    After confirming that your site is built correctly and the index.html file is present in the site/ folder, you can deploy the documentation to GitHub Pages with the following command:

```mkdocs gh-deploy```

This command will:

Build the site (if you haven’t already).

Push the content of the site/ folder to the gh-pages branch of your repository.

GitHub Pages will automatically serve the content from the gh-pages branch.

## Verify GitHub Pages Settings

Make sure that your GitHub Pages settings are correct:

1. Go to your repository’s Settings page.

2. Scroll down to the GitHub Pages section.

3. Set the Source to the gh-pages branch or the branch you're using (for example, main with /docs folder).

4. Ensure that the root or docs folder is selected as the source for your site.