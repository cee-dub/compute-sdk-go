## Unreleased

## 0.1.3 (2023-05-15)

### Changed

- Rename objectstore -> kvstore
- Deprecate fstctx

### Added

- Add fsthttp.RequestLimits

## 0.1.2 (2023-01-30)

### Changed

- Renamed edgedict -> configstore.
- Made HTTP Request/Response field size limit configurable

### Added

- Add support for Object Store API
- Add support for Secret Store API
- Add adaptor for net/http.RoundTripper (for net/http.Client support)
- Add adaptor for net/http.Handler
- Add fsthttp.Error() and fsthttp.NotFound() helpers

--
## 0.1.1 (2022-06-14)

### Changed

- Use Go 1.17

--
## 0.1.0 (2022-06-11)

### Added

- Initial Release
