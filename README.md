# Translation Converter (tx)

This tool provides a number of RESTful services for
processing and publishing translations on the [Door43 Content Service](https://git.door43.org).

# Development

All of the development commands have been place in a make file for easy use.

* `make` or `make doc` generate the documentation.
* `make dependencies` install the dependencies.
* `make test` run the tests.
* `make run` starts the development server.

## Contributing

When contributing please follow these practices:

* place new services within a new file under `./src/services/`.
* register your services in `./src/main.py` within the `register_services` function.
* add tests for your services in `./tests`.

# Documentation

All methods and modules **must** be documented with reStructured text.
These doc strings will be used to generate the documentation files.