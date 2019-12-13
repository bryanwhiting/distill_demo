# distill_demo
A quick demo on how to set up distill. Check out the site here: https://bryanwhiting.github.io/distill_demo/



[Following these instructions](https://rstudio.github.io/distill/website.html#getting-started):

1. Run `distill::create_website(dir='.', title='My Distill Demo')`
1. Add the following to `_site.yml::
  ```
  output_dir: "docs"
  base_url: bryanwhiting.github.io/distill_demo/
  output: 
    distill::distill_article:
      toc: true
  ``` 
1. Run `rmarkdown::render_site()`
1. git commit, git push
1. Set up GitHub pages. In GitHub: Settings > Options > GitHub Pages > Source > Master branch docs folder