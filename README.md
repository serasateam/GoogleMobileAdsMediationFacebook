# FBAudienceNetwork iOS SDK
FBAudienceNetwork iOS SDK for Swift Package Manager.

# Integration
The Swift Package Manager is a tool for managing the distribution of Swift code. It’s integrated with the Swift build system to automate the process of downloading, compiling, and linking dependencies.
To integrate the FBAudienceNetwork SDK into your project using Swift Package Manager:
1. Add it to the dependencies of your Package.swift:
```objc
    dependencies: [
        .package(url: "https://github.com/serasateam/GoogleMobileAdsMediationFacebook", .exact("6.9.0"))
    ]
```
2. Enable the `-ObjC` flag in Xcode: select Build Settings, search for Other Linker Flags and add `-ObjC`.

Check out our [integration docs](https://developers.facebook.com/docs/audience-network/setting-up/platform-setup/ios/add-sdk) for more info on getting started with FBAudienceNetwork SDK.

## Author

denys.galante, denys.galante@br.experian.com
