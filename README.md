## How to get the WRF code

Click below to download the code from the WRF site: 
[![Click here to download the most recent code from the WRF site](http://www2.mmm.ucar.edu/wrf/users/images/header.jpg)](http://www2.mmm.ucar.edu/wrf/users/downloads.html)

Or, you can click below to download the most recent code through Github: 

<a href="https://github.com/NCAR/WRF/releases/"><img src="https://assets-cdn.github.com/images/modules/logos_page/GitHub-Logo.png" alt="Click here to download the most recent code from Github"  height="50"/></a>

Users who are interested in contributing code may consider cloning the public repository, found at https://github.com/NCAR/WRF. See futher explanation [below](#Public-repository):

## What is WRF?

The Weather Research and Forecasting (WRF) Model is a next-generation mesoscale numerical weather prediction system designed for both atmospheric research and operational forecasting needs. It features two dynamical cores, a data assimilation system, and a software architecture facilitating parallel computation and system extensibility. You can find more information on [The WRF Users Page](http://www2.mmm.ucar.edu/wrf/users/), which includes extensive documentation on downloading, installing, and using the model.

## What is Git?

[Git](https://en.wikipedia.org/wiki/Git) is a [version control](https://en.wikipedia.org/wiki/Version_control) software which allows for development of software by large teams in a coordinated, organized way.

## What is Github?

[Github](https://en.wikipedia.org/wiki/Github) is a website for hosting Git repositories, as well as providing tools for developers to propose and introduce changes to software.

## Public repository
The WRF code has been hosted on Github in August 2016. For WRF Version 3.9, we are offering a "release repository" to the public. In contrast to previous releases [hosted on the WRF Users page](http://www2.mmm.ucar.edu/wrf/users/downloads.html), which simply offer a .tar file with the relevant code, you now have the choice of [downloading the WRF code through Github](https://github.com/NCAR/WRF/releases) or cloning [the release repository](https://github.com/NCAR/WRF/). Cloning the repository has the added benefit of including the full history of each change to the code, which can be accessed using [the appropriate git commands](https://git-scm.com/book/en/v2/Git-Basics-Viewing-the-Commit-History), or through [https://github.com/NCAR/WRF/commits/master](this web page).

If you do clone the release repository, you will see that the master branch of the public repository only contains history going back to August 2016, when the WRF code was moved from Subversion to Git. However, if you are interested in seeing earlier history, you can issue the command `git log old-history` to see older logs, which are contained on the "old-history" branch. This older history [can also be accessed on the web](https://github.com/NCAR/WRF/commits/old-history). The "old-history" branch should not be used directly, as it will likely not compile properly!

## Development repository
The main development repository is not publicly available, since it is often in a state of flux that should not be used for scientific experiments, and it is often not fully tested until the preparation for public releases. If you have made changes to the code that you wish to contribute (or are planning to do so in the future), contact kavulich@ucar.edu or wrfhelp@ucar.edu to request access to the Developer Repository.

<!--## Customizing

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

The theme contains a minimal test suite, to ensure a site with the theme would build successfully. To run the tests, simply run `script/cibuild`. You'll need to run `script/bootstrap` one before the test script will work.-->
