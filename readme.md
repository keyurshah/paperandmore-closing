how to run / build the project
1. install ruby https://rubyinstaller.org/downloads/, choose latest version 2.6
2. install jekyll
```shell
gem install jekyll bundler
```
3. go to the project, install all dependencies
```shell
bundle install
```
4. develop the project
```shell
bundle exec jekyll serve
# or
bundle exec jekyll serve --watch
```
5. build for production, or use github auto deployment feature
```shell
bundle exec jekyll build

```
