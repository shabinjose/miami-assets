# miami-assets

This folder contains sp attributes as assets. It does not get deployed in the war.
It is not dynamically generated, neither it should be. Ideally, this should still be tracked here, but a "deployment"
will copy contents to S3 or a hosted web server.

Important
=========
* The links in all metadata (json) files must be fully qualified, from https://
* The links must be accessible, without any credentials (publicly), from all miami hosts
