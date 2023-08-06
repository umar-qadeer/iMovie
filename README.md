# iMovie


![Platform](https://img.shields.io/badge/Platform-iOS-orange.svg)
![Languages](https://img.shields.io/badge/Language-Swift-orange.svg)

iOS code challange.

## Demo
<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExam9jdjU4eGEyMTBtMXF1ZXZydWt1Z3BhZ3lianFsYTk4OW9tbnF4NSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/0LoX7X2U3bvaF2bdmW/giphy.gif" width="222" height="480" />

## Features

- [x] iMovie is implemented with SwiftUI
- [x] Architecture is MVVM with DIContainers and Repository
- [x] Network Requests using URLSession
- [x] HTTP Response Validation
- [x] Image Caching
- [x] Unit Tests
- [x] Zero warnings
- [x] No Dependencies

## Requirements

- iOS 16.0+
- Xcode 14.2+
- Swift 5.5+

## Design Pattern: Model-View-ViewModel Coordinator (MVVM)
is a structural design pattern that separates objects into three distinct groups:
- #### Model 
  - Contains the data models of the application
- #### View
  - View layer contains the UI (UIViewController).
- #### ViewModel
  - The communication layer between model and views. It also contains the business logic.
  
- ### Coding flow
    - View -> ViewModel -> Repository -> NetworkLayer.
    

## Installation

### Clone Or Download Repository

- Clone the project and open 'iMovie.xcodeproj'.
