---
tags:
  - android
---

- Android Runtime environment is one of the most important part of Android. It contains components like core libraries and the Dalvik virtual machine(DVM).
- **Dalvik Virtual Machine (DVM)** is a register-based virtual machine and specially designed and optimized for android to ensure that a device can run multiple instances efficiently. It depends on the layer Linux kernel for threading and low-level memory management.
- The core libraries enable us to implement android applications using the standard JAVA or Kotlin programming languages.

> [!Note] Dalvik seems old. [[Android Runtime (ART)]] is what required after android v5.0 

> [!Note] Prior to Android version 5.0 (API level 21), Dalvik was the Android runtime. If your app runs well on ART, then it can work on Dalvik as well, but [the reverse might not be true](https://developer.android.com/guide/practices/verifying-apps-art).


![[Pasted image 20241017184319.png]]