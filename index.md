# yourusername.github.io

Personal dev reference site — quick lookups, patterns, and notes I actually use while building Android and Flutter apps.

## Pages

| Page | Description |
|------|-------------|
| [Android Clean Architecture](./android-arch-ref.html) | Interactive MVVM + Clean Arch reference with copy-ready Kotlin snippets |
| [AOSP Launcher Internals](./launcher-ref.html) | Deep-dive: LauncherApps, WorkspaceItemInfo, AppWidgetHost, CellLayout, DragController, launcher.db |

More coming: Flutter state management, TFLite integration, coroutines patterns.

## Stack

**Android** — Kotlin, Coroutines, StateFlow, Room, Hilt, Retrofit, ViewBinding, MVVM, Clean Architecture  
**Flutter** — Dart, BLoC, Riverpod  
**AI/ML** — TFLite, ML Kit, LLM APIs

## Structure

```
├── index.html            # Landing page
├── android-arch-ref.html # Android Clean Architecture reference
├── launcher-ref.html     # AOSP Launcher Internals deep-dive
└── README.md             # This file
```

## Local Development

No build step — just open any `.html` file directly in a browser. Files are fully self-contained.

## Deployment

Served via [GitHub Pages](https://pages.github.com/) from the `main` branch root.
