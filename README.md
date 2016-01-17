## Contributing

Pull Requests from our design, development and operations teams of [Haufe.Group](http://www.haufe-lexware.com) and its subsidiaries are greatly appreciated. If you've never contributed to an open source project before we are more than happy to walk you through how to create a pull request.

The short version of it is to simply clone this repo (a) into a repo of your own account with (b) the name `[your_account_name].github.io` and (c) manually change the `url` parameter in `_config.xml` to `http://[your_account_name].github.io`. Commit your changes and a couple of seconds later you should find the blog published on the above configured url. Now you can add your changes and test them live after each commit. **Please do not submit your _config.yml file as part of the pull request.** 

Support for Categories and Tags were inspired by [this blog entry](http://www.minddust.com/post/tags-and-categories-on-github-pages/). A list of the defined categories and tags can be found at `_data/categories.yml` and `_data\tags.yml` respectively. If you want to add new categories or tags, you need to add them to the corresponding `.yml` file and add the matching template into the `meta/category` or `meta/tag` directories. Please do not go overboard with adding new categories and tags but try to stay within the ones we have. On the other hand - if you feel strongly about adding one, feel free to submit a pull request.

If you want to find out more about using `github-pages` for blogging or want to improve our blog the following links might be good starting points
* [Jekyll documentation, i.e. how to include images](http://jekyllrb.com/docs/posts/)
* [Github pages powered by Jekyll](https://github.com/jekyll/jekyll/wiki/sites)

Please note to set the proxy if you are working from within the Haufe Intranet

    set HTTP_PROXY=http://10.12.1.236:8083/
    set HTTPS_PROXY=http://10.12.1.236:8083/

If you find bugs or issues you can [open an issue](https://github.com/Haufe-Lexware/Haufe-Lexware.github.io/issues/new) describing the problem that you're looking to resolve and we'll go from there.

