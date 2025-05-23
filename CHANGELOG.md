# Change Log

All notable changes to this project will be documented in this file.
Aside from features marked [🔥 Experimental 🔥], `Alamofire` adheres to [Semantic Versioning](https://semver.org/) for source stability.
[🔥 Experimental 🔥] features may require breaking changes in minor, rather than major, releases. This will be rare and compatibility should be preserved in most cases, but cannot be guaranteed.

#### 5.x Releases

- `5.10.x` Releases - [5.10.0](#5100) | [5.10.1](#5101) | [5.10.2](#5102)
- `5.9.x`  Releases - [5.9.0](#590) | [5.9.1](#591)
- `5.8.x`  Releases - [5.8.0](#580) | [5.8.1](#581)
- `5.7.x`  Releases - [5.7.0](#570) | [5.7.1](#571)
- `5.6.x`  Releases - [5.6.0](#560) | [5.6.1](#561) | [5.6.2](#562) | [5.6.3](#563) | [5.6.4](#564)
- `5.5.x`  Releases - [5.5.0](#550)
- `5.4.x`  Releases - [5.4.0](#540) | [5.4.1](#541) | [5.4.2](#542) | [5.4.3](#543) | [5.4.4](#544)
- `5.3.x`  Releases - [5.3.0](#530)
- `5.2.x`  Releases - [5.2.0](#520) | [5.2.1](#521) | [5.2.2](#522)
- `5.1.x`  Releases - [5.1.0](#510)
- `5.0.x`  Releases - [5.0.0](#500) | [5.0.1](#501) | [5.0.2](#502) | [5.0.3](#503) | [5.0.4](#504) | [5.0.5](#505)
- `5.0.0`  Release Candidates - [5.0.0-rc.1](#500-rc1) | [5.0.0-rc.2](#500-rc2) | [5.0.0-rc.3](#500-rc3)
- `5.0.0`  Betas - [5.0.0-beta.1](#500-beta1) | [5.0.0-beta.2](#500-beta2) | [5.0.0-beta.3](#500-beta3) | [5.0.0-beta.4](#500-beta4) | [5.0.0-beta.5](#500-beta5) | [5.0.0-beta.6](#500-beta6) | [5.0.0-beta.7](#500-beta7)

#### 4.x Releases

- `4.9.x` Releases - [4.9.0](#490) | [4.9.1](#491)
- `4.8.x` Releases - [4.8.0](#480) | [4.8.1](#481) | [4.8.2](#482)
- `4.7.x` Releases - [4.7.0](#470) | [4.7.1](#471) | [4.7.2](#472) | [4.7.3](#473)
- `4.6.x` Releases - [4.6.0](#460)
- `4.5.x` Releases - [4.5.0](#450) | [4.5.1](#451)
- `4.4.x` Releases - [4.4.0](#440)
- `4.3.x` Releases - [4.3.0](#430)
- `4.2.x` Releases - [4.2.0](#420)
- `4.1.x` Releases - [4.1.0](#410)
- `4.0.x` Releases - [4.0.0](#400) | [4.0.1](#401)
- `4.0.0` Betas - [4.0.0-beta.1](#400-beta1) | [4.0.0-beta.2](#400-beta2)

#### 3.x Releases

- `3.5.x` Releases - [3.5.0](#350) | [3.5.1](#351)
- `3.4.x` Releases - [3.4.0](#340) | [3.4.1](#341) | [3.4.2](#342)
- `3.3.x` Releases - [3.3.0](#330) | [3.3.1](#331)
- `3.2.x` Releases - [3.2.0](#320) | [3.2.1](#321)
- `3.1.x` Releases - [3.1.0](#310) | [3.1.1](#311) | [3.1.2](#312) | [3.1.3](#313) | [3.1.4](#314) | [3.1.5](#315)
- `3.0.x` Releases - [3.0.0](#300) | [3.0.1](#301)
- `3.0.0` Betas - [3.0.0-beta.1](#300-beta1) | [3.0.0-beta.2](#300-beta2) | [3.0.0-beta.3](#300-beta3)

#### 2.x Releases

- `2.0.x` Releases - [2.0.0](#200) | [2.0.1](#201) | [2.0.2](#202)
- `2.0.0` Betas - [2.0.0-beta.1](#200-beta1) | [2.0.0-beta.2](#200-beta2) | [2.0.0-beta.3](#200-beta3) | [2.0.0-beta.4](#200-beta4)

#### 1.x Releases

- `1.3.x` Releases - [1.3.0](#130) | [1.3.1](#131)
- `1.2.x` Releases - [1.2.0](#120) | [1.2.1](#121) | [1.2.2](#122) | [1.2.3](#123)
- `1.1.x` Releases - [1.1.0](#110) | [1.1.1](#111) | [1.1.2](#112) | [1.1.3](#113) | [1.1.4](#114) | [1.1.5](#115)
- `1.0.x` Releases - [1.0.0](#100) | [1.0.1](#101)

---

## [5.10.2](https://github.com/Alamofire/Alamofire/releases/tag/5.10.2]

Released on 2024-11-249. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/93?closed=1).

### Fixed
- Runtime crash when calling `validate` from a Swift 6-compiled target.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3920](https://github.com/Alamofire/Alamofire/pull/3920).
- Swift 6.0 `Package.swift` deprecation warning.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3911](https://github.com/Alamofire/Alamofire/pull/3911).

## [5.10.1](https://github.com/Alamofire/Alamofire/releases/tag/5.10.1)

Released on 2024-10-19. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/92?closed=1).

### Fixed
- `@Sendable` in `AdaptHandler` and `RetryHandler` types.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3906](https://github.com/Alamofire/Alamofire/pull/3906).
- Downstream `JSONResponseSerializer` wrapper by reverting output type to just `Any`.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3903](https://github.com/Alamofire/Alamofire/pull/3903).
- Missing `@Sendable` on `Authenticator.refresh`.
  - Fixed by [rono23](https://github.com/rono23) in Pull Request [#3901](https://github.com/Alamofire/Alamofire/pull/3901).

## [5.10.0](https://github.com/Alamofire/Alamofire/releases/tag/5.10.0)

Released on 2024-10-13. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/91?closed=1).

### Added
- 🔥 Full Swift concurrency support with `Sendable` requirements. Most APIs are also marked `@preconcurrency`, so there should be no breaking changes. Swift 5.9 now required to build.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3880](https://github.com/Alamofire/Alamofire/pull/3880).
- Existential `any` now required internally by Alamofire.
  - Added by [Keita Watanabe](https://github.com/kitwtnb) in Pull Request [#3881](https://github.com/Alamofire/Alamofire/pull/3881).

### Updated
- 🔥 `Session.init(... eventMonitors:)` to allow no `EventMonitor`s at all, and `CompositeEventMonitor` to fix thread-safety. Potentially breaking if previously passing `[]` but still expecting `Notification`s to be posted. Pass `[AlamofireNotifications()]` if you need that behavior.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3894](https://github.com/Alamofire/Alamofire/pull/3894).
- `DownloadRequest.validate` to read the `fileSize` rather than the whole file from disk.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3899](https://github.com/Alamofire/Alamofire/pull/3899).
- Links to `swiftlang` repositories.
  - Updated by [LamTrinh.Dev](https://github.com/lamtrinhdev) in Pull Request [#3882](https://github.com/Alamofire/Alamofire/pull/3882).

### Fixed
- Various documentation typos.
  - Fixed by [Alexander Cyon](https://github.com/Sajjon) in Pull Request [#3891](https://github.com/Alamofire/Alamofire/pull/3891).
- Passing `queue` parameter to `DataStream` serializers.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3879](https://github.com/Alamofire/Alamofire/pull/3879).
- `testThatDatesCanBeEncodedAsFormatted` when running with a non-Gregorian calendar.
  - Fixed by [Kittisak Phetrungnapha](https://github.com/kittisak-phetrungnapha) in Pull Request [#3858](https://github.com/Alamofire/Alamofire/pull/3858).

---

## [5.9.1](https://github.com/Alamofire/Alamofire/releases/tag/5.9.1)

Released on 2024-03-30. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/90?closed=1).

### Updated

- `HTTPHeaders` and `HTTPHeader` to be `Sendable`.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3856](https://github.com/Alamofire/Alamofire/pull/3856).
- `HTTPMethod` to be `Sendable`.
  - Updated by [Galvin Li](https://github.com/bestwnh) in Pull Request [#3848](https://github.com/Alamofire/Alamofire/pull/3848).

### Fixed

- CocoaPods visionOS support by explicitly declaring it in podspec.
  - Fixed by [Tamás Jäger](https://github.com/bestwnh) in Pull Request [#3845](https://github.com/Alamofire/Alamofire/pull/3845).

## [5.9.0](https://github.com/Alamofire/Alamofire/releases/tag/5.9.0)

Released on 2024-03-03. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/89?closed=1).

### Added

- [🔥 Experimental 🔥] `WebSocketRequest`, as a wrapper for `URLSessionWebSocketTask`. This preview release is undocumented behind `@_spi(WebSocket)`. Its API _will_ change in the future, especially to adopt typed throws, but it is largely feature complete, tested, and usable now. API feedback, missing use cases, and bug reports are much appreciated before it goes fully public.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3455](https://github.com/Alamofire/Alamofire/pull/3455).
- `PrivacyInfo.xcprivacy` file and integration with SPM, CocoaPods, and Carthage.
  - Added by [Dmitry Kuleshov](https://github.com/kdvmgn) and [Jon Shier](https://github.com/jshier) in Pull Requests [#3792](https://github.com/Alamofire/Alamofire/pull/3792), [#3831](https://github.com/Alamofire/Alamofire/pull/3831), and [#3839](https://github.com/Alamofire/Alamofire/pull/3839).
- `AlamofireDynamic` target, to force dynamic linking in Xcode when using SPM. Only use when you know you need it.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3808](https://github.com/Alamofire/Alamofire/pull/3808).
- `AFInfo` enum and a public `version` value to get Alamofire's current version, `AFInfo.version`.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3819](https://github.com/Alamofire/Alamofire/pull/3819).

### Updated

- Alamofire to require Swift 5.7.1.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3798](https://github.com/Alamofire/Alamofire/pull/3798).
- Project structure to break apart large `Request.swift` file and consolidate various `Request` subclasses into their own files.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3798](https://github.com/Alamofire/Alamofire/pull/3798).
- `Empty` type to be `Sendable`.
  - Updated by [Antoine van der Lee](https://github.com/AvdLee) in Pull Request [#3816](https://github.com/Alamofire/Alamofire/pull/3816).
- `.swiftformat` to remove duplicate rules.
  - Updated by [Fourenn](https://github.com/giftbott) in Pull Request [#3835](https://github.com/Alamofire/Alamofire/pull/3835).

### Fixed

- Platform deprecation warnings in `Package.swift` in newer Xcode versions.
  - Fxied by [fess](https://github.com/apps4everyone) in Pull Request [#3823](https://github.com/Alamofire/Alamofire/pull/3823).
- `Alamofire.podspec` after project restructuring.
  - Fixed by [mlch](https://github.com/mlch911) in Pull Request [#3825](https://github.com/Alamofire/Alamofire/pull/3825).
- Various documentation typos.
  - Fixed by [JaewoongLee-swift](https://github.com/JaewoongLee-swift), [TaeHyun](https://github.com/kth1210), and [hugo-syn](https://github.com/hugo-syn) in various Pull Requests.

---

## [5.8.1](https://github.com/Alamofire/Alamofire/releases/tag/5.8.1)

Released on 2023-10-26. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/88?closed=1).

### Updated

- Internal: `Protected` to no longer be a `@propertyWrapper`.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3777](https://github.com/Alamofire/Alamofire/pull/3777).

### Fixed

- `URLEncodedFormEncoder` encoding of `Encodable` values with optional properties using `encodeIfPresent`.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3779](https://github.com/Alamofire/Alamofire/pull/3779).
- Missing "Skip Install" setting for visionOS target.
  - Fixed by [Sai](https://github.com/Sai) in Pull Request [#3788](https://github.com/Alamofire/Alamofire/pull/3788).

## [5.8.0](https://github.com/Alamofire/Alamofire/releases/tag/5.8.0)

Released on 2023-08-31. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/87?closed=1).

#### Added

- visionOS support.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Requests [#3738](https://github.com/Alamofire/Alamofire/pull/3738) and [#3750](https://github.com/Alamofire/Alamofire/pull/3750).
- Hooks for initial `HTTPURLResponse` values.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3762](https://github.com/Alamofire/Alamofire/pull/3738).
- Android build support.
  - Added by [Hugo Gonzalez](https://github.com/hggz) in Pull Request [#3744](https://github.com/Alamofire/Alamofire/pull/3744).

#### Updated

- Async integration to obey automatic cancellation by default.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3757](https://github.com/Alamofire/Alamofire/pull/3757).
- Platform `#if` checks.
  - Updated by [brenno](https://github.com/brennobemoura) in Pull Request [#3756](https://github.com/Alamofire/Alamofire/pull/3756).
- Windows CI.
  - Updated by [Saleem Abdulrasool](https://github.com/compnerd) in Pull Request [#3763](https://github.com/Alamofire/Alamofire/pull/3763).
- `URL` conversion tests for 2023 `URL` changes.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3734](https://github.com/Alamofire/Alamofire/pull/3734).
- for-loop to `contains`.
  - Updated by [Mayank Kumar Gupta](https://github.com/Mayank-84) in Pull Request [#3726](https://github.com/Alamofire/Alamofire/pull/3726).

#### Fixed

- `MultipartFormData` stream to properly obey `bodyContentLength`.
  - Fixed by [Henrique Valcanaia](https://github.com/hvsw) in Pull Request [#3730](https://github.com/Alamofire/Alamofire/pull/3730).
- Unnecessary call to empty init.
  - Fixed by [Shinolr](https://github.com/Shinolr) in Pull Request [#3742](https://github.com/Alamofire/Alamofire/pull/3742).
- Documentation typos.
  - Fixed by [Jenna](https://github.com/ueunli) in Pull Request [#3733](https://github.com/Alamofire/Alamofire/pull/3733).

---

## [5.7.1](https://github.com/Alamofire/Alamofire/releases/tag/5.7.1)

Released on 2023-05-10. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/86?closed=1).

#### Updated

- Deployment targets reverted to (macOS 10.12, iOS 10, tvOS 10, and watchOS 3)+
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3720](https://github.com/Alamofire/Alamofire/pull/3720).

## [5.7.0](https://github.com/Alamofire/Alamofire/releases/tag/5.7.0)

Released on 2023-05-09. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/84?closed=1).

#### Added

- Request body compression support. This is disabled by default.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3701](https://github.com/Alamofire/Alamofire/pull/3701).
- `ArrayEncoding.custom` to `URLEncodedFormEncoder` and `URLEncoding`.
  - Added by [Mike Naquin](https://github.com/naquin) in Pull Request [#3699](https://github.com/Alamofire/Alamofire/pull/3699).
- `KeyPathEncoding` to `URLEncodedFormEncoder`.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3689](https://github.com/Alamofire/Alamofire/pull/3689).
- `NilEncoding` to `URLEncodedFormEncoder`.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3686](https://github.com/Alamofire/Alamofire/pull/3686).

#### Updated

- Alamofire now requires Swift 5.5+ and (macOS 10.13, iOS 11, tvOS 11, and watchOS 4)+.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Requests [#3670](https://github.com/Alamofire/Alamofire/pull/3670) and [#3717](https://github.com/Alamofire/Alamofire/pull/3717).
- `flatMap` to `map` in `HTTPHeaders`.
  - Updated by [kati](https://github.com/kati-kms) in Pull Request [#3704](https://github.com/Alamofire/Alamofire/pull/3704).
- Various CI integrations.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Requests [#3685](https://github.com/Alamofire/Alamofire/pull/3685) and [#3712](https://github.com/Alamofire/Alamofire/pull/3712).

#### Fixed

- Reachability API usage safety.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3684](https://github.com/Alamofire/Alamofire/pull/3684).
- Unused `bufferingPolicy` in `StreamOf`.
  - Fixed by [Duc](https://github.com/trungducc) in Pull Request [#3668](https://github.com/Alamofire/Alamofire/pull/3668).
- Various documentation typos.
  - Fixed by [Timo Wälisch](https://github.com/TimoWaelischIdealo), [Tony](https://github.com/iamtony), and [uhooi](https://github.com/uhooi) in various PRs.

---

## [5.6.4](https://github.com/Alamofire/Alamofire/releases/tag/5.6.4)

Released on 2022-11-21. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/85?closed=1).

#### Fixed

- Deprecated OS version support in Swift 5.7 SPM Package.
  - Fixed by [Guglielmo Faglioni](https://github.com/guidev) in Pull Request [#3665](https://github.com/Alamofire/Alamofire/pull/3665).

## [5.6.3](https://github.com/Alamofire/Alamofire/releases/tag/5.6.3)

Released on 2022-11-20. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/83?closed=1).

#### Updated

- Swift package to 5.7, CI to Xcode 14.1.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3653](https://github.com/Alamofire/Alamofire/pull/3653).

#### Fixed

- Calls to deprecated cancellation handler function.
  - Fixed by [Sven Münnich](https://github.com/svenmuennich) in Pull Request [#3657](https://github.com/Alamofire/Alamofire/pull/3657).
- Unnecessary protocol conformance on Combine publishers.
  - Fixed by [MoonkiKim(김문기)](https://github.com/tedKim5178) in Pull Request [#3650](https://github.com/Alamofire/Alamofire/pull/3650).
- Don't attempt retry when `Request` has already been cancelled.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3641](https://github.com/Alamofire/Alamofire/pull/3641).

## [5.6.2](https://github.com/Alamofire/Alamofire/releases/tag/5.6.2)

Released on 2022-07-17. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/82?closed=1).

#### Added

- Error when object provided to `JSONEcoding` contains values that can't be passed through `JSONSerialization`.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3624](https://github.com/Alamofire/Alamofire/pull/3624).

#### Updated

- CI support for all supported Xcode, macOS, and Linux versions.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Requests [#3607](https://github.com/Alamofire/Alamofire/pull/3607) and [#3622](https://github.com/Alamofire/Alamofire/pull/3622).
- Support for various Xcode version.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Requests [#3616](https://github.com/Alamofire/Alamofire/pull/3616) and [#3632](https://github.com/Alamofire/Alamofire/pull/3632).
- `Cache-Control` header tests to not require hard-coded delays.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3601](https://github.com/Alamofire/Alamofire/pull/3601).

#### Fixed

- Swift version check for `SecTrustCopyCertificateChain`.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3606](https://github.com/Alamofire/Alamofire/pull/3606).
- Various documentation issues.
  - Fixed by [Jacob Lange](https://github.com/jacoblange-dev), [rain2540](https://github.com/rain2540), [bondxf](https://github.com/bondxf), [Ikko Ashimine](https://github.com/eltociear), and [Elon Park](https://github.com/ElonPark) in various Pull Requests.

## [5.6.1](https://github.com/Alamofire/Alamofire/releases/tag/5.6.1)

Released on 2022-04-17. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/81?closed=1).

#### Fixed

- Missing `automaticallyCancelling` parameter in `serializingDownloadedFileURL`.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3597](https://github.com/Alamofire/Alamofire/pull/3597).

## [5.6.0](https://github.com/Alamofire/Alamofire/releases/tag/5.6.0)

Released on 2022-04-13. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/80?closed=1).

#### Added

- Support for `HTTPMethod.query` to support the [upcoming standard](https://datatracker.ietf.org/doc/html/draft-ietf-httpbis-safe-method-w-body-02).
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3553](https://github.com/Alamofire/Alamofire/pull/3553).
- Compile-time Swift version check to enforce minimum supported Swift version.
  - Added by [Dave Verwer](https://github.com/daveverwer) in Pull Request [#3549](https://github.com/Alamofire/Alamofire/pull/3549).
- GitHub Sponsors support. You can now sponsor Alamofire directly through GitHub.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3543](https://github.com/Alamofire/Alamofire/pull/3543).

#### Updated

- Swift version required to build [🔥 Experimental 🔥] Swift Concurrency support to 5.6.0 to avoid various Apple bugs with Xcode 13.2.0 and 13.2.1. Support now requires Xcode 13.3.1.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3590](https://github.com/Alamofire/Alamofire/pull/3590).
- `DownloadRequest` to avoid producing resume data when not explicitly requested on cancellation.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3538](https://github.com/Alamofire/Alamofire/pull/3538).
- Testing infrastructure to use XCTestPlans on Apple platforms.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3538](https://github.com/Alamofire/Alamofire/pull/3538).
- GitHub Actions support for greater OS coverage, more SPM platforms, and Swift 5.6.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Requests [#3534](https://github.com/Alamofire/Alamofire/pull/3534), [#3545](https://github.com/Alamofire/Alamofire/pull/3545), [#3570](https://github.com/Alamofire/Alamofire/pull/3570), and [#3587](https://github.com/Alamofire/Alamofire/pull/3587).

#### Fixed

- Various Security framework deprecation warnings when deploying to newer OSes.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3555](https://github.com/Alamofire/Alamofire/pull/3555).
- Various documentation issues.
  - Fixed by [Jon Shier](https://github.com/jshier), [Emanuele Fumagalli](https://github.com/emanuelef), [Huang-Libo](https://github.com/Huang-Libo), and [rain2540](https://github.com/rain2540) in Pull Requests [#3548](https://github.com/Alamofire/Alamofire/pull/3548), [#3562](https://github.com/Alamofire/Alamofire/pull/3562), [#3573](https://github.com/Alamofire/Alamofire/pull/3573), [#3574](https://github.com/Alamofire/Alamofire/pull/3574), and [#3585](https://github.com/Alamofire/Alamofire/pull/3585).

---

## [5.5.0](https://github.com/Alamofire/Alamofire/releases/tag/5.5.0)

Released on 2021-12-13. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/79?closed=1).

#### Added

- [🔥 Experimental 🔥] support for Swift Concurrency, including `async`-`await` for requests and `StreamOf` for streaming values.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3463](https://github.com/Alamofire/Alamofire/pull/3463).
- Generic static accessors for various protocols types for Swift 5.5.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3499](https://github.com/Alamofire/Alamofire/pull/3499).
- `.indexInBrackets` options for array encoding in query parameters.
  - Added by [Tiago Lopes](https://github.com/TiagoMaiaL) in Pull Request [#3516](https://github.com/Alamofire/Alamofire/pull/3516).
- `RequestAdapterState` and new protocol requirements for `RequestAdapter` to allow for additional state to be available.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request [#3504](https://github.com/Alamofire/Alamofire/pull/3504).

#### Updated

- `Session` to more safely target provided custom `DispatchQueue`s for internal use.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3523](https://github.com/Alamofire/Alamofire/pull/3523).
- `AFError` message regarding unacceptable `Content-Type`s to sort the types.
  - Updated by [Timur Yusipov](https://github.com/Usipov) in Pull Request [#3518](https://github.com/Alamofire/Alamofire/pull/3518).
- Base Swift language version requirement to 5.3.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3495](https://github.com/Alamofire/Alamofire/pull/3495).
- Sample app to show proper loading state for requests.
  - Updated by [Tiago Lopes](https://github.com/TiagoMaiaL) in Pull Request [#3514](https://github.com/Alamofire/Alamofire/pull/3514).

#### Deprecated

- `responseJSON` and associated methods, in preference to `responseDecodable`.
  - Deprecated by [Jon Shier](https://github.com/jshier) in Pull Request [#3502](https://github.com/Alamofire/Alamofire/pull/3502).

#### Fixed

- Use of `Protected` wrapper when accessing properties of the wrapped values to ensure proper thread-safety.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3505](https://github.com/Alamofire/Alamofire/pull/3505).
- Various documentation typos.
  - Fixed by [Christos Koninis](https://github.com/csknns), [Tiago Lopes](https://github.com/TiagoMaiaL), and [Eugene Berdnikov](https://github.com/evnik) in various Pull Requests.

---

## [5.4.4](https://github.com/Alamofire/Alamofire/releases/tag/5.4.4)

Released on 2021-09-20. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/78?closed=1).

#### Added

- Support for Xcode 13, including a workaround for Combine compilation on older architectures.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3486](https://github.com/Alamofire/Alamofire/pull/3486).
- Testing on watchOS.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3449](https://github.com/Alamofire/Alamofire/pull/3449).
- Support for building on Windows and Linux. Alamofire is unsupported on these platforms but should build correctly.
  - Added by [Jon Shier](https://github.com/jshier) and [Alex Taffe](https://github.com/alex-taffe) in Pull Requests [#3446](https://github.com/Alamofire/Alamofire/pull/3446) and [#3462](https://github.com/Alamofire/Alamofire/pull/3462).

#### Updated

- Usage of `.count >= 0` to `!.isEmpty`.
  - Updated by [Shafeer P](https://github.com/shafeerp) in Pull Request [#3478](https://github.com/Alamofire/Alamofire/pull/3478).

#### Fixed

- Async navigation title updating in example app.
  - Fixed by [Tiago Maia](https://github.com/TiagoMaiaL) in Pull Request [3494](https://github.com/Alamofire/Alamofire/pull/3494).
- Various documentation bugs.
  - Fixed by [Jordan de Laune](https://github.com/jdelaune), [Cédric Luthi](https://github.com/0xced), [Romain Bertozzi](https://github.com/r-mckay), and [Tiago Maia](https://github.com/TiagoMaiaL).

## [5.4.3](https://github.com/Alamofire/Alamofire/releases/tag/5.4.3)

Released on 2021-04-21. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/77?closed=1).

#### Fixed

- Change in multipart upload creation order.
  - Fixed by [Christian Noon](https://github.com/cnoon) in Pull Request [#3438](https://github.com/Alamofire/Alamofire/pull/3438).
- Typo in Alamofire 5 migration guide.
  - Fixed by [DevYeom](https://github.com/DevYeom) in Pull Request [#3431](https://github.com/Alamofire/Alamofire/pull/3431).

## [5.4.2](https://github.com/Alamofire/Alamofire/releases/tag/5.4.2)

Released on 2021-04-03. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/76?closed=1).

#### Updated

- Resume data handling for `DownloadRequest`s to access resume data from errors as well as cancellation.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3419](https://github.com/Alamofire/Alamofire/pull/3419).
- Project files and templates for Xcode 12.4 and GitHub templates.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3414](https://github.com/Alamofire/Alamofire/pull/3414).

#### Fixed

- `MultipartUpload` thread-safety.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3421](https://github.com/Alamofire/Alamofire/pull/3421).
- Multipart body stream length handling to better handle partial streams.
  - Fixed by [Yu Ao](https://github.com/YuAo) and [Jon Shier](https://github.com/jshier) in Pull Requests [#3380](https://github.com/Alamofire/Alamofire/pull/3380) and [#3420](https://github.com/Alamofire/Alamofire/pull/3420).

## [5.4.1](https://github.com/Alamofire/Alamofire/releases/tag/5.4.1)

Released on 2020-12-20. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/75?closed=1).

#### Updated

- Project and CocoaPods installation of Obj-C header.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3378](https://github.com/Alamofire/Alamofire/pull/3378).

## [5.4.0](https://github.com/Alamofire/Alamofire/releases/tag/5.4.0)

Released on 2020-10-17. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/74?closed=1).

#### Added

- `URLResponseSerializer` and attendant convenience methods so downloads can produce a non-optional `URL`.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3343](https://github.com/Alamofire/Alamofire/pull/3343).

#### Updated

- Handing of `file://` `URL`s, removing error added in 5.3.0 and adding support for `DownloadRequest`.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3342](https://github.com/Alamofire/Alamofire/pull/3342).

---

## [5.3.0](https://github.com/Alamofire/Alamofire/releases/tag/5.3.0)

Released on 2020-10-17. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/73?closed=1).

#### Added

- Closure callback APIs for the production of `URLRequest`s and `URLSessionTask`s.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3219](https://github.com/Alamofire/Alamofire/pull/3219).
- `URLSessionTaskMetrics` gathering on watchOS 7+.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3321](https://github.com/Alamofire/Alamofire/pull/3321).

#### Updated

- Project settings, GitHub Actions, tests, and formatting for newer Xcodes.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Requests [#3278](https://github.com/Alamofire/Alamofire/pull/3278), [#3284](https://github.com/Alamofire/Alamofire/pull/3284), [#3285](https://github.com/Alamofire/Alamofire/pull/3285), [#3309](https://github.com/Alamofire/Alamofire/pull/3309), and [#3320](https://github.com/Alamofire/Alamofire/pull/3320).
- Use of `URLRequest.headers` extension property in `URLEncoding`.
  - Updated by [tomisacat](https://github.com/tomisacat) in Pull Request [#3264](https://github.com/Alamofire/Alamofire/pull/3264).
- iOS example app.
  - Updated by [rain2540](https://github.com/rain2540) in Pull Request [#3268](https://github.com/Alamofire/Alamofire/pull/3268).
- Various documentation.
  - Updated by [Jaydeep Vora](https://github.com/jaydeep-vora), [Minhyuk Kim](https://github.com/mininny), and [Tieda](https://github.com/weitieda) in Pull Requests [#3274](https://github.com/Alamofire/Alamofire/pull/3274), [#3292](https://github.com/Alamofire/Alamofire/pull/3292), and [#3317](https://github.com/Alamofire/Alamofire/pull/3317).

#### Fixed

- Double lock crash in `AuthenticationInterceptor` caused by synchronous `refresh` implementations.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3322](https://github.com/Alamofire/Alamofire/pull/3322).
- Crash when requesting `file://` `URL`s by producing validation error.
  - Fixed by [hyotak.yun](https://github.com/devtak) in Pull Request [#3318](https://github.com/Alamofire/Alamofire/pull/3318).
- Missing rethrow of error produced when writing temporary multipart files fails.
  - Fixed by [sudo.park](https://github.com/sudopark) in Pull Request [#3306](https://github.com/Alamofire/Alamofire/pull/3306).
- Objective-C module conflicts in Xcode 12 by removing Obj-C module support.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3308](https://github.com/Alamofire/Alamofire/pull/3308).

---

## [5.2.2](https://github.com/Alamofire/Alamofire/releases/tag/5.2.2)

Released on 2020-07-17. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/72?closed=1).

#### Added

- `macOS(Catalyst)` `User-Agent` string.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3236](https://github.com/Alamofire/Alamofire/pull/3236).

#### Updated

- `debugDescription` of `DataRequest` and `DownloadRequest` to better handle non-text and long content, with better formatting.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3256](https://github.com/Alamofire/Alamofire/pull/3256).
- Code to use `switch` instead of `if else` statement.
  - Updated by [dirtmelon](https://github.com/dirtmelon) in Pull Request [#3214](https://github.com/Alamofire/Alamofire/pull/3214).

#### Fixed

- Linking on some Apple OS versions when using Swift Package Manager.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3259](https://github.com/Alamofire/Alamofire/pull/3259).
- Reliability issues with `DataStreamRequest`.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3216](https://github.com/Alamofire/Alamofire/pull/3216).

## [5.2.1](https://github.com/Alamofire/Alamofire/releases/tag/5.2.1)

Released on 2020-05-25. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/71?closed=1).

#### Updated

- Usage of `.background` `DispatchQoS` to `.utility` to avoid low-power issues.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3207](https://github.com/Alamofire/Alamofire/pull/3207).

#### Fixed

- Various memory leaks.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3199](https://github.com/Alamofire/Alamofire/pull/3199).

## [5.2.0](https://github.com/Alamofire/Alamofire/releases/tag/5.2.0)

Released on 2020-05-16. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/70?closed=1).

#### Added

- Combine support! `DataResponsePublisher`, `DownloadResponsePublisher`, and `DataStreamPublisher` to stream Alamofire responses.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3160](https://github.com/Alamofire/Alamofire/pull/3160).
- `AuthenticationInterceptor`, for easier adaptation and retry of requests with credentials.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request [#3164](https://github.com/Alamofire/Alamofire/pull/3164).

#### Updated

- Response handlers to take all serializer parameters.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3188](https://github.com/Alamofire/Alamofire/pull/3188).
- `DisabledEvaluator` to `DisabledTrustEvaluator`, deprecating the previous name.
  - Updated by [Florian Petit](https://github.com/MrCloud) in Pull Request [#3162](https://github.com/Alamofire/Alamofire/pull/3162).
- `Interceptor` to be initialized with multiple `RequestInterceptor`s, in addition to `RequestAdapter`s and `RequestRetrier`s.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3155](https://github.com/Alamofire/Alamofire/pull/3155).

#### Fixed

- Minor documentation issues.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3187](https://github.com/Alamofire/Alamofire/pull/3187).
- Encoding of `Decimal` values in `URLEncodedFormEncoder`.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3185](https://github.com/Alamofire/Alamofire/pull/3185).
- Thread-safety issue in `Session`.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3179](https://github.com/Alamofire/Alamofire/pull/3179).
- Memory leak in `NetworkReachabilityManager`.
  - Fixed by [dirtmelon](https://github.com/dirtmelon) in Pull Request [#3180](https://github.com/Alamofire/Alamofire/pull/3180).

---

## [5.1.0](https://github.com/Alamofire/Alamofire/releases/tag/5.1.0)

Released on 2020-04-04. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/64?closed=1).

#### Added

- `RequestModifier` closure to request APIs, allowing mutation of created `URLRequest`s.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3137](https://github.com/Alamofire/Alamofire/pull/3137).
- `DataStreamRequest`, for streaming HTTP responses.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3074](https://github.com/Alamofire/Alamofire/pull/3074).

#### Updated

- Various framework internals to make porting to Linux easier.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3115](https://github.com/Alamofire/Alamofire/pull/3115).
- Project to require Swift 5.1.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3066](https://github.com/Alamofire/Alamofire/pull/3066).

#### Fixed

- Typo in `ServerTrustEvaluating` documentation.
  - Fixed by [Lucas Tavares](https://github.com/tavares1) in Pull Request [#3138](https://github.com/Alamofire/Alamofire/pull/3138).

---

## [5.0.5](https://github.com/Alamofire/Alamofire/releases/tag/5.0.5)

Released on 2020-03-23. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/69?closed=1).

#### Fixed

- `Request` casting issue on retry that could lead to incomplete retry of `UploadRequest`s.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3127](https://github.com/Alamofire/Alamofire/pull/3127).
- Rare scenario where `finish()` could be called multiple times, leading to duplicate response handler calls.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3116](https://github.com/Alamofire/Alamofire/pull/3116).

## [5.0.4](https://github.com/Alamofire/Alamofire/releases/tag/5.0.4)

Released on 2020-03-15. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/68?closed=1).

#### Fixed

- Incompatibility with bitcode on watchOS.
  - Fixed by [Roman Podymov](https://github.com/RomanPodymov) in Pull Request [#3112](https://github.com/Alamofire/Alamofire/pull/3112).

## [5.0.3](https://github.com/Alamofire/Alamofire/releases/tag/5.0.3)

Released on 2020-03-14. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/67?closed=1).

#### Added

- SwiftPM testing support.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3102](https://github.com/Alamofire/Alamofire/pull/3102).
- Documentation around the prohibition of background `URLSessionConfiguration`s in Alamofire 5.
  - Added by [Teameh](https://github.com/teameh) in Pull Request [#3094](https://github.com/Alamofire/Alamofire/pull/3094).

#### Fixed

- watchOS memory leaks due to missing `didFinishCollecting` event.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3110](https://github.com/Alamofire/Alamofire/pull/3110).
- `RetryPolicy`'s handling of `AFError`.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3103](https://github.com/Alamofire/Alamofire/pull/3103).
- `DownloadRequest` cancellation reliability.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3102](https://github.com/Alamofire/Alamofire/pull/3102).
- `-no_compact_unwind` linker warning on watchOS by disabling the warning.
  - Fixed by [Christian Noon](https://github.com/cnoon) in Pull Request [#3083](https://github.com/Alamofire/Alamofire/pull/3083).
- SwiftPM package snippet in README.
  - Fixed by [Eddie Seay](https://github.com/eseay) in Pull Request [#3081](https://github.com/Alamofire/Alamofire/pull/3081).
- Various documentation issues.
  - Fixed by [dirtmelon](https://github.com/dirtmelon) in Pull Requests [#3105](https://github.com/Alamofire/Alamofire/pull/3105) and [#3097](https://github.com/Alamofire/Alamofire/pull/3097).
  - Fixed by [Josip Ćavar](https://github.com/jcavar) in Pull Request [#3095](https://github.com/Alamofire/Alamofire/pull/3095).
  - Fixed by [Teameh](https://github.com/dirtmelon) in Pull Request [#3093](https://github.com/Alamofire/Alamofire/pull/3093).
  - Fixed by [Michael Clifford](https://github.com/michaeldclifford) in Pull Request [#3087](https://github.com/Alamofire/Alamofire/pull/3087).

## [5.0.2](https://github.com/Alamofire/Alamofire/releases/tag/5.0.2)

Released on 2020-02-23. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/66?closed=1).

#### Fixed

- Swift 5 support for `AlamofireExtension`.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3077](https://github.com/Alamofire/Alamofire/pull/3077).

## [5.0.1](https://github.com/Alamofire/Alamofire/releases/tag/5.0.1)

Released on 2020-02-23. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/64?closed=1).

#### Updated

- `AlamofireExtension` to have public properties and initializer, and conform to `@dynamicMemberLookup`.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3075](https://github.com/Alamofire/Alamofire/pull/3075).

## [5.0.0](https://github.com/Alamofire/Alamofire/releases/tag/5.0.0)

Released on 2020-02-14. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/63?closed=1).

#### Added

- Support for `NSURLAuthenticationMethodClientCertificate` when handling auth challenges using `URLCredential`s.
  - Added by [刘富东](https://github.com/liuwin7) in Pull Request [#2993](https://github.com/Alamofire/Alamofire/pull/2993).
- Migration Guide for Alamofire 5.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#3061](https://github.com/Alamofire/Alamofire/pull/3061).

#### Updated

- Advanced Usage documentation for Alamofire 5.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3062](https://github.com/Alamofire/Alamofire/pull/3062).
- `AF` namespace to be a reference to `Session.default`.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#3059](https://github.com/Alamofire/Alamofire/pull/3059).

#### Fixed

- Runtime crashes due to overzealous state checking in `SessionDelegate` by reducing the severity of the assertions.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#3010](https://github.com/Alamofire/Alamofire/pull/3010).
- Unwanted `public` attribute on `_URLEncodedFormEncoder`.
  - Fixed by [Mattt](https://github.com/mattt) in Pull Request [#3053](https://github.com/Alamofire/Alamofire/pull/3053).

---

## [5.0.0-rc.3](https://github.com/Alamofire/Alamofire/releases/tag/5.0.0-rc.3)

Released on 2019-10-26. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/62?closed=1). **Note:** Alamofire 5 is now API stable.

#### Updated

- Automatic `resume()` behavior to be called after the first response handler is added instead of immediately after task creation.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#2965](https://github.com/Alamofire/Alamofire/pull/2965).

#### Fixed

- Incorrect header convenience method in Usage documentation.
  - Fixed by [Sebastian](https://github.com/Buesing-Sebastian) in Pull Request [#2952](https://github.com/Alamofire/Alamofire/pull/2952).
- Unstable parameter ordering in `URLEncodedFormEncoder`.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#2961](https://github.com/Alamofire/Alamofire/pull/2961).
- Xcode build issues and precompiled binary build issues by removing the dynamic bundle identifier.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#2966](https://github.com/Alamofire/Alamofire/pull/2966).
- Build warnings for deprecated `SecTrust` API when building for Catalyst.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#2977](https://github.com/Alamofire/Alamofire/pull/2977).
- Regression from Alamofire 4 causing Alamofire to reject NTLM and Negotiate authentication methods.
  - Fixed by [Adrian Kashivskyy](https://github.com/akashivskyy) in Pull Request [#2975](https://github.com/Alamofire/Alamofire/pull/2975).

## [5.0.0-rc.2](https://github.com/Alamofire/Alamofire/releases/tag/5.0.0-rc.2)

Released on 2019-09-08. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/59?closed=1). **Note:** Alamofire 5 is now API stable.

#### Fixed

- Single remaining use of `Error` instead of generic `Failure` constraint in `DataResponse` API.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#2937](https://github.com/Alamofire/Alamofire/pull/2937).

## [5.0.0-rc.1](https://github.com/Alamofire/Alamofire/releases/tag/5.0.0-rc.1)

Released on 2019-09-04. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/58?closed=1). **Note:** Alamofire 5 is now API stable.

#### Added

- `cancelAllRequests` method on `Session` to cancel all in flight requests.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2890](https://github.com/Alamofire/Alamofire/pull/2890).
- Ability to inject `FileManager` instance into `UploadRequest`.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2898](https://github.com/Alamofire/Alamofire/pull/2898).
- `DataPreprocessor` protocol and implementations, allowing the preprocessing of data before serialization.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2903](https://github.com/Alamofire/Alamofire/pull/2903).
- Internal `URLRequest` validation and error. `GET` requests with body data will now produce an error.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2905](https://github.com/Alamofire/Alamofire/pull/2905).
- Generic `Failure` constraint to `DataResponse` and `DownloadResponse`, making them `DataResponse<Success, Failure: Error>` and `DownloadResponse<Success, Failure: Error>`.
  - Added by [philtre](https://github.com/philtre) in Pull Request [#2893](https://github.com/Alamofire/Alamofire/pull/2893).
- Precondition to ensure `Session` can't be used with background `URLSessionConfiguration`s. Alamofire will explicitly support such functionality at some point in the future.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2917](https://github.com/Alamofire/Alamofire/pull/2917).
- SwiftFormat configuration and updated styling.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2918](https://github.com/Alamofire/Alamofire/pull/2918).
- `AFDataResponse<Success>` and `AFDownloadResponse<Success>` typealiases to help deal with the doubly generic responses.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2921](https://github.com/Alamofire/Alamofire/pull/2921).

#### Updated

- All internal `Result` usage to use the fully qualified type instead of `AFResult`.
  - Updated by [philtre](https://github.com/philtre) in Pull Request [#2891](https://github.com/Alamofire/Alamofire/pull/2891).
- `DataRequest` and `DownloadRequest` functional API, renaming `flatMap` to `tryMap`.
  - Updated by [philtre](https://github.com/philtre) in Pull Request [#2892](https://github.com/Alamofire/Alamofire/pull/2892).
- `HTTPMethod` to be a struct rather than an enum.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#2901](https://github.com/Alamofire/Alamofire/pull/2901).
- All errors produced by Alamofire to be `AFError` by default. All responses will now start with an `AFError` `Failure` type.
  - Updated by [philtre](https://github.com/philtre) in Pull Request [#2893](https://github.com/Alamofire/Alamofire/pull/2893).
- `NetworkReachabilityManager` to simplify and modernize its API.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#2915](https://github.com/Alamofire/Alamofire/pull/2915).
- `Usage.md` documentation to be fully up-to-date with Alamofire 5.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#2895](https://github.com/Alamofire/Alamofire/pull/2895).
- Bundle identifiers to include the platform name, fixing ITMS-90806.
  - Updated by [Jonathan](https://github.com/JonMo) in Pull Request [#2928](https://github.com/Alamofire/Alamofire/pull/2928).

#### Fixed

- Thread-safety issue with serialization queue usage.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#2885](https://github.com/Alamofire/Alamofire/pull/2885).

## [5.0.0-beta.7](https://github.com/Alamofire/Alamofire/releases/tag/5.0.0-beta.7)

Released on 2019-07-29. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/57?closed=1). **Note:** Alamofire will not be following semantic versioning during the beta process. There may be breaking changes until 5.0.0 is released.

#### Added

- `URLEncodedFormEncoder.DataEncoding` and `URLEncodedFormEncoder.KeyEncoding` to customize the encoding of `Data` and `CodingKeys` in `URLEncodedFormEncoder`.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2858](https://github.com/Alamofire/Alamofire/pull/2858).
- Asynchronous `cURLDescription` method to produce `cURL` commands for `Request`s which are in the process of creating their initial `URLRequest`.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2863](https://github.com/Alamofire/Alamofire/pull/2863).

#### Updated

- All inline API documentation.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#2845](https://github.com/Alamofire/Alamofire/pull/2845).
- Handling of response serializers appended after a `Request` has completed. This no longer produces an error but will instead trigger the normal `Request` lifetime methods.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request [#2862](https://github.com/Alamofire/Alamofire/pull/2862).

#### Fixed

- Empty parameters being encoded as an empty `String` instead of `nil` by `URLEncodedFormEncoder`.
  - Fixed by [David Barry](https://github.com/DavidBarry) in Pull Request [#2818](https://github.com/Alamofire/Alamofire/pull/2818).
- Handling of `os_unfair_lock` to prevent rare crash.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#2836](https://github.com/Alamofire/Alamofire/pull/2836).

## [5.0.0-beta.6](https://github.com/Alamofire/Alamofire/releases/tag/5.0.0-beta.6)

Released on 2019-04-23. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/56?closed=1). **Note:** Alamofire will not be following semantic versioning during the beta process. There may be breaking changes until 5.0.0 is released.

#### Updated

- `ServerTrustEvaluation` logic by simplifying public key equality checks for `SecKey` types.
  - Updated by [Aleksandar Vacić](https://github.com/radianttap) in Pull Request [#2800](https://github.com/Alamofire/Alamofire/pull/2800).
- `Request.State` access to lock access and task updates using internal locking API.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#2814](https://github.com/Alamofire/Alamofire/pull/2814).

#### Fixed

- Issues in `DownloadRequest` where some events were being duplicated and some were missing.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#2807](https://github.com/Alamofire/Alamofire/pull/2807).
- Issue with AppStore submissions where the pre-release version in the bundle short versions string was being rejected when built with Carthage or as a submodule.
  - Fixed by [Christian Noon](https://github.com/cnoon) in Pull Request [#2808](https://github.com/Alamofire/Alamofire/pull/2808).
- Issue where response serializer completions were not called when appended to a completed `Request`.
  - Fixed by [Christian Noon](https://github.com/cnoon) in Pull Request [#2810](https://github.com/Alamofire/Alamofire/pull/2810).

## [5.0.0-beta.5](https://github.com/Alamofire/Alamofire/releases/tag/5.0.0-beta.5)

Released on 2019-04-12. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/55). **Note:** Alamofire will not be following semantic versioning during the beta process. There may be breaking changes until 5.0.0 is released.

#### Added

- `Request.didResumeTaskNotification`, `Request.didSuspendTaskNotification`, `Request.didCancelTaskNotification`, and `Request.didCompleteTaskNotification` notifications.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request [#2803](https://github.com/Alamofire/Alamofire/pull/2803).
- Separate `URLSessionTask` lifetime events to `EventMonitor`.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2796](https://github.com/Alamofire/Alamofire/pull/2796).

#### Updated

- `SessionStateProvider` to no longer be `public` and renamed the file it lives in.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request [#2801](https://github.com/Alamofire/Alamofire/pull/2801).
- `MultipartUpload` to no longer be `public`.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request [#2805](https://github.com/Alamofire/Alamofire/pull/2805).
- `Request`, `DataRequest`, `UploadRequest`, and `DownloadRequest` to longer be `open`, as Alamofire does not support subclassing these types.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request [#2804](https://github.com/Alamofire/Alamofire/pull/2804).
- Names of the notifications posted by `Request` to include `Notification`.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request [#2803](https://github.com/Alamofire/Alamofire/pull/2803).
- `httpHeaders` extensions on `URLRequest`, `HTTPURLResponse`, and `URLSessionConfiguration` to be `headers` instead.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request [#2802](https://github.com/Alamofire/Alamofire/pull/2802).

#### Fixed

- Issue in `Request` where calling `cancel()` inside a response serializer would result in the serializer running again.
  - Fixed by [Christian Noon](https://github.com/cnoon) in Pull Request [#2778](https://github.com/Alamofire/Alamofire/pull/2778).
- Issue in `Session` where the delegate `precondition` would be triggered when running with a swizzled `URLSessionDelegate`.
  - Fixed by [Christian Noon](https://github.com/cnoon) in Pull Request [#2783](https://github.com/Alamofire/Alamofire/pull/2783).
- Compiler error in the example app.
  - Fixed by [Christian Noon](https://github.com/cnoon) in Pull Request [#2786](https://github.com/Alamofire/Alamofire/pull/2786).
- Issues `Request` where certain lifetime events could be triggered more than once by repeatedly calling `resume()`, `suspend()`, or `cancel()`.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#2796](https://github.com/Alamofire/Alamofire/pull/2796) in Regards to Issue [#2759](https://github.com/Alamofire/Alamofire/issues/2759).
- Framework version string to be compatible with TestFlight and AppStore releases.
  - Fixed by [Christian Noon](https://github.com/cnoon) in Pull Request [#2799](https://github.com/Alamofire/Alamofire/pull/2799) in Regards to Issue [#2797](https://github.com/Alamofire/Alamofire/issues/2797).

## [5.0.0-beta.4](https://github.com/Alamofire/Alamofire/releases/tag/5.0.0-beta.4)

Released on 2019-03-29. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A5.0.0-beta.4). **Note:** Alamofire will not be following semantic versioning during the beta process. There may be breaking changes until 5.0.0 is released.

#### Added

- The `AlamofireExtended` protocol and used it to namespace all public extensions.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2758](https://github.com/Alamofire/Alamofire/pull/2758).
- The ability to retry requests after encountering response serialization errors.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request [#2716](https://github.com/Alamofire/Alamofire/pull/2716).

#### Updated

- The `switch` and `DispatchQueue` logic throughout codebase to simplify usage patterns.
  - Updated by [Joan Disho](https://github.com/jdisho) and [Christian Noon](https://github.com/cnoon) in Pull Requests [#2691](https://github.com/Alamofire/Alamofire/pull/2691) and [#2765](https://github.com/Alamofire/Alamofire/pull/2765).
- The `MultipartFormData` data APIs by condensing them using optional parameters.
  - Updated by [Ernesto Rivera](https://github.com/rivera-ernesto) in Pull Request [#2766](https://github.com/Alamofire/Alamofire/pull/2766).
- The upload APIs for `MultipartFormData` to support custom boundaries.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request [#2764](https://github.com/Alamofire/Alamofire/pull/2764).
- The Xcode project, source code, SPM package, and podspec to support Swift 5 only.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request [#2771](https://github.com/Alamofire/Alamofire/pull/2771).
- The Alamofire `Result` type to be a new `AFResult` typealias on the new `Swift.Result` type in Swift 5 and removed all public extensions.
  - Updated by [Dave Camp](https://github.com/AtomicCat), [Eric Jensen](https://github.com/ejensen), and [Christian Noon](https://github.com/cnoon) in Pull Requests [#2769](https://github.com/Alamofire/Alamofire/pull/2769) and [#2774](https://github.com/Alamofire/Alamofire/pull/2774).

#### Fixed

- Issue in `RequestInterceptor` closures where callback arguments were not marked as `@escaping`.
  - Fixed by [Scott Talbot](https://github.com/cysp) in Pull Request [#2747](https://github.com/Alamofire/Alamofire/pull/2747).
- Issue in response serializers where `emptyResponseAllowed` logic was not working as expected.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#2772](https://github.com/Alamofire/Alamofire/pull/2772) in Regards to Issue [#2770](https://github.com/Alamofire/Alamofire/issues/2770).

## [5.0.0-beta.3](https://github.com/Alamofire/Alamofire/releases/tag/5.0.0-beta.3)

Released on 2019-01-07. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A5.0.0-beta.3). **Note:** Alamofire will not be following semantic versioning during the beta process. There may be breaking changes until 5.0.0 is released.

#### Added

- The `EmptyResponse` protocol, to allow any type to provides values to stand in for an empty response.
  - Added by [James Van Noord](https://github.com/jvannoord) in Pull Request [#2664](https://github.com/Alamofire/Alamofire/pull/2664).
- Request and response bodies to `Request`'s `debugDescription`.
  - Added by [rain2540](https://github.com/rain2540) in Pull Request [#2700](https://github.com/Alamofire/Alamofire/pull/2700).

#### Updated

- `Package.swift` for Swift 5 support, moving Swift 4.2 support to `Package@swift-4.2.swift`.
  - Updated by [Mattt](https://github.com/mattt) in Pull Requests [#2737](https://github.com/Alamofire/Alamofire/pull/2737) and [#2736](https://github.com/Alamofire/Alamofire/pull/2736).
- Use of `Array` to `Range` in `Request`'s default `acceptableResponseCodes`.
  - Updated by [StevenArmandLee](https://github.com/StevenArmandLee) in Pull Request [#2720](https://github.com/Alamofire/Alamofire/pull/2720).
- `RetryPolicy` to allow subclasses to override `retry(_:, for: Session, dueTo:, completion:)`.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request [#2713](https://github.com/Alamofire/Alamofire/pull/2713).
- Alamofire's `didResume` notification to `didFinish`, which is now called when a `Request` finished, not when tasks resume.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#2728](https://github.com/Alamofire/Alamofire/pull/2728).

#### Fixed

- `Request`s not finishing when their controlling `Session` is `deinit`d or invalidated.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#2728](https://github.com/Alamofire/Alamofire/pull/2728).
- Memory leak when using `validate()` due to reference cycle from implicit `self` capture when using an `@autoclosure`.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#2728](https://github.com/Alamofire/Alamofire/pull/2728).
- Crash when using `requestDidParseAnyResponse` when using `ClosureEventMonitor`.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#2740](https://github.com/Alamofire/Alamofire/pull/2740).
- `RetryPolicy` to properly conform to `RequestInterceptor`.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#2739](https://github.com/Alamofire/Alamofire/pull/2739).
- Typos in documentation.
  - Fixed by [Łukasz Mróz](https://github.com/sunshinejr), [Jacob Wood](https://github.com/jacoblukewood), [Paulo Henrique](https://github.com/Cardoso222), and [Todd Lahtinen](https://github.com/toddlahtinen0) in Pull Requests [#2715](https://github.com/Alamofire/Alamofire/pull/2715), [#2725](https://github.com/Alamofire/Alamofire/pull/2725), [#2729](https://github.com/Alamofire/Alamofire/pull/2729), and [#2697](https://github.com/Alamofire/Alamofire/pull/2697).

## [5.0.0-beta.2](https://github.com/Alamofire/Alamofire/releases/tag/5.0.0-beta.2)

Released on 2019-01-07. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A5.0.0-beta.2). **Note:** Alamofire will not be following semantic versioning during the beta process. There may be breaking changes until 5.0.0 is released.

#### Added

- Support for controlling redirect behavior per `Session` and per `Request` using the `RedirectHandler` protocol.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request [#2699](https://github.com/Alamofire/Alamofire/pull/2699).
- Support for controlling cached response behavior per `Session` and per `Request` using the `CachedResponseHandler` protocol.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request [#2701](https://github.com/Alamofire/Alamofire/pull/2701).
- Support for controlling retry behavior per `Session` and per `Request` using the `RequestInterceptor` protocol.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request [#2704](https://github.com/Alamofire/Alamofire/pull/2704) in regards to Issue [#2241](https://github.com/Alamofire/Alamofire/issues/2241).
- The `Adapter`, `Retrier`, and `Interceptor` types to provide fine grained control of retry behavior.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request [#2704](https://github.com/Alamofire/Alamofire/pull/2704).
- Support for exponential backoff retry policies through the new `RetryPolicy` and `ConnectionLostRetryPolicy` types.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request [#2704](https://github.com/Alamofire/Alamofire/pull/2704).

#### Updated

- The `RequestRetrier` protocol to take a `RetryResult` in the `completion` closure allowing custom retry errors to be thrown.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request [#2704](https://github.com/Alamofire/Alamofire/pull/2704).
- The `Hashable` implementation on `Request` to use new `hash(into:)` API.
  - Updated by [Jeff Kelley](https://github.com/SlaunchaMan) in Pull Request [#2696](https://github.com/Alamofire/Alamofire/pull/2696).

## [5.0.0-beta.1](https://github.com/Alamofire/Alamofire/releases/tag/5.0.0-beta.1)

Released on 2018-12-06. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A5.0.0.beta-1). **Note:** Alamofire will not be following semantic versioning during the beta process. There may be breaking changes until 5.0.0 is released.

#### Added

- Support for `Decodable` response serialization with `responseDecodable`.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Requests [#2265](https://github.com/Alamofire/Alamofire/pull/2265) and [#2657](https://github.com/Alamofire/Alamofire/pull/2657).
- Support for Brotli `Content-Encoding` in Alamofire's default headers.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2346](https://github.com/Alamofire/Alamofire/pull/2346).
- `HTTPHeaders` type and convenience APIs.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2629](https://github.com/Alamofire/Alamofire/pull/2629).
- Support for `Encodable` parameter types with `JSONParameterEncoder` and `URLEncodedFormParameterEncoder`.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2637](https://github.com/Alamofire/Alamofire/pull/2637).
- Customizable empty response handling in response serializers.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2639](https://github.com/Alamofire/Alamofire/pull/2639).
- `EventMonitor` protocol, to tap in to internal Alamofire lifetime events.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2521](https://github.com/Alamofire/Alamofire/pull/2521).
- `ServerTrustFailureReason` to `AFError`.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2608](https://github.com/Alamofire/Alamofire/pull/2608).
- Asynchronous request creation.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2521](https://github.com/Alamofire/Alamofire/pull/2521).

#### Updated

- `ResponseSerializer` and associated protocols' requirements and implementations.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Requests [#2265](https://github.com/Alamofire/Alamofire/pull/2265) and [#2639](https://github.com/Alamofire/Alamofire/pull/2639).
- `RequestAdapter` to allow for asynchronous adaptation.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#2628](https://github.com/Alamofire/Alamofire/pull/2628) .
- `SessionManager` to `Session`, with rewritten implementation and API.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#2521](https://github.com/Alamofire/Alamofire/pull/2521).
- `Request`, `DataRequest`, `UploadRequest`, and `DownloadRequest` with rewritten implementation and API.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#2521](https://github.com/Alamofire/Alamofire/pull/2521).
- Top level `request` API to be inside a real `AF` namespace enum rather than unnecessary `Alamofire.` usage.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#2585](https://github.com/Alamofire/Alamofire/pull/2585).

#### Removed

- Support for iOS < 10, macOS < 10.12, tvOS < 10, watchOS < 3.
  - Removed by [Jon Shier](https://github.com/jshier) in Pull Requests [#2254](https://github.com/Alamofire/Alamofire/pull/2254) and [#2521](https://github.com/Alamofire/Alamofire/pull/2521).
- Support for `PropertyListSerialization` and `responsePropertyList`.
  - Removed by [Jon Shier](https://github.com/jshier) in Pull Request [#2265](https://github.com/Alamofire/Alamofire/pull/2265).
- Support for `URLSessionStreamTask`.
  - Removed by [Jon Shier](https://github.com/jshier) in Pull Request [#2521](https://github.com/Alamofire/Alamofire/pull/2521).
- Closure override and customization API.
  - Removed by [Jon Shier](https://github.com/jshier) in Pull Request [#2521](https://github.com/Alamofire/Alamofire/pull/2521).
- `Timeline` type, as Alamofire now gathers `URLSessionTaskMetrics` for every request.
  - Removed by [Jon Shier](https://github.com/jshier) in Pull Request [#2521](https://github.com/Alamofire/Alamofire/pull/2521).

---

## [4.9.1](https://github.com/Alamofire/Alamofire/releases/tag/4.9.1)

Released on 2019-10-26. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/milestone/61?closed=1).

#### Added

- Support for GitHub Actions for CI.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request [#2979](https://github.com/Alamofire/Alamofire/pull/2979).

#### Updated

- `DataResponse` and `DownloadResponse` `debugDescription` to include more useful information.
  - Updated by [rain2540](https://github.com/rain2540) in Pull Request [#2976](https://github.com/Alamofire/Alamofire/pull/2976).

#### Fixed

- Dynamic bundle identifier causing issues with Xcode and precompiled binaries by removing the dynamic behavior.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#2967](https://github.com/Alamofire/Alamofire/pull/2967).
- Compiler warnings when building for Catalyst by updating the usage of deprecated API.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#2979](https://github.com/Alamofire/Alamofire/pull/2979).

## [4.9.0](https://github.com/Alamofire/Alamofire/releases/tag/4.9.0)

Released on 2019-09-03. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.9.0).

#### Added

- API to cancel `DownloadRequest`s without producing resume data.
  - Added by [ullstrm](https://github.com/ullstrm) in Pull Request [#2851](https://github.com/Alamofire/Alamofire/pull/2851).

#### Updated

- Bundle identifiers to include the platform name, fixing ITMS-90806.
  - Updated by [Jonathan](https://github.com/JonMo) in Pull Request [#2930](https://github.com/Alamofire/Alamofire/pull/2930).

#### Fixed

- `NetworkReachabilityManager` behavior regression from 4.8.1.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#2931](https://github.com/Alamofire/Alamofire/pull/2931).
- Memory leak when using `validate()`.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request [#2931](https://github.com/Alamofire/Alamofire/pull/2931).

## [4.8.2](https://github.com/Alamofire/Alamofire/releases/tag/4.8.2)

Released on 2019-03-27. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.8.2).

#### Updated

- Project for compatibility with Xcode 10.2.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#2767](https://github.com/Alamofire/Alamofire/pull/2767).
- MultipartFormData to have a mutable boundary.
  - Updated by [Ondrej Stocek](https://github.com/ondrejstocek) in Pull Request [#2705](https://github.com/Alamofire/Alamofire/pull/2705).

#### Fixed

- Compatibility with SPM from Xcode 10.2.
  - Fixed by [Klaas](https://github.com/klaas) in Pull Request [#2762](https://github.com/Alamofire/Alamofire/pull/2762).

## [4.8.1](https://github.com/Alamofire/Alamofire/releases/tag/4.8.1)

Released on 2019-01-15. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.8.1).

#### Fixed

- Issue where the network reachability listener closure was not being called immediately when launching an app in airplane mode.
  - Fixed by [Christian Noon](https://github.com/cnoon) in Pull Request [#2688](https://github.com/Alamofire/Alamofire/pull/2688) regards to Issues [#2275](https://github.com/Alamofire/Alamofire/issues/2275) and [#2677](https://github.com/Alamofire/Alamofire/issues/2677).

## [4.8.0](https://github.com/Alamofire/Alamofire/releases/tag/4.8.0)

Released on 2018-11-24. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.8.0).

#### Added

- Optional encoding completion callback queue for multipart upload.
  - Added by [jaltreuter](https://github.com/jaltreuter) in Pull Request [#2620](https://github.com/Alamofire/Alamofire/pull/2620).
- Versioned Swift package manifests.
  - Added by [Wanbok Choi (Wayne)](https://github.com/wanbok) in Pull Request [#2621](https://github.com/Alamofire/Alamofire/pull/2621) and [Jon Shier](https://github.com/jshier) in Pull Request [#2648](https://github.com/Alamofire/Alamofire/pull/2648).

#### Updated

- Project Swift version to 4.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#2648](https://github.com/Alamofire/Alamofire/pull/2648).
- Various `Result` methods to be `throw`/`rethrows`.
  - Updated by [Stéphane Copin](https://github.com/stephanecopin) in Pull Request [#2488](https://github.com/Alamofire/Alamofire/pull/2488).
- cURL representation implementation readability.
  - Updated by [Giulio](https://github.com/giulio92) in Pull Request [#2625](https://github.com/Alamofire/Alamofire/pull/2625).

---

## [4.7.3](https://github.com/Alamofire/Alamofire/releases/tag/4.7.3)

Released on 2018-7-8. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.7.3).

#### Updated

- Project for Xcode 10 and Swift 4.2 beta versions.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#2552](https://github.com/Alamofire/Alamofire/pull/2552).
- Documentation styling and content.
  - Updated by [Constantin Lungu](https://github.com/nemesis) in Pull Request [#2505](https://github.com/Alamofire/Alamofire/pull/2505), [Xing He](https://github.com/kukushi) in Pull Request [#2484](https://github.com/Alamofire/Alamofire/pull/2484), and [Karim](https://github.com/karimhm) in Pull Request [#2550](https://github.com/Alamofire/Alamofire/pull/2550).

## [4.7.2](https://github.com/Alamofire/Alamofire/releases/tag/4.7.2)

Released on 2018-4-15. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.7.2).

#### Fixed

- Leak of `Requests` after retry.
  - Fixed by [Artem Shimankski](https://github.com/mrdepth) in Pull Request [#2412](https://github.com/Alamofire/Alamofire/pull/2412).

## [4.7.1](https://github.com/Alamofire/Alamofire/releases/tag/4.7.1)

Released on 2018-3-31. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.7.1).

#### Updated

- Project for Xcode 9.3 and Swift 4.1 release versions.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#2473](https://github.com/Alamofire/Alamofire/pull/2473).

#### Fixed

- Quote escaping in cURL representation.
  - Fixed by [Jonah](https://github.com/jonah-williams) in Pull Request [#2474](https://github.com/Alamofire/Alamofire/pull/2474).

## [4.7.0](https://github.com/Alamofire/Alamofire/releases/tag/4.7.0)

Released on 2018-3-5. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.7.0).

#### Added

- Open accessibility to `NetworkReachabilityManager`
  - Added by [Pär Strindevall](https://github.com/parski) in Pull Request [#2393](https://github.com/Alamofire/Alamofire/pull/2393).
- Configurable parameter encoding for `URLEncoding`
  - Added by [Morten Heiberg](https://github.com/heiberg) in Pull Request [#2431](https://github.com/Alamofire/Alamofire/pull/2431).
- Response `Data` to `.DidComplete` notification.
  - Added by [Sven Driemecker](https://github.com/svendr) in Pull Request [#2427](https://github.com/Alamofire/Alamofire/pull/2427).
- Radar link for `URLSessionTaskMetrics` bug on watchOS.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request [#2387](https://github.com/Alamofire/Alamofire/pull/2387).

#### Updated

- Project for Xcode 9.3 and Swift 4.1.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request [#2441](https://github.com/Alamofire/Alamofire/pull/2441).
- OS versions affected by resume data bug.
  - Updated by [Aaron Brager](https://github.com/getaaron) in Pull Request [#2389](https://github.com/Alamofire/Alamofire/pull/2389).

#### Fixed

- Typos in `ResultTests`.
  - Fixed by [Aleph Retamal](https://github.com/alaphao) in Pull Request [#2416](https://github.com/Alamofire/Alamofire/pull/2416).

---

## [4.6.0](https://github.com/Alamofire/Alamofire/releases/tag/4.6.0)

Released on 2017-12-3. All issues associated with this milestone can be found using this [filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.6.0).

#### Added

- Error mapping functions to `Response` types.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request
    [#2361](https://github.com/Alamofire/Alamofire/pull/2361).
- Separation of Usage and Advanced Usage docs from README.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request
    [#2360](https://github.com/Alamofire/Alamofire/pull/2360).

#### Updated

- Travis CI and Ruby dependencies.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Requests
    [#2361](https://github.com/Alamofire/Alamofire/pull/2361), [#2302](https://github.com/Alamofire/Alamofire/pull/2302), [#2345](https://github.com/Alamofire/Alamofire/pull/2345).
- Swift Package Manager instructions.
  - Updated by [Ryosuke Hayashi](https://github.com/hayashikun) in Pull Request
    [#2341](https://github.com/Alamofire/Alamofire/pull/2341).

#### Fixed

- `#session-manager` link in Advanced Usage docs.
  - Fixed by [Naeem Shaikh](https://github.com/naeemshaikh90) in Pull Request
    [#2373](https://github.com/Alamofire/Alamofire/pull/2373).
- Missing `@discardableResult`.
  - Fixed by [Aron Cedercrantz](https://github.com/rastersize) in Pull Request
    [#2338](https://github.com/Alamofire/Alamofire/pull/2338).
- Colon placement.
  - Fixed by [Issarapong Poesua](https://github.com/Dekablade01) in Pull Request
    [#2329](https://github.com/Alamofire/Alamofire/pull/2329).

---

## [4.5.1](https://github.com/Alamofire/Alamofire/releases/tag/4.5.1)

Released on 2017-09-06. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.5.1).

#### Added

- GitHub templates for issues and pull requests.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request
    [#2179](https://github.com/Alamofire/Alamofire/pull/2179).
- Jazzy docs for the release to work with GitHub Pages.
  - Added by [Aaron McTavish](https://github.com/aamctustwo) in Pull Request
    [#2250](https://github.com/Alamofire/Alamofire/pull/2250).
- Dash support for Jazzy docs.
  - Added by [Jon Shier](https://github.com/jshier).

#### Updated

- The project to work with Xcode 9 beta 6 on Swift 3.2 and 4.0.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request
    [#2198](https://github.com/Alamofire/Alamofire/pull/2198).
- The Travis CI config to work with Xcode 9 beta 6.
  - Updated by [Jon Shier](https://github.com/jshier).
- The cURL representation logic to no longer force unwrap `URLCredential` values.
  - Updated by [Andrey Chernoprudov](https://github.com/achernoprudov) in Pull Request
    [#2184](https://github.com/Alamofire/Alamofire/pull/2184).
- The radars section of the README to split out open vs. resolved radars.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#2263](https://github.com/Alamofire/Alamofire/pull/2263).
- The installation section of the README to use the current version.
  - Updated by [Kim de Vos](https://github.com/kimdv) in Pull Request
    [#2266](https://github.com/Alamofire/Alamofire/pull/2266).

#### Fixed

- Issue in `TaskDelegate` where task access was not thread safe.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request
    [#2190](https://github.com/Alamofire/Alamofire/pull/2190).
- Issue in AF 4 migration guide where supported iOS versions was incorrect.
  - Fixed by [Antoine Cœur](https://github.com/Coeur) in Pull Request
    [#2212](https://github.com/Alamofire/Alamofire/pull/2212).
- Issue in README sample code where PNG representation API was incorrect.
  - Fixed by [Andy Ron](https://github.com/andyRon) in Pull Request
    [#2244](https://github.com/Alamofire/Alamofire/pull/2244).
- Swift 3.2+ API warnings for `substring` APIs.
  - Fixed by [htinlinn](https://github.com/htinlinn) in Pull Request
    [#2240](https://github.com/Alamofire/Alamofire/pull/2240).

## [4.5.0](https://github.com/Alamofire/Alamofire/releases/tag/4.5.0)

Released on 2017-06-16. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.5.0).

#### Added

- Missing `@escaping` annotation for session delegate closures.
  - Added by [Alexey Aleshkov](https://github.com/djmadcat) in Pull Request
    [#1951](https://github.com/Alamofire/Alamofire/pull/1951).
- New `mapError`, `flatMapError`, `withValue`, `withError`, `ifSuccess`, and `ifFailure` APIs to `Result`.
  - Added by [Jon Shier](https://github.com/jshier) in Pull Request
    [#2135](https://github.com/Alamofire/Alamofire/pull/2135).

#### Updated

- The Travis config file to Xcode 8.3.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request
    [#2059](https://github.com/Alamofire/Alamofire/pull/2059).
- Response serialization implementation to use separate internal variable.
  - Updated by [Eunju Amy Sohn](https://github.com/EJSohn) in Pull Request
    [#2125](https://github.com/Alamofire/Alamofire/pull/2125).
- `SessionDelegate` internal implementation by removing redundant optional unwrap.
  - Updated by [Boris Dušek](https://github.com/dusek) in Pull Request
    [#2056](https://github.com/Alamofire/Alamofire/pull/2056).
- The `debugPrintable` implementation of `Request` to use `curl -v` instead of `curl -i` to be more verbose.
  - Updated by [Simon Warta](https://github.com/webmaster128) in Pull Request
    [#2070](https://github.com/Alamofire/Alamofire/pull/2070).
- The `MultipartFormData` contentType property to be mutable.
  - Updated by [Eric Desa](https://github.com/ericdesa) in Pull Request
    [#2072](https://github.com/Alamofire/Alamofire/pull/2072).
- Travis CI yaml file to enable watchOS 3.2 builds.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request
    [#2135](https://github.com/Alamofire/Alamofire/pull/2135).
- Alamofire to build with Xcode 9 with Swift 3.2 and 4.0 in addition to Xcode 8.3 and Swift 3.1.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request
    [#2163](https://github.com/Alamofire/Alamofire/pull/2163).

#### Removed

- Custom string extension no longer needed in the test suite.
  - Removed by [Nicholas Maccharoli](https://github.com/Nirma) in Pull Request
    [#1994](https://github.com/Alamofire/Alamofire/pull/1994).

#### Fixed

- Issue in the `URLProtocolTestCase` where HTTP header capitalization was wrong due to httpbin.org change.
  - Fixed by [Natascha Fadeeva](https://github.com/Tanaschita) in Pull Request
    [#2025](https://github.com/Alamofire/Alamofire/pull/2025).
- Issues and typos throughout the README documentation and sample code and source code docstrings.
  - Fixed by
    [Raphael R.](https://github.com/reitzig),
    [helloyako](https://github.com/helloyako),
    [DongHyuk Kim](https://github.com/sss989870),
    [Bas Broek](https://github.com/BasThomas),
    [Jorge Lucena](https://github.com/jorgifumi),
    [MasahitoMizogaki](https://github.com/MMizogaki),
    [José Manuel Sánchez](https://github.com/buscarini),
    [SabinLee](https://github.com/SabinLee),
    [Mat Trudel](https://github.com/mtrudel),
    [Wolfgang Lutz](https://github.com/Lutzifer), and
    [Christian Noon](https://github.com/cnoon) in Pull Requests
    [#1995](https://github.com/Alamofire/Alamofire/pull/1995),
    [#1997](https://github.com/Alamofire/Alamofire/pull/1997),
    [#1998](https://github.com/Alamofire/Alamofire/pull/1998),
    [#2022](https://github.com/Alamofire/Alamofire/pull/2022),
    [#2031](https://github.com/Alamofire/Alamofire/pull/2031),
    [#2035](https://github.com/Alamofire/Alamofire/pull/2035),
    [#2080](https://github.com/Alamofire/Alamofire/pull/2080),
    [#2081](https://github.com/Alamofire/Alamofire/pull/2081),
    [#2092](https://github.com/Alamofire/Alamofire/pull/2092),
    [#2095](https://github.com/Alamofire/Alamofire/pull/2095),
    [#2104](https://github.com/Alamofire/Alamofire/pull/2104).
- Several warnings in the test suite related to Xcode 8.3.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request
    [#2057](https://github.com/Alamofire/Alamofire/pull/2057).
- Issue where reachability calculation incorrectly reported `.reachable` status with [`.connectionRequired`, `.isWWAN`] combination.
  - Fixed by [Marco Santarossa](https://github.com/MarcoSantarossa) in Pull Request
    [#2060](https://github.com/Alamofire/Alamofire/pull/2060).

---

## [4.4.0](https://github.com/Alamofire/Alamofire/releases/tag/4.4.0)

Released on 2017-02-26. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.4.0).

#### Added

- A new `Alamofire/Alamofire` Gitter channel and also added badge to the README.
  - Added by [Christian Noon](https://github.com/cnoon).
- Functional extensions for Result, Data and Download Response.
  - Added by [Gwendal Roué](https://github.com/groue) in Pull Request
    [#1836](https://github.com/Alamofire/Alamofire/pull/1836).

### Fixed

- Typo in the README in the Swift Package Manager section.
  - Fixed by [Sebastian Limbach](https://github.com/bastilimbach) in Pull Request
    [#1918](https://github.com/Alamofire/Alamofire/pull/1918).
- Issue in the "Modifying the Session Configuration" example code of the README where the
  `defaultHTTPHeaders` property was called incorrectly.
  - Fixed by [Artur Antonov](https://github.com/goingreen) in Pull Request
    [#1927](https://github.com/Alamofire/Alamofire/pull/1927).
- Issue in the "Security" section of the README where some example code was outdated.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request
    [#1973](https://github.com/Alamofire/Alamofire/pull/1973).
- Issue in the README where the POST request with parameters example was using the wrong method.
  - Fixed by [Pablo Bartolome](https://github.com/pbartolome) in Pull Request
    [#1984](https://github.com/Alamofire/Alamofire/pull/1984).
- Issue where `taskDidComplete` override closure was not calling task delegate leading to
  potential memory leaks.
  - Fixed by [Jon Shier](https://github.com/jshier) in regards to Issue
    [#1938](https://github.com/Alamofire/Alamofire/pull/1938).

---

## [4.3.0](https://github.com/Alamofire/Alamofire/releases/tag/4.3.0)

Released on 2017-01-15. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.3.0).

#### Added

- The host and path to router example in README.
  - Added by [Michael](https://github.com/muescha) in Pull Request
    [#1830](https://github.com/Alamofire/Alamofire/pull/1830).
- A `macOS` disclaimer to download request example in README.
  - Added by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#1818](https://github.com/Alamofire/Alamofire/issues/1818).
- New `value` and `error` computed properties to data and download responses.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull request
    [#1865](https://github.com/Alamofire/Alamofire/pull/1865).
- The HTTP method to the data and download response debug descriptions.
  - Added by [Jon Shier](https://github.com/jshier) in Pull request
    [#1880](https://github.com/Alamofire/Alamofire/pull/1880).
- A README entry about installing through SPM.
  - Added by [Jon Shier](https://github.com/jshier) in Pull request
    [#1898](https://github.com/Alamofire/Alamofire/pull/1898).
- The `dependencies` parameter to `Package` file for SPM since it's now required.
  - Added by [Arnaldo Capo](https://github.com/cyberdude) in Pull request
    [#1905](https://github.com/Alamofire/Alamofire/pull/1905).
- TLS evaluation tests for revoked certs for no policy and default policy.
  - Added by [Christian Noon](https://github.com/cnoon).
- New server trust policy for revoked certificates along with matching tests.
  - Added by [Wataru Suzuki](https://github.com/WataruSuzuki) in Pull request
    [#1822](https://github.com/Alamofire/Alamofire/pull/1822).

#### Updated

- Project to Xcode 8.2 recommend settings.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull request
    [#1854](https://github.com/Alamofire/Alamofire/pull/1854).
- The `NetworkReachabilityManager` to have a `public` instead of `open` ACL.
  - Updated by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#1809](https://github.com/Alamofire/Alamofire/issues/1809).
- The initializers for both default responses public and added metrics parameter.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1865](https://github.com/Alamofire/Alamofire/pull/1865).
- Internals by replacing `syncResult` extension with DispatchQueue `sync`.
  - Updated by [Alexander Ignition](https://github.com/Alexander-Ignition) in Pull Request
    [#1893](https://github.com/Alamofire/Alamofire/pull/1893).
- TLS tests for tvOS 10.1 and added expiration test for revoked evaluation.
  - Updated by [Christian Noon](https://github.com/cnoon).

#### Fixed

- `DownloadRequest` sample code issue in AF 4 migration guide.
  - Fixed by [Luca Torella](https://github.com/lucatorella) in Pull Request
    [#1802](https://github.com/Alamofire/Alamofire/pull/1802).
- `URLConvertible` compiler issue in the README example.
  - Fixed by [Wu Zhong](https://github.com/zhongwuzw) in Pull Request
    [#1844](https://github.com/Alamofire/Alamofire/pull/1844).
- An invalid comment in AF 4 migration guide.
  - Fixed by [Tom Brow](https://github.com/brow) in Pull Request
    [#1863](https://github.com/Alamofire/Alamofire/pull/1863).
- An issue where the `SessionManager` did not respect retry time delay.
  - Fixed by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1864](https://github.com/Alamofire/Alamofire/pull/1864) in regards to Issue
    [#1853](https://github.com/Alamofire/Alamofire/issues/1853).
- A broken reference link in the README.
  - Fixed by [Ulug'bek Ro'zimboyev](https://github.com/ulugbekrozimboyev) in Pull Request
    [#1866](https://github.com/Alamofire/Alamofire/pull/1866).
- Compiler issues in `RequestAdapter` and `RequestRetrier` examples in README.
  - Fixed by [William Entriken](https://github.com/fulldecent) in Pull Request
    [#1916](https://github.com/Alamofire/Alamofire/pull/1916).

---

## [4.2.0](https://github.com/Alamofire/Alamofire/releases/tag/4.2.0)

Released on 2016-11-20. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.2.0).

#### Added

- Request property overrides to fallback on original task if available.
  - Added by [Aron Cedercrantz](https://github.com/rastersize) in Pull Request
    [#1792](https://github.com/Alamofire/Alamofire/pull/1792).
- `Timeline` generation to `DefaultDataResponse` and `DefaultDownloadResponse`.
  - Added by [Christian Noon](https://github.com/cnoon).
- JSON encoding `encode` method that takes a JSON object along with unit tests.
  - Added by [Christian Noon](https://github.com/cnoon).

#### Updated

- The `RequestRetrier` example in the README to safely extract tokens.
  - Updated by [Pontus Andersson](https://github.com/pontus-andersson) in Pull Request
    [#1794](https://github.com/Alamofire/Alamofire/pull/1794).
- `TaskDelegate` `data` and `error` properties to a `public` ACL.
  - Updated by [Christian Noon](https://github.com/cnoon).
- Multipart form data uploads to now delete temp file if encoding fails.
  - Updated by [Christian Noon](https://github.com/cnoon).

#### Fixed

- Issue where `AdaptError` instances were being incorrectly sent to the `RequestRetrier`.
  - Fixed by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#1785](https://github.com/Alamofire/Alamofire/issues/1785).
- Issue where TLS tests were failing on iOS 10.0 and not on iOS 10.1.
  - Fixed by [Christian Noon](https://github.com/cnoon).

---

## [4.1.0](https://github.com/Alamofire/Alamofire/releases/tag/4.1.0)

Released on 2016-11-15. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.1.0).

#### Added

- Docstrings and a note to the README about `resumeData` and background session behavior.
  - Added by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#1553](https://github.com/Alamofire/Alamofire/issues/1553).
- Request `retryCount` property to support the `RequestRetrier`.
  - Added by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#1672](https://github.com/Alamofire/Alamofire/issues/1672).

#### Updated

- SPM package file to exclude tests since current configuration is not supported.
  - Updated by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#1544](https://github.com/Alamofire/Alamofire/issues/1544).
- An example in the README to use proper error checking in download response handler.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request
    [#1722](https://github.com/Alamofire/Alamofire/pull/1722).
- Embedded framework installation instructions.
  - Updated by [ILI4S K4RIM](https://github.com/ILI4S) in Pull Request
    [#1721](https://github.com/Alamofire/Alamofire/pull/1721).
- The AF4 Migration Guide to no longer use `DispatchQueue` internal APIs in the example.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request
    [#1736](https://github.com/Alamofire/Alamofire/pull/1736).
- The `RequestAdapter` to call the `RequestRetrier` when an `Error` is thrown.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1682](https://github.com/Alamofire/Alamofire/pull/1682).
- The `SessionManager` to clean up the temporary multipart form data file after upload.
  - Updated by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#1742](https://github.com/Alamofire/Alamofire/issues/1742).
- The deployment targets to **iOS 8.0** and **macOS 10.10**.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1774](https://github.com/Alamofire/Alamofire/pull/1774).
- The Travis CI yaml file to support iOS 8 simulators.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1774](https://github.com/Alamofire/Alamofire/pull/1774).
- The iOS Example app deployment target to iOS 8.0.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1774](https://github.com/Alamofire/Alamofire/pull/1774).

#### Removed

- Duplicate auto-code signing on macOS.
  - Removed by [Christian Noon](https://github.com/cnoon)
- Duplicate code signing identities on various targets.
  - Removed by [Christian Noon](https://github.com/cnoon)

#### Fixed

- A compiler error in response validation sample code in the README.
  - Fixed by [Vishrut Shah](https://github.com/vishrutshah) in Pull Request
    [#1615](https://github.com/Alamofire/Alamofire/pull/1615).
- Several internal `SessionManager` links that were broken in the README.
  - Fixed by [Vishrut Shah](https://github.com/vishrutshah) in Pull Request
    [#1625](https://github.com/Alamofire/Alamofire/pull/1625).
- Issue in the sample code of the README where `response.error` was used incorrectly.
  - Fixed by [Bob](https://github.com/bot2600) in Pull Request
    [#1633](https://github.com/Alamofire/Alamofire/pull/1633).
- Issue in the `ServerTrustPolicy` tests where a `macOS 10.12` check was needed.
  - Fixed by [Jon Shier](https://github.com/jshier).
- Compiler issue with `DownloadRequest` in AF4 Migration Guide.
  - Fixed by [Wolfgang Lutz](https://github.com/Lutzifer) in Pull Request
    [#1670](https://github.com/Alamofire/Alamofire/pull/1670).
- Test target compiler warning by not requiring app extension APIs only.
  - Fixed by [Christian Noon](https://github.com/cnoon).
- Typo in the HTTP Headers section of the README.
  - Fixed by [Carlos McEvilly](https://github.com/carlosmcevilly) in Pull Request
    [#1734](https://github.com/Alamofire/Alamofire/pull/1734).
- Incorrect response type in the response README examples.
  - Fixed by [Julien Chaumond](https://github.com/julien-c) in Pull Request
    [#1760](https://github.com/Alamofire/Alamofire/pull/1760).
- Xcode 8.1 compiler warnings and project suggestions.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request
    [#1735](https://github.com/Alamofire/Alamofire/pull/1735).
- Issue where download completion could crash on a `nil` response.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request
    [#1723](https://github.com/Alamofire/Alamofire/pull/1723).
- Issue in TLS tests where root certificate was missing from server trust.
  - Fixed by [Christian Noon](https://github.com/cnoon).

---

## [4.0.1](https://github.com/Alamofire/Alamofire/releases/tag/4.0.1)

Released on 2016-09-24. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.0.1).

#### Added

- The `OS_ACTIVITY_MODE` environment variable to iOS, tvOS and iOS Example.
  - Added by [Christian Noon](https://github.com/cnoon).
- Test verifying download request can be resumed with resume data.
  - Added by [Christian Noon](https://github.com/cnoon).

#### Updated

- All instances of `com.alamofire` with `org.alamofire` throughout the project.
  - Updated by [Christian Noon](https://github.com/cnoon).
- Project by adding `.swift-version` file and re-enabling `pod lib lint` in Travis file.
  - Updated by [Thibault Vlacich](https://github.com/ThibaultVlacich) in Pull Request
    [#1534](https://github.com/Alamofire/Alamofire/pull/1534).
- The entire project to use `macOS` in place of `OS X`.
  - Updated by [Justin Jia](https://github.com/JustinJiaDev) in Pull Request
    [#1520](https://github.com/Alamofire/Alamofire/pull/1520).
- Framework and test target override settings that duplicated the project settings.
  - Updated by [Christian Noon](https://github.com/cnoon).

#### Fixed

- Issue where the test suite was accidentally deleting contents of `~/Library/Application Support`
  on macOS.
  - Fixed by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#1512](https://github.com/Alamofire/Alamofire/issues/1512).
- Typo in the migration guide around availability checks.
  - Fixed by [Alexsander Akers](https://github.com/a2) in Pull Request
    [#1510](https://github.com/Alamofire/Alamofire/pull/1510).
- Typo in the README around response handlers.
  - Fixed by [Glenn R. Fisher](https://github.com/glennrfisher) in Pull Request
    [#1515](https://github.com/Alamofire/Alamofire/pull/1515).
- Issue in the download example in the README where a `to` parameter was missing.
  - Fixed by [Julien Colin](https://github.com/Toldy) in Pull Request
    [#1532](https://github.com/Alamofire/Alamofire/pull/1532).
- Issue in `AFError` where wrong case was used in several property implementations.
  - Fixed by [Victor Chee](https://github.com/victorchee) in Pull Request
    [#1558](https://github.com/Alamofire/Alamofire/pull/1558).
- Typo in AF 4 migration guide where "enhancements" was spelled incorrectly.
  - Fixed by [YeralYamil](https://github.com/YeralYamil) in Pull Request
    [#1590](https://github.com/Alamofire/Alamofire/pull/1590).
- Typo in code sample documentation where "already" was misspelled.
  - Fixed by [Fuad Kamal](https://github.com/abunur) in Pull Request
    [#1599](https://github.com/Alamofire/Alamofire/pull/1599).
- Typos in the Open Radars and Donations sections of README.
  - Fixed by [Brian Lu](https://github.com/bakemecookies) in Pull Request
    [#1606](https://github.com/Alamofire/Alamofire/pull/1606).
- Issue in `DispatchQueue` extension where `Foundation` needed to be imported for submodules.
  - Fixed by [CodeEagle](https://github.com/CodeEagle) in Pull Request
    [#1603](https://github.com/Alamofire/Alamofire/pull/1603).
- Memory leak in `Validation` closures where reference to `self` was causing retain cycle.
  - Fixed by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#1551](https://github.com/Alamofire/Alamofire/issues/1551).
- Compilation issue in response handler section of the README.
  - Fixed by [Vishrut Shah](https://github.com/vishrutshah) in Pull Request
    [#1612](https://github.com/Alamofire/Alamofire/pull/1612).

## [4.0.0](https://github.com/Alamofire/Alamofire/releases/tag/4.0.0)

Released on 2016-09-11. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.0.0).

#### Added

- Internal `DispatchQueue` extension set of convenience properties and methods.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1450](https://github.com/Alamofire/Alamofire/pull/1450).
- `RequestAdapter` and `RequestRetrier` protocols allowing requests to be retried.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1450](https://github.com/Alamofire/Alamofire/pull/1450).
- `RequestAdapter` tests on all testable `SessionManager` request APIs.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1450](https://github.com/Alamofire/Alamofire/pull/1450).
- Added an `Adapting and Retrying Requests` section to the README.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1450](https://github.com/Alamofire/Alamofire/pull/1450).
- `DataRequest`, `DownloadRequest`, `UploadRequest` and `StreamRequest` subclasses.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1455](https://github.com/Alamofire/Alamofire/pull/1455).
- Top-level APIs for creating `StreamRequest` instances.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1455](https://github.com/Alamofire/Alamofire/pull/1455).
- Extra `responseToSelector` overrides for stream delegate APIs.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1455](https://github.com/Alamofire/Alamofire/pull/1455).
- A new `syncResult` extension to `DispatchQueue` to simplify thread-safe locking.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1455](https://github.com/Alamofire/Alamofire/pull/1455).
- Two serialization failure reasons to support download response serializers.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1457](https://github.com/Alamofire/Alamofire/pull/1457).
- Download response serialization tests for all serializer types.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1457](https://github.com/Alamofire/Alamofire/pull/1457).
- The `dataFileNil` and `dataFileReadFailed` cases to `ResponseValidationFailureReason`.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1461](https://github.com/Alamofire/Alamofire/pull/1461).
- The `isWildcard` property to MIMEType struct for convenience.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1461](https://github.com/Alamofire/Alamofire/pull/1461).
- Missing `CustomDebugStringCovertible` conformance to `DownloadResponse`.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1462](https://github.com/Alamofire/Alamofire/pull/1462).
- URL variants to the `FileManager` extension in the test suite.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1462](https://github.com/Alamofire/Alamofire/pull/1462).
- `DownloadOptions` option set to make moving files more robust.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1462](https://github.com/Alamofire/Alamofire/pull/1462).
- Tests validating success and failure scenarios for `DownloadOptions`.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1462](https://github.com/Alamofire/Alamofire/pull/1462).
- Parameter encoding failure docstrings and refactored reasons to be consistent.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1465](https://github.com/Alamofire/Alamofire/pull/1465).
- Safeguards to url parameter encoding when extracting the url request’s url.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1465](https://github.com/Alamofire/Alamofire/pull/1465).
- The new `URLSessionTaskMetrics` to all `Response types`.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1492](https://github.com/Alamofire/Alamofire/pull/1492).
- The Alamofire 4.0 Migration Guide to the README.
  - Added by [Christian Noon](https://github.com/cnoon).
- `HTTPHeaders` typealias for top-level API convenience.
  - Added by [Christian Noon](https://github.com/cnoon).
- Complete safeguards to `URLStringConvertible`, `URLRequestConvertible` and `RequestAdapter`.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1505](https://github.com/Alamofire/Alamofire/pull/1505).
- Tests around invalidURL error cases for `Request` creation and adaptation.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1505](https://github.com/Alamofire/Alamofire/pull/1505).

#### Updated

- The `authorizationHeader` static method over to returning optional tuple.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1455](https://github.com/Alamofire/Alamofire/pull/1455).
- `SessionManager` queues to each have a unique name using a UUID suffix.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1455](https://github.com/Alamofire/Alamofire/pull/1455).
- The progress tracking system across all `Request` subclasses to improve accuracy.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1455](https://github.com/Alamofire/Alamofire/pull/1455).
- `BaseTestCase` to delete contents of common directories at the start of each test.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1457](https://github.com/Alamofire/Alamofire/pull/1457).
- Response handler extensions by moving them into `DataRequest` and added equivalents
  for `DownloadRequest`.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1457](https://github.com/Alamofire/Alamofire/pull/1457).
- The response serializer types to use the `Protocol` suffix.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1457](https://github.com/Alamofire/Alamofire/pull/1457).
- `Validation` typealias to include response data in a `DataRequest` type.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1461](https://github.com/Alamofire/Alamofire/pull/1461).
- `Validation` typealias to include temporary and destination URLs in a `DownloadRequest` type.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1461](https://github.com/Alamofire/Alamofire/pull/1461).
- `SessionManager` APIs to all leverage `TaskConvertible` conformance.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1461](https://github.com/Alamofire/Alamofire/pull/1461).
- `DownloadFileDestination` closures to be optional on top-level `DownloadRequest` APIs.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1462](https://github.com/Alamofire/Alamofire/pull/1462).
- The `request` and `download` APIs now default to `.get` method and `upload` defaults to `.post`.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1462](https://github.com/Alamofire/Alamofire/pull/1462).
- The `ParameterEncoding` encode API to throw instead of returning tuple.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1465](https://github.com/Alamofire/Alamofire/pull/1465).
- The `TaskDelegate` to only store the url session task error if `error` is `nil`.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1465](https://github.com/Alamofire/Alamofire/pull/1465).
- `ParameterEncoding` enum by switching to a protocol backed by url, json and plist structs.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1465](https://github.com/Alamofire/Alamofire/pull/1465).
- Updated RequestRetrier completion to be escaping.
  - Updated by [Aron Cedercrantz](https://github.com/rastersize) in Pull Request
    [#1489](https://github.com/Alamofire/Alamofire/pull/1489).
- Code signing to automatic with no team on framework, test and app targets.
  - Updated by [Christian Noon](https://github.com/cnoon).
- README for Swift 3 and Alamofire 4 along with reorganization.
  - Updated by [Christian Noon](https://github.com/cnoon).
- README with improved `Error` examples as well as typo and whitespace fixes.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request
    [#1504](https://github.com/Alamofire/Alamofire/pull/1504).
- `Request` task property is now optional allowing errors to propagate through.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1505](https://github.com/Alamofire/Alamofire/pull/1505).
- The Travis-CI device list in the yaml file.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1505](https://github.com/Alamofire/Alamofire/pull/1505).
- The top-level APIs by removing external `resource` parameter name.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1505](https://github.com/Alamofire/Alamofire/pull/1505).
- The `URLStringCovertible` by renaming to `URLConvertible` and removed protocol property.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1505](https://github.com/Alamofire/Alamofire/pull/1505).
- The README and migration guide with the `URLConvertible` and top-level API changes.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1505](https://github.com/Alamofire/Alamofire/pull/1505).

#### Removed

- Unnecessary `public` ACL declarations on `AFError` extensions.
  - Removed by [Christian Noon](https://github.com/cnoon).
- `URLStringConvertible` conformance on `URLRequest`.
  - Removed by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1491](https://github.com/Alamofire/Alamofire/pull/1491).
- Removed `downloadProgress` and `uploadProgress` Int64 variants.
  - Removed by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#1467](https://github.com/Alamofire/Alamofire/issues/1467) reported by
    [thebluepotato](https://github.com/thebluepotato).
- Duplicated change log message in the migration guide.
  - Removed by [Justin Jia](https://github.com/JustinJiaDev) in Pull Request
    [#1503](https://github.com/Alamofire/Alamofire/pull/1503).
- Code coverage generation by default to improve test suite stability.
  - Removed by [Christian Noon](https://github.com/cnoon).

#### Fixed

- Fixed `URLEncoding` issue around `NSNumber` parameter encoding.
  - Fixed by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#1458](https://github.com/Alamofire/Alamofire/issues/1458) reported by
    [Dhanush Balachandran](https://github.com/dhanushram).
- Issue where `MultipartFormData` temp directory creation needed to be done serially.
  - Fixed by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#1333](https://github.com/Alamofire/Alamofire/issues/1333) reported by
    [Fernando Mazzon](https://github.com/fer662).
- Issue in resume data tests where request was being cancelled multiple times.
  - Fixed by [Christian Noon](https://github.com/cnoon).

---

## [4.0.0-beta.2](https://github.com/Alamofire/Alamofire/releases/tag/4.0.0-beta.2)

Released on 2016-08-29. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.0.0-beta.2).

#### Fixed

- Build issue with `Manager` class due to cherry picked change that merged incorrectly.
  - Fixed by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#1438](https://github.com/Alamofire/Alamofire/pull/1438).

## [4.0.0-beta.1](https://github.com/Alamofire/Alamofire/releases/tag/4.0.0-beta.1)

Released on 2016-08-28. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A4.0.0-beta.1).

#### Added

- `discardableResult` annotations to all top-level Request APIs.
  - Added by [Christian Noon](https://github.com/cnoon).

#### Updated

- All source, test and example logic as well as project settings to compile against
  the Xcode 8 beta releases.
  - Updated by [Kevin Harwood](https://github.com/kcharwood),
    [Jon Shier](https://github.com/jshier) and
    [Christian Noon](https://github.com/cnoon).
- Deployment targets to iOS 9.0, macOS 10.11, tvOS 9.0 and watchOS 2.0.
  - Updated by [Christian Noon](https://github.com/cnoon).
- Notifications to use nested structs inside `Notification.Name` namespace.
  - Updated by [Christian Noon](https://github.com/cnoon).
- The `Manager` class to `SessionManager` to be more descriptive.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1385](https://github.com/Alamofire/Alamofire/pull/1385).
- The `SessionDelegate`, `TaskDelegate` and subclasses by pulling them into the global namespace.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1385](https://github.com/Alamofire/Alamofire/pull/1385).
- All the Core APIs and documentation to match Swift 3 API design guidelines.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1385](https://github.com/Alamofire/Alamofire/pull/1385).
- The `SessionDelegate` to store `Request` instances internally to prepare for retry logic.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1391](https://github.com/Alamofire/Alamofire/pull/1391).
- The podspec to 4.0.0-beta.1 and bumped the deployment targets.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request
    [#1401](https://github.com/Alamofire/Alamofire/pull/1401).
- The parameter order of custom `URLRequest` initializer to match other APIs.
  - Updated by [Christian Noon](https://github.com/cnoon).
- The travis yaml file for Xcode 8.
  - Updated by [Christian Noon](https://github.com/cnoon).
- The `Error` enum to `AFError` which now conforms to the new `Error` protocol.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request
    [#1419](https://github.com/Alamofire/Alamofire/pull/1419).

#### Fixed

- Typo in a parameter name in the `MultipartFormData` Swift 3 API refactor.
  - Fixed by [Joshua Hudson](https://github.com/jhudsonWA) in Pull Request
    [#1395](https://github.com/Alamofire/Alamofire/pull/1395).

#### Upgrade Notes

This release requires Xcode 8.0 beta 6+ because it has been completely refactored to compile against Swift 3.0. Any older versions of Xcode will **NOT COMPILE**.

This release is the start of the Alamofire 4.0.0 beta releases. We still have quite a few large changes we're trying to squeeze in before the Xcode 8 GM drops, so the APIs will continue to change over the next few weeks. Please keep in mind that each beta will likely bring new APIs and also refactor others. The betas **WILL NOT** follow semantic versioning. We'll most likely conform to semantic versioning once we start releasing the RCs unless we run into a major unforeseen issue.

We'd really appreciate everyone trying out the betas and letting us know if you find issues. We want to address every possible issue prior to the official Alamofire 4.0.0 release.

---

## [3.5.1](https://github.com/Alamofire/Alamofire/releases/tag/3.5.1)

Released on 2016-10-01. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.5.1).

#### Fixed

- Assorted memory leaks caused by underlying Swift runtime bugs.
  - Fixed by [Jon Shier](https://github.com/jshier) in regards to Issue
    [#1626](https://github.com/Alamofire/Alamofire/issues/1626).
- Issue in the test suite logic on macOS 10.12.
  - Fixed by [Jon Shier](https://github.com/jshier).

## [3.5.0](https://github.com/Alamofire/Alamofire/releases/tag/3.5.0)

Released on 2016-09-07. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.5.0).

#### Updated

- The `User-Agent` header generation formatting and also added docs and tests.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request
    [#1456](https://github.com/Alamofire/Alamofire/pull/1456) in regards to Issue
    [#1452](https://github.com/Alamofire/Alamofire/issues/1452).
- All source, test and example logic as well as project settings to compile against
  Xcode 7 and 8 against Swift 2.2 or 2.3 respectively.
  - Updated by [Kevin Harwood](https://github.com/kcharwood),
    [Jon Shier](https://github.com/jshier) and
    [Christian Noon](https://github.com/cnoon).
- The Travis CI yaml file to support both Xcode 7.3 and 8 simultaneously.
  - Updated by [Christian Noon](https://github.com/cnoon).

#### Fixed

- A TLS evaluation test that could fail with a different error when behind a proxy.
  - Fixed by [Christian Noon](https://github.com/cnoon).

---

## [3.4.2](https://github.com/Alamofire/Alamofire/releases/tag/3.4.2)

Released on 2016-08-28. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.4.2).

#### Added

- Added Cleanup Whitespace target to remove excess whitespace from Swift files.
  - Added by [Christian Noon](https://github.com/cnoon).

#### Updated

- All TLS evaluation tests from `disig.sk` to `badssl.com` to be more reliant and robust.
  - Updated by [Christian Noon](https://github.com/cnoon).
- Internal `URLRequest` method to maintain mutable variant data on an `NSURLRequest` passed
  into the top-level APIs.
  - Updated by [Greedwolf DSS](https://github.com/passchaos) in Pull Request
    [#1330](https://github.com/Alamofire/Alamofire/pull/1330).
- The `User-Agent` header to include version and build numbers.
  - Updated by [Sergey Demchenko](https://github.com/antrix1989) in Pull Request
    [#1420](https://github.com/Alamofire/Alamofire/pull/1420).

#### Removed

- All excess whitespace from Swift files using the `Cleanup Whitespace` target.
  - Removed by [Christian Noon](https://github.com/cnoon).

#### Fixed

- `Request` debug description tests to no longer require parameters in a specific order.
  - Fixed by [Marius Serban](https://github.com/marius-serban) in Pull Request
    [#1318](https://github.com/Alamofire/Alamofire/pull/1318).
- Small ACL issue in code sample of the Handling Errors section of the README.
  - Fixed by [Adrian Brink](https://github.com/adrianbrink) in Pull Request
    [#1315](https://github.com/Alamofire/Alamofire/pull/1315).

## [3.4.1](https://github.com/Alamofire/Alamofire/releases/tag/3.4.1)

Released on 2016-06-12. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.4.1).

#### Added

- Rdar `26761490` to the list of rdars affecting Alamofire.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1262](https://github.com/Alamofire/Alamofire/pull/1262).
- A new `debugDescription` test for a MultipartFormData Request with duplicate headers.
  - Added by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#1303](https://github.com/Alamofire/Alamofire/issues/1303).

#### Updated

- CocoaPod installation instructions in README to be compatible with 1.x.
  - Updated by [Luis Ferro](https://github.com/lferro9000) in Pull Request
    [#1288](https://github.com/Alamofire/Alamofire/pull/1288).
- The README to reflect the best error practices in response serializers.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request
    [#1273](https://github.com/Alamofire/Alamofire/pull/1273).
- The generation of the `User-Agent` header to use non-localized sources.
  - Updated by [Jon Shier](https://github.com/jshier) in Pull Request
    [#1292](https://github.com/Alamofire/Alamofire/pull/1292) in regards to Issue
    [#1269](https://github.com/Alamofire/Alamofire/pull/1269).
- The `Generic Response Object Serialization` section of the README to use protocol extension.
  - Updated by [Raphael Oliveira](https://github.com/raphaeloliveira) in Pull Request
    [#1257](https://github.com/Alamofire/Alamofire/pull/1257).
- Reachability by removing explicit IPv6 logic since OS handles this automatically.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1308](https://github.com/Alamofire/Alamofire/pull/1308) in regards to Issue
    [#1228](https://github.com/Alamofire/Alamofire/pull/1228).
- Host manager reachability test to use different hostname to improve test reliability.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1308](https://github.com/Alamofire/Alamofire/pull/1308).

#### Removed

- `ReleaseTest` configuration and updated Travis-CI yaml file to enable testability directly.
  - Removed by [Christian Noon](https://github.com/cnoon).

#### Fixed

- Memory leak in `Timeline` description and debugDescription due to string interpolation.
  - Fixed by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1262](https://github.com/Alamofire/Alamofire/issues/1262) in regards to Issue
    [#1232](https://github.com/Alamofire/Alamofire/issues/1232).

## [3.4.0](https://github.com/Alamofire/Alamofire/releases/tag/3.4.0)

Released on 2016-05-08. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.4.0).

#### Added

- Status code and content type values into validation `NSError` userInfo dictionaries.
  - Added by [Cédric Luthi](https://github.com/0xced) in Pull Request
    [#1166](https://github.com/Alamofire/Alamofire/pull/1166).
- New `authorizationHeader` API to generate base64 encoded authorization header.
  - Added by [Cédric Luthi](https://github.com/0xced) in Pull Request
    [#1187](https://github.com/Alamofire/Alamofire/pull/1187).

#### Updated

- URLProtocol tests to demonstrate using `NSURLProtocol` with `NSURLSession`.
  - Updated by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#1160](https://github.com/Alamofire/Alamofire/issues/1160).
- The `SessionDelegate` to no longer be `final` to allow subclassing.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1172](https://github.com/Alamofire/Alamofire/issues/1172) in regards to Issue
    [#1145](https://github.com/Alamofire/Alamofire/issues/1145).
- The `SessionDelegate` subscript public to allow full control when subclassing.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1172](https://github.com/Alamofire/Alamofire/issues/1172).
- The `Response Serialization` section of the README to include validation examples.
  - Updated by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#1213](https://github.com/Alamofire/Alamofire/issues/1213).
- The delegate guard in the `Manager` initializer in front of property assignment.
  - Updated by [Broccoliii](https://github.com/broccolii) in Pull Request
    [#1226](https://github.com/Alamofire/Alamofire/issues/1226).
- Header example in the README to use `Accept` header instead of `Content-Type`.
  - Updated by [Christian Noon](https://github.com/cnoon) in regards to Pull Request
    [#1229](https://github.com/Alamofire/Alamofire/issues/1229).

#### Deprecated

- The `errorWithCode` APIs and updated NSURLError\* domains to `NSURLErrorDomain`.
  - Deprecated by [Cédric Luthi](https://github.com/0xced) in Pull Request
    [#1166](https://github.com/Alamofire/Alamofire/pull/1166).

#### Fixed

- Issue where Requests with invalid credentials were not terminating with 401 status code.
  - Fixed by [Cédric Luthi](https://github.com/0xced) in Pull Request
    [#1164](https://github.com/Alamofire/Alamofire/pull/1164) in regards to Issue
    [#1159](https://github.com/Alamofire/Alamofire/issues/1159).
- Issue in URLProtocol test where config headers are not passed prior to iOS 9.0.
  - Fixed by [Christian Noon](https://github.com/cnoon).
- Issue where Request `cURLRepresentation` method was not coalescing duplicate headers.
  - Fixed by [Chris Richards](https://github.com/chrisrichards) in Pull Request
    [#1186](https://github.com/Alamofire/Alamofire/pull/1186) in regards to Issue
    [#1184](https://github.com/Alamofire/Alamofire/issues/1184).
- Issue where incorrect dash in License file was breaking markdown parsing.
  - Fixed by [Gemma Barlow](https://github.com/gemmakbarlow) in Pull Request
    [#1218](https://github.com/Alamofire/Alamofire/issues/1218).
- Issue where internal quotes were not escaped correctly in cURL output.
  - Fixed by [Christian Noon](https://github.com/cnoon).

---

## [3.3.1](https://github.com/Alamofire/Alamofire/releases/tag/3.3.1)

Released on 2016-04-06. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.3.1).

#### Added

- Tests for the `SessionDelegate` redirect with completion override closure.
  - Added by [Kevin Harwood](https://github.com/kcharwood) in Pull Request
    [#1141](https://github.com/Alamofire/Alamofire/issues/1141).
- Tests for all the `SessionDelegate` override closures.
  - Added by [Christian Noon](https://github.com/cnoon).

#### Updated

- The authentication test cases to clear out all cookies to help stabilize Travis-CI.
  - Updated by [Christian Noon](https://github.com/cnoon).
- The cache test check for no store header to use availability checks.
  - Updated by [Christian Noon](https://github.com/cnoon).

#### Fixed

- The `respondsToSelector` check for the new HTTP redirect closure with completion.
  - Fixed by [Kevin Harwood](https://github.com/kcharwood) in Pull Request
    [#1141](https://github.com/Alamofire/Alamofire/issues/1141) in regards to Issue
    [#1140](https://github.com/Alamofire/Alamofire/issues/1140).
- Issue where the challenge and response `SessionDelegate` override closures were not called.
  - Fixed by [Christian Noon](https://github.com/cnoon).
- Typo in the Travis YAML file that was causing all tests to always fail on iOS 9.1.
  - Fixed by [Christian Noon](https://github.com/cnoon).
- Race condition in the cache tests that was causing random failures on Travis-CI.
  - Fixed by [Christian Noon](https://github.com/cnoon).

## [3.3.0](https://github.com/Alamofire/Alamofire/releases/tag/3.3.0)

Released on 2016-03-23. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.3.0).

#### Added

- Added override closures for all `SessionDelegate` APIs with completion handlers.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1099](https://github.com/Alamofire/Alamofire/pull/1099).

#### Updated

- The `User-Agent` header implementation to use more aggressive type-safety checks.
  - Updated by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#1100](https://github.com/Alamofire/Alamofire/issues/1100).
- All shared response serializers to accept a custom queue for execution.
  - Updated by [Luca Torella](https://github.com/lucatorella) in Pull Request
    [#1112](https://github.com/Alamofire/Alamofire/pull/1112).
- The network reachability manager to use IPv4 on iOS 8.x and OSX 10.9.x.
  - Updated by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#1086](https://github.com/Alamofire/Alamofire/issues/1086).
- All source, test and example code to compile against Swift 2.2.
  - Updated by [James Barrow](https://github.com/Baza207) and [Dominik Hadl](https://github.com/nickskull) in Pull Requests
    [#1030](https://github.com/Alamofire/Alamofire/pull/1030) and
    [#1128](https://github.com/Alamofire/Alamofire/pull/1128).
- The Travis CI YAML file to use Xcode 7.3 and also updated matrix targets.
  - Updated by [Christian Noon](https://github.com/cnoon).

#### Fixed

- Issue in JSON response serialization test case where the wrong serializer was being tested.
  - Fixed by [Gregory J.H. Rho](https://github.com/topchul) in Pull Request
    [#1108](https://github.com/Alamofire/Alamofire/pull/1108).
- Issue where multipart form data encoding was unnecessarily scheduling input and output
  streams with the current runloop.
  - Fixed by [Brian King](https://github.com/KingOfBrian) in Pull Request
    [#1121](https://github.com/Alamofire/Alamofire/pull/1121).

#### Upgrade Notes

This release requires Xcode 7.3+ otherwise the Swift 2.2 changes will **NOT COMPILE**. There are several reasons why this was deployed as a MINOR and not MAJOR release. First off, the public API changes of this release are fully backwards compatible. There are no breaking API changes in the public APIs. Strictly following semver dictates that this is a MINOR, not MAJOR release.

> See [semver](https://semver.org/#semantic-versioning-specification-semver) for more info.

We also realize that this can be frustrating for those out there not ready to upgrade to Xcode 7.3. Please know that we consider each release version carefully before deploying. Our decision to bump the MINOR version was not only due to strictly following semver, but also because it's difficult and undesirable for all OSS libraries to bump MAJOR versions each time the Swift APIs are incremented. Alamofire would have had to go through 6 additional MAJOR versions if this was the policy. That would mean we'd already be running on Alamofire 10.x. Incrementing MAJOR versions this quickly is disruptive to the community and would cause even more confusion. Instead, we try to carefully plan our MAJOR version releases and accompany them with detailed Migration Guides to help make the transition as smooth as possible.

If anyone has additional questions, please feel free to open an issue and we'll be more than happy to discuss further.

---

## [3.2.1](https://github.com/Alamofire/Alamofire/releases/tag/3.2.1)

Released on 2016-02-27. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.2.1).

#### Updated

- `StringResponseSerializer` implementation to build with the latest Swift toolchain.
  - Updated by [Chris Cieslak](https://github.com/vivid-cieslak) in Pull Request
    [#1050](https://github.com/Alamofire/Alamofire/pull/1050).
- Expanded the Component Libraries section and moved it up in the README.
  - Updated by [Christian Noon](https://github.com/cnoon).

#### Fixed

- Issue where JSON and plist custom content types were not retained during parameter encoding.
  - Fixed by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1088](https://github.com/Alamofire/Alamofire/pull/1088).

## [3.2.0](https://github.com/Alamofire/Alamofire/releases/tag/3.2.0)

Released on 2016-02-07. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.2.0).

#### Added

- Notifications that post when an `NSURLSessionTask` changes state to allow support for the
  network activity indicator.
  - Added by [Christian Noon](https://github.com/cnoon).
- `Timeline` struct to capture timings throughout the lifecycle of a `Request`.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1054](https://github.com/Alamofire/Alamofire/issues/1054).
- A new `Timeline` section to the README.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1054](https://github.com/Alamofire/Alamofire/issues/1054).
- `NetworkReachabilityManager` to listen for reachability status changes.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1053](https://github.com/Alamofire/Alamofire/issues/1053).
- Unit tests for all the testable network reachability manager APIs.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1053](https://github.com/Alamofire/Alamofire/issues/1053).
- A new `Network Reachability` section to the README.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#1053](https://github.com/Alamofire/Alamofire/issues/1053).

#### Updated

- The `NSURLSessionStream` APIs to support `tvOS`.
  - Updated by [Christian Noon](https://github.com/cnoon).
- The `ParameterEncoding` encode method to allow empty parameters to still be encoded.
  - Updated by [Christian Noon](https://github.com/cnoon) in regards to Issues
    [#1032](https://github.com/Alamofire/Alamofire/issues/1032) and
    [#1049](https://github.com/Alamofire/Alamofire/issues/1049).

#### Fixed

- Broken CocoaDocs generation by moving iOS Example project into Examples folder.
  - Fixed by [Jon Shier](https://github.com/jshier) in Pull Request
    [#1027](https://github.com/Alamofire/Alamofire/issues/1027) in regards to Issue
    [#1025](https://github.com/Alamofire/Alamofire/issues/1025).

---

## [3.1.5](https://github.com/Alamofire/Alamofire/releases/tag/3.1.5)

Released on 2016-01-17. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.1.5).

#### Added

- `Package.swift` to the project to support Swift Package Manager (SPM).
  - Added by [Kyle Fuller](https://github.com/kylef) in Pull Request
    [#979](https://github.com/Alamofire/Alamofire/pull/979).
- Safeguards to the `Request` class's `debugDescription` property.
  - Added by [tokorom](https://github.com/tokorom) in Pull Request
    [#983](https://github.com/Alamofire/Alamofire/pull/983).

#### Updated

- `Accept-Language` header generation to use functional style.
  - Updated by [Dapeng Gao](https://github.com/dapenggao) in Pull Request
    [#982](https://github.com/Alamofire/Alamofire/pull/982).
- `Accept-Encoding` and `Accept-Language` header values to have separator spaces between values.
  - Updated by [Christian Noon](https://github.com/cnoon).
- Copyright headers to include 2016! 🎉🎉🎉
  - Updated by [Christian Noon](https://github.com/cnoon).

## [3.1.4](https://github.com/Alamofire/Alamofire/releases/tag/3.1.4)

Released on 2015-12-16. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.1.4).

#### Added

- `NSTemporaryExceptionMinimumTLSVersion` documentation to the ATS section in the README.
  - Added by [Marandon Antoine](https://github.com/ntnmrndn) in Pull Request
    [#952](https://github.com/Alamofire/Alamofire/pull/952).
- Added `ReleaseTest` configuration to allow running tests against optimized build.
  - Added by [Christian Noon](https://github.com/cnoon).

#### Updated

- Carthage instructions in the README to clearly callout the `carthage update` command.
  - Updated by [vlad](https://github.com/vlastachu) in Pull Request
    [#955](https://github.com/Alamofire/Alamofire/pull/955).
- `ParameterEncoding` to early out when passed an empty parameters dictionary.
  - Updated by [Anthony Miller](https://github.com/AnthonyMDev) in Pull Request
    [#954](https://github.com/Alamofire/Alamofire/pull/954).
- The `certificatesInBundle` to support `cer`, `crt` and `der` extensions.
  - Updated by [Jacob Jennings](https://github.com/jacobjennings) in Pull Request
    [#956](https://github.com/Alamofire/Alamofire/pull/956).
- The `ENABLE_TESTABILITY` flag to `NO` for Release configuration and disabled tests for
  non-test builds to better support Carthage.
  - Updated by [Jed Lewison](https://github.com/jedlewison) in Pull Request
    [#953](https://github.com/Alamofire/Alamofire/pull/953).
- The server certificates for the TLS tests and added all certificates to all test targets.
  - Updated by [Christian Noon](https://github.com/cnoon).
- The Travis-CI configuration to Xcode 7.2, iOS 9.2, tvOS 9.1 and watchOS 2.1.
  - Updated by [Christian Noon](https://github.com/cnoon).

#### Removed

- `SecCertificate` array Swift workaround in `ServerTrustPolicy` for Xcode 7.2.
  - Removed by [Christian Noon](https://github.com/cnoon).

## [3.1.3](https://github.com/Alamofire/Alamofire/releases/tag/3.1.3)

Released on 2015-11-22. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.1.3).

#### Added

- Custom `Info.plist` for tvOS setting the `UIRequiredDeviceCapabilities` to `arm64`.
  - Added by [Simon Støvring](https://github.com/simonbs) in Pull Request
    [#913](https://github.com/Alamofire/Alamofire/pull/913).

#### Updated

- All code samples in the README to use `https` instead of `http`.
  - Updated by [Tomonobu Sato](https://github.com/tmnb) in Pull Request
    [#912](https://github.com/Alamofire/Alamofire/pull/912).

## [3.1.2](https://github.com/Alamofire/Alamofire/releases/tag/3.1.2)

Released on 2015-11-06. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.1.2).

#### Updated

- Code signing on iOS simulator builds to not sign simulator builds.
  - Updated by [John Heaton](https://github.com/JRHeaton) in Pull Request
    [#903](https://github.com/Alamofire/Alamofire/pull/903).
- Code signing on watchOS and tvOS simulators builds to not sign simulator builds.
  - Updated by [Christian Noon](https://github.com/cnoon).

## [3.1.1](https://github.com/Alamofire/Alamofire/releases/tag/3.1.1)

Released on 2015-10-31. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.1.1).

#### Added

- Support for 204 response status codes in the response serializers.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#889](https://github.com/Alamofire/Alamofire/pull/889).
- ATS section to the README explaining how to configure the settings.
  - Added by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#876](https://github.com/Alamofire/Alamofire/issues/876).

#### Updated

- Several unnecessary uses of `NSString` with `String`.
  - Updated by [Nicholas Maccharoli](https://github.com/Nirma) in Pull Request
    [#885](https://github.com/Alamofire/Alamofire/pull/885).
- Content type validation to always succeeds when server data is `nil` or zero length.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#890](https://github.com/Alamofire/Alamofire/pull/890).

#### Removed

- The mention of rdar://22307360 from the README since Xcode 7.1 has been released.
  - Removed by [Elvis Nuñez](https://github.com/3lvis) in Pull Request
    [#891](https://github.com/Alamofire/Alamofire/pull/891).
- An unnecessary availability check now that Xcode 7.1 is out of beta.
  - Removed by [Christian Noon](https://github.com/cnoon).
- The playground from the project due to instability reasons.
  - Removed by [Christian Noon](https://github.com/cnoon).
- The data length checks in the `responseData` and `responseString` serializers.
  - Removed by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#889](https://github.com/Alamofire/Alamofire/pull/889).

## [3.1.0](https://github.com/Alamofire/Alamofire/releases/tag/3.1.0)

Released on 2015-10-22. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.1.0).

#### Added

- New tvOS framework and test targets to the project.
  - Added by [Bob Scarano](https://github.com/bscarano) in Pull Request
    [#767](https://github.com/Alamofire/Alamofire/pull/767).
- The tvOS deployment target to the podspec.
  - Added by [Christian Noon](https://github.com/cnoon).
- The `BITCODE_GENERATION_MODE` user defined setting to tvOS framework target.
  - Added by [Christian Noon](https://github.com/cnoon).

#### Updated

- The README to include tvOS and bumped the required version of Xcode.
  - Updated by [Christian Noon](https://github.com/cnoon).
- The default tvOS and watchOS deployment targets in the Xcode project.
  - Updated by [Christian Noon](https://github.com/cnoon).
- The `APPLICATION_EXTENSION_API_ONLY` enabled flag to `YES` in the tvOS framework target.
  - Updated by [James Barrow](https://github.com/Baza207) in Pull Request
    [#771](https://github.com/Alamofire/Alamofire/pull/771).
- The Travis-CI yaml file to run watchOS and tvOS builds and tests on xcode7.1 osx_image.
  - Updated by [Christian Noon](https://github.com/cnoon).

---

## [3.0.1](https://github.com/Alamofire/Alamofire/releases/tag/3.0.1)

Released on 2015-10-19. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.0.1).

#### Added

- Tests around content type validation with accept parameters.
  - Added by [Christian Noon](https://github.com/cnoon).

#### Fixed

- Content type validation issue where parameter parsing on `;` was incorrect.
  - Fixed by [Christian Noon](https://github.com/cnoon).

## [3.0.0](https://github.com/Alamofire/Alamofire/releases/tag/3.0.0)

Released on 2015-10-10. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.0.0).

#### Updated

- `Downloading a File` code sample in the README to compile against Swift 2.0.
  - Updated by [Screon](https://github.com/Screon) in Pull Request
    [#827](https://github.com/Alamofire/Alamofire/pull/827).
- Download code samples in the README to use `response` serializer.
  - Updated by [Christian Noon](https://github.com/cnoon).
- CocoaPods and Carthage installation instructions for 3.0.
  - Updated by [Christian Noon](https://github.com/cnoon).
- Carthage description and installation instructions in the README.
  - Updated by [Ashton Williams](https://github.com/Ashton-W) in Pull Request
    [#843](https://github.com/Alamofire/Alamofire/pull/843).
- URL encoding internals to leverage the dictionary keys lazy evaluation.
  - Updated by [Christian Noon](https://github.com/cnoon).

#### Fixed

- Small typo in the Alamofire 3.0 Migration Guide `Response` section.
  - Fixed by [neugartf](https://github.com/neugartf) in Pull Request
    [#826](https://github.com/Alamofire/Alamofire/pull/826).
- User defined `BITCODE_GENERATION_MODE` setting for Carthage builds.
  - Fixed by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#835](https://github.com/Alamofire/Alamofire/issues/835).

---

## [3.0.0-beta.3](https://github.com/Alamofire/Alamofire/releases/tag/3.0.0-beta.3)

Released on 2015-09-27. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.0.0-beta.3).

#### Updated

- The `Response` initializer to have a `public` ACL instead of `internal`.
  - Updated by [Christian Noon](https://github.com/cnoon).

## [3.0.0-beta.2](https://github.com/Alamofire/Alamofire/releases/tag/3.0.0-beta.2)

Released on 2015-09-26. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.0.0-beta.2).

#### Added

- Tests around the header behavior for redirected requests.
  - Added by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#798](https://github.com/Alamofire/Alamofire/issues/798).
- A migration guide for Alamofire 3.0 documenting all API changes.
  - Added by [Christian Noon](https://github.com/cnoon).

#### Updated

- `Response` initializer to have `internal` ACL.
  - Updated by [Christian Noon](https://github.com/cnoon).
- All sample code in the README to conform to the Alamofire 3.0 APIs.
  - Updated by [Christian Noon](https://github.com/cnoon).
- URL percent escaping to only batch on OS's where required improving
  overall performance.
  - Updated by [Christian Noon](https://github.com/cnoon).
- Basic auth example in the README to compile on Swift 2.0.
  - Updated by [David F. Muir V](https://github.com/dfmuir) in Pull Request
    [#810](https://github.com/Alamofire/Alamofire/issues/810).

#### Fixed

- Compiler errors in the playground due to the new response serializer APIs.
  - Fixed by [Christian Noon](https://github.com/cnoon).

## [3.0.0-beta.1](https://github.com/Alamofire/Alamofire/releases/tag/3.0.0-beta.1)

Released on 2015-09-21. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A3.0.0-beta.1).

#### Added

- A new `Response` struct to simplify response serialization.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#792](https://github.com/Alamofire/Alamofire/pull/792).
- A new initializer to the `Manager` allowing dependency injection of the
  underlying `NSURLSession`.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#795](https://github.com/Alamofire/Alamofire/pull/795).
- Tests around the new `Manager` initialization methods.

#### Updated

- Result type to take two generic parameters (`Value` and `Error`) where `Error`
  conforms to `ErrorType`.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#791](https://github.com/Alamofire/Alamofire/pull/791).
- All response serializers to now return the original server data as `NSData?`.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#791](https://github.com/Alamofire/Alamofire/pull/791).
- The `TaskDelegate` to store an error as an `NSError` instead of `ErrorType`.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#791](https://github.com/Alamofire/Alamofire/pull/791).
- The `ValidationResult` failure case to require an `NSError` instead of `ErrorType`.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#791](https://github.com/Alamofire/Alamofire/pull/791).
- All tests around response serialization and `Result` type usage.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#791](https://github.com/Alamofire/Alamofire/pull/791).
- All response serializers to use the new `Response` type.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request -
    [#792](https://github.com/Alamofire/Alamofire/pull/792).
- The designated initializer for a `Manager` to accept a `SessionDelegate` parameter
  allowing dependency injection for better background session support.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#795](https://github.com/Alamofire/Alamofire/pull/795).

---

## [2.0.2](https://github.com/Alamofire/Alamofire/releases/tag/2.0.2)

Released on 2015-09-20. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A2.0.2).

#### Updated

- The Embedded Framework documentation to include `git init` info.
  - Updated by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#782](https://github.com/Alamofire/Alamofire/issues/782).

#### Fixed

- Alamofire iOS framework target by adding Alamofire iOS Tests as Target Dependency.
  - Fixed by [Nicky Gerritsen](https://github.com/nickygerritsen) in Pull Request
    [#780](https://github.com/Alamofire/Alamofire/pull/780).
- Percent encoding issue for long Chinese strings using URL parameter encoding.
  - Fixed by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#206](https://github.com/Alamofire/Alamofire/issues/206).

## [2.0.1](https://github.com/Alamofire/Alamofire/releases/tag/2.0.1)

Released on 2015-09-16. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A2.0.1).

#### Updated

- The CocoaPods installation instructions in the README.
  - Updated by [Christian Noon](https://github.com/cnoon).
- The Carthage installation instructions in the README.
  - Updated by [Gustavo Barbosa](https://github.com/barbosa) in Pull Request
    [#759](https://github.com/Alamofire/Alamofire/pull/759).

#### Fixed

- The link to the 2.0 migration guide in the README.
  - Fixed by [Dwight Watson](https://github.com/dwightwatson) in Pull Request
    [#750](https://github.com/Alamofire/Alamofire/pull/750).
- Issue where NTLM authentication credentials were not used for authentication challenges.
  - Fixed by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#721](https://github.com/Alamofire/Alamofire/pull/721).

## [2.0.0](https://github.com/Alamofire/Alamofire/releases/tag/2.0.0)

Released on 2015-09-09. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A2.0.0).

#### Added

- A new `URLEncodedInURL` case to the `ParameterEncoding` for encoding in the URL.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#742](https://github.com/Alamofire/Alamofire/pull/742).

---

## [2.0.0-beta.4](https://github.com/Alamofire/Alamofire/releases/tag/2.0.0-beta.4)

Released on 2015-09-06. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A2.0.0-beta.4).

#### Added

- The `parameters` and `encoding` parameters to download APIs.
  - Added by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#719](https://github.com/Alamofire/Alamofire/issues/719).
- Section to the README about wildcard domain matching with server trust policies.
  - Added by [Sai](https://github.com/sai-prasanna) in Pull Request
    [#718](https://github.com/Alamofire/Alamofire/pull/718).
- A UTF-8 charset to Content-Type header for a URL encoded body.
  - Added by [Cheolhee Han](https://github.com/cheolhee) in Pull Request
    [#731](https://github.com/Alamofire/Alamofire/pull/731).
- Tests around posting unicode parameters with URL encoding.
  - Added by [Christian Noon](https://github.com/cnoon) in regards to Pull Request
    [#731](https://github.com/Alamofire/Alamofire/pull/731).
- Tests for uploading base 64 encoded image data inside JSON.
  - Added by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#738](https://github.com/Alamofire/Alamofire/issues/738).
- An Alamofire 2.0 migration guide document to the new Documentation folder.
  - Added by [Christian Noon](https://github.com/cnoon).
- A Migration Guides section to the README with link to 2.0 guide.
  - Added by [Christian Noon](https://github.com/cnoon).

#### Updated

- Response serialization to prevent unnecessary call to response serializer.
  - Updated by [Julien Ducret](https://github.com/brocoo) in Pull Request
    [#716](https://github.com/Alamofire/Alamofire/pull/716).
- Travis-CI yaml file to support iOS 9, OSX 10.11 and Xcode 7.
  - Updated by [Christian Noon](https://github.com/cnoon).
- Result types to store an `ErrorType` instead of `NSError`.
  - Updated by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#732](https://github.com/Alamofire/Alamofire/issues/732).
- Docstrings on the download method to be more accurate.
  - Updated by [Christian Noon](https://github.com/cnoon).
- The README to require Xcode 7 beta 6.
  - Updated by [Christian Noon](https://github.com/cnoon).
- The background session section of the README to use non-deprecated API.
  - Updated by [David F. Muir V](https://github.com/dfmuir) in Pull Request
    [#724](https://github.com/Alamofire/Alamofire/pull/724).
- The playground to use the `Result` type.
  - Updated by [Jonas Schmid](https://github.com/jschmid) in Pull Request
    [#726](https://github.com/Alamofire/Alamofire/pull/726).
- Updated progress code samples in the README to show how to call onto the main queue.
  - Updated by [Christian Noon](https://github.com/cnoon).

#### Removed

- The AFNetworking sections from the FAQ in the README.
  - Removed by [Christian Noon](https://github.com/cnoon).

#### Fixed

- Issue on Windows where the wildcarded cert name in the test suite included asterisk.
  - Fixed by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#723](https://github.com/Alamofire/Alamofire/issues/723).
- Crash when multipart form data was uploaded from in-memory data on background session.
  - Fixed by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#740](https://github.com/Alamofire/Alamofire/issues/740).
- Issue where the background session completion handler was not called on the main queue.
  - Fixed by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#728](https://github.com/Alamofire/Alamofire/issues/728).

## [2.0.0-beta.3](https://github.com/Alamofire/Alamofire/releases/tag/2.0.0-beta.3)

Released on 2015-08-25.

#### Removed

- The override for `NSMutableURLRequest` for the `URLRequestConvertible` protocol
  conformance that could cause unwanted URL request referencing.
  - Removed by [Christian Noon](https://github.com/cnoon).

## [2.0.0-beta.2](https://github.com/Alamofire/Alamofire/releases/tag/2.0.0-beta.2)

Released on 2015-08-24. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A2.0.0-beta.2).

#### Added

- Host and certificate chain validation section to the README.
  - Added by [Christian Noon](https://github.com/cnoon).
- Tests verifying configuration headers are sent with all configuration types.
  - Added by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#692](https://github.com/Alamofire/Alamofire/issues/692).
- New rdar to the list in the README about the #available check issue.
  - Added by [Christian Noon](https://github.com/cnoon).
- Override for `NSMutableURLRequest` for the `URLRequestConvertible` protocol.
  - Added by [Christian Noon](https://github.com/cnoon).

#### Updated

- The README to note that CocoaPods 0.38.2 is required.
  - Updated by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#682](https://github.com/Alamofire/Alamofire/issues/682).
- The README to include note about keeping a reference to the `Manager`.
  - Updated by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#681](https://github.com/Alamofire/Alamofire/issues/681).
- Server trust host validation over to use SSL policy evaluation.
  - Updated by [Christian Noon](https://github.com/cnoon).
- The documentation for the `URLRequestConvertible` section in the README.
  - Updated by [Christian Noon](https://github.com/cnoon).
- The `ServerTrustPolicyManager` to be more flexible by using `public` ACL.
  - Updated by [Jan Riehn](https://github.com/jriehn) in Pull Request
    [#696](https://github.com/Alamofire/Alamofire/pull/696).
- The `ServerTrustPolicyManager` policies property to use `public` ACL and
  added docstrings.
  - Updated by [Christian Noon](https://github.com/cnoon).
- The Ono response serializer example for Swift 2.0 in the README.
  - Updated by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#700](https://github.com/Alamofire/Alamofire/issues/700).
- `Result` failure case to store an `ErrorType` instead of `NSError`.
  - Updated by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#703](https://github.com/Alamofire/Alamofire/issues/703).
- All source code to compile with Xcode 7 beta 6.
  - Updated by [Michael Gray](https://github.com/mishagray) in Pull Request
    [#707](https://github.com/Alamofire/Alamofire/pull/707).

#### Removed

- The `required` declaration on the `Manager` init method.
  - Removed by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#672](https://github.com/Alamofire/Alamofire/issues/672).

#### Fixed

- Issue where the `TaskDelegate` operation queue would leak if the task was
  never started.
  - Fixed by [Christian Noon](https://github.com/cnoon).
- Compiler issue on OS X target when creating background configurations
  in the test suite.
  - Fixed by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#693](https://github.com/Alamofire/Alamofire/issues/693).

## [2.0.0-beta.1](https://github.com/Alamofire/Alamofire/releases/tag/2.0.0-beta.1)

Released on 2015-08-10. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A2.0.0-beta.1).

#### Added

- A `watchOS` deployment target to the podspec.
  - Added by [Kyle Fuller](https://github.com/kylef) in Pull Request
    [#574](https://github.com/Alamofire/Alamofire/pull/574).
- Full screen support in the iOS Example App.
  - Added by [Corinne Krych](https://github.com/corinnekrych) in Pull Request
    [#612](https://github.com/Alamofire/Alamofire/pull/612).
- Temporary workaround for `SecCertificate` array compiler crash.
  - Added by [Robert Rasmussen](https://github.com/robrasmussen) in Issue
    [#610](https://github.com/Alamofire/Alamofire/issues/610).
- `Result` and `Error` types to refactor response validation and serialization.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#627](https://github.com/Alamofire/Alamofire/pull/627).
- Tests around response data, string and json serialization result behavior.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#627](https://github.com/Alamofire/Alamofire/pull/627).
- `CustomStringConvertible` and `CustomDebugStringConvertible` conformance
  to the `Result` enumeration.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#648](https://github.com/Alamofire/Alamofire/pull/648).
- A Resume Data section to the README inside the Downloads section.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#648](https://github.com/Alamofire/Alamofire/pull/648).
- A `watchOS` framework target to the project.
  - Added by [Tobias Ottenweller](https://github.com/tomco) in Pull Request
    [#616](https://github.com/Alamofire/Alamofire/pull/616).
- `Result` tests pushing code coverage for `Result` enum to 100%.
  - Added by [Christian Noon](https://github.com/cnoon).
- Tests around all response serializer usage.
  - Added by [Christian Noon](https://github.com/cnoon).
- Public docstrings for all public `SessionDelegate` methods.
  - Added by [Christian Noon](https://github.com/cnoon).
- A section to the README that calls out all open rdars affecting Alamofire.
  - Added by [Christian Noon](https://github.com/cnoon).
- Test for wildcard validation that contains response with nil MIME type.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#662](https://github.com/Alamofire/Alamofire/pull/662).
- Support for stream tasks in iOS 9+ and OSX 10.11+.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#659](https://github.com/Alamofire/Alamofire/pull/659).

#### Updated

- All logic to compile against Swift 2.0.
  - Updated by [Christian Noon](https://github.com/cnoon).
- All logic to use the latest Swift 2.0 conventions.
  - Updated by [Christian Noon](https://github.com/cnoon).
- All public docstrings to the latest Swift 2.0 syntax.
  - Updated by [Christian Noon](https://github.com/cnoon).
- `URLRequestConvertible` to return an `NSMutableURLRequest`.
  - Updated by [Christian Noon](https://github.com/cnoon).
- All HTTP requests to HTTPS to better align with ATS.
  - Updated by [Christian Noon](https://github.com/cnoon).
- The `escape` method in `ParameterEncoding` to use non-deprecated methods.
  - Updated by [Christian Noon](https://github.com/cnoon).
- All source code and docstrings to fit roughly within 120 characters.
  - Updated by [Christian Noon](https://github.com/cnoon).
- The `MultipartFormData` encoding to leverage Swift 2.0 error handling.
  - Updated by [Christian Noon](https://github.com/cnoon).
- All README code samples to match the latest Swift 2.0 API changes.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#648](https://github.com/Alamofire/Alamofire/pull/648).
- All frameworks to enable code coverage generation.
  - Updated by [Christian Noon](https://github.com/cnoon).
- All frameworks to set the enable testability flag to YES for release builds.
  - Updated by [Christian Noon](https://github.com/cnoon) in regard to Issue
    [#652](https://github.com/Alamofire/Alamofire/issues/652).
- `ParameterEncoding` to leverage guard for parameters to increase safety.
  - Updated by [Christian Noon](https://github.com/cnoon).
- iOS Example App to use optional bind around response to safely extract headers.
  - Updated by [John Pope](https://github.com/johndpope) in Pull Request
    [#665](https://github.com/Alamofire/Alamofire/pull/665).
- The `queryComponents` and `escape` methods in `ParameterEncoding` to `public` to
  better support `.Custom` encoding.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#660](https://github.com/Alamofire/Alamofire/pull/660).
- The static error convenience functions to a public ACL.
  - Updated by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#668](https://github.com/Alamofire/Alamofire/issues/668).

#### Removed

- Explicit string values in `ParameterEncoding` since they are now implied.
  - Removed by [Christian Noon](https://github.com/cnoon).
- An OSX cookie check in the `CustomDebugStringConvertible` conformance of a `Request`.
  - Removed by [Christian Noon](https://github.com/cnoon).

#### Fixed

- Issue in automatic validation tests where mutable URL request was not used.
  - Fixed by [Christian Noon](https://github.com/cnoon).
- Potential crash cases in Validation MIME type logic exposed by chaining.
  - Fixed by [Christian Noon](https://github.com/cnoon).
- Compiler issue in the iOS Example App around `Result` type usage.
  - Fixed by [Jan Kase](https://github.com/jankase) in Pull Request
    [#639](https://github.com/Alamofire/Alamofire/pull/639).
- The error code in the custom response serializers section of the README.
  - Fixed by [Christian Noon](https://github.com/cnoon).

---

## [1.3.1](https://github.com/Alamofire/Alamofire/releases/tag/1.3.1)

Released on 2015-08-10. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A1.3.1).

#### Fixed

- Issue where a completed task was not released by the `SessionDelegate` if the
  task override closure was set.
  - Fixed by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#622](https://github.com/Alamofire/Alamofire/issues/622).

## [1.3.0](https://github.com/Alamofire/Alamofire/releases/tag/1.3.0)

Released on 2015-07-24. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A1.3.0).

#### Added

- Test case around `NSURLProtocol` checking header passthrough behaviors.
  - Added by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#473](https://github.com/Alamofire/Alamofire/issues/473).
- Stream method on `Request` to receive data incrementally from data responses.
  - Added by [Peter Sobot](https://github.com/psobot) in Pull Request
    [#512](https://github.com/Alamofire/Alamofire/pull/512).
- Example to the README demonstrating how to use the `responseCollection` serializer.
  - Added by [Josh Brown](https://github.com/joshuatbrown) in Pull Request
    [#532](https://github.com/Alamofire/Alamofire/pull/532).
- Link to the README to the CocoaDocs documentation for Alamofire.
  - Added by [Robert](https://github.com/rojotek) in Pull Request
    [#541](https://github.com/Alamofire/Alamofire/pull/541).
- Support for uploading `MultipartFormData` in-memory and streaming from disk.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#539](https://github.com/Alamofire/Alamofire/pull/539).
- Tests for uploading `MultipartFormData` with complete code coverage.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#539](https://github.com/Alamofire/Alamofire/pull/539).
- The iOS 8.4 simulator to the Travis CI builds by switching to the Xcode 6.4 build.
  - Added by [Syo Ikeda](https://github.com/ikesyo) in Pull Request
    [#568](https://github.com/Alamofire/Alamofire/pull/568).
- Tests for the custom header support with complete code coverage.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#586](https://github.com/Alamofire/Alamofire/pull/586).
- Section to the README about new HTTP header support in the global functions.
  - Added by [Christian Noon](https://github.com/cnoon).
- Basic auth `Authorization` header example to the README.
  - Added by [Christian Noon](https://github.com/cnoon).
- TLS certificate and public key pinning support through the `ServerTrustPolicy`.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#581](https://github.com/Alamofire/Alamofire/pull/581).
- Tests for TLS certificate and public key pinning with complete code coverage.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#581](https://github.com/Alamofire/Alamofire/pull/581).
- Security section to the README detailing various server trust policies.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#581](https://github.com/Alamofire/Alamofire/pull/581).
- The `resumeData` property to `Request` to expose outside data response serializer.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#595](https://github.com/Alamofire/Alamofire/pull/595).
- Download request sample to iOS example app.
  - Added by [Kengo Yokoyama](https://github.com/kentya6) in Pull Request
    [#579](https://github.com/Alamofire/Alamofire/pull/579).

#### Updated

- The INFOPLIST_FILE Xcode project setting to be a relative path.
  - Updated by [Christian Noon](https://github.com/cnoon).
- Exposed persistence parameter for basic auth credentials.
  - Updated by [Christian Noon](https://github.com/cnoon) in regard to Issue
    [#537](https://github.com/Alamofire/Alamofire/issues/537).
- The Travis CI builds to run a full `pod lib lint` pass on the source.
  - Updated by [Kyle Fuller](https://github.com/kylef) in Pull Request
    [#542](https://github.com/Alamofire/Alamofire/pull/542).
- All cases of force unwrapping with optional binding and where clause when applicable.
  - Updated by [Syo Ikeda](https://github.com/ikesyo) in Pull Request
    [#557](https://github.com/Alamofire/Alamofire/pull/557).
- The `ParameterEncoding` encode return tuple to return a mutable URL request.
  - Updated by [Petr Korolev](https://github.com/skywinder) in Pull Request
    [#478](https://github.com/Alamofire/Alamofire/pull/478).
- The `URLRequest` convenience method to return a mutable `NSURLRequest`.
  - Updated by [Christian Noon](https://github.com/cnoon).
- The `request` / `download` / `upload` methods to support custom headers.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#586](https://github.com/Alamofire/Alamofire/pull/586).
- The global `request` / `download` / `upload` method external parameters convention.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#586](https://github.com/Alamofire/Alamofire/pull/586).
- Response serialization to use generics and a `ResponseSerializer` protocol.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#593](https://github.com/Alamofire/Alamofire/pull/593).
- Download task delegate to store resume data for a failed download if available.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#595](https://github.com/Alamofire/Alamofire/pull/595).
- The `TaskDelegate.queue` to public to allow custom request extension operations.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#590](https://github.com/Alamofire/Alamofire/pull/590).
- The README code samples for Advanced Response Serialization.
  - Updated by [Christian Noon](https://github.com/cnoon).

#### Removed

- An unnecessary `NSURLSessionConfiguration` type declaration that can be inferred.
  - Removed by [Avismara](https://github.com/avismarahl) in Pull Request
    [#576](https://github.com/Alamofire/Alamofire/pull/576).
- Unnecessary `respondsToSelector` overrides for `SessionDelegate` methods.
  - Removed by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#590](https://github.com/Alamofire/Alamofire/pull/590).
- Unnecessary calls to `self` throughout source, test and example logic.
  - Removed by [Christian Noon](https://github.com/cnoon).

#### Fixed

- Random test suite basic auth failures by clearing credentials in `setUp` method.
  - Fixed by [Christian Noon](https://github.com/cnoon).
- Error where wildcard was failing due to missing response MIME type.
  - Fixed by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#598](https://github.com/Alamofire/Alamofire/pull/598).
- Typo in the basic auth headers example code in the README.
  - Fixed by [蒲公英の生活](https://github.com/fewspider) in Pull Request
    [#605](https://github.com/Alamofire/Alamofire/pull/605).
- Issue where the example app was printing elapsed time in optional form.
  - Fixed by [Christian Noon](https://github.com/cnoon).

#### Upgrade Notes

There are a couple changes in the 1.3.0 release that are not fully backwards
compatible and need to be called out.

- The global `request` / `download` / `upload` external parameter naming conventions
  were not consistent nor did they match the `Manager` equivalents. By making them
  consistent across the board, this introduced the possibility that you "may" need to
  make slight modifications to your global function calls.
- In order to support generic response serializers, the lowest level
  `Request.response` method had to be converted to a generic method leveraging the new
  `ResponseSerializer` protocol. This has many advantages, the most obvious being that
  the `response` convenience method now returns an `NSData?` optional instead of an
  `AnyObject?` optional. Nice!

  > Please note that every effort is taken to maintain proper semantic versioning. In
  > these two rare cases, it was deemed to be in the best interest of the community to
  > slightly break semantic versioning to unify naming conventions as well as expose a
  > much more powerful form of response serialization.

  > If you have any issues, please don't hesitate to reach out through
  > [GitHub](https://github.com/Alamofire/Alamofire/issues) or
  > [Twitter](https://twitter.com/AlamofireSF).

---

## [1.2.3](https://github.com/Alamofire/Alamofire/releases/tag/1.2.3)

Released on 2015-06-12. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A1.2.3).

#### Added

- Tests for data task progress closure and NSProgress updates.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#494](https://github.com/Alamofire/Alamofire/pull/494).
- More robust tests around download and upload progress.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#494](https://github.com/Alamofire/Alamofire/pull/494).
- More robust redirect tests around default behavior and task override closures.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#507](https://github.com/Alamofire/Alamofire/pull/507).
- The "[" and "]" to the legal escape characters and added more documentation.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#504](https://github.com/Alamofire/Alamofire/pull/504).
- Percent escaping tests around reserved / unreserved / illegal characters.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#504](https://github.com/Alamofire/Alamofire/pull/504).
- Tests for various Cache-Control headers with different request cache policies.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#505](https://github.com/Alamofire/Alamofire/pull/505).
- Link to Carthage in the README.
  - Added by [Josh Brown](https://github.com/joshuatbrown) in Pull Request
    [#520](https://github.com/Alamofire/Alamofire/pull/520).

#### Updated

- iOS 7 instructions to cover multiple Swift files in the README.
  - Updated by [Sébastien Michoy](https://github.com/SebastienMichoy) in regards
    to Issue [#479](https://github.com/Alamofire/Alamofire/pull/479).
- All tests to follow the Given / When / Then structure.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#489](https://github.com/Alamofire/Alamofire/pull/489).
- All tests to be crash safe.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#489](https://github.com/Alamofire/Alamofire/pull/489).
- The OS X tests so that they are all passing again.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#489](https://github.com/Alamofire/Alamofire/pull/489).
- Re-enabled Travis-CI tests for both iOS and Mac OS X.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#506](https://github.com/Alamofire/Alamofire/pull/506).
- Travis-CI test suite to run all tests in both debug and release.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#506](https://github.com/Alamofire/Alamofire/pull/506).
- Travis-CI test suite to run all tests on iOS 8.1, 8.2 and 8.3 as well as Mac OS X 10.10.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#506](https://github.com/Alamofire/Alamofire/pull/506).
- Travis-CI test suite to run `pod lib lint` against the latest version of CocoaPods.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#506](https://github.com/Alamofire/Alamofire/pull/506).

#### Fixed

- Random deinitialization test failure by handling task state race condition.
  - Fixed by [Christian Noon](https://github.com/cnoon).
- Typo in the API Parameter Abstraction in the README.
  - Fixed by [Josh Brown](https://github.com/joshuatbrown) in Pull Request
    [#500](https://github.com/Alamofire/Alamofire/pull/500).
- Cookies are now only applied in the DebugPrintable API when appropriate.
  - Fixed by [Alex Plescan](https://github.com/alexpls) in Pull Request
    [#516](https://github.com/Alamofire/Alamofire/pull/516).

## [1.2.2](https://github.com/Alamofire/Alamofire/releases/tag/1.2.2)

Released on 2015-05-13. All issues associated with this milestone can be found using this
[filter](https://github.com/Alamofire/Alamofire/issues?utf8=✓&q=milestone%3A1.2.2).

#### Added

- Contributing Guidelines document to the project.
  - Added by [Mattt Thompson](https://github.com/mattt).
- Documentation to the `URLStringConvertible` protocol around RFC specs.
  - Added by [Mattt Thompson](https://github.com/mattt) in regards to Issue
    [#464](https://github.com/Alamofire/Alamofire/pull/464).
- The `Carthage/Build` ignore flag to the `.gitignore` file.
  - Added by [Tomáš Slíž](https://github.com/tomassliz) in Pull Request
    [#451](https://github.com/Alamofire/Alamofire/pull/451).
- The `.DS_Store` ignore flag to the `.gitignore` file.
  - Added by [Christian Noon](https://github.com/cnoon).
- Response status code asserts for redirect tests.
  - Added by [Christian Noon](https://github.com/cnoon).
- A CHANGELOG to the project documenting each official release.
  - Added by [Christian Noon](https://github.com/cnoon).

#### Updated

- `SessionDelegate` override closure properties to match the method signatures.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#456](https://github.com/Alamofire/Alamofire/pull/456).
- Documentation for the `Printable` protocol on `Request` to reference output stream
  rather than the specific `OutputStreamType`.
  - Updated by [Mattt Thompson](https://github.com/mattt).
- Deployment targets to iOS 8.0 and OS X 10.9 for the respective frameworks.
  - Updated by [Christian Noon](https://github.com/cnoon).
- `SessionDelegate` willPerformHTTPRedirection method to accept optional return type
  from override closure.
  - Updated by [Chungsub Kim](https://github.com/subicura) in Pull Request
    [#469](https://github.com/Alamofire/Alamofire/pull/469).
- Embedded Framework and Source File documentation in the README.
  - Updated by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#427](https://github.com/Alamofire/Alamofire/pull/427).
- Alamofire source to be split into multiple core files and feature files.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#471](https://github.com/Alamofire/Alamofire/pull/471).
- `TaskDelegate` override closure signatures and delegate method implementations.
  - Updated by [Christian Noon](https://github.com/cnoon).

#### Removed

- Travis-CI build status from the README until Xcode 6.3 is supported.
  - Removed by [Mattt Thompson](https://github.com/mattt).
- Unnecessary parentheses from closure parameters and typealiases.
  - Removed by [Christian Noon](https://github.com/cnoon).

#### Fixed

- `SessionDelegate` override closure documentation.
  - Fixed by [Siemen Sikkema](https://github.com/siemensikkema) in Pull Request
    [#448](https://github.com/Alamofire/Alamofire/pull/448).
- Some inaccurate documentation on several of the public `SessionDelegate` closures.
  - Fixed by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#456](https://github.com/Alamofire/Alamofire/pull/456).
- A deinit race condition where the task delegate queue could fail to `dispatch_release`.
  - Fixed by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#379](https://github.com/Alamofire/Alamofire/pull/379).
- `TaskDelegate` to only set `qualityOfService` for `NSOperationQueue` on iOS 8+.
  - Fixed by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#472](https://github.com/Alamofire/Alamofire/pull/472).
- Expectation order issue in the redirect tests.
  - Fixed by [Christian Noon](https://github.com/cnoon).
- `DataTaskDelegate` behavior ensuring `NSProgress` values and `progress` override
  closures are always updated and executed.
  - Fixed by [Christian Noon](https://github.com/cnoon) in regards to Issue
    [#407](https://github.com/Alamofire/Alamofire/pull/407).

## [1.2.1](https://github.com/Alamofire/Alamofire/releases/tag/1.2.1)

Released on 2015-04-21.

#### Added

- Redirect tests for the `SessionDelegate`.
  - Added by [Jonathan Hersh](https://github.com/jhersh) in Pull Request
    [#424](https://github.com/Alamofire/Alamofire/pull/424).
- TLS evaluation test case.
  - Added by [Mattt Thompson](https://github.com/mattt).
- Additional guards to ensure unique task identifiers for upload and download tasks.
  - Added by [Mattt Thompson](https://github.com/mattt) in regards to Issue
    [#393](https://github.com/Alamofire/Alamofire/pull/393).

#### Updated

- Required Xcode version to Xcode to 6.3 in the README.
  - Updated by [Mattt Thompson](https://github.com/mattt).
- SSL validation to use default system validation by default.
  - Updated by [Michael Thole](https://github.com/mthole) in Pull Request
    [#394](https://github.com/Alamofire/Alamofire/pull/394).

## [1.2.0](https://github.com/Alamofire/Alamofire/releases/tag/1.2.0)

Released on 2015-04-09.

#### Added

- New `testURLParameterEncodeStringWithSlashKeyStringWithQuestionMarkValueParameter`
  test.
  - Added by [Mattt Thompson](https://github.com/mattt) in regards to Issue
    [#370](https://github.com/Alamofire/Alamofire/pull/370).
- New `backgroundCompletionHandler` property to the `Manager` called when the
  session background tasks finish.
  - Added by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#317](https://github.com/Alamofire/Alamofire/pull/317).

#### Updated

- `Request` computed property `progress` to no longer be an optional type.
  - Updated by [Pitiphong Phongpattranont](https://github.com/pitiphong-p) in
    Pull Request
    [#404](https://github.com/Alamofire/Alamofire/pull/404).
- All logic to Swift 1.2.
  - Updated by [Aron Cedercrantz](https://github.com/rastersize) and
    [Mattt Thompson](https://github.com/mattt).
- The `responseString` serializer to respect server provided character encoding with
  overrideable configuration, default string response serialization to ISO-8859-1, as
  per the HTTP/1.1 specification.
  - Updated by [Kyle Fuller](https://github.com/kylef) and
    [Mattt Thompson](https://github.com/mattt) in Pull Request
    [#359](https://github.com/Alamofire/Alamofire/pull/359) which also resolved Issue
    [#358](https://github.com/Alamofire/Alamofire/pull/358).
- `SessionDelegate` methods to first call the override closures if set.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#317](https://github.com/Alamofire/Alamofire/pull/317).
- `SessionDelegate` and all override closures to a public ACL allowing for customization.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#317](https://github.com/Alamofire/Alamofire/pull/317).
- `SessionDelegate` class to `final`.
  - Updated by [Mattt Thompson](https://github.com/mattt).
- `SessionDelegate` header documentation for method override properties.
  - Updated by [Mattt Thompson](https://github.com/mattt).
- Xcode project to set `APPLICATION_EXTENSION_API_ONLY` to `YES` for OS X target.
  - Updated by [Mattt Thompson](https://github.com/mattt).

#### Removed

- Ambiguous response serializer methods that collided with default parameters.
  - Removed by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#408](https://github.com/Alamofire/Alamofire/pull/408).
- `SessionDelegate` initializer and replaced with default property value.
  - Removed by [Mattt Thompson](https://github.com/mattt).

#### Fixed

- Async tests where asserts were potentially not being run by by moving
  `expectation.fulfill()` to end of closures.
  - Fixed by [Nate Cook](https://github.com/natecook1000) in Pull Request
    [#420](https://github.com/Alamofire/Alamofire/pull/420).
- Small grammatical error in the ParameterEncoding section of the README.
  - Fixed by [Aaron Brager](https://github.com/getaaron) in Pull Request
    [#416](https://github.com/Alamofire/Alamofire/pull/416).
- Typo in a download test comment.
  - Fixed by [Aaron Brager](https://github.com/getaaron) in Pull Request
    [#413](https://github.com/Alamofire/Alamofire/pull/413).
- Signature mismatch in the `dataTaskDidBecomeDownloadTask` override closure.
  - Fixed by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#317](https://github.com/Alamofire/Alamofire/pull/317).
- Issue in the `SessionDelegate` where the `DataTaskDelegate` was not being called.
  - Fixed by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#317](https://github.com/Alamofire/Alamofire/pull/317).

---

## [1.1.5](https://github.com/Alamofire/Alamofire/releases/tag/1.1.5)

Released on 2015-03-26.

#### Added

- Convenience upload functions to the `Manager`.
  - Added by [Olivier Bohrer](https://github.com/obohrer) in Pull Request
    [#334](https://github.com/Alamofire/Alamofire/pull/334).
- Info to the README about Swift 1.2 support.
  - Added by [Mattt Thompson](https://github.com/mattt).

#### Updated

- All request / upload / download methods on `Manager` to match the top-level functions.
  - Updated by [Mattt Thompson](https://github.com/mattt).
- The `testDownloadRequest` to no longer remove the downloaded file.
  - Updated by [Mattt Thompson](https://github.com/mattt).
- Ono XML response serializer example in the README.
  - Updated by [Mattt Thompson](https://github.com/mattt).
- Travis-CI settings to only build the master branch.
  - Updated by [Mattt Thompson](https://github.com/mattt).
- Code signing identities for the frameworks and targets to better support Carthage.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#400](https://github.com/Alamofire/Alamofire/pull/400).
- iOS deployment target to iOS 8.0 for iOS target and tests.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#401](https://github.com/Alamofire/Alamofire/pull/401).
- Legal characters to be escaped according to RFC 3986 Section 3.4.
  - Updated by [Stephane Lizeray](https://github.com/slizeray) in Pull Request
    [#370](https://github.com/Alamofire/Alamofire/pull/370).

#### Fixed

- Travis-CI scheme issue, added podspec linting and added ENV variables.
  - Fixed by [Jonathan Hersh](https://github.com/jhersh) in Pull Request
    [#351](https://github.com/Alamofire/Alamofire/pull/351).
- Code sample in the README in the Manual Parameter Encoding section.
  - Fixed by [Petr Korolev](https://github.com/skywinder) in Pull Request
    [#381](https://github.com/Alamofire/Alamofire/pull/381).

## [1.1.4](https://github.com/Alamofire/Alamofire/releases/tag/1.1.4)

Released on 2015-01-30.

#### Added

- Podspec argument `requires_arc` to the podspec file.
  - Added by [Mattt Thompson](https://github.com/mattt).
- Support for Travis-CI for automated testing purposes.
  - Added by [Kyle Fuller](https://github.com/kylef) in Pull Request
    [#279](https://github.com/Alamofire/Alamofire/pull/279).

#### Updated

- Installation instructions in the README to include CocoaPods, Carthage and
  Embedded Frameworks.
  - Updated by [Mattt Thompson](https://github.com/mattt).
- Travis-CI to use Xcode 6.1.1.
  - Updated by [Mattt Thompson](https://github.com/mattt).
- The `download` method on `Manager` to use `Request.DownloadFileDestination` typealias.
  - Updated by [Alexander Strakovich](https://github.com/astrabot) in Pull Request
    [#318](https://github.com/Alamofire/Alamofire/pull/318).
- `RequestTests` to no longer delete all cookies in default session configuration.
  - Updated by [Mattt Thompson](https://github.com/mattt).
- Travis-CI yaml file to only build the active architecture.
  - Updated by [Mattt Thompson](https://github.com/mattt).
- Deployment targets to iOS 7.0 and Mac OS X 10.9.
  - Updated by [Mattt Thompson](https://github.com/mattt).

#### Removed

- The `tearDown` method in the `AlamofireDownloadResponseTestCase`.
  - Removed by [Mattt Thompson](https://github.com/mattt).

#### Fixed

- Small formatting issue in the CocoaPods Podfile example in the README.
  - Fixed by [rborkow](https://github.com/rborkow) in Pull Request
    [#313](https://github.com/Alamofire/Alamofire/pull/313).
- Several issues with the iOS and OSX targets in the Xcode project.
  - Fixed by [Mattt Thompson](https://github.com/mattt).
- The `testDownloadRequest` in `DownloadTests` by adding `.json` file extension.
  - Fixed by [Martin Kavalar](https://github.com/mk) in Pull Request
    [#302](https://github.com/Alamofire/Alamofire/pull/302).
- The `AlamofireRequestDebugDescriptionTestCase` on OSX.
  - Fixed by [Mattt Thompson](https://github.com/mattt).
- Spec validation error with CocoaPods 0.36.0.beta-1 by disabling -b flags in `cURL`
  debug on OSX.
  - Fixed by [Mattt Thompson](https://github.com/mattt).
- Travis-CI build issue by adding support for an `iOS Example` scheme.
  - Fixed by [Yasuharu Ozaki](https://github.com/yasuoza) in Pull Request
    [#322](https://github.com/Alamofire/Alamofire/pull/322).

## [1.1.3](https://github.com/Alamofire/Alamofire/releases/tag/1.1.3)

Released on 2015-01-09.

#### Added

- Podspec file to support CocoaPods deployment.
  - Added by [Marius Rackwitz](https://github.com/mrackwitz) in Pull Request
    [#218](https://github.com/Alamofire/Alamofire/pull/218).
- Shared scheme to support Carthage deployments.
  - Added by [Yosuke Ishikawa](https://github.com/ishkawa) in Pull Request
    [#228](https://github.com/Alamofire/Alamofire/pull/228).
- New target for Alamofire OSX framework.
  - Added by [Martin Kavalar](https://github.com/mk) in Pull Request
    [#293](https://github.com/Alamofire/Alamofire/pull/293).

#### Updated

- Upload and Download progress state to be updated before calling progress closure.
  - Updated by [Alexander Strakovich](https://github.com/astrabot) in Pull Request
    [#278](https://github.com/Alamofire/Alamofire/pull/278).

#### Fixed

- Some casting code logic in the Generic Response Object Serialization example in
  the README.
  - Fixed by [Philip Heinser](https://github.com/philipheinser) in Pull Request
    [#258](https://github.com/Alamofire/Alamofire/pull/258).
- Indentation formatting of the `responseString` parameter documentation.
  - Fixed by [Ah.Miao](https://github.com/mrahmiao) in Pull Request
    [#291](https://github.com/Alamofire/Alamofire/pull/291).

## [1.1.2](https://github.com/Alamofire/Alamofire/releases/tag/1.1.2)

Released on 2014-12-21.

#### Added

- POST request JSON response test.
  - Added by [Mattt Thompson](https://github.com/mattt).

#### Updated

- The response object example to use a failable initializer in the README.
  - Updated by [Mattt Thompson](https://github.com/mattt) in regards to Issue
    [#230](https://github.com/Alamofire/Alamofire/pull/230).
- Router example in the README by removing extraneous force unwrap.
  - Updated by [Arnaud Mesureur](https://github.com/nsarno) in Pull Request
    [#247](https://github.com/Alamofire/Alamofire/pull/247).
- Xcode project `APPLICATION_EXTENSION_API_ONLY` flag to `YES`.
  - Updated by [Michael Latta](https://github.com/technomage) in Pull Request
    [#273](https://github.com/Alamofire/Alamofire/pull/273).
- Default HTTP header creation by moving it into a public class method.
  - Updated by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#261](https://github.com/Alamofire/Alamofire/pull/261).

#### Fixed

- Upload stream method to set `HTTPBodyStream` for streamed request.
  - Fixed by [Florent Vilmart](https://github.com/flovilmart) and
    [Mattt Thompson](https://github.com/mattt) in Pull Request
    [#241](https://github.com/Alamofire/Alamofire/pull/241).
- ParameterEncoding to compose percent-encoded query strings from
  percent-encoded components.
  - Fixed by [Oleh Sannikov](https://github.com/sunnycows) in Pull Request
    [#249](https://github.com/Alamofire/Alamofire/pull/249).
- Serialization handling of NSData with 0 bytes.
  - Fixed by [Mike Owens](https://github.com/mowens) in Pull Request
    [#254](https://github.com/Alamofire/Alamofire/pull/254).
- Issue where `suggestedDownloadDestination` parameters were being ignored.
  - Fixed by [Christian Noon](https://github.com/cnoon) in Pull Request
    [#257](https://github.com/Alamofire/Alamofire/pull/257).
- Crash caused by `Manager` deinitialization and added documentation.
  - Fixed by [Mattt Thompson](https://github.com/mattt) in regards to Issue
    [#269](https://github.com/Alamofire/Alamofire/pull/269).

## [1.1.1](https://github.com/Alamofire/Alamofire/releases/tag/1.1.1)

Released on 2014-11-20.

#### Updated

- Dispatch-based synchronized access to subdelegates.
  - Updated by [Mattt Thompson](https://github.com/mattt) in regards to Pull Request
    [#175](https://github.com/Alamofire/Alamofire/pull/175).
- iOS 7 instructions in the README.
  - Updated by [Mattt Thompson](https://github.com/mattt).
- CRUD example in the README to work on Xcode 6.1.
  - Updated by [John Beynon](https://github.com/johnbeynon) in Pull Request
    [#187](https://github.com/Alamofire/Alamofire/pull/187).
- The `cURL` example annotation in the README to pick up `bash` syntax highlighting.
  - Updated by [Samuel E. Giddins](https://github.com/segiddins) in Pull Request
    [#208](https://github.com/Alamofire/Alamofire/pull/208).

#### Fixed

- Out-of-memory exception by replacing `stringByAddingPercentEncodingWithAllowedCharacters`
  with `CFURLCreateStringByAddingPercentEscapes`.
  - Fixed by [Mattt Thompson](https://github.com/mattt) in regards to Issue
    [#206](https://github.com/Alamofire/Alamofire/pull/206).
- Several issues in the README examples where an NSURL initializer needs to be unwrapped.
  - Fixed by [Mattt Thompson](https://github.com/mattt) in regards to Pull Request
    [#213](https://github.com/Alamofire/Alamofire/pull/213).
- Possible exception when force unwrapping optional header properties.
  - Fixed by [Mattt Thompson](https://github.com/mattt).
- Optional cookie entry in `cURL` output.
  - Fixed by [Mattt Thompson](https://github.com/mattt) in regards to Issue
    [#226](https://github.com/Alamofire/Alamofire/pull/226).
- Optional `textLabel` property on cells in the example app.
  - Fixed by [Mattt Thompson](https://github.com/mattt).

## [1.1.0](https://github.com/Alamofire/Alamofire/releases/tag/1.1.0)

Released on 2014-10-20.

#### Updated

- Project to support Swift 1.1 and Xcode 6.1.
  - Updated by [Aral Balkan](https://github.com/aral),
    [Ross Kimes](https://github.com/rosskimes),
    [Orta Therox](https://github.com/orta),
    [Nico du Plessis](https://github.com/nduplessis)
    and [Mattt Thompson](https://github.com/mattt).

---

## [1.0.1](https://github.com/Alamofire/Alamofire/releases/tag/1.0.1)

Released on 2014-10-20.

#### Added

- Tests for upload and download with progress.
  - Added by [Mattt Thompson](https://github.com/mattt).
- Test for question marks in url encoded query.
  - Added by [Mattt Thompson](https://github.com/mattt).
- The `NSURLSessionConfiguration` headers to `cURL` representation.
  - Added by [Matthias Ryne Cheow](https://github.com/rynecheow) in Pull Request
    [#140](https://github.com/Alamofire/Alamofire/pull/140).
- Parameter encoding tests for key/value pairs containing spaces.
  - Added by [Mattt Thompson](https://github.com/mattt).
- Percent character encoding for the `+` character.
  - Added by [Niels van Hoorn](https://github.com/nvh) in Pull Request
    [#167](https://github.com/Alamofire/Alamofire/pull/167).
- Escaping for quotes to support JSON in `cURL` commands.
  - Added by [John Gibb](https://github.com/johngibb) in Pull Request
    [#178](https://github.com/Alamofire/Alamofire/pull/178).
- The `request` method to the `Manager` bringing it more inline with the top-level methods.
  - Added by Brian Smith.

#### Fixed

- Parameter encoding of ampersands and escaping of characters.
  - Fixed by [Mattt Thompson](https://github.com/mattt) in regards to Issues
    [#146](https://github.com/Alamofire/Alamofire/pull/146) and
    [#162](https://github.com/Alamofire/Alamofire/pull/162).
- Parameter encoding of `HTTPBody` from occurring twice.
  - Fixed by Yuri in Pull Request
    [#153](https://github.com/Alamofire/Alamofire/pull/153).
- Extraneous dispatch to background by using weak reference for delegate in response.
  - Fixed by [Mattt Thompson](https://github.com/mattt).
- Response handler threading issue by adding a `subdelegateQueue` to the `SessionDelegate`.
  - Fixed by [Essan Parto](https://github.com/parto) in Pull Request
    [#171](https://github.com/Alamofire/Alamofire/pull/171).
- Challenge issue where basic auth credentials were not being unwrapped.
  - Fixed by [Mattt Thompson](https://github.com/mattt).

## [1.0.0](https://github.com/Alamofire/Alamofire/releases/tag/1.0.0)

Released on 2014-09-25.

#### Added

- Initial release of Alamofire.
  - Added by [Mattt Thompson](https://github.com/mattt).
