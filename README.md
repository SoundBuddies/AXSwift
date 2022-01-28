# AXSwift

Forked from tmandry and added some convenience functions and computed properties. 

Use the following link for Swift Package Manager
```
.package(url: "https://github.com/SoundBuddies/AXSwift", from: 0.3.0"),"
```


# AXSwift


AXSwift is a Swift wrapper for macOS's C-based accessibility client APIs. Working with these APIs is
error-prone and a huge pain, so AXSwift makes everything easier:

- Modern API that's 100% Swift
- Explicit error handling
- Complete coverage of the underlying C API
- Better documentation than Apple's, which is pretty poor

This framework is intended as a basic wrapper, and doesn't keep any state or do any "magic".
That's up to you!

## Using AXSwift

### SPM
In your Package.swift:
```
.package(url: "https://github.com/tmandry/AXSwift", from: "0.3.0"),
```


