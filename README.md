# EmbeddedStackLab

**Embedded Linux & Android practical learning, knowledge base and project lab.**

This repository is not only a daily study log. It is the long-term home for:

- learning notes and experiments
- reusable technical knowledge and architecture
- system call / kernel / driver / HAL / Binder/AIDL logic
- debugging methods and root-cause analysis
- real hardware projects
- project decisions, interfaces, source code and test evidence
- Git engineering practice

## Website

GitHub Pages: https://hasirqi.github.io/EmbeddedStackLab/

## Main Structure

```text
EmbeddedStackLab/
├── index.html
├── assets/
│   └── site.css
├── roadmap/
├── knowledge/
├── projects/
├── notes/
├── docs/
├── day01/
└── README.md
```

## Seven Core Goals

1. Explain Linux → Driver → HAL → Android Service call paths.
2. Write and debug Linux C/C++ programs.
3. Read Kernel Driver `probe/remove/ioctl`.
4. Understand Binder/AIDL/HAL responsibilities.
5. Use `gdb/strace/dmesg/logcat` for layer isolation.
6. Be confident with branch/rebase/cherry-pick/conflict/code review.
7. Navigate large codebases by interfaces and call paths.

## Current Status

Day 1 is in progress: Ubuntu ARM64 environment, toolchain, and first C program are complete.
