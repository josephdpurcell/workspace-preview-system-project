# Workspace Preview System

This is a distro that shows the use of the [Workspace Preview System](https://www.drupal.org/node/2675680).

# Requirements

1. Composer

# Getting Started

1. Create a Drupal.

    ```
    $ composer create-project josephdpurcell/workspace_preview_system-project MY_PROJECT --no-interaction --stability dev
    ```

    This will create a directory `MY_PROJECT`. Inside of it will be a directory `web` which is the website's docroot.

2. Install the Drupal.

    ```
    drush si
    ```

    or

    go to `/install.php`.

# TODO

- [ ] Install a theme on install.
- [ ] Setup a content type as moderated on install.
- [ ] Create example content on install?
