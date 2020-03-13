# TimeTV

This a project for studies on architecture MVVM Cleaner, similar project template from [Kudoleh](https://github.com/kudoleh/iOS-Clean-Architecture-MVVM)

## Layers

- Domain Layer = Entities + Use Cases + Repositories Interfaces
- Data Repositories Layer = Repositories Implementations + API (Network) + Persistence DB
- Presentation Layer (MVVM) = ViewModels + Views

### Dependency Direction

![](https://raw.githubusercontent.com/kudoleh/iOS-Clean-Architecture-MVVM/master/README_FILES/CleanArchitectureDependencies.png)

Note: Domain Layer should not include anything from other layers(e.g Presentation — UIKit or SwiftUI or Data Layer — Mapping Codable)

## Requirements

- Xcode version 11+
- Swift 5.0

## Improviments

- Create a test for all layers;
- Register CI for compile;