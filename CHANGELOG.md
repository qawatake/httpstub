# Changelog

## [v0.11.0](https://github.com/k1LoW/httpstub/compare/v0.10.0...v0.11.0) - 2023-06-01
- Add Router.URL for get *httptest.Server.URL by @k1LoW in https://github.com/k1LoW/httpstub/pull/27

## [v0.10.0](https://github.com/k1LoW/httpstub/compare/v0.9.2...v0.10.0) - 2023-04-14
- [BREAKING CHANGE] Fix path match logic by @k1LoW in https://github.com/k1LoW/httpstub/pull/23
- Support `text/*` response using `examples:` by @k1LoW in https://github.com/k1LoW/httpstub/pull/24

## [v0.9.2](https://github.com/k1LoW/httpstub/compare/v0.9.1...v0.9.2) - 2023-04-12
- Fix handling Content-Type header in ResponseExample by @k1LoW in https://github.com/k1LoW/httpstub/pull/21

## [v0.9.1](https://github.com/k1LoW/httpstub/compare/v0.9.0...v0.9.1) - 2023-04-12
- Skip scheme://host:port validation by @k1LoW in https://github.com/k1LoW/httpstub/pull/19

## [v0.9.0](https://github.com/k1LoW/httpstub/compare/v0.8.0...v0.9.0) - 2023-04-12
- Add Query() for query match by @k1LoW in https://github.com/k1LoW/httpstub/pull/16
- Support response using examples of OpenAPI v3 Document by @k1LoW in https://github.com/k1LoW/httpstub/pull/18

## [v0.8.0](https://github.com/k1LoW/httpstub/compare/v0.7.0...v0.8.0) - 2023-03-20
- Setup tagpr by @k1LoW in https://github.com/k1LoW/httpstub/pull/13
- Support request/response validation using OpenAPI Spec v3 by @k1LoW in https://github.com/k1LoW/httpstub/pull/15

## [v0.7.0](https://github.com/k1LoW/httpstub/compare/v0.6.0...v0.7.0) (2023-03-17)

* Add utility methods that embedds fmt.Sprintf [#12](https://github.com/k1LoW/httpstub/pull/12) ([k1LoW](https://github.com/k1LoW))

## [v0.6.0](https://github.com/k1LoW/httpstub/compare/v0.5.0...v0.6.0) (2023-03-01)

* Add ClearRequests() for clearing recieved requests [#11](https://github.com/k1LoW/httpstub/pull/11) ([k1LoW](https://github.com/k1LoW))

## [v0.5.0](https://github.com/k1LoW/httpstub/compare/v0.4.2...v0.5.0) (2023-02-03)

* Support Client Certificates [#10](https://github.com/k1LoW/httpstub/pull/10) ([k1LoW](https://github.com/k1LoW))

## [v0.4.2](https://github.com/k1LoW/httpstub/compare/v0.4.1...v0.4.2) (2023-02-02)

* Fix Server [#9](https://github.com/k1LoW/httpstub/pull/9) ([k1LoW](https://github.com/k1LoW))

## [v0.4.1](https://github.com/k1LoW/httpstub/compare/v0.4.0...v0.4.1) (2023-02-02)

* Fix option [#8](https://github.com/k1LoW/httpstub/pull/8) ([k1LoW](https://github.com/k1LoW))

## [v0.4.0](https://github.com/k1LoW/httpstub/compare/v0.3.2...v0.4.0) (2023-02-02)

* Add option `UseTLS` `UseTLSWithCertificates` [#7](https://github.com/k1LoW/httpstub/pull/7) ([k1LoW](https://github.com/k1LoW))
* Add NewTLSServer and *Router.TLSServer [#6](https://github.com/k1LoW/httpstub/pull/6) ([k1LoW](https://github.com/k1LoW))

## [v0.3.2](https://github.com/k1LoW/httpstub/compare/v0.3.1...v0.3.2) (2022-07-02)


## [v0.3.1](https://github.com/k1LoW/httpstub/compare/v0.3.0...v0.3.1) (2022-06-01)

* Fix race [#5](https://github.com/k1LoW/httpstub/pull/5) ([k1LoW](https://github.com/k1LoW))

## [v0.3.0](https://github.com/k1LoW/httpstub/compare/v0.2.0...v0.3.0) (2022-05-18)

* `router` to `Router` [#4](https://github.com/k1LoW/httpstub/pull/4) ([k1LoW](https://github.com/k1LoW))

## [v0.2.0](https://github.com/k1LoW/httpstub/compare/v0.1.0...v0.2.0) (2022-05-18)

* Record received requests [#3](https://github.com/k1LoW/httpstub/pull/3) ([k1LoW](https://github.com/k1LoW))
* Fix error handling [#2](https://github.com/k1LoW/httpstub/pull/2) ([k1LoW](https://github.com/k1LoW))
* Add `NewServer(t *testing.T)` [#1](https://github.com/k1LoW/httpstub/pull/1) ([k1LoW](https://github.com/k1LoW))

## [v0.1.0](https://github.com/k1LoW/httpstub/compare/19c899f43c45...v0.1.0) (2022-05-17)
