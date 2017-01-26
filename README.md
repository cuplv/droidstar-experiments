# DroidStar #

## Building the library ##

You will need the [`sbt`](http://www.scala-sbt.org/) scala/java build
tool installed on your system.  Please follow
[the installation directions on the `sbt` site](http://www.scala-sbt.org/download.html).

If you have the Android SDK installed on your system, make sure the
environment variable `ANDROID_HOME` in pointing to the SDK root
directory.  If you don't have it, `sbt` will fetch it for you when you
build the application.

The application can be built compiled and packaged in one go.  From
the project's root directory (where this README is located), run:

    sbt android:package

The resulting jar will be placed at:

    target/android/intermediates/classes.jar
