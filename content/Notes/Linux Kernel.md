---
tags:
  - android
---
> [!Note] Linux Kernel is heart of the android architecture. It manages all the available drivers such as display drivers, camera drivers, Bluetooth drivers, audio drivers, memory drivers, etc. which are required during the runtime.

- Provides an [[Abstraction]] layer between the device hardware and the other components of [[Architecture of Android | android architecture]].
- **Security**: handles the security between the application and the system.
- **Memory Managemen**t: handles the memory management thereby providing the freedom to develop our apps.
- **Process Management**: It manages the process well, allocates resources to processes whenever they need them.
- **Network Stack**: It effectively handles the network communication.
- **Driver Model**: It ensures that the application works properly on the device and hardware manufacturers responsible for building their drivers into the Linux build.

The foundation of the Android platform is the Linux kernel. For example, [[Android Runtime (ART)]] relies on the Linux kernel for underlying functionalities such as threading and low-level memory management.