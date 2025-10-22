# Swift Android Examples

This repository contains example apps for the [Swift SDK for Android](https://www.swift.org/install/).

# Build and run

1. [Setup the Swift SDK for Android](https://www.swift.org/documentation/articles/swift-android-getting-started.html)
2. Clone this repository
3. Open the whole project in Android Studio
4. Select the example app you want to run in the top bar (you may need to sync gradle first)
5. Click the play button to run the example

The swift-java-hashing example requires different steps, see the README there for more info.

You can also build the examples from the command line if you prefer. Use `./gradlew` to build everything. For individual tasks, see `./gradlew tasks`.

To see the tasks for an individual example, run the tasks task for that directory. For example, `./gradlew :hello-swift:tasks` will show the tasks for the hello-swift app.

You can build all sample apps for both the debug and release build types by running `./gradlew assemble`.
