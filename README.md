# landrop
Lando + Drop: Automate a Drupal download, install and launch by almost zero config

# Usage

```
landrop init govcms my-govcms

# modify the generated drop.yml to specify Drupal core version and distribution of choice

landrop launch
```
This will download, install and launch a GovCMS instance!

# Install
You need to have `lando` installed.
You need to have `drush` installed (@todo use the one provided with `lando` instead)

# Configuration
Modify `drop.yml` to specify Drupal core version and distribution of choice.
Look at `templates/govcms` for example.
