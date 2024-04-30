# Docker for Localization

ubuntu20 with ros-noetic
```bash
docker pull ghcr.io/sjtu-cyberc3/loc-env:noetic
```

ubuntu20 with ros-noetic-desktop
```bash
docker pull ghcr.io/sjtu-cyberc3/loc-env:noetic-desktop
```

ubuntu22 with ros-humble (ros2)
```bash
docker pull ghcr.io/sjtu-cyberc3/loc-env:humble
```

ubuntu22 with ros-humble-desktop (ros2)
```bash
docker pull ghcr.io/sjtu-cyberc3/loc-env:humble-desktop
```

---

toolchains:
* GCC: 13
* LLVM: 18
* CMake: latest
* Ninja-build

packages:
* pcl
* opencv
