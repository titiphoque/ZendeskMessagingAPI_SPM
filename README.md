# ZendeskMessagingAPI_SPM

SPM Package to make Zendesk MessagingAPI available via SPM

## Installation

```swift
dependencies: [
    .package(
        name: "MessagingAPI", url: "https://github.com/titiphoque/ZendeskMessagingAPI_SPM", 
        .upToNextMajor(from: "3.8.0")
    )
]
```

and in `target` :

```swift
dependencies: [
    .product(name: "MessagingAPI", package: "MessagingAPI"),
]
```
