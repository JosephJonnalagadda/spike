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
* Slick native UI components
* Can be integrated with angular

### Angular
Cross platform framework for Node.js applications
#### Pros
* Code splitting using component routing for a faster and more efficient application
* Uses Karma for unit testing for intuitive TDD

### ElectronJS
#### Pros
* Open source solution to build cross-platform desktop apps with JavaScript, HTML, and CSS
* Assortment of APIs and addons

### Fastlane
Quickest way to build and deploy apps to marketplaces such as iOS App Store or Android Marketplace
#### Pros
* Automated code signing, uploading, and changelog
* Freely switch between betas without reconfiguring Fastlane

#### Cons
* Cannot automate signing and deployment to macOS App Store

### Jenkins
Open source CICD server solution
#### Pros
* Integration with Fastlane
