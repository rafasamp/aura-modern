# Aura Modern Pelican Theme

Aura Modern is a Pelican theme built from the ground up using Bootstrap 5. You can check out a live example at [rafaelsampaio.net](https://www.rafaelsampaio.net/).

## Focus

- Minimal design
- Cross device compatibility
- Clean and focused presentation
- Built on modern web technologies

## Features

- Built from scratch using Bootstrap 5
- Integrated comments with Disqus and analytics via Google Analytics
- Social media buttons
- Easy to customize (feel free to fork!)

## Missing Features
Check out the [TODO](TODO) file for a list of things I am planning on supporting or adding to the theme.

## Screenshots

Coming soon

## How To Use

Coming soon

```python
### Theme Settings ###
THEME = 'themes/aura-modern'
FAVICON = 'favicon.png'
LOGO = 'logo.png'

### About You ###
GRAVATAR = 'https://secure.gravatar.com/avatar/#'
ABOUT = 'This is a small snippet about yourself that will show on the front page.'

### Links ###
LINKS = (('Pelican', 'https://getpelican.com'),
         ('Aura Modern', 'https://github.com/rafasamp/aura-modern'))

### Social Networks ###
SOCIAL = (('facebook', 'https://www.facebook.com/#'),
          ('twitter', 'http://twitter.com/#'),
          ('instagram', 'http://instagram.com/#'),
          ('linkedin', 'http://linkedin.com/#'),
          ('github', 'http://github.com/#'))

### Google Analytics and Disqus ###
DISQUS_SITENAME = ''
GOOGLE_ANALYTICS = ''

### Archives ###
YEAR_ARCHIVE_SAVE_AS = 'posts/{date:%Y}/index.html'
MONTH_ARCHIVE_SAVE_AS = 'posts/{date:%Y}/{date:%b}/index.html'
```

## Notes

- Syntax highlighting is fully supported using highlight.js, however, the default Pelican library does not embed code in <pre> or <code> tags, therefore, you must do it yourself on your posts for it to work. This is not a problem on my site since [all my postings are on html format which is fully supported by Pelican](https://docs.getpelican.com/en/latest/content.html#file-metadata).

## License

[GNU GPLv3](LICENSE)
