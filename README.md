# Dabbling in Dogmas

## Local testing

Ensure Ruby is installed and then install Jekyll:

```sh
gem install jekyll bundler
```

Install the required Gem files using:

```sh
bundle install`
```

Then run the server using:

```sh
bundle exec jekyll serve
```

The server should then be available at [http://localhost:4000/](http://localhost:4000/).

## Audio File Data

Audio files should be uploaded to the podcast's [Internet Archive page](https://archive.org/details/dabbling-in-dogmas), and then a data file must be downloaded and saved to the `_data` directory from the following URL:

[https://archive.org/metadata/dabbling-in-dogma?output=json](https://archive.org/metadata/dabbling-in-dogma?output=json)

## Styling

The theme used by this website is a [Bootstrap 5](https://getbootstrap.com/docs/5.0/getting-started/introduction/) theme, so any Bootstrap 5 components can be used.
