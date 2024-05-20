---
title: Overview
description: Here you can learn how to navigate around the Dashboard
---
# Navigating around the Dashboard

{: .fs-9 }

sdiuyg haiusyg duiaysg iusyd g {: .fs-6 .fw-300 }

[Get started now](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View it on GitHub](https://github.com/just-the-docs/just-the-docs){: .btn .fs-5 .mb-4 .mb-md-0 }

* * *

{: .warning }

> This website documents the features of the current `main` branch of the Just the Docs theme. See \[the CHANGELOG\]({% link CHANGELOG.md %}) for a list of releases, new features, and bug fixes.

!\[Media\](/docs/media/image1.png)

Just the Docs is a theme for generating static websites with [Jekyll](https://jekyllrb.com). You can write source files for your web pages using [Markdown](https://daringfireball.net/projects/markdown/), the [Liquid](https://github.com/Shopify/liquid/wiki) templating language, and HTML.\[^1\] Jekyll builds your site by converting all files that have [front matter](https://jekyllrb.com/docs/front-matter/) to HTML. Your [Jekyll configuration](https://jekyllrb.com/docs/configuration/) file determines which theme to use, and sets general parameters for your site, such as the URL of its home page.

Jekyll builds this Just the Docs theme docs website using the theme itself. These web pages show how your web pages will look _by default_ when you use this theme. But you can easily _\[customize\]_ the theme to make them look completely different!

Browse the docs to learn more about how to use this theme.

## Getting started

The [Just the Docs Template](https://just-the-docs.github.io/just-the-docs-template/) provides the simplest, quickest, and easiest way to create a new website that uses the Just the Docs theme. To get started with creating a site, just click "\[use the template\]"!

{: .note } To use the theme, you do **_not_** need to clone or fork the [Just the Docs repo](https://github.com/just-the-docs/just-the-docs)! You should do that only if you intend to browse the theme docs locally, contribute to the development of the theme, or develop a new theme based on Just the Docs.

You can easily set the site created by the template to be published on [GitHub Pages](https://pages.github.com/) – the [template README](https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md) file explains how to do that, along with other details.

If [Jekyll](https://jekyllrb.com) is installed on your computer, you can also build and preview the created site _locally_. This lets you test changes before committing them, and avoids waiting for GitHub Pages.\[^2\] And you will be able to deploy your local build to a different platform than GitHub Pages.

More specifically, the created site:

*   uses a gem-based approach, i.e. uses a `Gemfile` and loads the `just-the-docs` gem
    
*   uses the [GitHub Pages / Actions workflow](https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/) to build and publish the site on GitHub Pages
    

Other than that, you're free to customize sites that you create with the template, however you like. You can easily change the versions of `just-the-docs` and Jekyll it uses, as well as adding further plugins.

{: .note } See the theme [README](https://github.com/just-the-docs/just-the-docs/blob/main/README.md) for how to use the theme as a gem without creating a new site.

## About the project

Just the Docs is © 2017-{{ "now" | date: "%Y" }} by [Patrick Marsceill](https://patrickmarsceill.com).

### License

Just the Docs is distributed by an [MIT license](https://github.com/just-the-docs/just-the-docs/tree/main/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/just-the-docs/just-the-docs#contributing).

#### Thank you to the contributors of Just the Docs!

*   {% for contributor in site.github.contributors %}
    
*   \[<img src="{{ contributor.avatar_url }}" alt="{{ contributor.login }}" width="32" height="32">\]({{ contributor.html\_url }})
    
*   {% endfor %}
    

### Code of Conduct

Just the Docs is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/just-the-docs/just-the-docs/tree/main/CODE_OF_CONDUCT.md) on our GitHub repository.

* * *

\[^1\]: The [source file for this page](https://github.com/just-the-docs/just-the-docs/blob/main/index.md) uses all three markup languages.

\[^2\]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).

\[customize\]: {% link docs/customization.md %} \[use the template\]: [https://github.com/just-the-docs/just-the-docs-template/generate](https://github.com/just-the-docs/just-the-docs-template/generate)