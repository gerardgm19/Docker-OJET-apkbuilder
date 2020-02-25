# Docker-OJET-apkbuilder
Ojet project with docker. It is configured to build an apk automatically from a Ojet project


# Docker instructions
APK build at /usr/src/app/hybrid/platforms/android/app/build/outputs/apk/debug/app-debug.apk
Commands to run the apk builder:

docker build -t build-name .
docker run -it -v (local folder):/usr/src/app/apk build-name /usr/src/app/copyAPK.sh

# After run
The build file (apk) will be allocated at (project)/apk/app-debug.apk
