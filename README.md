# EmbeddedStackLab

Hands-on learning project for Embedded Linux & Android: from C/C++ and Linux Kernel Driver to HAL, Binder/AIDL, Android Service, debugging, Git workflow, and real hardware.

## Learning Goals

By the end of the project, the goal is to be able to:

1. Draw and explain the call path from Linux → Driver → HAL → Android Service.
2. Write and debug simple Linux C/C++ programs.
3. Read basic Linux Kernel Driver code including `probe`, `remove`, and `ioctl`.
4. Explain what Binder, AIDL, and HAL each solve.
5. Use `gdb`, `strace`, `dmesg`, and `logcat` to isolate problems by layer.
6. Work confidently with Git branches, rebase, cherry-pick, conflicts, and code review.
7. Navigate large codebases by following interfaces and call paths instead of reading everything.

## Repository Structure

```text
EmbeddedStackLab/
├── README.md
├── docs/
│   └── Day01_Phase1.html
├── day01/
│   └── hello.c
└── .gitignore
```

## Current Environment

- Host: Mac Studio / Apple Silicon
- Virtualization: VMware Fusion
- Guest OS: Ubuntu 24.04 ARM64
- Architecture: aarch64
- GCC: 13.3
- Git: 2.43
- GDB: 15.1
- strace: 6.8
- CMake: 3.28.3

## Progress

### Day 01
- [x] Ubuntu ARM64 environment setup
- [x] GCC / Git / GDB / strace / CMake verification
- [x] First C program compiled and executed
- [ ] Trace `printf()` → `write()` → Linux Kernel with `strace`
- [ ] Start GDB debugging practice

## Project Direction

The project will gradually move from userspace programming to real embedded hardware:

```text
C/C++
  ↓
Linux system calls
  ↓
Kernel / Device Driver
  ↓
HAL
  ↓
Binder / AIDL
  ↓
Android Service
  ↓
Real Hardware
```

Later phases will include GPIO, I²C, SPI, CAN, sensors, and an embedded Linux/Android development board.
