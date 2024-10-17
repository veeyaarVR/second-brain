---
tags:
  - android
---

For devices running Android version 5.0 (API level 21) or higher, each app runs in its own process and with its own instance of the [Android Runtime (ART)](https://source.android.com/devices/tech/dalvik/index.html). ART is written to run multiple virtual machines on low-memory devices by executing [[Dalvik Executable format (DEX)]] files Build tools, such as [[d8]], compile Java sources into DEX bytecode, which can run on the Android platform.

> [!Note] **TLDR;**
>  - Compiles to dex file in a way to improve faster boot into apps
>  - Responsible for crash reporting, watchpoints to debug, diagnose exceptions

### features
- [[Ahead of Time Compilation (AOT)]] & just-in-time (JIT) compilation
- Optimized [[Garbage Collection (GC)]]
- Better debugging support, including a dedicated sampling profiler, detailed diagnostic exceptions and crash reporting, and the ability to set watchpoints to monitor specific fields
