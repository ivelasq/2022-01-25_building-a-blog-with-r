# 2022-01-25 Building a Blog With R
R Enterprise Community Meetup on Building a Blog With R

## Today's Presentation

* [Slides](https://colorado.rstudio.com/rsc/building-a-blog-with-r/)

## [YouTube Playlist](https://youtube.com/playlist?list=PLXKlQEvIRus-qu1hjc8SyElSamAcT-KaE)

## Distill Resources

* [Distill for R Markdown](https://rstudio.github.io/distill/)
* [Building a blog with distill by Tom Mock](https://themockup.blog/posts/2020-08-01-building-a-blog-with-distill/)
* [(Re-)introducing Distill for R Markdown](https://www.rstudio.com/blog/distill/)
* [The distillery](https://distillery.rbind.io/)
* [Postcards package](https://github.com/seankross/postcards)

### Getting Started

```
# Install packages
install.packages("distill”)

# Create a new site
library(distill)
create_blog(dir = "my-blog", title = "My Blog")
```

## Blogdown Resources

* [blogdown: Creating Websites with R Markdown](https://bookdown.org/yihui/blogdown/)
* [Hugo Themes](https://themes.gohugo.io/)
* [Hugo Apéro](https://hugo-apero-docs.netlify.app/)
* [A Blogdown New Post Workflow with Github and Netlify](https://www.garrickadenbuie.com/blog/blogdown-netlify-new-post-workflow/)

### Getting Started

```
# Install packages
install.packages("blogdown")
blogdown::install.hugo(version = "0.79.1")

# Create a new site
library(blogdown)
new_site(theme = "hugo-apero/hugo-apero", 
           format = "toml",
           sample = FALSE,
           empty_dirs = TRUE)
```
