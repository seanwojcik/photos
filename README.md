# Photos (Google Photos Album Portal)

This is a mini project that displays Google Photos Albums, with links to them,
as Google Photos doesn't have a profile with public albums per se.

This web interface will leverage the Jekyll templating paradigm and the
bootstrap framework.

An example of the UI can be seen here: [http://kevinhira.com/photos](http://kevinhira.com/photos)

# Usage

## Prerequisites:
[Jekyll](http://jekyllrb.com)

## Setting Up Your Environment
1. Clone the repository: `git clone https://github.com/kdhira/photos.git`
2. Move into your cloned repository `cd photos`
3. Edit `_data/albums.yml` and `_data/env.yml`
    - `albums.yml` contains the data for displaying the album cards, each card
      has a title, url, date, and cover_image
    - `env.yml` has all of the customisable variables for the UI itself. This is
      so that you don't have to edit the source code itself, (but there's
      nothing stopping you).

## Deploying your Photos UI
From within the root of the repository, run `jekyll serve`. You can also deploy it
to github pages. If you do, please fork the repository
