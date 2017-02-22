# This is the new experimental public release page for the Weather Research and Forecasting (WRF) Model

Click here to download the code from the WRF site
[![Click here to download the most recent code from the WRF site](http://www2.mmm.ucar.edu/wrf/users/images/header.jpg)](http://www2.mmm.ucar.edu/wrf/users/downloads.html)

Or, you can click here to download the most recent code through Github
[![Click here to download the most recent code from Github](http://www.aha.io/assets/integration_logos/github-bb449e0ffbacbcb7f9c703db85b1cf0b.png)](https://github.com/NCAR/WRF/releases/tag/V3.8.1)

Users who are interested in contributing code may consider cloning the public repository, found at https://github.com/NCAR/WRF. See futher explanation [here](#Public-repository)

## What is WRF?

The Weather Research and Forecasting (WRF) Model is a next-generation mesoscale numerical weather prediction system designed for both atmospheric research and operational forecasting needs. It features two dynamical cores, a data assimilation system, and a software architecture facilitating parallel computation and system extensibility.

## What is Github?
We can include whatever type of explanation we want here!

## Public repository
We can include whatever explanation we think is appropriate here!

## Customizing

### Configuration variables

Architect will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
show_downloads: ["true" or "false" to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]
```

### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:
    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

### Layouts

If you'd like to change the theme's HTML layout:

1. [Copy the original template](https://github.com/pages-themes/architect/blob/master/_layouts/default.html) from the theme's repository<br />(*Pro-tip: click "raw" to make copying easier*)
2. Create a file called `/_layouts/default.html` in your site
3. Paste the default layout content copied in the first step
4. Customize the layout as you'd like

### Previewing the theme locally

If you'd like to preview the theme locally (for example, in the process of proposing a change):

1. Clone down the theme's repository (`git clone https://github.com/pages-themes/architect`)
2. `cd` into the theme's directory
3. Run `script/bootstrap` to install the necessary dependencies
4. Run `bundle exec jekyll serve` to start the preview server
5. Visit [`localhost:4000`](http://localhost:4000) in your browser to preview the theme

### Running tests

The theme contains a minimal test suite, to ensure a site with the theme would build successfully. To run the tests, simply run `script/cibuild`. You'll need to run `script/bootstrap` one before the test script will work.
