# Guides Demo

Trying to demo the functionality of the guides gem.
Currently this is a very simple demo.

## Running Guide

The wonderful people at strobe have created
a pkg to install guides on your mac.

http://guides-pkg.strobeapp.com/Guides.pkg

If you have ruby 1.9.2 (not default on OSX)
you can simply install the guides gem.
Ruby 1.8 does not seem to work for me.

Then run the below in your terminal.

```bash
guides preview
```

## Adding new items to the guide.

Adding items to the guide is *REALLY* easy.  
Look in guides.yml for an example of how
to add an item to the guide index.  
Then add a your_new_guide.textile to
the source source/ directory. See source/getting_started.textile for an
example.


