# MyViewPager

Lightweight Android sample demonstrating a ViewPager with background color transitions and simple fragments.

## Summary

This sample (Java, Android Support libraries) shows a `ViewPager` that interpolates background colors and fades text while swiping between pages. It's intended as a small learning/example project.

## Key files

- [app/src/main/java/com/example/mnilg/daggerapplication/MainActivity.java](app/src/main/java/com/example/mnilg/daggerapplication/MainActivity.java) — main activity with ViewPager setup and color interpolation.
- [app/src/main/java/com/example/mnilg/daggerapplication/CustomOnPageChangeListener.java](app/src/main/java/com/example/mnilg/daggerapplication/CustomOnPageChangeListener.java) — page-change listener.
- [app/src/main/res/layout/activity_main.xml](app/src/main/res/layout/activity_main.xml) — layout containing the ViewPager and indicators.
- [app/src/main/res/layout/fragment_main.xml](app/src/main/res/layout/fragment_main.xml) — fragment layout used by each page.

## Requirements

- JDK (Java 8 recommended)
- Android SDK (compile/target in project configured for API 26)
- Gradle (wrapper included)

## Build & Run

From the project root, build or install using the Gradle wrapper:

```bash
./gradlew assembleDebug
./gradlew installDebug   # device/emulator required
```

Run the app on a connected device or emulator.

## Tests

- Unit tests: `./gradlew test`
- Instrumented tests: `./gradlew connectedAndroidTest` (requires device/emulator)

## Notes & Suggestions

- Project currently uses Android Support libraries (compile SDK 26). Consider migrating to AndroidX and updating plugin/Gradle versions before adding significant changes.
- Colors, page count, and behavior are implemented in `MainActivity.java`.

## License

No license specified in repository.

---

If you want, I can: add a CONTRIBUTING/CHANGELOG, migrate to AndroidX, or run the build in this environment. Which would you like next?
