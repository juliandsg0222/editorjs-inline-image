# Changelog

## 2.1.0 (04.04.2024)

* Update the security policy. See[PR #137](https://github.com/kommitters/editorjs-inline-image/pull/137)
* Update all dependencies. See[PR #134](https://github.com/kommitters/editorjs-inline-image/pull/134)
* Replace and remove `intrinsic-scale`. See[PR #134](https://github.com/kommitters/editorjs-inline-image/pull/134)
* Implement orientation feature to select query images between landscape, portrait, and squarish. See [Issue #135](https://github.com/kommitters/editorjs-inline-image/issues/135)

## 2.0.0 (26.02.2024)

* ⚠️ **Breaking change:** The plugin now requires a proxy to fetch images from Unsplash. This change is made to adhere to the [Unsplash API guidelines](https://help.unsplash.com/en/articles/2511245-unsplash-api-guidelines) and enhance security by preventing the exposure of the Unsplash Access Key on the client-side.

  Each user of the plugin needs to set up their own proxy that forwards requests to the Unsplash API. Learn more about this requirement and how to configure the proxy in [this guide](https://github.com/kommitters/editorjs-inline-image/blob/main/proxy_api.md).

  To integrate the proxy, set the proxy URL in the `config.unsplash.apiUrl` parameter.

  Pull request: [Do not expose Unsplash Access Key by receiving the proxy URL #124](https://github.com/kommitters/editorjs-inline-image/pull/124)

* Update dependencies:
  * [Update all dependencies and allowed-endpoints in CI, CD, Scorecards workflows #116](https://github.com/kommitters/editorjs-inline-image/pull/116)
  * [Bump webpack from 5.53.0 to 5.76.0 [SECURITY] #117](https://github.com/kommitters/editorjs-inline-image/pull/117)
  * [Update dependency axios to v1.6.0 [SECURITY] #123](https://github.com/kommitters/editorjs-inline-image/pull/123)

## 1.2.4 (16.01.2023)

* Update all dependencies.
* Block egress traffic in GitHub Actions.
* Add stability badge in README.

## 1.2.3 (28.12.2022)

* Add Renovate as dependency update tool.
* Keep read-only permissions in CI workflow.

## 1.2.2 (22.12.2022)

* Apply security best practices hardening GitHub Actions.

## 1.2.1 (07.12.2022)

* Bump minimatch from 3.0.4 to 3.1.2

## 1.2.0 (06.12.2022)

* Bump loader-utils from 1.4.0 to 1.4.2
* Bump decode-uri-component from 0.2.0 to 0.2.2
* Implement feature: Image zoom when clicked

## 1.1.5 (28.10.2022)

* Add Coverage Report with Coveralls

## 1.1.4 (12.09.2022)

* Add OpenSSF BestPractices & Scorecard badges
* Add CDN version documentation

## 1.1.3 (09.08.2022)

* Add scorecards actions

## 1.1.2 (25.07.2022)

* Add security policy to repository
* Update packages with known security breaches

## 1.1.1 (15.07.2022)

* Add workflow for automatic publishing in npm

## 1.1.0 (12.04.2022)

* Change some classes names in order to avoid incompatibilities with some frameworks.

## 1.0.3 (29.03.2022)

* Updated packages with known security breaches.

## 1.0.2 (21.02.2022)

* Updated packages with known security breaches.

## 1.0.1 (19.01.2022)

* Updated packages with known security breaches.
* Update the css dependencies.

## 1.0.0 (09.11.2021)

* Updated packages with known security breaches.

## 0.2.1 (29.09.2021)

* Updated packages with known security breaches.

## 0.2.0 (09.09.2021)

* Added a CI workflow with Github actions.
* Updated packages with known security breaches.
* Docs updated.

## 0.1.4 (28.06.2021)

* Updated bundle file.
* Bug fix.

## 0.1.3 (01.06.2021)

* Config to disable the embed images tab was added.
* Updated packages with known security breaches.

## 0.1.2 (29.04.2021)

* Added support to read-only mode.
* Updated packages with known security breaches.

## 0.1.1 (4.06.2020)

Bugfix

* Only renders image credits if Unsplash data is valid.

## 0.1.0 (2.06.2020)

Initial release
