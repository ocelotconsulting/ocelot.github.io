# Website Redesign

## Development Setup

1. Install [Ruby][ruby].

    ```
    brew install ruby
    ```

2. Ruby installations are not symlinked to `/usr/local` because macOS already provides a (much older) ruby installation. You have to update your `$PATH` to put the Homebrew Ruby installation ahead of the default macOS installation.

    ```
    export PATH="/usr/local/opt/ruby/bin:$PATH"
    ```

3. Install the dependencies. The [`github-pages`][ghp] gem is a wrapper around all of the [gems made available to GitHub Pages][ghp-gems].

    ```
    bundle install
    ```

4. Build the site and watch for changes. Using `bundle exec <cmd>` here ensures that you're using the `jekyll` version specified by `github-pages`.

    ```
    bundle exec jenkins serve
    ```


[ruby]: https://www.ruby-lang.org/en/
[ghp]: https://rubygems.org/gems/github-pages
[ghp-gems]: https://pages.github.com/versions/
