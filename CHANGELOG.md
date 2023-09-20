# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).  
<br/>

## [Unreleased](https://github.com/thunderbiscuit/padawan-wallet/compare/v0.11.0...master)  
<br>

## [v0.10.0 to 0.11.0](https://github.com/thunderbiscuit/padawan-wallet/compare/v0.10.0...v0.11.0) — September 18, 2023
### Added
+ Copy address by pressing on it
+ Better formatting for bitcoin balance
+ Sync animation
+ Automatic sync on startup
+ A lot of small UI changes
+ Better support for smaller screens
+ Start fee rate slider at 1.0
+ Migrate LiveData to Kotlin Flows
+ Images in tutorials
<br>

## [v0.9.0 to 0.10.0](https://github.com/thunderbiscuit/padawan-wallet/compare/v0.9.0...v0.10.0) — January 25, 2023
### Added
+ Fairly extensive re-write of the app
+ Brand new UI
+ New chapters
+ Better content
<br>

## [v0.8.0 to v0.9.0](https://github.com/thunderbiscuit/padawan-wallet/compare/v0.8.0...v0.9.0) — May 26, 2022
### Added
+ Complete re-write of the user interface in Jetpack Compose.
+ Many more tests
<br>

## [v0.7.2 to v0.8.0](https://github.com/thunderbiscuit/padawan-wallet/compare/v0.7.2...v0.8.0) — March 23, 2022
### Added
+ Wallet sync is now done in a coroutine
+ Add transaction fees in transaction history card
+ Add tests
+ Sync wallet on startup

### Fixed
+ Bug of tutorials done requiring restart
+ Database corruption when data not flushed to disk

### Changed
+ Intro screens UI is now written in Jetpack Compose
+ Migrate to [bdk-android](https://github.com/bitcoindevkit/bdk-kotlin)

### Removed
+ Navigation broadcast fragment  
+ Remove dependency on androidmads QR code library  
<br>

## [v0.7.0 to v0.7.2](https://github.com/thunderbiscuit/padawan-wallet/compare/v0.7.0...v0.7.2) — August 26, 2021
### Added
+ Add _Privacy Policy_
+ Clean up transaction history card UI
+ Add screen to send coins back to the Padawan Wallet project

### Changed
+ Bump bitcoindevkit dependency to `v0.3.0-rc1`  
<br>

## [v0.6.0 to v0.7.0](https://github.com/thunderbiscuit/padawan-wallet/compare/v0.6.0...v0.7.0) — June 8, 2021
### Added
+ Enable APK builds to split on ABI variants (smaller apps with only the required native bdk library)
+ Display amount received for received transactions
+ Add _About_ screen
+ Use Nunito Sans as base font

### Changed
+ Bump bitcoindevkit dependency to `v0.2.1`  
<br>

## [v0.5.0 to v0.6.0](https://github.com/thunderbiscuit/padawan-wallet/compare/v0.5.0...v0.6.0) — May 14, 2021
### Added
+ Allow new users to request testnet coins to Tatooine faucet
+ Add database to store transactions
+ Display transaction history in recyclerview
+ Use camera to scan QR code formatted bitcoin addresses
+ Add app version number to drawer  

### Changed
+ Update bitcoindevkit library to 0.2.0
+ Upload new logo `v1.0.0`  
+ Bump Kotlin version to `1.5.0`
+ Better handling of network and API failures
+ Clean up UI for larger devices
+ Tons of small UI improvements
+ Streamline use of snackbars across the app  
<br>  

## [v0.4.0 to v0.5.0](https://github.com/thunderbiscuit/padawan-wallet/compare/v0.4.0...v0.5.0) — Apr 7, 2021
### Added
+ Add QR codes when displaying receive addresses
+ Shared preferences keep track of completed tutorials
+ All 8 essential tutorials
+ Added Discord community to readme
+ Add twitter badge
+ Prevent app from going into landscape mode
+ Add GitHub Actions basic CI workflow
+ Add splash screen

### Changed
+ Better readme and docs
+ Move gradle build files to Kotlin DSL
+ Use Repository architecture element
+ Move the bitcoindevkit to Wallet Object
+ Point bdk to blockstream.info servers  
<br>  

## [v0.3.0 to v0.4.0](https://github.com/thunderbiscuit/padawan-wallet/compare/v0.3.0...v0.4.0) — Jan 12, 2021
### Added
+ Add tutorial fragments UI
+ Enable marking tutorials as done
+ Make tutorials list scrollable

### Changed
+ Various improvements to the codebase  
<br>  

## [v0.2.0 to v0.3.0](https://github.com/thunderbiscuit/padawan-wallet/compare/v0.2.0...v0.3.0) — Jan 5, 2021
### Added
+ Tutorial tab now handles fragments
+ Separate wallet and tutorials in their respective packages
+ Add tutorial navigation and draft UI
+ Add license and tags badges to readme
+ Add draft launcher icon
+ Display toggle for wallet balance in either satoshi or bitcoin
+ Added changelog
+ Set official application ID
+ Streamline use of snackbars
+ Perform basic checks on inputs for transaction building fragment

### Changed
+ Use Material alert dialog
+ Remove use of theme background colour
+ Do not generate new address by default upon navigation to receive fragment  
<br>

## [v0.1.0 to v0.2.0](https://github.com/thunderbiscuit/padawan-wallet/compare/v0.1.0...v0.2.0) — Jan 3, 2021
### Added
+ Wallet sync functionality
+ Wallet can display wallet current balance upon sync
+ Receive fragment that can generate new addresses
+ Send fragment that can create transactions
+ Verify + Broadcast fragment that can broadcast transactions  
<br>

## [v0.1.0](https://github.com/thunderbiscuit/padawan-wallet/releases/tag/v0.1.0) — Dec 20, 2020
### Added
+ Draft UI for wallet generation
+ Draft UI for home activity (wallet and tutorials)
+ Drawer activity (settings, about, etc.)
+ Navigation drawer
+ Option to display wallet recovery phrase
+ Wallet is BIP84 compatible
+ Wallet recovery functionality
