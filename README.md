# ManyMath/monorepo

A monorepo used for development of ManyMath.

## Getting started

```
git clone git@github.com:ManyMath/monorepo
cd monorepo
git submodule update --init --recursive
cd xmrdart
dart pub get
dart --enable-experiment=native-assets run bin/xmrdart_example.dart
```
<!--- TODO: Remove the `git submodule update --init --recursive` step after libxmr transitions from monero-serai to monero-wallet. --->
and wait a moment as the native assets are built.

Refer to the submodules for their documentation.
