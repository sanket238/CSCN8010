Thie files in this folder demonstrates:
1. A conversion of a Jupyter notebook into a static HTML
2. Serving this HTML using Github Pages

## Convert the Notebook to an HTML file

1. `jupyter nbconvert --to html NOTEBOOK-PATH --output-dir ./docs/STUDENT-ID --TagRemovePreprocessor.enabled=True --TagRemovePreprocessor.remove_input_tags="['noshow']"` - converts the notebook into an HTML file. `NOTEBOOK-PATH` = the path of the notebook that you want to convert, for example: `./class_notebooks/github_pages/index.ipynb` `STUDENT-ID` should be your student ID, for example `123456`

## Serve the HTML through Github Pages
(reference: [official docs](https://docs.github.com/en/pages/quickstart). Jekyll built-in support: [official docs](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll))
1. Enable Github Pages through the repository settings. For this the repository will have to be public, or your user should be on the Pro program. 

![image](../../images/github_pages/enable_github_pages.jpg)

2. The public URL is: `GITHUB-USER-NAME.github.io/REPOSITORY-NAME/STUDENT-ID/NOTEBOOK-NAME.html`. For instance: https://conestoga-aaiml-2023-spring.github.io/CSCN8010/instructor/example.html