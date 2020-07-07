# Spike
Using Ionic and various other development tools to develop a enterprise grade, cross-platform video conferencing application

### Application Requirements
* Face-to-face video conferencing
* Screen sharing
* Scheduling
* Messaging
* Recording
  * Potentially transcription
  * Potentially Cloud Recording
* Real-time drawing tools

## Development and Deployment Tools
### Ionic
Cross platform framework focused on UX and UI
#### Pros
* Modern native UI components
* UI components are shared from platform to platform
* Only create one code base that can conveniently be ported anywhere
* Easily port to a desktop app using ElectronJS

### Angular
Cross platform framework for Node.js applications
#### Pros
* Code splitting using component routing for a faster and more efficient application

### ElectronJS
Tool to create a desktop application for macOS or Windows with JavaScript
#### Pros
* Open source solution to build cross-platform desktop apps with JavaScript, HTML, and CSS
* Assortment of APIs and add ons
* Use Electron as a desktop shell for a web-hybrid ionic application

### Fastlane
Quickest way to build and deploy apps to marketplaces such as iOS App Store or Android Marketplace
#### Pros
* Automated code signing, uploading, and changelog
* Freely switch between betas without reconfiguring Fastlane

#### Cons
* Cannot automate signing and deploying to macOS App Store or Microsoft store

### Jenkins
Open source CICD server solution
#### Pros
* Integration with Fastlane
* Easy configuration with web interface
* Many extendable plugins
* Distributable to many devices
* Multiple test recording, reporting, and visualization plugins
* JUnit and Karma testing integration
