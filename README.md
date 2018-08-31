# esk8bluetoothapp
my iOS app in beta testing for the open source electronic speed controller

an iphone app the communicates with an open source electronic speed controller
via bluetooth low energy through the CAN bus.

the open source hardware design and infomation can be found here
http://vedder.se

my ios app uses a HM-10 bluetooth low energy module. the app is built via
native swift for iOS 11 and upp.

App features
- Geo Tracking
- Geo Pathing
- Telementry Data retrived from the Vesc
- Profiling, allowing users to switch modes on their skateboard
- Trip Logging, keeps track of users ride data, such as avg speed, top speed, distance, duration and date.
- Trip logging also keeps track of the route and will draw a line on google maps to view the route
- Support for multiple localized regions. Metric system, imperal system.
- GPS Speed tracking and or speed via gear ratios from motor gear and wheel gear calulcated from the RPM from the motor
- Also keeps track of voltage of your skateboard
- Calculates battery life percent and shows an anmation of a battery bar
- Calculates watt-hour per unit distance, KM or MI
- Fetches weather data from openweathermaps API to gather tempature for current geo location and wind speeds, refreshes every 15 minutes
- Tracks Elevation of the user as they ride.

https://betatestesk8.herokuapp.com/
visit here to try out the app!

beta test is over, app is officaly on app store
https://itunes.apple.com/us/app/xmatic-electric-skateboard/id1382937037?ls=1&mt=8
