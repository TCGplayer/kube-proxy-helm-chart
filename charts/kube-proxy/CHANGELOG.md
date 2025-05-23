# kube-proxy Helm Chart Changelog

> [!NOTE]
> All notable changes to this project will be documented in this file; the format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

<!--
### Added - For new features.
### Changed - For changes in existing functionality.
### Deprecated - For soon-to-be removed features.
### Removed - For now removed features.
### Fixed - For any bug fixes.
### Security - In case of vulnerabilities.
-->

## [UNRELEASED]

## [v0.0.8] - 2025-04-01

### Fixed

- Fix validation/unwanted output in `kube-proxy.image` template. ([#1156](https://github.com/stevehipwell/helm-charts/pull/1156)) _@robertoriv_

## [v0.0.7] - 2025-03-18

### Changed

- Align app version to chart version. ([#1149](https://github.com/stevehipwell/helm-charts/pull/1149)) _@stevehipwell_
- Require end-user to provide the image tag. ([#1149](https://github.com/stevehipwell/helm-charts/pull/1149)) _@stevehipwell_

### Removed

- Remove default image tag logic. ([#1149](https://github.com/stevehipwell/helm-charts/pull/1149)) _@stevehipwell_

## [v0.0.6] - 2024-08-13

### Changed

- Updated _kube-proxy_ OCI image to [v1.31.0](https://github.com/kubernetes/kubernetes/releases/tag/v1.31.0).

## [v0.0.5] - 2024-08-01

### Fixed

- Fixed security context.

## [v0.0.4] - 2024-08-01

### Fixed

- Removed unknown `logtostderr` arg.

## [v0.0.3] - 2024-08-01

### Added

- Added default behavior to run an init container to allow the default container to [run unprivileged](https://www.kubernetes.dev/blog/2024/01/05/kube-proxy-non-privileged/).

## [v0.0.2] - 2024-07-30

### Changed

- Changed security context.

## [v0.0.1] - 2024-07-30

### Added

- Added first chart release.

<!--
RELEASE LINKS
-->
[UNRELEASED]: https://github.com/stevehipwell/helm-charts/tree/main/charts/kube-proxy
[v0.0.8]: https://github.com/stevehipwell/helm-charts/releases/tag/kube-proxy-0.0.8
[v0.0.7]: https://github.com/stevehipwell/helm-charts/releases/tag/kube-proxy-0.0.7
[v0.0.6]: https://github.com/stevehipwell/helm-charts/releases/tag/kube-proxy-0.0.6
[v0.0.5]: https://github.com/stevehipwell/helm-charts/releases/tag/kube-proxy-0.0.5
[v0.0.4]: https://github.com/stevehipwell/helm-charts/releases/tag/kube-proxy-0.0.4
[v0.0.3]: https://github.com/stevehipwell/helm-charts/releases/tag/kube-proxy-0.0.3
[v0.0.2]: https://github.com/stevehipwell/helm-charts/releases/tag/kube-proxy-0.0.2
[v0.0.1]: https://github.com/stevehipwell/helm-charts/releases/tag/kube-proxy-0.0.1
