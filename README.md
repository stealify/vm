# vm
Build Custom Virtual Machines using any Language or Runtime that can then later get Compiled for Any Platform Arch.

## Features

### RISC-V system emulator 
RV128IMAFDQC base ISA (user level ISA version 2.2, priviledged architecture version 1.10) 
including:
- 32/64/128 bit integer registers
- 32/64/128 bit floating point instructions (using the SoftFP Library)
- Compressed instructions
- Dynamic XLEN change

### x86 system emulator based on KVM
- VirtIO console, network, block device, input and 9P filesystem
- Graphical display with SDL
Remote HTTP block device and filesystem
Remote Network Support 

### Support for other Emulations like
- https://github.com/ptitSeb/box64/

### Cross Platform Host OS Bindings
- Windows / WSLg / virtio / kvm / qemu
- Linux,Mac,Android,virtio / kvm / qemu

## Components

### Core Languages
C, C++, Rust, Asm(S), Stealify Interface Definition Language, Stealify Lang, ECMAScript, TypeScript.

### Compiler & Toolchains 
Generators, CodeStubAssembler, many more.

### Coding Language Implementation and Integration Framework and Toolchains
In addition to running ECMAScript on StealifyVM, you can also call any other language implemented with the @stealify/lang language implementation framework or the component system as also directly from ECMAScript. See the Polyglot Programming and Embedding Languages guides for more information about interoperability with other programming languages.

### Version Management & Asset Tracking & Software Distribution
Stealify from the Ground up is based on the concepts of Version Tracking, Integrity Checking, and Asset/Artifacts Distribution State Tracking.
It offers a hugh set of concepts and tooling to allow you to fast adopt this concepts into your workflow.

### Headless and GUI Testrunners
Stealify supports the Majority of testrunners out of the box and ships with sane defaults for every part of the stack.
