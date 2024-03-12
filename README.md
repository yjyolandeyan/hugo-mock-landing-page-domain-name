# hugo-mock-landing-page
I made a website for a product where you can upload your recipes with your family, so that everyone can be a part of the making and meal designing stage together.

# Description of workflow
The workflow, .github/workflows/gh-pages-deployment.yaml file, I've created is designed for automating the build and deployment of a Hugo-powered website to GitHub Pages using GitHub Actions. It's a sequence of operations triggered by a push event to the main branch of your GitHub repository. 

The workflow is triggered by any 'push' even to the 'main' branch of the GitHub repository, which ensures that any new changes pushed to this branch initiate the build and deployment process.

It consists of a single job named 'deploy' which runs on an 'ubuntu-22.04' virtual environment. It checks out the repository, sets up Hugo, builds the static files to 'gh-pages', and publishes them to GitHub Pages. 

Furthermore, after importing the hugo-mock-landing-page repository, I also modified configurations for the repository settings to ensure the workflow runs smoothly. This includes but not limits to configuring GITHUB_TOKEN Permissions to enable read and write operations; enabling GitHub Pages to set the publishing source to gh-pages; and set permissions for GitHub Actions so that it grants me to edit and manage this repository.
