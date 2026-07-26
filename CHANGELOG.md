# Changelog

All notable changes to the Akismet API spec are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.1]

### Fixed

- Corrected the `/1.2/key-sites` examples to match live backend responses: the `month` key now contains an array of site objects, per-site statistics are represented as quoted strings, and the CSV example header was updated to match backend output. ([#3](https://github.com/Automattic/akismet-api/pull/3))

## [1.0.0]

- Initial release of the Akismet API spec.
