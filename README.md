# Show Location
Sample android app for determining current lattitude/longitude using location service

Note that this app requires permissions to access either find or coarse grained location on the device.

An interesting observation from installing this app on my actual phone is that if the location is constantly checking the location then it will drain the battery, so I limited the checks to update every minute (6000msec).
