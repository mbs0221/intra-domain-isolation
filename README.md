# Awesome intra-domain isolation related projects 

## Intra-process isolation

* Control-Flow Attestation
  * ReCFA: Resillent Control-Flow Attestation, [code](https://github.com/suncongxd/ReCFA)
* Basic Data/Metadata Protection
  * Usage of Intel Memory Protection Keys (MPK) to protect Nginx Private Keys, [code](https://github.com/ChristopherHammond13/Dissertation-Public)
  * CoMpk : Isolating Data in Private, and Secure Compartments, [code](https://github.com/arulthileeban/CoMpk)
  * No Need to Hide: Protecting Safe Regions on Commodity Hardware, [code](https://github.com/vusec/memsentry)
* eXecute-Only Memory (XOM)
  * eXecutable-Only-Memory-Switch (XOM-Switch): Hiding your code from advanced code reuse attacks in one shot, [code](https://github.com/intel/xom-switch)
  * System Call Interposer
    * Zpoline: a system call hook mechanism based on binary rewriting, [code](https://github.com/yasukata/zpoline/)
* ERIM: Secure, Efficient In-Process Memory Isolation using Intel MPK, [code](https://gitlab.mpi-sws.org/vahldiek/erim)
* Hodor: Intra-Process Isolation for High-Throughput Data Plane Libraries, [code](https://github.com/hedayati/hodor)
* libmpk: Software Abstraction for Intel Memory Protection Keys (Intel MPK), [code](https://github.com/sslab-gatech/libmpk)
* ConfLLVM: A compiler for enforcing data confidentiality in low-level code, [code](https://github.com/TrustedCloud/ConfLLVM)
* PKU pitfalls: Attacks on PKU-based memory isolation systems, [code](https://github.com/VolSec/pku-pitfalls)
* Donky: Efficient In-Process Isolation for RISC-V and x86, [code](https://github.com/isec-tugraz/Donky)
* Jenny: Securing syscalls for PKU-based memory isolation systems, [code](https://github.com/isec-tugraz/Jenny)
* You Shall Not (by)Pass! Practical, Secure, and Fast PKU-based Sandboxing, [code](https://github.com/ku-leuven-msec/The-Cerberus-Project)
* Multi-Variant Execution
  * Secure and Efficient In-process Monitor (and Library) Protection with Intel MPK, [code](https://github.com/ssrg-vt/MonGuard)
  * sMVX: Multi-Variant Execution on Selected Code Paths, [code](https://github.com/ssrg-vt/sMVX/)
  * Secure and Efficient Application Monitoring and Replication without Kernel Patches, [code](https://github.com/ReMon-MVEE/ReMon)
  * Sharing is caring: secure and efficient shared memory support for MVEEs, [code](https://github.com/ReMon-MVEE/ReMon), [zenodo](https://doi.org/10.5281/zenodo.6360039)
* MPKAlloc: Efficient Heap Meta-Data Integrity Through Hardware Memory Protection Keys, [code](https://github.com/BUseclab/mpkalloc)
* VIP: Safeguard Value Invariant Property for Thwarting Critical Memory Corruption Attacks, [code](https://github.com/cosmoss-jigu/vip)
* Simplex: Repurposing Intel Memory Protection Extensions for Secure Storage, [code](https://github.com/bingseclab/simplex)
* InversOS: Efficient Control-Flow Protection for AArch64 Applications with Privilege Inversion, [code](https://github.com/URSec/InversOS)
* Framework 
  * Enclosures: language-based restriction of untrusted libraries, [code](https://github.com/aghosn/enclosures)
  * uSwitch: Fast Kernel Context Isolation with Implicit Context Switches, [code](https://github.com/rssys/uswitch)
* CAPACITY: Cryptographically-Authenticated Intra-process Isolation on ARM, [code](https://github.com/sslab-skku/capacity)
* Language Runtime Integration
  * WebAssembly Runtime
    * Put your memory in order: Efficient domain-based memory isolation for WASM applications, [code](https://github.com/PKU-ASAL/PKUWA)
    * Going beyond the Limits of SFI: Flexible and Secure Hardware-Assisted In-Process Isolation with HFI, [code](https://github.com/PLSysSec/hfi-root)
    * Swivel: Hardening WebAssembly against Spectre, [code](https://github.com/PLSysSec/swivel)
    * Cage: Hardware-Accelerated Safe WebAssembly, [code](https://doi.org/10.5281/zenodo.13772996)
* Auditing Frameworks Need Resource Isolation: A Systematic Study on the Super Producer Threat to System Auditing and Its Mitigation, [code](https://github.com/nodropforsecurity/nodrop)
* Userspace OS Subsystem
  * Endokernel: A Thread Safe Monitor for Lightweight Subprocess Isolation, [code](https://github.com/endokernel/endokernel-paper-ver)
  * Pegasus: Transparent and Unified Kernel-Bypass Networking for Fast Local and Remote Communication, [code](https://github.com/rssys/pegasus-artifact)
* Toast: A Heterogeneous Memory Management System, [code](https://github.com/TUM-DSE/Toast)
* Fault Tolerance
  * Secure Rewind & Discard of Isolated Domains, [code](https://github.com/EricssonResearch/secure-rewind-and-discard)
* Serverless
  * Faastlane: Accelerating Function-as-a-Service Workflows, [code](https://github.com/csl-iisc/faastlane)
  * Rethinking Deployment for Serverless Functions: A Performance-first Perspective, [code](https://github.com/tjulym/Chiron)
* Mixed-Language Security
  * TRust: A Compilation Framework for In-process Isolation to Protect Safe Rust against Untrusted Code, [code](https://github.com/seccompgeek/trust23-metsafe24)
  * METASAFE: Compiling for Protecting Smart Pointer Metadata to Ensure Safe Rust Integrity, [code](https://github.com/seccompgeek/trust23-metsafe24)
  * Secure Rewind & Discard of Isolated Domains for Foreign Function Interface in Rust, [code](https://github.com/EricssonResearch/sdradrustffi)
  * PKRU-Safe: Automatically Locking Down the Heap Between Safe and Unsafe Languages, [code](https://github.com/securesystemslab/PKRU-Safe)
  * Keeping Safe Rust Safe with Galeed, [code](https://github.com/mit-ll/galeed)
* Dedicated Storage & File Systems
  * Persistent Memory
    * TENET: Memory Safe and Fault Tolerant Persistent Transactional Memory, [code](https://github.com/cosmoss-jigu/TENET)
  * File Systems
    * ctFS: Replacing file indexing with hardware memory translation through contiguous file allocation for persistent memory, [code](https://github.com/robinlee09201/ctFS)
    * MPFS: A Scalable User-Space Persistent Memory File System for Multiple Processes, [code](https://github.com/BOGEDABUDA/MPFS)
    * Overcoming the Last Mile between Log-Structured File Systems and Persistent Memory via Scater Logging, [code](https://github.com/HIT-HSSL/slotfs-eurosys)
  * Userspace Storage
    * Rearchitecting in-memory object stores for low latency, [code](https://github.com/danyangz/lightning)
    * Aeolia: Fast and Secure Userspace Interrupt-Based Storage Stack, [code](https://github.com/TELOS-syslab/Aeolia)
 
## Intra-Kernel isolation

* Basic Data/Metadata Protection
  * Fast Intra-Kernel Isolation and Security with IskiOS, [code](https://github.com/URSec/iskios)
* Kernel compartmentalization
  * Preventing Kernel Hacks with HAKCs, [code](https://github.com/mit-ll/HAKC)
  * BULKHEAD: Secure, Scalable, and Efficient Kernel Compartmentalization with PKS, [code](https://github.com/gyg128/BULKHEAD/)
  * Erebor: A Drop-In Sandbox Solution for Private Data Processing in Untrusted Confidential Virtual Machines, [code](https://github.com/ASTERISC-Release/Erebor), [zenodo](https://doi.org/10.5281/zenodo.14943102)
* Kernel Extension & eBPF Security
  * MOAT: Towards Safe BPF Kernel Extension, [code](https://github.com/jwnhy/MOAT-Open)

## Intra-Enclave/CVM isolation

* SGXJail: Defeating Enclave Malware via Confinement, [code](https://github.com/isec-tugraz/sgxjail)
* SGXLock: Towards Efficiently Establishing Mutual Distrust Between Host Application and Enclave for SGX, [code](https://github.com/blocksecteam/sgxlock)
* More Granular, Less Trust: Enforcing Intra-Process Isolation With Arm CCA in an Untrusted Management Environment, [code](https://github.com/erhade/CCAegis)

## Intra-Unikernel isolation

* Intra-Unikernel Isolation with Intel Memory Protection Keys, [code](https://github.com/ssrg-vt/libhermitMPK)
* AlloyStack: A Library Operating System for Serverless Workflow Applications, [code](https://github.com/tanksys/AlloyStack)
* Unishyper: A Rust-based Unikernel Enhancing Reliability and Efficiency of Embedded Systems, [code](https://github.com/hky1999/Unishyper)
* Intra-Unikraft Isolation
  * CubicleOS: A Library OS with Software Componentisation for Practical Isolation, [code](https://github.com/lsds/CubicleOS)
  * FlexOS: Towards Flexible OS Isolation, [code](https://github.com/project-flexos/asplos22-ae)
  * uIO: Lightweight and Extensible Unikernels, [code](https://github.com/TUM-DSE/uio)
  * SURE: Secure Unikernels Make Serverless Computing Rapid and Efficient, [code](https://github.com/ucr-serverless/sure)
  * Reboot-Based Recovery of Unikernels at the Component Level, [code](https://zenodo.org/records/10784506)
  * MorphOS: An Extensible Networked Operating System, [code](https://github.com/TUM-DSE/MorphOS)
