# blogsa - template and demo project

You can use this repo as a template to build your own blog with your current repository.

It is so simple to install. 

We have made a deployment file to test your own blog on Heroku! It is easy. Just click "Deploy to Heroku" button.

<a href="https://heroku.com/deploy?template=https://github.com/se/heroku-core-test/tree/master">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>


If you want to implement this to your git repo copy definition files to make your own settings.

config.json file will help us to read your git repo folders. (It means where is your blog posts, pages and pictures etc.)

*config.json file*
```
{
    "Title": "My Git Blog!",
    "Description": "This will help you to understand my blog!",
    "Keywords": "blogs, blogsa, blog, git blog",
    "Repository": {
        "PostsFolder": "posts",
        "PagesFolder": "pages",
        "PostsRoute": "post/{name}",
        "PagesRoute": "page/{name}"
    }
}
```