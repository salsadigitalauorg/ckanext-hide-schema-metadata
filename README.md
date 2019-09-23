# ckanext-hide-metadata-schema

A simple example extension to hide the schema validation 
fields on the resource detail view if no validation schema is
added to the resource.

## Installation

Clone repo into the `/usr/lib/ckan/default/src` directory, then:

    cd ckanext-hide-schema-metadata

    python setup.py develop

## Configuration

Enable extension in CKAN `.ini` file, e.g.

    ckan.plugins = ... hide_metadata_schema

Restart Apache, Nginx, etc.
    