Acquia CMS Styleguide
====

This is an Acquia CMS Styleguide module providing [Acquia CMS Styleguide](https://www.acquia.com/products-services/acquia-cohesion) UI Kit componenent that is completely based on Styleguide.

This module automates the necessary of changing components, custom styles based on user design's colors and typography. By introducing Site Studio Styleguide. All the components, custom styles colors and typography would be based on Site studio Styleguide.

## Installation

To use this module, you must already have a Drupal 10 project or later, and Acquia Site Studio 7.4.0 or later.

The `1.x` branch supports Site Studio 7.4.0 and above.

Add the following to the `repositories` section of your project's composer.json:

```
"acquia-cms-styleguide": {
    "type": "vcs",
    "url": "https://github.com/acquia-pso/ps-styleguide-project.git",
    "no-api": true
}
```

or run:

```
composer config repositories.acquia-cms-styleguide '{"type": "vcs", "url": "https://github.com/acquia-pso/ps-styleguide-project.git", "no-api": true}'
```

Require the plugin with Composer:

`composer require drupal/acquia_cms_styleguide:dev-main`

## Usage

This module will provide packages that will create Site Studio Styleguide.