# Blog Post: How to select the correct architecture for your next enterprise mobile application

## Comparison Chart:

| No  | Functionality                                      | Native [n/5] | Web [n/5] | Hybrid [n/5] |
| --- | :---                                               | :---         | :---      | :---         |
| 1   | Tapping into the device hardware capability        | 5            | 2         | 4            |
| 2   | Computational Power                                | 5            | 3         | 5            |
| 3   | Local Storage, Offline Capability                  | 5            | 3         | 4            |
| 4   | User Experience, User Interaction & Personlization | 5            | 4         | 4            |
| 5   | Responsive Design                                  | 2            | 5         | 5            |
| 6   | Monetization                                       | 3            | 4         | 3            |
| 7   | Time to Market, Approvals in App-stores            | 3            | 5         | 3            |
| 8   | Application Update Frequency                       | 3            | 5         | 3            |
| 9   | Dsicoverability, SEO, Application Reach            | 3            | 5         | 3            |
| 10  | Internationalization & Localization                | 5            | 5         | 5            |
| 11  | Prototyping Options                                | 5            | 4         | 4            |
| 12  | Charts & Graphs                                    | 3            | 5         | 4            |
| 13  | Platform Independence                              | 2            | 5         | 4            |
| 14  | Gaming Applications                                | 5            | 3         | 4            |
| 15  | Development Cost                                   | 3            | 5         | 4            |
| 16  | Open Source Contribution & 3rd Party Framework     | 3            | 5         | 5            |

## Notes on each of the items in the comparison chart:
  1. Tapping into the device hardware capability
    - accessing the camera
    - bluetooth connectivity
    - GPS
    - scanning
    - accelerometer
    - photo library
    - Native apps give full access to the latest and greatest device features
  2. Computational Power
    - Apps that require more computational power (i.e. photo processing,
      gaming) are better suited for native apps
    - responsive-web apps suffer the most in this category since it's
      dependent on the web browser.
      + both UI and the business logic run on the same thread
    - hybrid apps:
      + embedded webview hybrid apps have the same issue as responsive-web
        app
      + react-native and titanium have multi-threading built in
  3. Local Storage, Offline Capability
    - Native/Hybrid: core data, local db, sqlite
    - responsive-web: application cache, local storage, session storage
  4. User Experience, User Interaction & Personlization
    - Gestures like zoom, pan, scoll, swipe are better and smoother in
      native and hybrid apps
    - responsive-web and embeded hybrid apps are limited by the capability
      of a web browser
    - rendering large amount of tabular data can hinder performance for
      responsive-web app due to the UI and business logic being on the
      same thread
  5. Responsive Design
    - Biggest advantage for responsive-web apps
    - One code base that can accommodate multiple screen sizes and
      platforms
    - large number of css frameworks are available such as bootstrap, 960
      Grid, Susy, etc.
  6. Monetization
    - Native and hybrid - monetization opportunities thru app store or
      in-app purchase
    - responsive-web - advertisements and subscriptions
  7. Time to Market, Approvals in App-stores
    - Responsive-web - quickest time to market since it doesn't have to go
      through any app-store approvals
    - Hybrid and native - can take significantly longer due to the
      approval process.
      + Apple's guidelines are the most stringent
  8. Application Update Frequency
    - similar to time to market
  9. Dsicoverability, SEO, Application Reach
    - native and hybrid apps are closed environments and cannot be crawled
      by search engines
    - responsive-web have a much wider reach and bigger audience
  10. Internationalization & Localization
  11. Prototyping Options
  12. Charts & Graphs
  13. Platform Independence
  14. Gaming Applications
  15. Development Cost
  16. Open Source Contribution & 3rd Party Framework

## Quick descriptions on each type:

#### Native Applications
  + distributed through app store and installed locally on device
    - android allows for side loading of apps
    - recently, as of iOS 9 allows for sideloading of apps
  + Tightly integrated with the underlying operating system
  + Dependent on app-store approvals
    - more difficult for iOS apps
  + Has to be built for specific screen sizes
    - more difficult for Android because of all the different devices
    - easier to handle for iOS due to Apple's hardware control
  + requires devs that have obj-c/swift/java/c++ skills

#### Web Responsive Applications
  + Works in web or mobile-web browser
  + primarily built with HTML5/CSS/JS
  + Requires web browser to run
  + Fastest time-to-market
  + can mimic the look of a native app
  + can be responsive in nature to run across multiple devices and screen sizes

#### Hybrid Applications
  + cross platform
  + primarily built with HTML5/CSS/JS
  + same time to market as native - dependent on app store approvals
  + Two major different types of hybrid apps
    - Embedded webview in a native wrapper
      + phonegap
      + ionic
    - Native components with API's that are accessible to JS
      + react-native
      + titanium
      + xamarin

## Research
  + [HTML5 is Quietly Changing the App Landscape](http://goo.gl/XJO0MV)
  + [The Beauty of React Native](https://goo.gl/vXAI5i)
  + [Ionic vs React-Native](https://goo.gl/7ry802)

