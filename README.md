# Resume

My resume

## Running on local machine

Follow the [official documentation](https://jekyllrb.com/docs/step-by-step/01-setup) to install Jeykll

* Install required ruby gems

```bash
bundle install
```

* Serve the site locally

```bash
bundle exec jekyll serve
```

* Navigate to `http://localhost:4000`


* Install test

```bash
gem install html-proofer
```

* Build site to test directory

```bash
bundle exec jekyll build -d _site_test
```

* Run HTML-Proofer

```bash
htmlproofer ./_site_test --disable-external --checks Html,Images,Links
```