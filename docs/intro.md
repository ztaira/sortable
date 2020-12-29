## Sortable

Sortable is an open-source JavaScript and CSS library which adds sorting
functionality to tables. It is tiny (<code>&lt;2kb</code> min+gzip) and has no
dependencies.

#### Features

- Drop-in script
- Tiny footprint (<code>&lt;2kb</code> min+gzip) and no dependencies

#### Requirements

- None

#### Browser Support

- IE8+
- Firefox 4+
- Current WebKit (Chrome, Safari)
- Opera

#### Manually Including

For the most common usage of sortable, you’ll want to include following:

```html
<script src="sortable.js"></script>
```

Now all tables that exist at the time of script import will be made sortable.
They'll also have a class you can use for styling if you load the right CSS
files.

All your tables will be transformed into something like this:

```html
<table class="sortable-theme-light" data-sortable>
    <!-- ... -->
</table>
```

#### Why did you remove all the coffeescript/themes/etc from Hubspot?

My main use case at the moment is vendorizing this wholesale and dropping it
into a static site. Those things would have required a lot of overhead for
relatively little gain.

I might add them back piecemeal as they become necessary.

#### Credits

Sortable is free and open-source, released on the [MIT License](https://github.com/HubSpot/sortable/blob/master/LICENSE).

Sortable was built by [Adam Schwartz](http://twitter.com/adamfschwartz)
