# Beautiful Jekyll

## Local install

```sh
brew install ruby # install ruby https://jekyllrb.com/docs/installation/macos/
echo 'export PATH="/opt/homebrew/opt/ruby/bin:$PATH"' >> ~/.zshrc 
gem install jekyll bundler # install needed packages using gem, the ruby package manager 
gem env # consult current ruby env
bundle install # install gems from gemfile.lock
```

```sh
bundle exec jekyll serve # launch the webserver in local
```

## CICD Set up

Be sure to activate the option [Publishing with a custom GitHub Actions workflow](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-with-a-custom-github-actions-workflow) and not the default CICD for Pages. Otherwise two different workflows would be launched 


## Credits

Taken from https://github.com/daattali/beautiful-jekyll/. 
Details can be consulted here for [parameter customization](https://github.com/daattali/beautiful-jekyll/blob/master/README.md#customizing-parameters-for-each-page)
