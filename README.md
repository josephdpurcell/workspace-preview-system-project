# Workspace Preview System

This is a distro that shows the use of the [Workspace Preview System](https://www.drupal.org/node/2675680) in Drupal 8.2.

# Requirements

1. [Composer](https://getcomposer.org/)

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
