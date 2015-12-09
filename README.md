# Jekyll Content Modeling Example

A example built with Jekyll for rapidly prototyping a content model for a new website. Isn't an actual clickable site way better than a bunch of PDFs?

## Installing Jekyll

Depending on how your machine permissions are set, you might be able to get away with just this:
```shell
gem install jekyll
```

But if you get a warning about not having the right permissions, try this instead:
```shell
sudo gem install jekyll
```

## Starting the Jekyll server and rebuilding files

```shell
cd ~/path/to/repo
jekyll serve
```

This will run a server for the project that can be accessed at [http://localhost:4000](http://localhost:4000). Changes to files will tell Jekyll to automatically rebuild the site.

Sometimes when you change the _config.yml file you'll need to stop the server, delete the _site folder, and restart the server to get changes to populate. You'll know if you need to do this because instead of a page you'll get nothing in a render.