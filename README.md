# Drupalville - A Docksal powered Drupal 9 With Composer Project

This project contain my learning journey code for Drupalville project based on OSTraining course. I started this project based on Drupal 9 with Composer installation pre-configured for use with Docksal.

## Setup instructions

### Step #1: Docksal environment setup

**This is a one time setup - skip this if you already have a working Docksal environment.**

Follow [Docksal environment setup instructions](https://docs.docksal.io/getting-started/setup/)

### Step #2: Project setup

1. Clone this repo into your Projects directory

    ```
    git clone https://github.com/saqibsarwar/drupalville.git
    cd drupalville
    ```

2. Initialize the site

    This will initialize local settings and install the site via drush

    ```
    fin init
    ```
   A `composer.lock` file will be generated. This file should be committed to your repository.

3. Point your browser to

    ```
    http://drupalville.docksal
    ```

When the automated installation is complete the command line output will display the admin username and password.

Test changes while using github.dev.