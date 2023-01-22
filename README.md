# python-web-dash-mvc-cockroachdb-single-node-without-ssl-simple

## Description
Simple web app that serves for a dash project.

Uses sqlalchemy query a table `dog`.

## Tech stack
- python
  - dash
  - sqlalchemy
  - pandas
- cockroachdb

## Docker stack
- python:latest
- cockroachdb/cockroach:v19.2.4

## To run
`sudo ./install.sh -u`
- [web app](http://localhost)
- [Master node webui](http://localhost:8000)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
