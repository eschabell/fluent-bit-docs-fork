
# Download and install Fluent Bit

<img referrerpolicy="no-referrer-when-downgrade" src="https://static.scarf.sh/a.png?x-pxid=e9732f9c-44a4-46d3-ab87-86138455c698" />

| Operating System | Distribution | Architectures |
| :--- | :--- | :--- |
| Linux | [Amazon Linux 2023](downloads/linux/amazon-linux.md) | x86_64, Arm64v8 |
|  | [Amazon Linux 2](downloads/linux/amazon-linux.md) | x86_64, Arm64v8 |
|  | [CentOS 9 Stream](downloads/linux/redhat-centos.md) | x86_64, Arm64v8 |
|  | [CentOS 8](downloads/linux/redhat-centos.md) | x86_64, Arm64v8 |
|  | [CentOS 7](downloads/linux/redhat-centos.md) | x86_64, Arm64v8 |
|  | [Rocky Linux 8](downloads/linux/alma-rocky.md) | x86_64, Arm64v8 |
|  | [Rocky Linux 9](downloads/linux/alma-rocky.md) | x86_64, Arm64v8 |
|  | [Alma Linux 8](downloads/linux/alma-rocky.md) | x86_64, Arm64v8 |
|  | [Alma Linux 9](downloads/linux/alma-rocky.md) | x86_64, Arm64v8 |
|  | [Debian 12 (Bookworm)](downloads/linux/debian.md) | x86_64, Arm64v8 |
|  | [Debian 11 (Bullseye)](downloads/linux/debian.md) | x86_64, Arm64v8 |
|  | [Debian 10 (Buster)](downloads/linux/debian.md) | x86_64, Arm64v8 |
|  | [Ubuntu 24.04 (Noble Numbat)](downloads/linux/ubuntu.md) | x86_64, Arm64v8 |
|  | [Ubuntu 22.04 (Jammy Jellyfish)](downloads/linux/ubuntu.md) | x86_64, Arm64v8 |
|  | [Raspbian 12 (Bookworm)](downloads/linux/raspbian-raspberry-pi.md) | Arm32v7 |
| macOS | * | x86_64, Apple M1 |
| Windows | [Windows Server 2019](downloads/windows.md) | x86_64, x86 |
|  | [Windows 10 1903](downloads/windows.md) | x86_64, x86 |
|  | [openSUSE Leap 15.6](downloads/linux/suse.md) | x86_64, Arm64v8 |
|  | [SUSE Linux Enterprise Server (SLES) 15.7](downloads/linux/suse.md) | x86_64, Arm64v8 |

Fluent Bit is compatible with most x86-based, x86_64-based, arm32v7-based, and arm64v8-based systems.

## Build from source code

You can [build and install Fluent Bit from its source code](../installation/downloads/source.md). There are also platform-specific guides for building Fluent Bit from source on [macOS](../installation/downloads/macos.md#compile-from-source) and [Windows](../installation/downloads/windows.md#compile-from-source).

## Supported platforms and packages

To install Fluent Bit from one of the available packages, use the installation method for your chosen platform.

### Container deployment

Fluent Bit is available for the following container deployments:

- [Containers on AWS](../installation/downloads/aws-container.md)
- [Docker](../installation/downloads/docker.md)
- [Kubernetes](../installation/downloads/kubernetes.md)

### Linux

Fluent Bit is available on [Linux](../installation/downloads/linux.md), including the following distributions:

- [Amazon Linux](../installation/downloads/linux/amazon-linux.md)
- [Buildroot embedded Linux](../installation/downloads/linux/buildroot-embedded-linux.md)
- [Debian](../installation/downloads/linux/debian.md)
- [Raspbian and Raspberry Pi](../installation/downloads/linux/raspbian-raspberry-pi.md)
- [Red Hat and CentOS](../installation/downloads/linux/redhat-centos.md)
- [Rocky Linux and Alma Linux](../installation/downloads/linux/alma-rocky.md)
- [Ubuntu](../installation/downloads/linux/ubuntu.md)
- [Yocto embedded Linux](../installation/downloads/linux/yocto-embedded-linux.md)

### macOS

Fluent Bit is available on [macOS](../installation/downloads/macos.md).

### Windows

Fluent Bit is available on [Windows](../installation/downloads/windows.md).

### Other platforms

Official support is based on community demand. Fluent Bit might run on older operating systems, but must be built from source or using custom packages.

Fluent Bit can run on Berkeley Software Distribution (BSD) systems and IBM Z Linux (s390x) systems with restrictions. Not all plugins and filters are supported.

## Enterprise providers

Fluent Bit packages are also provided by [enterprise providers](https://fluentbit.io/enterprise/) for older end-of-life versions, Unix systems, or for additional support and features including aspects (such as CVE backporting).
