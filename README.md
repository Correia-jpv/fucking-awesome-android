# Awesome Android [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/jstumpp/awesome-android/main/awesome-android.png">](https://github.com/correia-jpv/fucking-awesome-android)

<p align="center">
  <a href="https://github.com/sindresorhus/awesome"><img alt="awesome" src="https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" /></a>
  <a href="https://github.com/correia-jpv/fucking-awesome-android/actions/workflows/awesome-lint.yml"><img alt="Awesome Lint" src="https://github.com/correia-jpv/fucking-awesome-android/actions/workflows/awesome-lint.yml/badge.svg" /></a>
  <img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" />
</p>

A curated list of awesome Android libraries and resources. For general Java libraries have a look at <b><code>&nbsp;49530⭐</code></b> <b><code>&nbsp;&nbsp;7745🍴</code></b> [awesome-java](https://github.com/akullpp/awesome-java)).

Awesome-Android is an amazing list for people who need a certain feature on their app, so the best ways to use are:
- Simply press <kbd>Ctrl</kbd> + <kbd>F</kbd> (or <kbd>⌘</kbd> + <kbd>F</kbd> on macOS) to search for a keyword
- Go through our Content Menu

## Contents
- [Emulators](#emulators)
- [Libraries](#libraries)
	- [Jetpack Compose](#jetpack-compose)
	- [Architecture](#architecture)
	- [Charts](#charts)
	- [Data binding](#data-binding)
	- [Dependency Injection](#dependency-injection)
	- [Game Development](#game-development)
	- [Security](#security)
	- [GUI](#gui)
	- [JSON](#json)
	- [Crash monitoring](#crash-monitoring)
	- [Networking](#networking)
	- [Logger](#logger)
	- [Database](#database)
	- [Testing](#testing)
	- [Tracking](#tracking)
	- [Maps](#maps)
	- [Utility](#utility)
	- [Debugging Tools](#debugging-tools)
	- [Wireless](#wireless)
	- [Chat & Messaging](#chat--messaging)
	- [Date & Time](#date--time)
	- [Payments](#payments)
	- [Google Play](#google-play)
	- [Code Quality](#code-quality)
	- [Other](#other)
- [Resources](#resources)
	- [Code examples](#code-examples)
	- [Podcasts](#podcasts)
	- [More lists of libraries](#more-lists-of-libraries)
- [Development Alternatives](#development-alternatives)
	- [Cross-Platform](#cross-platform)
	- [Kotlin Multiplatform](#kotlin-multiplatform)
- [Build & Performance](#build--performance)
- [Other Awesome Lists](#other-awesome-lists)

## Emulators
- 🌎 [Android Emulator](developer.android.com/studio/run/emulator) - Official Android emulator integrated into Android Studio.
- 🌎 [Genymotion](www.genymotion.com) - Fast Android emulator for app testing and development. *Commercial*

## Libraries

### Jetpack Compose

- 🌎 [Jetpack Compose](developer.android.com/compose) - Modern toolkit for building native Android UI with declarative Kotlin APIs and Material 3 support.

### Architecture

- <b><code>&nbsp;&nbsp;1860⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;124🍴</code></b> [Circuit](https://github.com/slackhq/circuit)) - Modern architecture framework for building Android apps with Compose.
- <b><code>&nbsp;&nbsp;2890⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;111🍴</code></b> [Decompose](https://github.com/arkivanov/Decompose)) - Kotlin Multiplatform library for breaking down your code into lifecycle-aware business logic components.

### Charts

- <b><code>&nbsp;38187⭐</code></b> <b><code>&nbsp;&nbsp;8962🍴</code></b> [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)) - An Android chart and graph library supporting scaling and dragging by gesture.
- <b><code>&nbsp;&nbsp;3204⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;203🍴</code></b> [Vico](https://github.com/patrykandpatrick/vico)) - Modern chart library with support for both Jetpack Compose and Android Views.

### Data binding

- 🌎 [Data Binding Library](developer.android.com/topic/libraries/data-binding/) - Official Android Data Binding Library to write declarative layouts and minimize the glue code necessary to bind application logic and layouts.

### Dependency Injection

- 🌎 [Hilt](developer.android.com/training/dependency-injection/hilt-android) - Official dependency injection library built on top of Dagger for Android.
- <b><code>&nbsp;17689⭐</code></b> <b><code>&nbsp;&nbsp;2042🍴</code></b> [Dagger 2](https://github.com/google/dagger)) - A fast dependency injector for Android and Java.
- 🌎 [Koin](insert-koin.io/) - Lightweight dependency injection framework for Kotlin.

### Game Development

- 🌎 [Libgdx](libgdx.com/) - Cross-platform game engine and SDK. <b><code>&nbsp;25527⭐</code></b> <b><code>&nbsp;&nbsp;6522🍴</code></b> [Open Source](https://github.com/libgdx/libgdx))
- <b><code>120109⭐</code></b> <b><code>&nbsp;27490🍴</code></b> [Godot](https://github.com/godotengine/godot)) - Cross-platform 2/3D game engine with an IDE and under MIT license.
- 🌎 [Vuforia](www.ptc.com/en/products/vuforia) - Augmented Reality library. *Commercial*
- 🌎 [Unity](unity.com/features/multiplatform) - Cross-platform game creation system. *Commercial*

### Security

- <b><code>&nbsp;&nbsp;&nbsp;315⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41🍴</code></b> [Google Tink](https://github.com/tink-crypto/tink-java)) - Multi-language cross-platform cryptography library providing secure APIs for common cryptographic tasks.

### GUI

- <b><code>&nbsp;17453⭐</code></b> <b><code>&nbsp;&nbsp;3227🍴</code></b> [Material Components for Android](https://github.com/material-components/material-components-android)) - Modular and customizable Material Design UI components for Android.
- 🌎 [Navigation](developer.android.com/guide/navigation) - Framework for building in-app navigation with type-safe argument passing.
- 🌎 [Pull to refresh](developer.android.com/reference/androidx/swiperefreshlayout/widget/SwipeRefreshLayout) - A swipe refresh layout is available in AndroidX.
- <b><code>&nbsp;&nbsp;5458⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;589🍴</code></b> [TapTargetView](https://github.com/KeepSafe/TapTargetView)) - An implementation of tap targets from the Material Design guidelines for feature discovery.
- <b><code>&nbsp;&nbsp;7809⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;769🍴</code></b> [Litho (By Meta)](https://github.com/meta/litho)) - A declarative framework for building efficient UIs on Android.
- <b><code>&nbsp;11640⭐</code></b> <b><code>&nbsp;&nbsp;2010🍴</code></b> [MaterialDrawer](https://github.com/mikepenz/MaterialDrawer)) - Simple take on a material design navigation drawer.
- <b><code>&nbsp;10566⭐</code></b> <b><code>&nbsp;&nbsp;1760🍴</code></b> [AppIntro](https://github.com/AppIntro/AppIntro)) - Library for creating beautiful intro slides for your app.
- <b><code>&nbsp;35771⭐</code></b> <b><code>&nbsp;&nbsp;5426🍴</code></b> [Lottie](https://github.com/airbnb/lottie-android)) - Library for rendering After Effects animations natively on Android.
- <b><code>&nbsp;12430⭐</code></b> <b><code>&nbsp;&nbsp;2406🍴</code></b> [Android View Animations](https://github.com/daimajia/AndroidViewAnimations)) - Cute view animation collection.
- <b><code>&nbsp;&nbsp;7229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;962🍴</code></b> [Compressor](https://github.com/zetbaitsu/Compressor)) - Lightweight and powerful Android image compression library.
- <b><code>&nbsp;&nbsp;3607⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;362🍴</code></b> [Material Dots Indicators](https://github.com/tommybuonomo/dotsindicator)) - Three Material Dots Indicators styles for View Pagers.
- <b><code>&nbsp;35011⭐</code></b> <b><code>&nbsp;&nbsp;6168🍴</code></b> [Glide](https://github.com/bumptech/glide)) - An image loading and caching library for Android focused on smooth scrolling, Recommended by Google.
- <b><code>&nbsp;17163⭐</code></b> <b><code>&nbsp;&nbsp;3733🍴</code></b> [Fresco](https://github.com/meta/fresco)) - An Android library for managing images and the memory they use.
- <b><code>&nbsp;11959⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;801🍴</code></b> [Coil](https://github.com/coil-kt/coil)) - Image loading for Android backed by Kotlin Coroutines.
- <b><code>&nbsp;&nbsp;3074⭐</code></b> <b><code>&nbsp;&nbsp;1020🍴</code></b> [Media3 (ExoPlayer)](https://github.com/androidx/media)) - Jetpack Media3 support libraries for media use cases, including ExoPlayer, an extensible media player for Android.
- 🌎 [CameraX](developer.android.com/training/camerax) - Jetpack library that makes camera app development easier with consistent API across devices.


### JSON

- <b><code>&nbsp;&nbsp;5955⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;692🍴</code></b> [kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization)) - Kotlin multiplatform serialization library with JSON support.
- <b><code>&nbsp;24230⭐</code></b> <b><code>&nbsp;&nbsp;4512🍴</code></b> [Gson](https://github.com/google/gson)) - Java library used for serializing and deserializing Java objects from and into JSON.
- <b><code>&nbsp;&nbsp;9836⭐</code></b> <b><code>&nbsp;&nbsp;1223🍴</code></b> [Jackson JSON Processor](https://github.com/FasterXML/jackson)) - High-performance JSON processor.
- <b><code>&nbsp;10164⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;819🍴</code></b> [Moshi](https://github.com/square/moshi)) - A modern JSON library for Android and Java.
### Crash monitoring

- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?🍴</code></b> [Measure](https://github.com/measure-sh/measure/)) - Open source tool to monitor crashes, ANRs, and performance of mobile apps. Can be self-hosted.
- <b><code>&nbsp;&nbsp;1362⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;481🍴</code></b> [Sentry Android](https://github.com/getsentry/sentry-java)) - Open source error tracking with real-time crash reporting. *Commercial (has free tier)*
- 🌎 [Bugsnag](www.bugsnag.com/) - Cross platform error monitoring. Free tier. Support for SDK & NDK. Error reports include data on device, release, user, and allows arbitrary data. *Commercial*
- 🌎 [Firebase Crashlytics](firebase.google.com/products/crashlytics) - Easy crash reporting solution. *Commercial (has free tier)*

### Networking

- <b><code>&nbsp;43938⭐</code></b> <b><code>&nbsp;&nbsp;7323🍴</code></b> [Retrofit](https://github.com/lysine-dev/retrofit)) - Turns your REST API into a Java interface (continued project).
- <b><code>&nbsp;47112⭐</code></b> <b><code>&nbsp;&nbsp;9285🍴</code></b> [OkHttp](https://github.com/lysine-dev/okhttp)) - An HTTP+SPDY client for Android and Java applications (continued project).
- <b><code>&nbsp;14564⭐</code></b> <b><code>&nbsp;&nbsp;1323🍴</code></b> [Ktor Client](https://github.com/ktorio/ktor)) - Asynchronous HTTP client for Kotlin with multiplatform support.
- <b><code>&nbsp;&nbsp;3976⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;699🍴</code></b> [Apollo Kotlin](https://github.com/apollographql/apollo-kotlin)) - Strongly-typed GraphQL client for Kotlin and Java.
- 🌎 [Android Volley](google.github.io/volley/) - Official Android HTTP library that makes networking for easier and faster.
- <b><code>&nbsp;&nbsp;5937⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;977🍴</code></b> [Fast-Android-Networking](https://github.com/amitshekhariitbhu/Fast-Android-Networking)) - A Complete Fast Android Networking Library that also support HTTP/2.

### Logger
- <b><code>&nbsp;10857⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;994🍴</code></b> [timber](https://github.com/JakeWharton/timber)) - A logger with a small, extensible API which provides utility on top of Android's normal Log class.
- <b><code>&nbsp;&nbsp;1044⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Kermit](https://github.com/touchlab/Kermit)) - Kotlin Multiplatform logging library with support for multiple platforms.
- <b><code>&nbsp;13826⭐</code></b> <b><code>&nbsp;&nbsp;2116🍴</code></b> [logger](https://github.com/orhanobut/logger)) - Simple, pretty and powerful logger for Android.
- <b><code>&nbsp;&nbsp;1362⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;120🍴</code></b> [LoggingInterceptor](https://github.com/ihsanbal/LoggingInterceptor)) - An OkHttp interceptor which pretty logs request and response data.
- <b><code>&nbsp;&nbsp;1265⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;185🍴</code></b> [Logback Android](https://github.com/tony19/logback-android)) - Logback port to Android which provides a highly configurable logging framework for Android apps. 

### Database
- 🌎 [Room](developer.android.com/training/data-storage/room) - Official SQLite object mapping library with compile-time verification of SQL queries.
- <b><code>&nbsp;&nbsp;6906⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;582🍴</code></b> [SQLDelight](https://github.com/sqldelight/sqldelight)) - Generates typesafe Kotlin APIs from SQL statements with Kotlin Multiplatform support.
- <b><code>&nbsp;&nbsp;4629⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;310🍴</code></b> [ObjectBox](https://github.com/objectbox/objectbox-java)) - Simple but powerful object database, optimized for performance & mobile.
- <b><code>&nbsp;&nbsp;3123⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;238🍴</code></b> [requery](https://github.com/requery/requery)) - Compile time ORM and SQL query library for Java & Android.
- <b><code>&nbsp;&nbsp;4842⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;591🍴</code></b> [DBFlow](https://github.com/agrosner/DBFlow)) - Fast and powerful ORM with compile-time annotation processing.
- <b><code>&nbsp;&nbsp;&nbsp;955⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94🍴</code></b> [DbInspector](https://github.com/infinum/android_dbinspector)) - Provides a simple way to view the contents of the in-app database for debugging purposes.
- <b><code>&nbsp;&nbsp;&nbsp;923⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;96🍴</code></b> [Nitrite Database](https://github.com/nitrite/nitrite-java)) - A NoSQL embedded document store for Android with MongoDB like API.

### Testing

- 🌎 [Espresso](developer.android.com/training/testing/espresso) - Official Android UI testing framework for writing reliable UI tests.
- <b><code>&nbsp;&nbsp;1229⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;343🍴</code></b> [AndroidX Test](https://github.com/android/android-test)) - Testing libraries for Android including JUnit rules and Espresso APIs.
- 🌎 [Roboletric](robolectric.org/) - Unit test framework to run tests inside the JVM on your workstation, not in the emulator.
- <b><code>&nbsp;&nbsp;5769⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;432🍴</code></b> [MockK](https://github.com/mockk/mockk)) - Mocking library for Kotlin with natural syntax and comprehensive DSL.
- <b><code>&nbsp;&nbsp;2874⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;137🍴</code></b> [Turbine](https://github.com/cashapp/turbine)) - Testing library for Kotlin Flows with simple and expressive assertions.
- <b><code>&nbsp;&nbsp;4789⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;705🍴</code></b> [Kotest](https://github.com/kotest/kotest)) - Flexible and comprehensive testing framework for Kotlin with multiple testing styles.
- <b><code>&nbsp;16399⭐</code></b> <b><code>&nbsp;&nbsp;1022🍴</code></b> [Maestro](https://github.com/mobile-dev-inc/maestro)) - Mobile UI testing framework for end-to-end testing with simple YAML-based syntax.
- <b><code>&nbsp;&nbsp;2640⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;273🍴</code></b> [Paparazzi](https://github.com/cashapp/paparazzi)) - Render Android screens as images for snapshot testing without a device or emulator.
- <b><code>&nbsp;&nbsp;1082⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;67🍴</code></b> [Roborazzi](https://github.com/takahirom/roborazzi)) - Screenshot testing library for Android using Robolectric.
- <b><code>&nbsp;&nbsp;&nbsp;421⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52🍴</code></b> [Ghost in the Droid](https://github.com/ghost-in-the-droid/android-agent)) - Python MCP server for AI agent control of Android and iOS devices via ADB and WebDriverAgent.
- <b><code>&nbsp;&nbsp;&nbsp;536⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58🍴</code></b> [Droidline](https://github.com/KnifeLemon/Droidline)) - Automate real Android phones from Python, Node.js, C# or a CLI over Wi-Fi, without ADB or root.

### Tracking

- 🌎 [Countly](countly.com/) - Open source mobile & web analytics, push notifications and crash reporting platform, based on Node.js, MongoDB and Linux.
- 🌎 [Mixpanel](mixpanel.com/) - Analytics platform to analyze the users. *Commercial*

### Maps

- <b><code>&nbsp;&nbsp;3625⭐</code></b> <b><code>&nbsp;&nbsp;1549🍴</code></b> [android-maps-utils](https://github.com/googlemaps/android-maps-utils)) - Utility library for Google Maps Android API with features like marker clustering and heat maps.
- <b><code>&nbsp;&nbsp;1319⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;185🍴</code></b> [Maps Compose](https://github.com/googlemaps/android-maps-compose)) - Jetpack Compose components for Google Maps.

### Utility
- 🌎 [Byte Buddy](bytebuddy.net) - Runtime code generation library with support for Android.
- <b><code>&nbsp;30009⭐</code></b> <b><code>&nbsp;&nbsp;3989🍴</code></b> [LeakCanary](https://github.com/square/leakcanary)) - Catch memory leaks as they occur.
 
### Debugging Tools

- <b><code>&nbsp;&nbsp;&nbsp;789⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;92🍴</code></b> [Linx](https://github.com/pedrovgs/Lynx)) - Show logcat inside the device for debug builds.
- <b><code>&nbsp;&nbsp;4588⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;468🍴</code></b> [Chucker](https://github.com/ChuckerTeam/chucker)) - An HTTP inspector for Android & OkHTTP (like Charles but on device).
- <b><code>&nbsp;&nbsp;8710⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;883🍴</code></b> [Android Debug Database](https://github.com/amitshekhariitbhu/Android-Debug-Database)) - Powerful library for debugging databases and shared preferences in Android applications.
- <b><code>&nbsp;12539⭐</code></b> <b><code>&nbsp;&nbsp;2288🍴</code></b> [Android Debug Bridge - ADB](https://github.com/mzlogin/awesome-adb/blob/master/README.en.md)) - A command-line tool to assist in debugging Android-powered devices.
- <b><code>&nbsp;&nbsp;1400⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;85🍴</code></b> [ADB Enhanced](https://github.com/ashishb/adb-enhanced)) - A command-line wrapper around ADB for developers, so that, developers don't have to remember esoteric version-dependent commands.
- <b><code>&nbsp;&nbsp;&nbsp;122⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12🍴</code></b> [handsets](https://github.com/elliotgao2/handsets)) - Android control CLI that drives devices over ADB with no APK required.
- <b><code>&nbsp;&nbsp;4953⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;516🍴</code></b> [Pidcat](https://github.com/JakeWharton/pidcat)) - A colored command-line ADB wrapper that only shows log entries for a specific application package.


### Wireless

- <b><code>&nbsp;&nbsp;1205⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;115🍴</code></b> [Kable](https://github.com/JuulLabs/kable)) - Kotlin Asynchronous Bluetooth Low Energy library for Android and other platforms.
- <b><code>&nbsp;&nbsp;2429⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;463🍴</code></b> [Nordic Android-BLE-Library](https://github.com/NordicSemiconductor/Android-BLE-Library)) - Android BLE library from Nordic Semiconductor for reliable BLE communication.

### Chat & Messaging

- 🌎 [Stream Chat](getstream.io/chat/sdk/android/tutorial/compose/) - Comprehensive SDK & Components for real-time chat, powered by 🌎 [Stream](getstream.io/chat/). *Commercial*

### Date & Time

- <b><code>&nbsp;&nbsp;2824⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;135🍴</code></b> [kotlinx-datetime](https://github.com/Kotlin/kotlinx-datetime)) - A multiplatform Kotlin library for working with date and time.

### Payments

- 🌎 [Square In-App Payments for Android](developer.squareup.com/docs/in-app-payments-sdk/build-on-android) - Integrate Square payments into your mobile app with Digital wallet and stored card support for quick checkout. *Commercial*

### Google Play

- 🌎 [Google Play Billing](developer.android.com/google/play/billing) - Official library for in-app purchases and subscriptions on Google Play.
- 🌎 [In-App Updates](developer.android.com/guide/playcore/in-app-updates) - Keep your app up to date with flexible and immediate in-app update flows.
- 🌎 [In-App Review](developer.android.com/guide/playcore/in-app-review) - Prompt users to submit Play Store ratings and reviews without leaving your app.

### Code Quality

- <b><code>&nbsp;&nbsp;7117⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;887🍴</code></b> [Detekt](https://github.com/detekt/detekt)) - Static code analysis tool for Kotlin with over 200 built-in rules.
- <b><code>&nbsp;&nbsp;6776⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;530🍴</code></b> [ktlint](https://github.com/ktlint/ktlint)) - Anti-bikeshedding Kotlin linter with built-in formatter.
- <b><code>&nbsp;&nbsp;5729⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;569🍴</code></b> [Spotless](https://github.com/diffplug/spotless)) - Code formatter that supports multiple languages and can enforce consistent formatting in builds.

### Other

- 🌎 [AndroidX](developer.android.com/jetpack/androidx) - The modern Android development toolkit that replaces the Android Support Library, providing backward-compatible versions of Android framework APIs.
- <b><code>&nbsp;13820⭐</code></b> <b><code>&nbsp;&nbsp;1949🍴</code></b> [Kotlin Coroutines](https://github.com/Kotlin/kotlinx.coroutines)) - Library for asynchronous programming with coroutines and Flow for reactive streams.
- 🌎 [WorkManager](developer.android.com/topic/libraries/architecture/workmanager) - Schedule deferrable and guaranteed background work with a flexible API.
- 🌎 [Paging](developer.android.com/topic/libraries/architecture/paging/v3-overview) - Load and display pages of data from a larger dataset with efficient memory usage.
- 🌎 [DataStore](developer.android.com/topic/libraries/architecture/datastore) - Modern data storage solution using Kotlin coroutines and Flow to replace SharedPreferences.
- <b><code>&nbsp;&nbsp;6588⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;475🍴</code></b> [Arrow](https://github.com/arrow-kt/arrow)) - Functional companion to Kotlin's Standard Library with typed functional programming support.
- <b><code>&nbsp;&nbsp;3485⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;427🍴</code></b> [KSP](https://github.com/google/ksp)) - Kotlin Symbol Processing API for writing lightweight compiler plugins with better performance than kapt.
- 🌎 [Google Play Services](developers.google.com/android/guides/overview) - Library to access Google services, such as account syncing, Google+ (sharing, single sign-on), Google Maps, Location APIs, Google Play Games, Cloud Messaging, Android Device Manager, and others.
- 🌎 [ML Kit](developers.google.com/ml-kit) - Mobile SDK for machine learning tasks like barcode scanning, text recognition, and face detection.
- 🌎 [Google Code Scanner](developers.google.com/ml-kit/vision/barcode-scanning/code-scanner) - High-quality barcode scanning without requiring app permissions using Google Play Services.
- <b><code>&nbsp;51922⭐</code></b> <b><code>&nbsp;11245🍴</code></b> [Guava: Google Core Libraries for Java](https://github.com/google/guava)) - Collections, caching, primitives support, concurrency libraries, common annotations, string processing, I/O, and so forth.
- <b><code>&nbsp;48152⭐</code></b> <b><code>&nbsp;&nbsp;7568🍴</code></b> [RxJava](https://github.com/ReactiveX/RxJava)) - Reactive Extensions for the JVM – a library for composing asynchronous and event-based programs using observable sequences for the Java VM.
- <b><code>&nbsp;19893⭐</code></b> <b><code>&nbsp;&nbsp;2930🍴</code></b> [RxAndroid](https://github.com/ReactiveX/RxAndroid)) - Adds minimum RxJava bindings for easy writing of reactive Android java code.
- <b><code>&nbsp;&nbsp;4497⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;611🍴</code></b> [AboutLibraries](https://github.com/mikepenz/AboutLibraries)) - Automatically generates an About this app section, with a list of used libraries.
- <b><code>&nbsp;&nbsp;1709⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;111🍴</code></b> [refreshVersions](https://github.com/Splitties/refreshVersions)) - A Kotlin dsl to simplify dependencies management.
- <b><code>&nbsp;&nbsp;&nbsp;757⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42🍴</code></b> [Licensee](https://github.com/cashapp/licensee)) - Gradle plugin which validates the licenses of your dependency graph match what you expect, or it fails your build!

## Resources

- 🌎 [Programming Community Curated Resources for Learning Android Development](hackr.io/tutorials/learn-android-development) - Android Tutorials & Courses submitted and voted by the programming community.
- 🌎 [Vogella Tutorials](www.vogella.com/tutorials/android.html) - Very good tutorials by Lars Vogel.
- 🌎 [Android API Levels](apilevels.com/) - A quick reference table of Android versions with SDK & API levels, version codes, codenames, cumulative usage, and more.
- 🌎 [Android Hive Tutorials](www.androidhive.info) - Very good tutorials for beginners.
- 🌎 [Android Weekly](androidweekly.net) - Newsletter with weekly information about Android.
- 🌎 [Android Asset Studio](romannurik.github.io/AndroidAssetStudio/) - Generator for icons and other assets.
- 🌎 [Device Art Generator](developer.android.com/distribute/marketing-tools/device-art-generator) - Wraps app screenshots in real device artwork.
- 🌎 [Pencil Project](pencil.evolus.vn/) - An open source prototyping software.
- 🌎 [Future Studio](futurestud.io/tutorials/tag/android) - Extensive Android tutorials on Retrofit, Glide & Gson.
- <b><code>&nbsp;&nbsp;4745⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;563🍴</code></b> [Android Tips & Tricks](https://github.com/nisrulz/android-tips-tricks)) - Cheatsheet about tips and tricks for Android Development.
- 🌎 [Google Developers Training](developer.android.com/courses/) -  Google Developers Official Training page has list of various useful learning resources for beginner as well seasoned developer.
- 🌎 [Mindorks](mindorks.com/) - Become a complete and happy Android developer.
- 🌎 [AndroidVille](ayusch.com/) - Become a better Android Engineer. A website dedicated to Android Development covering advanced topics such as RxJava, Android Zygote and much more.
- 🌎 [Android Stack Weekly](canopas.com/tagged/canopas-android-weekly) - A weekly newsletter on new development and updates of Android universe.
- 🌎 [Roadmap.sh Android Roadmap](roadmap.sh/android) - Community-created Android developer roadmap.

### Code examples
- <b><code>&nbsp;22078⭐</code></b> <b><code>&nbsp;&nbsp;4717🍴</code></b> [Now in Android](https://github.com/android/nowinandroid)) - Official sample app demonstrating modern Android development best practices.
- <b><code>&nbsp;23554⭐</code></b> <b><code>&nbsp;&nbsp;5489🍴</code></b> [Compose Samples](https://github.com/android/compose-samples)) - Official sample apps showcasing Jetpack Compose UI toolkit.
- <b><code>&nbsp;45900⭐</code></b> <b><code>&nbsp;11847🍴</code></b> [Android Architecture Blueprints](https://github.com/android/architecture-samples)) - The Android Architecture Blueprints project demonstrates strategies to help solve or avoid common Android problems.

### Podcasts
- 🌎 [Fragmented](fragmentedpodcast.com/) - Is the Android developer podcast where Donn Felker and Kaushik Gopal talk about building good software and becoming better Android developers.
- 🌎 [Android Developers Backstage](androidbackstage.blogspot.com/) - Is a podcast by and for Android developers. Hosted by developers from the Android engineering team, this show covers topics of interest to Android programmers, with in-depth discussions and interviews with engineers on the Android team at Google.
- 🌎 [Android Dialogs](www.youtube.com/channel/UCMEmNnHT69aZuaOrE-dF6ug/feed) - Is a video based podcast, where they have bite-sized conversations with people from the Android community.
- 🌎 [Talking Kotlin](talkingkotlin.com/) - A Podcast on Kotlin and more.
- 🌎 [Android Authority](www.androidauthority.com/podcast/) - Is a weekly Android podcast hosted by Adam Doud, Joe Hindy, and Jonathan Feist from the Android Authority team.

### More lists of libraries
- 🌎 [Square libraries](square.github.io/) - Multiple high quality libraries by square.
- 🌎 [Awesome Android @LibHunt](android.libhunt.com) - Your go-to Android Toolbox.
- 🌎 [Android Store](mindorks.com/android/store) - Search Android Libraries, Projects, and Tools.

## Development Alternatives

My personal recommendation is (for now) to use the Android SDK to build a native app. Scala and Kotlin are both options; multidex requirements depend on an app's method-reference count and minimum SDK level, not its language. Cross-platform alternatives can also be useful when they fit a project's requirements.

### Cross-Platform

- 🌎 [Flutter](flutter.dev/) - Google's mobile app SDK for high-quality native interfaces for Android and iOS in very quick time.
- <b><code>126915⭐</code></b> <b><code>&nbsp;25492🍴</code></b> [React Native](https://github.com/react/react-native)) - A framework for building native apps with React.
- <b><code>&nbsp;23321⭐</code></b> <b><code>&nbsp;&nbsp;2004🍴</code></b> [.NET MAUI](https://github.com/dotnet/maui)) - .NET Multi-platform App UI, the evolution of Xamarin.Forms, for building native cross-platform apps with .NET and C#.
- 🌎 [NativeScript](nativescript.org/) - An open-source framework to build native iOS and Android apps with JavaScript from a single code base.
- 🌎 [Ionic Framework](ionicframework.com) - A framework to build hybrid apps with mobile-optimized HTML, CSS and JS with AngularJS.
- <b><code>&nbsp;&nbsp;3794⭐</code></b> <b><code>&nbsp;&nbsp;1570🍴</code></b> [Apache Cordova](https://github.com/apache/cordova-android)) - Cordova based applications are, at the core, applications written with web technology: HTML, CSS and JavaScript.
- <b><code>&nbsp;17083⭐</code></b> <b><code>&nbsp;&nbsp;1318🍴</code></b> [Capacitor](https://github.com/ionic-team/capacitor)) - Build cross-platform Native Progressive Web Apps for iOS, Android, and the web. Very promising Cordova alternative.
- <b><code>&nbsp;&nbsp;2904⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;316🍴</code></b> [Solar2D](https://github.com/coronalabs/corona)) - Cross-platform framework for creating 2D games and apps (formerly Corona SDK).
- <b><code>&nbsp;&nbsp;5429⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;837🍴</code></b> [BeeWare](https://github.com/beeware/toga)) - Write native Android apps in Python using Toga and Briefcase.
- <b><code>&nbsp;17550⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;752🍴</code></b> [Flet](https://github.com/flet-dev/flet)) - Build Flutter apps using Python.
- <b><code>&nbsp;19028⭐</code></b> <b><code>&nbsp;&nbsp;3145🍴</code></b> [Kivy](https://github.com/kivy/kivy)) - Open source Python framework for Android apps, packaged with Buildozer.

### Kotlin Multiplatform
- <b><code>&nbsp;19487⭐</code></b> <b><code>&nbsp;&nbsp;1435🍴</code></b> [Compose Multiplatform](https://github.com/JetBrains/compose-multiplatform)) - Jetpack Compose for iOS, Desktop, and Web built on Kotlin Multiplatform.
- <b><code>&nbsp;&nbsp;3636⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;327🍴</code></b> [KuiklyUI](https://github.com/Tencent-TDS/KuiklyUI)) - Kotlin Multiplatform UI framework supporting Android, iOS, and other platforms.
- <b><code>&nbsp;&nbsp;1054⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;267🍴</code></b> [Kotlin coding challenges](https://github.com/igorwojda/kotlin-coding-challenges)) - Set of programming challenges thats helps to improve whiteboard coding and problem-solving skills.

## Build & Performance

- 🌎 [R8](developer.android.com/topic/performance/app-optimization/enable-app-optimization) - Default code shrinker and optimizer for Android apps.
- 🌎 [ProGuard](www.guardsquare.com/proguard) - Open-source Java bytecode optimizer and shrinker for Android apps.
- 🌎 [ProGuard Playground](playground.proguard.com/) - Interactive online tool for visualizing and testing ProGuard and R8 keep rules.
- <b><code>&nbsp;&nbsp;5075⭐</code></b> <b><code>&nbsp;&nbsp;&nbsp;590🍴</code></b> [Booster](https://github.com/didi/booster)) - An optimization toolkit for Android applications.

## Other Awesome Lists
Other amazingly awesome lists can be found in the <b><code>&nbsp;33786⭐</code></b> <b><code>&nbsp;&nbsp;3597🍴</code></b> [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness)) list.

## Contributing

Your contributions are always welcome! Please read the [contribution guidelines](contributing.md) first.

## Source
<b><code>&nbsp;12458⭐</code></b> <b><code>&nbsp;&nbsp;1799🍴</code></b> [JStumpp/awesome-android](https://github.com/JStumpp/awesome-android))