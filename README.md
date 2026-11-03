# Jaxen Wood's website

A personal homepage built with Jekyll and hosted on GitHub Pages at [jaxenwood.com](https://jaxenwood.com).

## Preview locally

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

Open <http://localhost:4000>. To build without running a server:

```sh
bundle exec jekyll build
```

## Update the homepage

- `_data/projects.yml`: project titles, descriptions, links, image paths, and image dimensions. `featured` is the large lead project, `selected` contains the supporting cards, and `earlier` contains the additional image cards. Use `image_fit: contain` to show an entire portrait image without cropping it.
- `imgs/`: locally hosted project previews. Keep map attribution visible when replacing screenshots.
- `index.html`: project sections and about copy.
- `_layouts/home.html`: homepage navigation, metadata, and footer.
- `assets/css/home.css`: homepage colours, typography, and responsive layout.

`pendulums.md` uses the shared homepage layout and styles. The privacy statement is a Markdown page rendered with the Cayman theme.
