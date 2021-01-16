
To build the jitsi-meet sdk, and then include it in the Android set top box

In this repository:

./android/scripts/release-sdk.sh ../FAB/assistant-tv/apps/lib

This will compile the react native modules and publish a package to the "local" maven repository in the FAB assistant-tv project.

Then go an build the set top box application.  It will bundle the jitsi-meet-sdk into the set top box application.  The end result can then be published directly to the set top box through Android Studio, or built with a production key and released as an apk.
