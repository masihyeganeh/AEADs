# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.4.2 (2020-03-09)
### Fixed
- Off-by-one error in `debug_assert` for `BlockCipher::ParBlocks` ([#104])

[#104]: https://github.com/RustCrypto/AEADs/pull/104

## 0.4.1 (2020-03-07) - YANKED, see [#104]
### Added
- Support instantiation from an existing cipher instance ([#101])

[#101]: https://github.com/RustCrypto/AEADs/pull/101

## 0.4.0 (2020-03-07) - YANKED, see [#104]
### Added
- `aes` cargo feature; 3rd-party AES crate support ([#96])

### Changed
- Make generic around `BlockCipher::ParBlocks` ([#97])

[#96]: https://github.com/RustCrypto/AEADs/pull/96
[#97]: https://github.com/RustCrypto/AEADs/pull/97

## 0.3.2 (2020-02-27)
### Fixed
- Wording in documentation about security audit ([#84])

[#84]: https://github.com/RustCrypto/AEADs/pull/84

## 0.3.1 (2020-02-26)
### Added
- Notes about NCC audit to documentation ([#80])

[#80]: https://github.com/RustCrypto/AEADs/pull/80

## 0.3.0 (2019-11-26)
### Added
- `heapless` feature ([#51])

[#51]: https://github.com/RustCrypto/AEADs/pull/51

## 0.2.1 (2019-11-26)
### Added
- Document in-place API ([#49])

[#49]: https://github.com/RustCrypto/AEADs/pull/49

## 0.2.0 (2019-11-26)
### Changed
- Upgrade `aead` crate to v0.2; `alloc` now optional ([#43])

[#43]: https://github.com/RustCrypto/AEADs/pull/43

## 0.1.1 (2019-11-14)
### Changed
- Upgrade `zeroize` to 1.0 ([#36])

[#36]: https://github.com/RustCrypto/AEADs/pull/36

## 0.1.0 (2019-10-06)
- Initial release
