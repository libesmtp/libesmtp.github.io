# libESMTP Website

## API Reference

Note that the API reference is maintained as part of libESMTP and may be built
independently of this site, which may be what you actually want.

## Build

To build the website you will need [Sphinx](https://www.sphinx-doc.org/)
and the Sphinx __readthedocs__ theme.

The API reference should be built first, so that documentation comments are
extracted from the source files.  Create a symlink to `source/reference` from
the `docs` directory in the libESMTP distribution. Then use `sphinx-build` to
create the site. For example:

``` sh
$ ln -s /path/to/libESMTP/docs source/reference
$ sphinx-build source site-dir
```
