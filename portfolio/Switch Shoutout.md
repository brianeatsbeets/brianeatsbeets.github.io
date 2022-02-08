# Switch Shoutout

![login](https://user-images.githubusercontent.com/94752449/152709335-67e85c32-594c-45af-a90a-7eb91ae9e90f.png) ![switch_shoutout](https://user-images.githubusercontent.com/94752449/150655719-b92391bc-591c-4fec-b73d-09a23fb4ba49.PNG)

Switch Shoutout is a companion app for the Nintendo Switch that allows users to notify friends of games they were playing, add their game library, and chat with friends.

This was my first serious attempt at a complete iOS project. It utilized many different facets of iOS interface functionality as well as a number of backend frameworks/utilities (UserDefaults, Firebase database, OneSignal for push notifications, etc.). It currently exists in a bit of a broken and outdated state, and the Firebase database is no longer active. My purpose in uploading this is to preserve my first passion project and give me a goal to surpass in the future. Decisions and methodologies used in this app do not reflect my current knowledge and judgement.

Below are some of the features used in this app:
- Firebase Database
  - User registration and authentication
  - Profile and friend management
  - Mirrored UserDefaults local storage for quick loading of data to UI
- OneSignal (push notifications)
- Pods
  - Alamofire
  - Firebase
  - Onesignal
  - ReachabilitySwift
  - and many more, for better or worse
