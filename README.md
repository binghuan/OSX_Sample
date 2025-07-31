# macOS Development Sample Collection

This repository contains two demonstration projects showcasing JavaScript integration techniques with macOS applications.

## Project Overview

### 1. CallJS - WebKit JavaScript Interaction Sample

The `CallJS` project demonstrates how to use the WebKit framework in macOS applications to achieve bidirectional communication between Objective-C and JavaScript.

**Key Features:**
- Embed WebView in macOS applications
- Call JavaScript functions from Objective-C with parameters
- Callback Objective-C methods from JavaScript
- Implement data sharing between Objective-C and JavaScript

**Technical Highlights:**
- Uses WebKit framework's WebView component
- Implements WebScripting protocol to expose Objective-C methods to JavaScript
- Demonstrates handling of JavaScript alert dialogs
- Provides complete bidirectional communication mechanism

**File Structure:**
- `SampleController.h/m`: Main controller handling WebView and JavaScript interaction
- `test.html`: Test page containing JavaScript functions
- `MainMenu.nib`: Application user interface

### 2. ColorMyWords - JavaScriptCore Text Coloring Application

`ColorMyWords` is a simple text editing application that uses the JavaScriptCore framework to provide color highlighting for typed text.

**Key Features:**
- Real-time text color highlighting
- JavaScript engine for color processing logic
- NSTextView integration with JavaScriptCore
- Dynamic text styling

**Technical Highlights:**
- Uses JavaScriptCore.framework to execute JavaScript code
- Implements NSTextStorageDelegate for handling text changes
- Efficient data exchange between JavaScript and Objective-C
- Demonstrates modern macOS JavaScript integration best practices

**File Structure:**
- `AppDelegate.h/m`: Application delegate and main logic
- `colors.js`: JavaScript plugin handling text color highlighting logic
- `MainMenu.xib`: Application user interface

## Development Requirements

- **Xcode**: Supporting Objective-C development
- **macOS SDK**: Including WebKit and JavaScriptCore frameworks
- **Target System**: macOS 10.7 or higher

## Usage Instructions

### CallJS Project
1. Open `CallJS/CallJS.xcodeproj` in Xcode
2. Build and run the project
3. Enter parameters in the interface to test JavaScript function calls
4. Observe the interaction between Objective-C and JavaScript

### ColorMyWords Project
1. Open `ColorMyWords/ColorMyWords.xcodeproj` in Xcode
2. Build and run the project
3. Type text in the text area and observe real-time color highlighting
4. Experience the integration of JavaScriptCore with text processing

## Learning Points

These sample projects demonstrate:

1. **WebKit Integration**: How to embed web content in native macOS applications and achieve interaction
2. **JavaScript Bridging**: Two different JavaScript integration approaches (WebKit vs JavaScriptCore)
3. **Delegate Pattern**: Implementation of delegate patterns in macOS development
4. **Interface Design**: Using Interface Builder to design native macOS interfaces
5. **Resource Management**: Memory management best practices in Objective-C
