# Auto-convert Jupyter Notebooks To Posts

[`fastpages`](https://github.com/fastai/fastpages) will automatically convert [Jupyter](https://jupyter.org/) Notebooks saved into this directory as blog posts!

You must save your notebook with the naming convention `YYYY-MM-DD-*.ipynb`.  Examples of valid filenames are:

```shell
2020-01-28-My-First-Post.ipynb
2012-09-12-how-to-write-a-blog.ipynb
```

```
# Title
> summary

- toc: true 
- badges: true
- hide_binder_badge: true
- comments: true
- categories: [Network Analysis, Intellectual property, Patent data]
- image: image/trading.jfif
```


If you fail to name your file correctly, `fastpages` will automatically attempt to fix the problem by prepending the last modified date of your notebook. However, it is recommended that you name your files properly yourself for more transparency.

See [Writing Blog Posts With Jupyter](https://github.com/fastai/fastpages#writing-blog-posts-with-jupyter) for more details.
