# RE list

A list of open-source reverse engineering tools with a focus on binary analysis.

- **[Amoco](https://github.com/bdcht/amoco)**: A python package dedicated to the (static) analysis of binaries.

- **[Angr](http://angr.io/)**: A python framework for analyzing binaries. It combines both static and dynamic symbolic ("concolic") analysis, making it applicable to a variety of tasks.

- **[ANVILL](https://github.com/lifting-bits/anvill)**: ANVILL forges beautiful LLVM bitcode out of raw machine code. Anvill implements simple machine code lifting primitives using Remill. The goal of these components is to produce high quality bitcode, which can then be further decompiled to C (via Clang ASTs) using Rellic.

 - **[Avatar²](https://github.com/avatartwo/avatar2)**:  Avatar is a target orchestration framework with focus on dynamic analysis of embedded devices' firmware.
 
- **[BARF](https://github.com/programa-stic/barf-project)**: An open source binary analysis framework. It is a scriptable platform that supports instruction lifting from multiple architectures, binary translation to an intermediate representation, an extensible framework for code analysis plugins and interoperation with external tools such as debuggers, SMT solvers and instrumentation tools.

- **[BAP](https://github.com/BinaryAnalysisPlatform/bap)**: The Binary Analysis Platform is a reverse engineering and program analysis platform that targets binaries, i.e., compiled programs without the source code. BAP supports multiple architectures (more than 30), though the first tier architectures are x86, x86-64, and ARM. 

- **[BinCAT](https://github.com/airbus-seclab/bincat)**: A static Binary Code Analysis Toolkit, designed to help reverse engineers, directly from IDA. It features: value analysis (registers and memory), taint analysis, type reconstruction and propagation, backward and forward analysis

- **[Bindead](https://bitbucket.org/mihaila/bindead/wiki/Home)**: An analyzer for executable machine code. It features a disassembler that translates machine code bits into an assembler like language (RREIL) that in turn is then analyzed by the static analysis component using abstract interpretation. As Bindead operates on the machine code level, it can be used without having the source code of the program to be analyzed.

- **[BitBlaze](http://bitblaze.cs.berkeley.edu/)**: BitBlaze Binary Analysis Platform features a novel fusion of static and dynamic analysis techniques, dynamic symbolic execution, and whole-system emulation and binary instrumentation. 

- **[Cemu](https://github.com/hugsy/cemu)**: Cheap EMUlator: lightweight multi-architecture assembly playground

- **[Cutter](https://github.com/radareorg/cutter)**: A Qt and C++ GUI for radare2.

- **[cwe_checker](https://github.com/fkie-cad/cwe_checker)**: A suite of tools to detect common bug classes such as use of dangerous functions and simple integer overflows. Its main focus are ELF binaries that are commonly found on Linux and Unix operating systems. cwe_checker is built on top of BAP(Binary Analysis Platform).

- **[DECAF](https://github.com/sycurelab/DECAF)**: DECAF(short for Dynamic Executable Code Analysis Framework) is a binary analysis platform based on QEMU.
 
- **[Deepstate](https://github.com/trailofbits/deepstate)**: A framework that provides C and C++ developers with a common interface to various symbolic execution and fuzzing engines. Users can write one test harness using a Google Test-like API, then execute it using multiple backends without having to learn the complexities of the underlying engines.
 
- **[DynamoRIO](http://www.dynamorio.org/)**: DynamoRIO is a runtime code manipulation system that supports code transformations on any part of a program, while it executes. DynamoRIO exports an interface for building dynamic tools for a wide variety of uses: program analysis and understanding, profiling, instrumentation, optimization, translation, etc.

- **[Echo](https://github.com/Washi1337/Echo)**: Echo is an experimental generic, static analysis, symbolic execution and emulation framework, that aims to help out with binary code analysis for a variety of platforms.

- **[ERESI](https://github.com/thorkill/eresi)**: The ERESI Reverse Engineering Software Interface is a multi-architecture binary analysis framework with a domain-specific language tailored to reverse engineering and program manipulation.
 
- **[esilsolve](https://github.com/radareorg/esilsolve)**: A python symbolic execution framework using radare2's ESIL.

- **[Falcon](https://github.com/falconre/falcon)**: A formal binary analysis framework in Rust. Falcon seeks to implement data-flow analysis, abstract interpretation, and constraint solving over compiled, binary executables.

- **[Gdbgui](https://github.com/cs01/gdbgui)**: A modern, browser-based frontend to gdb (gnu debugger). Add breakpoints, view stack traces, and more in C, C++, Go, and Rust! Simply run gdbgui from the terminal and a new tab will open in your browser.

- **[GTIRB](https://github.com/GrammaTech/gtirb)**: The GrammaTech Intermediate Representation for Binaries (GTIRB) is a machine code analysis and rewriting data structure. It is intended to facilitate the communication of binary IR between programs performing binary disassembly, analysis, transformation, and pretty printing. GTIRB is modeled on LLVM-IR, and seeks to serve a similar functionality of encouraging communication and interoperability between tools

- **[haybale](https://github.com/PLSysSec/haybale)**: A general-purpose symbolic execution engine written in Rust. It operates on LLVM IR, which allows it to analyze programs written in C/C++, Rust, Swift, or any other language which compiles to LLVM IR.

- **[hobbits](https://github.com/Mahlet-Inc/hobbits)**: A multi-platform GUI for bit-based analysis, processing, and visualization.

- **[IceBox](https://github.com/thalium/icebox)**: A Virtual Machine Introspection solution that enable you to stealthily trace and debug any process (kernel or user).

- **[Insight](https://insight.labri.fr/)**: The Insight project is devoted to binary analysis to serve several purposes such as:    Binary verification, Reverse engineering, Binary test cases extraction, Decompilation to higher-level languages.

- **[Jakstab](http://www.jakstab.org/)**: An Abstract Interpretation-based, integrated disassembly and static analysis framework for designing analyses on executables and recovering reliable control flow graphs.

- **[Kaitai Struct](http://kaitai.io/)**: A declarative language used for describe various binary data structures, laid out in files or in memory: i.e. binary file formats, network stream packet formats, etc.

- **[libvmi](https://libvmi.com/)**: A C library with Python bindings that makes it easy to monitor the low-level details of a running virtual machine by viewing its memory, trapping on hardware events, and accessing the vCPU registers.

- **[LIEF](https://github.com/lief-project/LIEF)**: Library to Instrument Executable Formats. The purpose of this project is to provide a cross platform library which can parse, modify and abstract ELF, PE and MachO formats.

- **[LLVM-mctoll](https://github.com/Microsoft/llvm-mctoll)**: This tool statically (AOT) translates (or raises) binaries to LLVM IR.

- **[LuaQEMU](https://github.com/Comsecuris/luaqemu)**: A QEMU-based framework exposing several of QEMU-internal APIs to a LuaJIT core injected into QEMU itself. Among other things, this allows fast prototyping of target systems without any native code and minimal effort in Lua.

- **[macaw](https://github.com/GaloisInc/macaw)**: Open source binary analysis tools.

- **[Maat](https://github.com/trailofbits/maat)**: Open-source Dynamic Symbolic Execution and Binary Analysis framework. It provides various functionalities such as symbolic execution, taint analysis, constraint solving, binary loading, environment simulation, and leverages Ghidra's sleigh library for assembly lifting

- **[Manticore](https://github.com/trailofbits/manticore)**: A prototyping tool for dynamic binary analysis, with support for symbolic execution, taint analysis, and binary instrumentation.

- **[Mcsema](https://github.com/trailofbits/mcsema)**: Framework for lifting x86, amd64, and aarch64 program binaries to LLVM bitcode.

- **[Metasm](https://github.com/jjyg/metasm)**: Ruby assembly manipulation suite

- **[Medusa](https://github.com/wisk/medusa)**: A disassembler designed to be both modular and interactive. 

- **[MemProcFS](https://github.com/ufrisk/MemProcFS)**: MemProcFS is an easy and convenient way of viewing physical memory as files in a virtual file system. Easy trivial point and click memory analysis without the need for complicated commandline arguments! Access memory content and artifacts via files in a mounted virtual file system or via a feature rich application library to include in your own projects!

- **[Miasm](https://github.com/cea-sec/miasm)**: Free and open source (GPLv2) reverse engineering framework. Miasm aims to analyze / modify / generate binary programs.

- **[Multiverse](https://github.com/utds3lab/multiverse)**: A static binary rewriter with an emphasis on simplicity and correctness. It does not rely on heuristics to perform its rewriting, and it attempts to make as few assumptions as possible to produce a rewritten binary. 

- **[Panda](https://github.com/panda-re/panda)**: PANDA is an open-source Platform for Architecture-Neutral Dynamic Analysis. It is built upon the QEMU whole system emulator, and so analyses have access to all code executing in the guest and all data. PANDA adds the ability to record and replay executions, enabling iterative, deep, whole system analyses. 

- **[Panopticon](https://github.com/das-labor/panopticon)**: A cross platform disassembler for reverse engineering written in Rust. It can disassemble AMD64, x86, AVR and MOS 6502 instruction sets and open ELF files. Panopticon comes with Qt GUI for browsing and annotating control flow graphs.

- **[Pharos](https://github.com/cmu-sei/pharos)**: The framework is designed to facilitate the automated analysis of binary programs. It uses the ROSE compiler infrastructure for disassembly, control flow analysis, instruction semantics, and more.

- **[Pimp](https://github.com/radare/radare2-extras/tree/master/pimp)**: Triton based R2 plugin for concolic execution

- **[Pin](https://software.intel.com/en-us/articles/pin-a-dynamic-binary-instrumentation-tool)**: Pin is a dynamic binary instrumentation framework for the IA-32, x86-64 and MIC instruction-set architectures that enables the creation of dynamic program analysis tools.

- **[PINCE](https://github.com/korcankaraokcu/PINCE)**: A front-end/reverse engineering tool for the GNU Project Debugger (GDB), focused on games. But it can be used for any reverse-engineering related stuff.

- **[Ponce](https://github.com/illera88/Ponce)**: An IDA Pro plugin that provides users the ability to perform taint analysis and symbolic execution over binaries in an easy and intuitive fashion. With Ponce you are one click away from getting all the power from cutting edge symbolic execution.

- **[PyREBox](https://github.com/Cisco-Talos/pyrebox)**: PyREBox is a Python scriptable Reverse Engineering sandbox. It is based on QEMU, and its goal is to aid reverse engineering by providing dynamic analysis and debugging capabilities from a different perspective. PyREBox allows to inspect a running QEMU VM, modify its memory or registers, and to instrument its execution, by creating simple scripts in python to automate any kind of analysis.

- **[Pysymemu](https://github.com/feliam/pysymemu)**: A symbolic execution tool, capable of automatically generating interesting inputs for x86/x64 binary programs.

- **[QBDI](https://github.com/quarkslab/QBDI)**: A modular, cross-platform and cross-architecture DBI framework. It aims to support Linux, macOS, Android, iOS and Windows operating systems running on x86, x86-64, ARM and AArch64 architectures

- **[Qiling Framework](https://github.com/qilingframework/qiling)**: An advanced binary emulation framework.

- **[radius2](https://github.com/aemmitt-ns/radius)**: A fast binary emulation and symbolic execution framework using radare2.

- **[Rellic](https://github.com/lifting-bits/rellic)**:  Rellic produces goto-free C output from LLVM bitcode. Rellic is an implementation of the pattern-independent structuring algorithm to produce a goto-free C output from LLVM bitcode.

- **[Remill](https://github.com/trailofbits/remill)**: A static binary translator that translates machine code instructions into LLVM bitcode. It translates x86 and amd64 machine code into LLVM bitcode. Remill focuses on accurately lifting instructions. It is meant to be used as a library for other tools, e.g. McSema.

- **[REDasm](https://github.com/REDasmOrg/REDasm)**: An interactive, multiarchitecture disassembler written in C++ using Qt5 as UI Framework, its core is light and it can be extended in order to support new instructions and file formats.

- **[REVEN](https://www.tetrane.com/free-edition/Get-REVEN-Free-Edition.html)**: A Timeless Debugging and Analysis (TDnA) Platform designed to go x10 faster & x10 deeper while reverse engineering. Technically, REVEN records the execution of an entire virtual machine for a duration of time, then provides access to that recording via both a GUI (named Axion) and an Python API to allow analysis. The analyst can follow the trace of all executed CPU instructions for all processes and kernel modules, alongside memory and CPU registers. Moreover, REVEN provides unique analysis features such as the Memory history or the Taint. Finally, REVEN provides high-level context with process names, binaries and symbols.

- **[Rev.ng](https://rev.ng/)**: rev.ng is a suite of tools for binary analysis based on QEMU and LLVM, aiming at accuracy and portability of the analyses across a wide range of architectures.

 - **[S²E](http://s2e.systems/)**: S²E is a platform for writing tools that analyze the properties and behavior of software systems. S²E comes as a modular library that gives virtual machines symbolic execution and program analysis capabilities. S²E runs unmodified x86, x86-64, or ARM software stacks, including programs, libraries, the kernel, and drivers. Symbolic execution then automatically explores hundreds of thousands of paths through the system, while analyzers check that the desired properties hold on these paths and selectors focus path exploration on components of interest.
 
- **[ScratchABit](https://github.com/pfalcon/ScratchABit)**: An interactive incremental disassembler with data/control flow analysis capabilities. ScratchABit supports well-known in the community IDAPython API to write disassembly/extension modules.

- **[Simplify](https://github.com/CalebFenton/simplify)**: Simplify virtually executes an app to understand its behavior and then tries to optimize the code so that it behaves identically but is easier for a human to understand. Each optimization type is simple and generic, so it doesn't matter what the specific type of obfuscation is used.

- **[SimplifyGraph](https://github.com/fireeye/SimplifyGraph)**: IDA Pro plugin to assist with complex graphs

- **[Sibyl](https://github.com/cea-sec/Sibyl)**: Identifies function by studying its side-effects. Uses Miasm under the hood.

- **[SymGDB](https://github.com/SQLab/symgdb)**: Symbolic execution extention for gdb. Uses triton for symbolic execution.

- **[Triton](https://triton.quarkslab.com/)**: A dynamic binary analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a Taint Engine, AST representations of the x86 and the x86-64 instructions set semantics, SMT simplification passes, an SMT Solver Interface and, the last but not least, Python bindings.

- **[Valgrind](http://valgrind.org/)**: Valgrind is an instrumentation framework for building dynamic analysis tools. There are Valgrind tools that can automatically detect many memory management and threading bugs, and profile your programs in detail. You can also use Valgrind to build new tools. 

- **[Vivisect](https://github.com/vivisect/vivisect)**: Python based static analysis and emulation framework.

- **[VTIL](https://github.com/vtil-project)**: VTIL (Virtual-machine Translation Intermediate Language) Project is a set of tools that can be used for binary deobfuscation and devirtualization.

- **[X86isa](http://www.cs.utexas.edu/users/moore/acl2/manuals/current/manual/index-seo.php/ACL2____X86ISA)**: x86 ISA model and machine-code analysis framework developed at UT Austin.
