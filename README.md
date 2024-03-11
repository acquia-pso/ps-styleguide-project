PS Style Guide
====

This is an PS Style Guide module providing [PS Style Guide](https://sitestudiodocs.acquia.com/7.4/user-guide/using-style-guides) UI Kit component that is completely based on Style Guide.

This module automates the necessary of changing components, custom styles based on user design's colors and typography. By introducing Site Studio Style Guide. All the components, custom styles colors and typography would be based on Site studio Style Guide.

## Installation

To use this module, you must already have a Drupal 10 project or later, and Acquia Site Studio 7.4.0 or later.

The `1.x` branch supports Site Studio 7.4.0 and above.

Add the following to the `repositories` section of your project's composer.json:

```
"ps-style-guide": {
    "type": "vcs",
    "url": "https://github.com/acquia-pso/ps-styleguide-project.git",
    "no-api": true
}
```

or run:

```
composer config repositories.ps-style-guide '{"type": "vcs", "url": "https://github.com/acquia-pso/ps-styleguide-project.git", "no-api": true}'
```

Require the plugin with Composer:

`composer require drupal/ps_styleguide:dev-main`

## Usage

This module will provide packages that will create Site Studio Style Guide based on UI Kit components.