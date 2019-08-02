<p align="center">
    <h2 align="center">Welcome to my blog!</h2>
</p>

---

## Setup

0. :star: to the project. :metal:
1. Fork the project [Indigo](https://github.com/sergiokopplin/indigo/fork)
1. Edit `_config.yml` with your data (check <a href="README.md#settings">settings</a> section)
1. Write some posts :bowtie:

If you want to test locally on your machine, do the following steps also:

1. Install [Jekyll](http://jekyllrb.com), [NodeJS](https://nodejs.org/) and [Bundler](http://bundler.io/).
2. Clone the forked repo on your machine
3. Enter the cloned folder via terminal and run `bundle install`
4. Then run `bundle exec jekyll serve --config _config.yml,_config-dev.yml`
5. Open it in your browser: `http://localhost:4000`
6. Test your app with `bundle exec htmlproofer ./_site`

## Settings

You must fill some informations on `_config.yml` to customize your site.

```
name: John Doe
bio: 'A Man who travels the world eating noodles'
picture: 'assets/images/profile.jpg'
...

and lot of other options, like width, projects, pages, read-time, tags, related posts, animations, multiple-authors, etc.
```

## How To?

Check the [FAQ](./FAQ.md) if you have any doubt or problem.

---

[MIT](http://kopplin.mit-license.org/) License © Sérgio Kopplin
