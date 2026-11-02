# Black for Android

An unofficial native Android port of the original Xbox version of Black, with touch controls, gamepad support, Vulkan rendering, and Android host integration.

## Supported architectures

This fork keeps Android 10+ compatibility while adding armv7a (32-bit ARM) alongside the existing arm64-v8a build.

- arm64-v8a
- armeabi-v7a

## Build notes

- minSdk: 29
- targetSdk: 34
- NDK: 28.2.13676358
- Gradle / CMake toolchain: Android Studio-managed

The app intentionally ships split APKs per ABI to keep support explicit for both 64-bit and 32-bit ARM devices.
