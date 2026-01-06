# Example Drupal Recipe

This is an example recipe used as part of a series of tutorials on creating, and managing, Drupal recipes. It is not intended to be complete, or useful, for real world purposes. Which is to say, you probably only need this if you're following along with the tutorials.

## What it contains

Adds a Blog content type (blog) with Body and Tags, and grants permissions to the content_editor role.

## Apply
From your webroot:

Drush (requires Drush 13):

```sh
drush recipe ../recipes/dme_example_recipe
```

Or ...:

```sh
php core/scripts/drupal recipe ../recipes/dme_example_recipe -v
```
