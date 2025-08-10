
# Contributing
Visit [GitHub](https://github.com/entrypointdailies/wiki)

Do not update the site branch immediately. This will revert all changes upon push.

Additionally, do not duplicate content from other online sources. Write original text for the world.
# By editing on the web
This method is less technically-involved, but will require a bit of imagination.

1. Sign in/sign up to [GitHub](https://github.com/).
2. Fork the repository [here](https://github.com/EntryPointDailies/wiki/fork).
3. Navigate to /docs and edit the corresponding file.
4. Commit your changes to your repository.
5. Create a pull request with your changes.
# With GitHub Pages
This method is minimally technically-involved, but will require a some setup and patience.

1. Sign in/sign up to [GitHub](https://github.com/).
2. Fork the repository [here](https://github.com/EntryPointDailies/wiki/fork). Clone all branches.
3. Go to your repository settings, visit the `Pages` tab and select deploy from a branch, then choose to deploy from the `site` branch.
4. Navigate to /docs and edit the corresponding file.
5. Commit your changes to your repository.
6. Create a pull request with your changes
# On your machine with Git
This method is more technically-involved, but will allow for easier editing. Prior knowledge to using Git and Python will be helpful.
## Dependencies
[Python](https://www.python.org/downloads/) and [Git](https://git-scm.com/downloads) must be installed for this.

[GitHub Desktop](https://desktop.github.com/download/) should also be installed.

Additional Python packages must also be installed:

1. mkdocs
2. mkdocs-material
3. markdown
4. pygments
5. pymdown-extensions

To install these, open your terminal and run:

`pip install pip && pip install mkdocs-material`
## Running MkDocs
1. Open GitHub Desktop and clone your repository.
2. Ensure that the `wiki` branch is selected.
3. Open terminal (or an equivalent), then navigate to the cloned directory and run `mkdocs serve` within the shell.
4. Open the webpage shown within the shell.
5. Edit freely in the `/docs` directory. The webpage should update every time a file is saved.
6. Once complete, commit and push your changes.
7. Create a pull request with your changes.

Note: for those familiar with Git, feel free to commit and push from the command line.

# Resources
https://squidfunk.github.io/mkdocs-material/

https://stackedit.io/

https://www.mkdocs.org/