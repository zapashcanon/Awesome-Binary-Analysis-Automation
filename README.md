# Awesome Binary Analysis Automation

<p align="center">
   <img width=100% src="cover.gif">
</p>

<p align="center">
A comprehensive list of tools and resources for automating binary analysis, vulnerability research, and reverse engineering using various techniques like machine learning, scripting, and static/dynamic analysis.
</p>

<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://github.com/user1342/Awesome-Binary-Analysis-Automation)
![GitHub contributors](https://img.shields.io/github/contributors/user1342/Awesome-Binary-Analysis-Automation)
![GitHub Repo stars](https://img.shields.io/github/stars/user1342/Awesome-Binary-Analysis-Automation?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/user1342/Awesome-Binary-Analysis-Automation?style=social)
![GitHub last commit](https://img.shields.io/github/last-commit/user1342/Awesome-Binary-Analysis-Automation)
<br>

</div>

# How to Use

Awesome Binary Analysis Automation is an amazing list for people who work in taking apart binaries and firmware. Simply press `ctrl + F` to search for a keyword, go through our Contents Menu, or look out for a '☆' indicating some great and up-to-date resources.

# Contents

- [Tools](#tools)
  - [Decompilers/ Disassemblers](#decompilers-disassemblers)
  - [Automated Reverse Engineering](#automated-reverse-engineering)
  - [Automated Vulnerability Detection](#automated-vulnerability-detection)
  - [Automated Malware Detection](#automated-malware-detection)
  - [Emulation and Fuzzing](#emulation-and-fuzzing)
  - [Binary Feature Extraction](#binary-feature-extraction)
  - [Function Comparison and Diffing](#function-comparison-and-diffing)
  - [Misc](#misc)
- [Books](#books)
- [Videos](#videos)

# Tools 

## Decompilers/ Disassemblers

- [IDA Pro](https://hex-rays.com/ida-pro/) - Advanced disassembler and reverse engineering tool with extensive scripting capabilities.
- [☆ Ghidra](https://ghidra-sre.org/) - NSA's reverse engineering framework offering disassembly, decompilation, and scripting.
- [☆ Binary Ninja](https://binary.ninja/) - Known for its intuitive UI and powerful scripting capabilities for various binary analysis tasks.
- [☆ Radare2](https://www.radare.org/) - Open-source framework for reverse engineering and binary analysis.
- [Hopper](https://www.hopperapp.com/) - Disassembler for macOS and Linux with decompiling and debugging capabilities.
- [Jakstab](https://www.jakstab.org/) - Integrated disassembly and static analysis framework.
- [GTIRB](https://github.com/GrammaTech/gtirb) - IR Binary analysis and rewriting data structure.

## Automated Reverse Engineering

- [Firmware-Mod-Kit](https://github.com/rampageX/firmware-mod-kit) - Collection of scripts for modifying firmware images.
- [☆ Binwalk](https://github.com/ReFirmLabs/binwalk) - For firmware analysis, extraction, and reverse engineering.
- [Firmwalker](https://github.com/craigz28/firmwalker) - A script for searching the extracted firmware file system for goodies.
- [Srecord](http://srecord.sourceforge.net/) - Tools for manipulating EPROM load files.
- [Pharos](https://github.com/cmu-sei/pharos) - Carnegie Mellon University’s framework for automating reverse engineering tasks.
- [Triton](https://triton.quarkslab.com/) - Dynamic Binary Analysis (DBA) framework.
- [Echo](https://github.com/Washi1337/Echo) - Static analysis, symbolic execution, and emulation framework.
- [LIEF](https://lief.quarkslab.com/) - Parses, modifies, and abstracts binary formats.
- [☆ Monocle](https://github.com/user1342/Monocle) - Large Language Model For Binary Analysis Search.
- [Owi](https://github.com/OCamlPro/owi) - Parallel (dynamic) symbolic execution engine built on WebAssembly (Wasm). ([paper](https://hal.science/hal-04627413))


## Automated Vulnerability Detection

- [Fwanalyzer](https://github.com/cruise-automation/fwanalyzer) - Firmware security analysis.
- [☆ Flawfinder](https://github.com/david-a-wheeler/flawfinder) - Tool for analyzing the entropy of firmware files.
- [Fdiff](https://github.com/david-a-wheeler/flawfinder) - Identifies potential security flaws in source code.
- [Checksec](https://github.com/slimm609/checksec.sh) - Security checks for binaries.
- [Cwe_checker](https://github.com/fkie-cad/cwe_checker) - Identifies common bug patterns in binaries.
- [Searchsploit](https://www.exploit-db.com/searchsploit) - Command-line search tool for Exploit Database.
- [CVE Search](https://github.com/cve-search/cve-search) - Searching for known vulnerabilities.
- [Exploitdb](https://www.exploit-db.com/) - An archive of public exploits and corresponding vulnerable software.
- [Dependency-check](https://github.com/jeremylong/DependencyCheck) - A software composition analysis utility that detects publicly disclosed vulnerabilities in application dependencies.
- [BinSkim](https://github.com/microsoft/binskim) - Analyzes PE and ELF binary formats for security and correctness.

## Automated Malware Detection

- [Yara](https://github.com/VirusTotal/yara) - Malware detection and classification.

## Emulation and Fuzzing

- [☆ QEMU](https://www.qemu.org/) - Emulator for hardware virtualization used by EMBA for live testing modules.
- [Firmadyne](https://github.com/firmadyne/firmadyne) - A full-system emulation tool for analyzing Linux-based firmware.
- [☆ Unicorn Engine](https://www.unicorn-engine.org/) - CPU emulator framework used for binary analysis and vulnerability research.
- [AFL++ (American Fuzzy Lop)](https://github.com/AFLplusplus/AFLplusplus) - Fuzzing framework for vulnerability discovery.
- [LibFuzzer](https://llvm.org/docs/LibFuzzer.html) - In-process fuzzing tool targeting specific functions.
- [DECAF](https://github.com/sycurelab/DECAF) - QEMU-based binary analysis platform.
- [DeepState](https://github.com/trailofbits/deepstate) - Framework for symbolic execution and fuzzing engines.
- [oss-fuzz-gen](https://github.com/google/oss-fuzz-gen) - LLM powered fuzzing via OSS-Fuzz.

## Binary Feature Extraction

- [☆ bin2ml](https://github.com/br0kej/bin2ml) - Extracting ML-ready data from software binaries.

## Function Comparison and Diffing

- [FASER](https://github.com/br0kej/FASER) - Cross-Architecture Function Similarity Search Model.
- [☆ Tweezer](https://github.com/user1342/tweezer) - Identifies unknown function names in binaries

# Contributing
Your contributions are always welcome! Please read the contribution guidelines first. We  follow the Contributor Covenant Code of Conduct. Please make sure to review and adhere to this code of conduct when contributing.

# Licence <a href="LICENCE"> ![GitHub](https://img.shields.io/github/license/user1342/Awesome-Binary-Analysis-Automation) </a>
This project is licensed under the MIT License - see the LICENSE.md file for details.

