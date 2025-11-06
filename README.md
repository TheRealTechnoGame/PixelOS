# PixelOS

**PixelOS** is an experimental **open-source** operating system based on the **XNU** kernel. It has been designed to provide a **multiplatform** and **multi-architecture** experience, combining **performance**, **stability**, and **flexibility**. This project focuses on innovation, using modern technologies and solid principles to provide a powerful and adaptable operating system.

PixelOS builds on elements of **macOS**, but with substantial improvements, utilizing the **ZFS** file system, the **Vulkan** graphics engine, and the **OpenCore** bootloader. The primary goal is to offer a free and high-performance alternative for a variety of hardware platforms, supporting multiple architectures such as **x86_64**, **ARM64**, **RISC-V**, and more.

[Access the PixelOS GitHub repository](https://github.com/TheRealTechnoGame/PixelOS)

---

## Table of Contents
- [Introduction](#introduction)
- [Project Goals](#project-goals)
  - [Technologies and Tools Used](#technologies-and-tools-used)
  - [Project Architecture](#project-architecture)
- [Contributing](#contributing)
- [Licenses](#licenses)
- [Useful Links](#useful-links)

---

## Introduction

**PixelOS** is designed to provide a modern, stable, and high-performance system experience. This project goes beyond the traditional operating system approach by leveraging advanced technologies to deliver a more flexible, secure, and compatible system across various hardware platforms. The project is inspired by the principles of **macOS** and **Linux**, but stands out due to its unique approach and goal of making the system compatible with a range of architectures, whether it be **x86_64**, **ARM64**, **RISC-V**, or other emerging architectures.

By choosing **Vulkan** for graphics rendering and **ZFS** for data management, PixelOS aims to offer top-tier performance while ensuring system stability and resilience. PixelOS also integrates **OpenCore** as the bootloader, offering maximum flexibility during boot and enabling the system to be adapted to a variety of hardware platforms.

---

## Project Goals

The goal of **PixelOS** is to create a free and robust operating system that overcomes the limitations of traditional systems. Here are the key objectives of the project:

### 1. **Multiplatform and Multi-architecture**

PixelOS is designed to run on a variety of hardware platforms and software architectures. It is intended to be deployed on **x86_64**, **ARM64**, **RISC-V**, and other upcoming architectures. The goal is to create a system that can adapt to all types of hardware while being performant and compatible with existing environments.

### 2. **Use of Modern Technologies**
- **XNU Kernel**: By leveraging the **XNU** kernel (a combination of Mach and BSD), PixelOS benefits from proven stability, advanced memory management capabilities, and great compatibility with Unix software.
- **ZFS**: The **ZFS** file system is used for its resilience, advanced features (compression, deduplication, snapshots), and ability to reliably manage large amounts of data.
- **Vulkan**: The use of **Vulkan**, a low-level multiplatform graphics API, allows PixelOS to deliver exceptional graphical performance while being compatible with many platforms.

### 3. **Compatibility with Various Hardware Configurations**
The choice of **OpenCore** as the bootloader allows PixelOS to be highly configurable and support a wide range of hardware. OpenCore makes it easy to customize the boot process for different machines, whether they are classic PCs or **ARM**-based machines.

### 4. **Security and Performance**
Thanks to the integration of **ZFS**, PixelOS provides secure data management with mechanisms to prevent corruption while offering exceptional performance. The ZFS file system is also designed to ensure security and stability over the long term.

---

## Technologies and Tools Used

### **XNU Kernel**
The **XNU** kernel is hybrid, combining the strengths of **Mach** (microkernel) and **BSD** (monolithic kernel). This combination allows **PixelOS** to provide fine-grained resource management while benefiting from the advantages of a microkernel for process and thread management.
- **Advantages**: High performance, optimized memory management, and enhanced security.
- **Use**: The kernel manages processes, memory, devices, and provides the basic services of the operating system.

### **ZFS (Zettabyte File System)**
**ZFS** is a modern and advanced file system that offers numerous advantages over traditional file systems. Some key features include:
- **Protection against data corruption**: Thanks to its built-in integrity verification architecture.
- **Compression and deduplication** of data, optimizing disk space.
- **Snapshots**: The ability to create instant backup points and restore them when needed.
ZFS allows **PixelOS** to efficiently manage storage volumes while ensuring data security.

### **Vulkan**
**Vulkan** is a low-level graphics API that provides direct and optimized access to graphics hardware. It is designed to offer high performance, full control over graphical resources, and multiplatform compatibility. Unlike higher-level APIs like OpenGL or Metal, Vulkan maximizes performance on modern systems.
- **Advantages**: Better control over hardware resources, maximized performance, multiplatform compatibility.
- **Use**: Used for managing graphics rendering, visual effects, and graphical processing applications in PixelOS.

### **OpenCore**
**OpenCore** is a highly flexible and modular bootloader, often used in Hackintosh systems. It enables a customizable boot process and adapts to a wide variety of hardware configurations.
- **Advantages**: Extensive hardware support, ability to customize the boot process for various devices.
- **Use**: Ensures the booting of **PixelOS**, loading the kernel, and initializing necessary peripherals.

### **C/C++**
The **C** and **C++** languages are used for the majority of **PixelOS** development due to their low level of abstraction, allowing full control over hardware resources and efficient execution.

---

## Project Architecture

The structure of **PixelOS** is modular, with each component playing an essential role in optimizing system performance and stability. Here are the key components of the project:
1. **Bootloader (OpenCore)**: The flexible and customizable boot process ensures that PixelOS runs on a wide range of hardware.
2. **Modified XNU Kernel**: Responsible for managing processes, memory, hardware resources, and devices. The kernel is the core of the system and ensures stability.
3. **ZFS File System**: Manages storage and ensures data protection with features like snapshots and compression. ZFS also guarantees optimal volume management.
4. **Vulkan Graphics Engine**: Provides low-level graphics control and optimized performance. It is designed to deliver high-quality graphics while remaining multiplatform.
5. **User Subsystems**: Command line interface, file manager, and other essential system tools that allow smooth interaction with the system.

---

## Contributing

**PixelOS** is an open-source project, and we welcome contributions from the community! Whether it’s fixing bugs, adding new features, or improving documentation, every contribution is valuable.

### How to Contribute
1. **Fork** this repository on GitHub.
2. Create a branch for your feature or fix:
    ```bash
    git checkout -b feature/my-feature
    ```
3. Make your changes and commit:
    ```bash
    git commit -am "Add a new feature"
    ```
4. **Push** your branch:
    ```bash
    git push origin feature/my-feature
    ```
5. Open a **Pull Request** to share your changes with the project.

### Code of Conduct
We encourage a respectful and collaborative development environment. Please read our **Code of Conduct**, available in the `CODE_OF_CONDUCT.md` file, and adhere to it.

---

## Licenses

The **PixelOS** project is distributed under the **MIT License**. For more details, please refer to the [`LICENSE`](LICENSE) file.

---

## Useful Links
- [Official Vulkan Website](https://www.vulkan.org/)
- [OpenZFS](https://openzfs.org/)
- [OpenCore Bootloader](https://github.com/acidanthera/OpenCorePkg)
- [XNU Kernel Documentation](https://opensource.apple.com/source/xnu/)

---

Thank you for exploring **PixelOS**! 🚀
