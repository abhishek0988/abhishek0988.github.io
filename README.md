# aagrawal.me

This is the source code behind [aagrawal.me][], the personal website of Abhishek Agrawal.

[aagrawal.me]: http://aagrawal.me

The website is powered entirely by [Jekyll][], which uses [Markdown][] and
[Liquid][] for markup, and is hosted and served by [GitHub Pages][].

[Jekyll]: http://jekyllrb.com/
[Markdown]: http://daringfireball.net/projects/markdown/
[Liquid]: http://www.liquidmarkup.org/
[GitHub Pages]: http://pages.github.com/

## Development

1) Install Jekyll using Bundler. See instructions [here](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/#step-2-install-jekyll-using-bundler).

2) In the root directory, run the following to run the Jekyll server and have it watch for changes.

    $ bundle exec jekyll serve

3) In the source branch, run the following to publish the generated site to the master branch.

    $ rake publish