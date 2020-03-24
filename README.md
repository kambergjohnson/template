# Katie's Portfolio

This repo contains a professional portfolio based on the [html5up miniport](https://html5up.net/miniport) theme, but converted to use Jekyll so that text can be written in markdown and the HTML/CSS can be (somewhat) modularized.

## Installation

To build this site locally, you must first install Jekyll by running the following command:

```
sudo gem install bundler jekyll
```

## Updating the site

After that, you can build your site by running the following command in the top-level directory:

```
$ bundle exec jekyll serve 2>/dev/null
````

Here's what the output should look like:

```
$ bundle exec jekyll serve 2>/dev/null
Configuration file: /Users/philipjohnson/github/kaj2/kaj2.github.io/_config.yml
            Source: /Users/philipjohnson/github/kaj2/kaj2.github.io
       Destination: /Users/philipjohnson/github/kaj2/kaj2.github.io/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
       Jekyll Feed: Generating feed for posts
                    done in 0.502 seconds.
 Auto-regeneration: enabled for '/Users/philipjohnson/github/kaj2/kaj2.github.io'
    Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop.
```

The site should now be available at http://localhost:4000.  Each time you edit the source files, the site should be regenerated. Just refresh the page in your browser to see the update.

If you are returned to the command line, then there was an error.  Re-run the command without the `serve 2>/dev/null` to see what went wrong.

## Structure

Here is a guide to the files in the site that you might want to edit:

 * index.html: The top-level file. It simply includes html files from the \_includes directory.
 * \_includes/: The directory containing code to render the sections of the home page.
 * images/: Location of images and screenshots.
 * resources/: Location of resume, papers not online elsewhere.


## Misc todo

  * Delete high school from LinkedIn. (Or not, if you want to maintain the local connection)
  * Update CV by pushing new version of resources/Amberg_Johnson_Katherine_CV.pdf


