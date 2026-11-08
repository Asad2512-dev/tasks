# Architecture

## What this is

tasksmaster. The repository is a Flutter application.

## Layout

- `android/`
- `assets/`
- `ios/`
- `lib/` — `main.dart`, `Screens`
- `linux/`
- `macos/`
- `test/`
- `web/`
- `windows/`
- Tooling: `.gitignore`, `.metadata`
- Root files: `analysis_options.yaml`, `pubspec.lock`, `pubspec.yaml`, `README.md`

## How the pieces fit

Flutter app: `pubspec.yaml` plus `lib/` (main.dart, Screens). Platform folders: `android/`, `ios/`, `web/`, `macos/`, `linux/`, `windows/`. Entrypoint file `lib/main.dart` is present. Pub dependencies include `shared_preferences`.

## How to run

This repository does not document a run procedure.
