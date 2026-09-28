# anatomy.md

> Auto-maintained by OpenWolf. Last scanned: 2026-09-28T08:07:03.088Z
> Files: 147 tracked | Anatomy hits: 0 | Misses: 0

## ./

- `.gitignore` — Git ignore rules (~199 tok)
- `.metadata` — This file tracks properties of this Flutter project. (~455 tok)
- `AGENTS.md` — OpenWolf (~68 tok)
- `analysis_options.yaml` — - android/** (~442 tok)
- `CLAUDE.md` — OpenWolf (~57 tok)
- `kincony_boards_provisioing.iml` (~225 tok)
- `pubspec.yaml` — Dart/Flutter package manifest (~1102 tok)
- `README.md` — Project documentation (~162 tok)

## .claude/

- `settings.json` (~514 tok)

## .claude/commands/

- `reframe.md` — Mode: migrate [framework] (~551 tok)
- `security-audit.md` — Layer 1 — Dependencies (~510 tok)

## .claude/rules/

- `openwolf.md` (~328 tok)

## .codex/

- `config.toml` (~7 tok)
- `hooks.json` (~705 tok)

## .codex/prompts/

- `reframe.md` — Mode: migrate [framework] (~551 tok)
- `security-audit.md` — Layer 1 — Dependencies (~510 tok)

## .dart_tool/

- `package_config.json` (~1595 tok)
- `package_graph.json` (~1205 tok)
- `version` (~2 tok)

## .dart_tool/dartpad/

- `web_plugin_registrant.dart` — Flutter web plugin registrant file. (~39 tok)

## .dart_tool/extension_discovery/

- `README.md` — Project documentation (~263 tok)
- `vs_code.json` (~30 tok)

## .opencode/command/

- `reframe.md` — Mode: migrate [framework] (~551 tok)
- `security-audit.md` — Layer 1 — Dependencies (~510 tok)

## .opencode/plugin/

- `openwolf.ts` — OpenWolf plugin entry — installed by `openwolf init --agent opencode`. (~74 tok)

## .opencode/plugin/openwolf/

- `anatomy.ts` — Exports parseAnatomy, serializeAnatomy, extractDescription, STORE_FILE + 12 more (~2922 tok)
  - fn `parseAnatomy` L5-28 (~207 tok)
  - fn `serializeAnatomy` L29-53 (~240 tok)
  - fn `extractDescription` L54-106 (~577 tok)
  - fn `sha256` L107-110 (~33 tok)
  - section `StoreFileEntry` L111-121 (~83 tok)
  - section `AnatomyStoreData` L122-127 (~63 tok)
  - fn `newStore` L128-132 (~64 tok)
  - fn `loadStore` L133-142 (~92 tok)
  - fn `saveStore` L143-157 (~162 tok)
  - fn `renderStore` L158-188 (~380 tok)
  - fn `renderToFile` L189-202 (~146 tok)
  - fn `importFromMarkdown` L203-227 (~305 tok)
  - fn `loadStoreReconciled` L228-240 (~137 tok)
  - fn `lockSleep` L241-244 (~31 tok)
  - fn `withAnatomyLock` L245-276 (~373 tok)
- `fs.ts` — Exports getWolfDir, wolfDirExists, readJSON, writeJSON + 6 more (~538 tok)
  - fn `getWolfDir` L5-8 (~28 tok)
  - fn `wolfDirExists` L9-12 (~31 tok)
  - fn `readJSON` L13-20 (~50 tok)
  - fn `writeJSON` L21-33 (~144 tok)
  - fn `readMarkdown` L34-41 (~41 tok)
  - fn `appendMarkdown` L42-47 (~64 tok)
  - fn `timeShort` L48-52 (~46 tok)
  - fn `timestamp` L53-56 (~22 tok)
  - fn `normalizePath` L57-60 (~24 tok)
  - fn `estimateTokens` L61-64 (~60 tok)
- `index.ts` — Exports OpenWolf (~1081 tok)
- `post-read.ts` — Exports handlePostRead (~629 tok)
  - fn `handlePostRead` L7-57 (~553 tok)
- `post-write.ts` — Exports handlePostWrite, summarizeEdit, autoDetectBugFix, detectFixPattern (~3226 tok)
  - fn `handlePostWrite` L8-39 (~302 tok)
  - fn `updateAnatomy` L40-86 (~473 tok)
  - fn `appendToMemory` L87-114 (~302 tok)
  - fn `trackSession` L115-150 (~338 tok)
  - fn `summarizeEdit` L151-184 (~471 tok)
  - fn `autoDetectBugFix` L185-228 (~523 tok)
  - fn `detectFixPattern` L229-265 (~610 tok)
  - fn `extractChangedLines` L266-270 (~88 tok)
- `pre-read.ts` — Exports handlePreRead (~685 tok)
  - fn `handlePreRead` L7-63 (~613 tok)
- `pre-write.ts` — Exports handlePreWrite (~1167 tok)
  - fn `tokenize` L14-21 (~63 tok)
  - fn `handlePreWrite` L22-35 (~132 tok)
  - fn `checkCerebrum` L36-65 (~369 tok)
  - section `BugEntry` L66-74 (~37 tok)
  - fn `checkBugLog` L75-105 (~399 tok)
- `session.ts` — Exports getSessionState, setSessionState, deleteSession, handleSessionStart (~952 tok)
  - fn `getSessionState` L8-11 (~33 tok)
  - fn `setSessionState` L12-15 (~33 tok)
  - fn `deleteSession` L16-19 (~26 tok)
  - fn `handleSessionStart` L20-89 (~783 tok)
- `stop.ts` — Exports handleStop (~1444 tok)
  - fn `handleStop` L6-35 (~262 tok)
  - fn `checkForMissingBugLogs` L36-50 (~165 tok)
  - fn `buildLedgerEntry` L51-114 (~743 tok)
  - fn `appendSessionSummary` L115-126 (~218 tok)
- `types.ts` — Exports FileRead, FileWrite, SessionState, PartialSessionState + 2 more (~217 tok)

## android/

- `.gitignore` — Git ignore rules (~68 tok)
- `build.gradle.kts` — Gradle Kotlin build configuration (~144 tok)
- `gradle.properties` (~80 tok)
- `gradlew` — ############################################################################# (~1326 tok)
- `gradlew.bat` (~642 tok)
- `kincony_boards_provisioing_android.iml` (~427 tok)
- `local.properties` (~25 tok)
- `settings.gradle.kts` — Gradle Kotlin settings (~206 tok)

## android/app/

- `build.gradle.kts` — Gradle Kotlin build configuration (~481 tok)

## android/app/src/debug/

- `AndroidManifest.xml` (~108 tok)

## android/app/src/main/

- `AndroidManifest.xml` (~633 tok)

## android/app/src/main/java/io/flutter/plugins/

- `GeneratedPluginRegistrant.java` — Generated file. Do not edit. (~148 tok)

## android/app/src/main/kotlin/com/example/kincony_boards_provisioing/

- `MainActivity.kt` — Declares MainActivity (~38 tok)

## android/app/src/main/res/drawable-v21/

- `launch_background.xml` (~126 tok)

## android/app/src/main/res/drawable/

- `launch_background.xml` (~124 tok)

## android/app/src/main/res/values-night/

- `styles.xml` (~285 tok)

## android/app/src/main/res/values/

- `styles.xml` (~285 tok)

## android/app/src/profile/

- `AndroidManifest.xml` (~108 tok)

## android/gradle/wrapper/

- `gradle-wrapper.jar` (~13666 tok)
- `gradle-wrapper.properties` (~54 tok)

## ios/

- `.gitignore` — Git ignore rules (~152 tok)

## ios/Flutter/

- `AppFrameworkInfo.plist` (~192 tok)
- `Debug.xcconfig` — include "Generated.xcconfig" (~8 tok)
- `flutter_export_environment.sh` — This is a generated file; do not edit or check into version control. (~204 tok)
- `Generated.xcconfig` — This is a generated file; do not edit or check into version control. (~180 tok)
- `Release.xcconfig` — include "Generated.xcconfig" (~8 tok)

## ios/Flutter/ephemeral/

- `flutter_lldb_helper.py` — handle_new_rx_page (~365 tok)
- `flutter_lldbinit` (~29 tok)
- `flutter_native_integration.env` (~140 tok)

## ios/Flutter/ephemeral/Packages/.packages/FlutterFramework/

- `Package.swift` — Swift package manifest (~124 tok)

## ios/Flutter/ephemeral/Packages/.packages/FlutterFramework/Sources/FlutterFramework/

- `FlutterFramework.swift` (~11 tok)

## ios/Flutter/ephemeral/Packages/FlutterGeneratedPluginSwiftPackage/

- `Package.swift` — Swift package manifest (~212 tok)

## ios/Flutter/ephemeral/Packages/FlutterGeneratedPluginSwiftPackage/Sources/FlutterGeneratedPluginSwiftPackage/

- `FlutterGeneratedPluginSwiftPackage.swift` (~11 tok)

## ios/Runner.xcodeproj/

- `project.pbxproj` — !$*UTF8*$! (~6917 tok)

## ios/Runner.xcodeproj/project.xcworkspace/

- `contents.xcworkspacedata` (~36 tok)

## ios/Runner.xcodeproj/project.xcworkspace/xcshareddata/

- `IDEWorkspaceChecks.plist` (~64 tok)
- `WorkspaceSettings.xcsettings` (~61 tok)

## ios/Runner.xcodeproj/xcshareddata/xcschemes/

- `Runner.xcscheme` (~1258 tok)

## ios/Runner.xcworkspace/

- `contents.xcworkspacedata` (~41 tok)

## ios/Runner.xcworkspace/xcshareddata/

- `IDEWorkspaceChecks.plist` (~64 tok)
- `WorkspaceSettings.xcsettings` (~61 tok)

## ios/Runner/

- `AppDelegate.swift` — AppDelegate: application, didInitializeImplicitFlutterEngine (~144 tok)
- `GeneratedPluginRegistrant.h` — clang-format off (~108 tok)
- `GeneratedPluginRegistrant.m` — clang-format off (~60 tok)
- `Info.plist` (~600 tok)
- `Runner-Bridging-Header.h` — import "GeneratedPluginRegistrant.h" (~11 tok)
- `SceneDelegate.swift` — Declares SceneDelegate (~21 tok)

## ios/Runner/Assets.xcassets/AppIcon.appiconset/

- `Contents.json` (~720 tok)

## ios/Runner/Assets.xcassets/LaunchImage.imageset/

- `Contents.json` (~112 tok)
- `README.md` — Project documentation (~84 tok)

## ios/Runner/Base.lproj/

- `LaunchScreen.storyboard` (~634 tok)
- `Main.storyboard` (~428 tok)

## ios/RunnerTests/

- `RunnerTests.swift` — RunnerTests: testExample (~76 tok)

## lib/

- `main.dart` — Stateful widget: MyApp (~1373 tok)

## linux/

- `.gitignore` — Git ignore rules (~5 tok)
- `CMakeLists.txt` — CMake build configuration (~1198 tok)

## linux/flutter/

- `CMakeLists.txt` — CMake build configuration (~704 tok)
- `generated_plugin_registrant.cc` — clang-format off (~43 tok)
- `generated_plugin_registrant.h` — clang-format off (~87 tok)
- `generated_plugins.cmake` (~198 tok)

## linux/runner/

- `CMakeLists.txt` — CMake build configuration (~244 tok)
- `main.cc` — include "my_application.h" (~48 tok)
- `my_application.cc` — include "my_application.h" (~1465 tok)
- `my_application.h` — my_application_new: (~129 tok)

## macos/

- `.gitignore` — Git ignore rules (~24 tok)

## macos/Flutter/

- `Flutter-Debug.xcconfig` — include "ephemeral/Flutter-Generated.xcconfig" (~13 tok)
- `Flutter-Release.xcconfig` — include "ephemeral/Flutter-Generated.xcconfig" (~13 tok)
- `GeneratedPluginRegistrant.swift` (~40 tok)

## macos/Flutter/ephemeral/

- `flutter_export_environment.sh` — This is a generated file; do not edit or check into version control. (~194 tok)
- `flutter_native_integration.env` (~133 tok)
- `Flutter-Generated.xcconfig` — This is a generated file; do not edit or check into version control. (~152 tok)

## macos/Flutter/ephemeral/Packages/.packages/FlutterFramework/

- `Package.swift` — Swift package manifest (~124 tok)

## macos/Flutter/ephemeral/Packages/.packages/FlutterFramework/Sources/FlutterFramework/

- `FlutterFramework.swift` (~11 tok)

## macos/Flutter/ephemeral/Packages/FlutterGeneratedPluginSwiftPackage/

- `Package.swift` — Swift package manifest (~212 tok)

## macos/Flutter/ephemeral/Packages/FlutterGeneratedPluginSwiftPackage/Sources/FlutterGeneratedPluginSwiftPackage/

- `FlutterGeneratedPluginSwiftPackage.swift` (~11 tok)

## macos/Runner.xcodeproj/

- `project.pbxproj` — !$*UTF8*$! (~7489 tok)

## macos/Runner.xcodeproj/project.xcworkspace/xcshareddata/

- `IDEWorkspaceChecks.plist` (~64 tok)

## macos/Runner.xcodeproj/xcshareddata/xcschemes/

- `Runner.xcscheme` (~1243 tok)

## macos/Runner.xcworkspace/

- `contents.xcworkspacedata` (~41 tok)

## macos/Runner.xcworkspace/xcshareddata/

- `IDEWorkspaceChecks.plist` (~64 tok)

## macos/Runner/

- `AppDelegate.swift` — AppDelegate: applicationShouldTerminateAfterLastWindowClosed, applicationSupportsSecureRestorableState (~83 tok)
- `DebugProfile.entitlements` (~93 tok)
- `Info.plist` (~283 tok)
- `MainFlutterWindow.swift` — MainFlutterWindow: awakeFromNib (~104 tok)
- `Release.entitlements` (~64 tok)

## macos/Runner/Assets.xcassets/AppIcon.appiconset/

- `Contents.json` (~369 tok)

## macos/Runner/Base.lproj/

- `MainMenu.xib` (~6327 tok)

## macos/Runner/Configs/

- `AppInfo.xcconfig` — Application-level settings for the Runner target. (~170 tok)
- `Debug.xcconfig` — include "../../Flutter/Flutter-Debug.xcconfig" (~21 tok)
- `Release.xcconfig` — include "../../Flutter/Flutter-Release.xcconfig" (~22 tok)
- `Warnings.xcconfig` (~155 tok)

## macos/RunnerTests/

- `RunnerTests.swift` — RunnerTests: testExample (~78 tok)

## test/

- `widget_test.dart` — This is a basic Flutter widget test. (~308 tok)

## web/

- `index.html` — kincony_boards_provisioing (~416 tok)
- `manifest.json` (~271 tok)

## windows/

- `.gitignore` — Git ignore rules (~78 tok)
- `CMakeLists.txt` — CMake build configuration (~1047 tok)

## windows/flutter/

- `CMakeLists.txt` — CMake build configuration (~936 tok)
- `generated_plugin_registrant.cc` — clang-format off (~44 tok)
- `generated_plugin_registrant.h` — clang-format off (~87 tok)
- `generated_plugins.cmake` (~199 tok)

## windows/runner/

- `CMakeLists.txt` — CMake build configuration (~449 tok)
- `flutter_window.cpp` — include "flutter_window.h" (~607 tok)
- `flutter_window.h` — ifndef RUNNER_FLUTTER_WINDOW_H_ (~266 tok)
- `main.cpp` — include <flutter/dart_project.h> (~366 tok)
- `resource.h` — {{NO_DEPENDENCIES}} (~124 tok)
- `runner.exe.manifest` (~161 tok)
- `Runner.rc` — Microsoft Visual C++ generated resource script. (~827 tok)
- `utils.cpp` — include "utils.h" (~620 tok)
- `utils.h` — ifndef RUNNER_UTILS_H_ (~192 tok)
- `win32_window.cpp` — include "win32_window.h" (~2439 tok)
- `win32_window.h` — ifndef RUNNER_WIN32_WINDOW_H_ (~1007 tok)
