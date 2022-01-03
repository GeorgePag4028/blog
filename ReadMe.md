<h1>Simple blog with jekyll</h1>



<h3>Change this to have a working project<!h3>
```
    gem install jekyll bundler
    jekyll new blog
    cd myblog
    bundle exec jekyll serve --livereload
```
in _config.yml change baseurl= "/blog"
bundle add webrick
change in Gemfile.lock the dependecny from liquid (5.1.0) to liquid (4.0.3)
