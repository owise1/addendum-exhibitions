# addedum-exhibitions

The central registry for [addendum](http://addendum.kadist.org) exhibitions.

## Exhibitions

1. How long can we tolerate this? by Leah Modigliani 
2. Fond, objet et ombre portée by Rometti Costales 
3. Espacio Escultórico by Pedro Reyes
4. Performing Animals Postcards by Dana Levy
5. What we think in America is not always clear by US ENGLISH
6. Whats the Quality of your Thought in this Moment? by Mads Lynnerup
7. WHILE TALKING ON THE PHONE by Hilla Toony Navok
8. PIECES OF PAPER by Micah Lexier
9. Because of Children on My Street by Jon Rubin
10. Las fotos de america by Enrique Ramírez

### config

Most fields are self-explanatory. A `work` needs an `image` attribute, but can optionally take a `title` and `link`

If the `work.link` attribute is an array (rather than a string) a random item will be selected from the array
