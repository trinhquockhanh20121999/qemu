Section 1:
1. Introduce:
- Qemu is Quick Emulator
- Packages Qemu: qemu-system-arm, qemu-system-mips, qemu-system-x86
- Command that list the supported board and CPU: qemu-system-arm -machine help (list the board), qemu-system-arm -machine none -cpu help (list the CPU).

2. How to work
- Host system: your machine (laptop, your computer, ...)
- Guest system: the board, cpu that is simulated.

Command of Guest system -----> QEMU -----> Command of Host system

Section 3: Toolchain
- Build a cross compilation toolchain by crosstool-NG.
- Install crosstool-NG step: InstallCrosstool-ngStep.txt

