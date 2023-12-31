# Personal web portfolio

## Quick Setup

1. Install [Jekyll](https://jekyllrb.com/): `gem install jekyll bundler`
2. Fork or clone this repository into your own project
3. Edit `_config.yml` to personalize your site

## Settings

You ought to fill in some information in `_config.yml` to customize your site:

### Site settings
```yml
description: A personal portfolio
baseurl: "" # the subpath of your site
url: "https://localhost:4080" # the base hostname & protocol for your site
```

### User settings
```yml
username: lorem_ipsum
user_description: Software Developer at Lorem Ipsum Dolor
user_title: Lorem Ipsum
```

> Don't forget to change the URL before you deploy your site!

## Color and Particle Customization

- Color Customization
  - Edit the file `assets/css/main.css`

- Particle Customization
  - Edit the json data in particle function in `assets/js/main.js`
  - Refer to [particles.js](https://vincentgarreau.com/particles.js/) for help

## Content

You can (and should) edit the `.html` files for adding your own information, icons, working experience, social links, etc.:

```html
<a aria-label="My Github" target="_blank" href="https://github.com/richim96">
  <i class="icon fa fa-github-alt" aria-hidden="true"></i>
</a>
```

## Running locally

Compile the assets and run `Jekyll` locally:

1. Run `bundle install`
2. Run `bundle exec jekyll build`

## Credits

- Original project developed by [Mauricio Urraco](https://github.com/murraco)
