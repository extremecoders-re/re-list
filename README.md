# RE list

A list of reverse engineering tools with a focus on binary analysis.

- **[Amoco](https://github.com/bdcht/amoco)**: A python package dedicated to the (static) analysis of binaries.

- **[Angr](http://angr.io/)**: A python framework for analyzing binaries. It combines both static and dynamic symbolic ("concolic") analysis, making it applicable to a variety of tasks.

- **[BARF](https://github.com/programa-stic/barf-project)**: An open source binary analysis framework. It is a scriptable platform that supports instruction lifting from multiple architectures, binary translation to an intermediate representation, an extensible framework for code analysis plugins and interoperation with external tools such as debuggers, SMT solvers and instrumentation tools.

- **[BAP](https://github.com/BinaryAnalysisPlatform/bap)**: The Binary Analysis Platform is a reverse engineering and program analysis platform that targets binaries, i.e., compiled programs without the source code. BAP supports multiple architectures (more than 30), though the first tier architectures are x86, x86-64, and ARM. 

- **[BinCAT](https://github.com/airbus-seclab/bincat)**: A static Binary Code Analysis Toolkit, designed to help reverse engineers, directly from IDA. It features: value analysis (registers and memory), taint analysis, type reconstruction and propagation, backward and forward analysis

- **[Bindead](https://bitbucket.org/mihaila/bindead/wiki/Home)**: An analyzer for executable machine code. It features a disassembler that translates machine code bits into an assembler like language (RREIL) that in turn is then analyzed by the static analysis component using abstract interpretation. As Bindead operates on the machine code level, it can be used without having the source code of the program to be analyzed.

- **[BitBlaze](http://bitblaze.cs.berkeley.edu/)**: BitBlaze Binary Analysis Platform features a novel fusion of static and dynamic analysis techniques, dynamic symbolic execution, and whole-system emulation and binary instrumentation. 

- **[Cemu](https://github.com/hugsy/cemu)**: Cheap EMUlator: lightweight multi-architecture assembly playground

- **[Cutter](https://github.com/radareorg/cutter)**: A Qt and C++ GUI for radare2.

- **[Falcon](https://github.com/falconre/falcon)**: A formal binary analysis framework in Rust. Falcon seeks to implement data-flow analysis, abstract interpretation, and constraint solving over compiled, binary executables.

- **[Jakstab](http://www.jakstab.org/)**: An Abstract Interpretation-based, integrated disassembly and static analysis framework for designing analyses on executables and recovering reliable control flow graphs.

- **[Kaitai Struct](http://kaitai.io/)**: A declarative language used for describe various binary data structures, laid out in files or in memory: i.e. binary file formats, network stream packet formats, etc.

- **[Manticore](https://github.com/trailofbits/manticore)**: A prototyping tool for dynamic binary analysis, with support for symbolic execution, taint analysis, and binary instrumentation.

- **[Mcsema](https://github.com/trailofbits/mcsema)**: Framework for lifting x86, amd64, and aarch64 program binaries to LLVM bitcode.

- **[Metasm](https://github.com/jjyg/metasm)**: Ruby assembly manipulation suite

- **[Medusa](https://github.com/wisk/medusa)**: A disassembler designed to be both modular and interactive. 

- **[Miasm](https://github.com/cea-sec/miasm)**: Free and open source (GPLv2) reverse engineering framework. Miasm aims to analyze / modify / generate binary programs.

- **[Panda](https://github.com/panda-re/panda)**: PANDA is an open-source Platform for Architecture-Neutral Dynamic Analysis. It is built upon the QEMU whole system emulator, and so analyses have access to all code executing in the guest and all data. PANDA adds the ability to record and replay executions, enabling iterative, deep, whole system analyses. 

- **[Panopticon](https://github.com/das-labor/panopticon)**: A cross platform disassembler for reverse engineering written in Rust. It can disassemble AMD64, x86, AVR and MOS 6502 instruction sets and open ELF files. Panopticon comes with Qt GUI for browsing and annotating control flow graphs.

- **[Pharos](https://github.com/cmu-sei/pharos)**: The framework is designed to facilitate the automated analysis of binary programs. It uses the ROSE compiler infrastructure for disassembly, control flow analysis, instruction semantics, and more.

- **[Pimp](https://github.com/radare/radare2-extras/tree/master/pimp)**: Triton based R2 plugin for concolic execution

- **[Ponce](https://github.com/illera88/Ponce)**: An IDA Pro plugin that provides users the ability to perform taint analysis and symbolic execution over binaries in an easy and intuitive fashion. With Ponce you are one click away from getting all the power from cutting edge symbolic execution.

- **[Remill](https://github.com/trailofbits/remill)**: A static binary translator that translates machine code instructions into LLVM bitcode. It translates x86 and amd64 machine code into LLVM bitcode. 
Remill focuses on accurately lifting instructions. It is meant to be used as a library for other tools, e.g. McSema.

- **[ScratchABit](https://github.com/pfalcon/ScratchABit)**: An interactive incremental disassembler with data/control flow analysis capabilities. ScratchABit supports well-known in the community IDAPython API to write disassembly/extension modules.

- **[Simplify](https://github.com/CalebFenton/simplify)**: Simplify virtually executes an app to understand its behavior and then tries to optimize the code so that it behaves identically but is easier for a human to understand. Each optimization type is simple and generic, so it doesn't matter what the specific type of obfuscation is used.

- **[Sibyl](https://github.com/cea-sec/Sibyl)**: Identifies function by studying its side-effects. Uses Miasm under the hood.

- **[SymGDB](https://github.com/SQLab/symgdb)**: Symbolic execution extention for gdb. Uses triton for symbolic execution.

- **[Triton](https://triton.quarkslab.com/)**: A dynamic binary analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a Taint Engine, AST representations of the x86 and the x86-64 instructions set semantics, SMT simplification passes, an SMT Solver Interface and, the last but not least, Python bindings.

- **[Vivisect](https://github.com/vivisect/vivisect)**: Python based static analysis and emulation framework.
