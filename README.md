# SwiftLintPlugin

SwiftPM build tool plugin for SwiftLint

## Usage

### Package.swift

```swift
dependencies: [
    .package(url: "https://github.com/usami-k/SwiftLintPlugin", branch: "main"),
],
targets: [
    .target(
        name: "MyTarget",
        plugins: [
            .plugin(name: "SwiftLintPlugin", package: "SwiftLintPlugin"),
        ]
    )
]
```

## Xcode Project Sample

https://github.com/usami-k/XcodeSwiftPMSample

## Thanks

This plugin uses binary artifact created by [juozasvalancius](https://github.com/juozasvalancius).

Thanks to https://github.com/juozasvalancius/ExampleSPMProjectWithSwiftLint

