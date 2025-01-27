# Doomhowl Interactive Maven Repository

Source repo: https://github.com/Doomhowl-Interactive/ndkports

Delivers the following pre-built packages:
- [google/libwebp](https://chromium.googlesource.com/webm/libwebp)
- [raysan5/raylib](https://github.com/raysan5/raylib)
- [doomhowl/raylib](https://github.com/Doomhowl-Interactive/raylib) (In-house Raylib fork)
- [walterschell/lua](https://github.com/walterschell/Lua) (CMake supported Lua)

## Usage

Put in settings.gradle:
```gradle
dependencyResolutionManagement {
    repositories {
        // ...
        maven {
            url = "https://doomhowl-interactive.github.io/maven/"
        }

        // ... 
    }
}
```

## Disclaimers

- Comes with absolutely no warranty!
- Old builds can become unavailable.
- Can contain patches that suit our products.
- Provided with "best-efforts", packages might be in a broken state or removed.

