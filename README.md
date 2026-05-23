# pidcapital

Investing in Perception, Intelligence, and Data

# build

```
docker run --rm -it \
  -v "$PWD:/srv/jekyll" \
  -w /srv/jekyll \
  -p 4000:4000 \
  ruby:3.1 \
  bash -lc "gem install bundler && bundle install && bundle exec jekyll serve --host 0.0.0.0 --port 4000"
```
