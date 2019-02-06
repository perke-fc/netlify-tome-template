[![Netlify Status](https://api.netlify.com/api/v1/badges/e2eae7df-eddb-4d18-afaa-39c08c24b969/deploy-status)](https://app.netlify.com/sites/fc-tome/deploys)



[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/drupal-tome/netlify-template)

# Netlify template for Tome projects

This project is a great place to start for building new Tome projects on Netlify.

To get started, click the "Deploy to netlify" button above and deploy a copy of
this template to Netlify. 

# Requirements

- PHP 7+
- [Composer](https://getcomposer.org/)
- [Drush](https://github.com/drush-ops/drush-launcher#installation---phar)
- SQLite and the related PHP extensions

# Local usage

To install Tome locally, run:

```bash
drush tome:install
```

To start a local webserver, run:

```bash
drush runserver
```

When you're ready to build your static site, run:

```bash
drush tome:static
```

## Further reading

This template is largely based on [drupal-composer/drupal-project], so it's
recommended that you consult their [README.md] for more information.

[drupal-composer/drupal-project]: https://github.com/drupal-composer/drupal-project
[README.md]: https://github.com/drupal-composer/drupal-project/blob/8.x/README.md
