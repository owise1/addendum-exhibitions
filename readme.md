# addedum-exhibitions

The central registry for [addendum](http://addendum.kadist.org) exhibitions.

## Exhibitions

1. How long can we tolerate this? by Leah Modigliani 
2. Fond, objet et ombre portée by Victor Costales & Julia Rometti

### config

Most fields are self-explanatory. A `work` needs an `image` attribute, but can optionally take a `title` and `link`

If the `work.link` attribute is an array (rather than a string) a random item will be selected from the array
