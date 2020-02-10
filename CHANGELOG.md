# Changelog
All notable changes to this project are documented in this file.

## [Unreleased]
### Changed
-  `api/v1/render` api
   *  param changes: json to context
   *  render by specific Jinja2 template engine rather than generic django renderer
   *  pass handler as param to use required handler, use jinja2 as default handler
-  Frontend: minor css changes, removed unwanted code

## [0.1.1](https://github.com/wilspi/django-template-editor/releases/tag/v0.1.1) - 2020-02-08
### Added
-  Reusable django application: `django-template-editor`.
-  Pure API that returns rendered template given template and context data.
-  UI: Template and json web editors, and text view for rendered template.

This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


