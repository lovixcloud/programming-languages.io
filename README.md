<div align="center">

# 📘 The Comprehensive Programming Languages Bible

**A curated encyclopedia of 100+ programming languages, paradigms, and ecosystems**

[![Languages](https://img.shields.io/badge/Languages-100%2B-blue?style=flat-square&logo=bookstack)](.)
[![Paradigms](https://img.shields.io/badge/Paradigms-15%2B-purple?style=flat-square&logo=atom)](.)
[![Last Updated](https://img.shields.io/badge/Updated-May%202026-green?style=flat-square&logo=calendar)](.)
[![License](https://img.shields.io/badge/License-CC%20BY--SA%204.0-orange?style=flat-square&logo=creativecommons)](.)
[![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=flat-square&logo=github)](.)

```
    ╔══════════════════════════════════════════════════════════╗
    ║  💻  🌐  📱  🤖  🎮  🧮  🗃️  🔒  🎨  ⚡  🐚  📊  🔬  ║
    ║     Every Language. Every Paradigm. One Document.       ║
    ╚══════════════════════════════════════════════════════════╝
```

</div>

---

## 📑 Table of Contents

- [Introduction](#-introduction)
- [Languages by Category](#-languages-by-category)
  - [🔧 Systems & Native Code](#-systems--native-code)
  - [🏢 Object-Oriented & Enterprise](#-object-oriented--enterprise)
  - [🐍 Scripting & Dynamic](#-scripting--dynamic)
  - [λ Functional & Declarative](#-functional--declarative)
  - [🌐 Web & Browser](#-web--browser)
  - [📊 Data, Math & Query](#-data-math--query)
  - [🐚 Shell & Automation](#-shell--automation)
  - [🚀 Emerging & Specialized](#-emerging--specialized)
  - [🎭 Esoteric & Educational](#-esoteric--educational)
  - [📝 Markup, Config & Formats](#-markup-config--formats)
- [Trends & The Future](#-trends--the-future)
- [How to Contribute](#-how-to-contribute)
- [License](#-license)

---

## 🌟 Introduction

Welcome to the **Comprehensive Programming Languages Bible** — a single, definitive reference documenting the syntax, history, ecosystem, and modern relevance of over 100 programming languages. From the bare-metal power of C and Assembly to the abstract beauty of Haskell and the pragmatic versatility of Python, this document exists to educate, compare, and inspire.

Whether you are a systems engineer, a web developer, a data scientist, or a language enthusiast, you will find:
- **Accurate, up-to-date version information** (as of 2026)
- **Runnable "Hello World" examples** for every language
- **Installation instructions** across Windows, macOS, and Linux
- **Curated learning resources** and official documentation links
- **Honest pros, cons, and fun facts**

> *"A language that doesn't affect the way you think about programming is not worth knowing."* — Alan J. Perlis

---

## 🗂️ Languages by Category

| Category | Count | Paradigms | Notable Members |
|----------|-------|-----------|-----------------|
| [🔧 Systems & Native Code](#-systems--native-code) | 12 | Procedural, Imperative, Systems | C, Rust, Zig, Ada, Fortran |
| [🏢 Object-Oriented & Enterprise](#-object-oriented--enterprise) | 11 | OOP, Class-based, Enterprise | Java, C#, Kotlin, Swift, ABAP |
| [🐍 Scripting & Dynamic](#-scripting--dynamic) | 11 | Dynamic, Duck-typed, Scripting | Python, Ruby, Lua, PHP, JS |
| [λ Functional & Declarative](#-functional--declarative) | 12 | Functional, Logic, Declarative | Haskell, Erlang, Prolog, Elm |
| [🌐 Web & Browser](#-web--browser) | 8 | Event-driven, Markup, Compiled | HTML/CSS, WASM, TS, CoffeeScript |
| [📊 Data, Math & Query](#-data-math--query) | 10 | Array, Statistical, Query | R, SQL, MATLAB, APL, K/Q |
| [🐚 Shell & Automation](#-shell--automation) | 6 | Command, Scripting, Pipeline | Bash, PowerShell, Fish, AWK |
| [🚀 Emerging & Specialized](#-emerging--specialized) | 14 | Domain-specific, Experimental | Mojo, Carbon, Gleam, Solidity |
| [🎭 Esoteric & Educational](#-esoteric--educational) | 9 | Esoteric, Visual, Academic | Brainfuck, Malbolge, Scratch |
| [📝 Markup, Config & Formats](#-markup-config--formats) | 8 | Markup, Data-serialization | Markdown, JSON, YAML, LaTeX |

---

## 🔧 Systems & Native Code

> Languages that speak directly to the machine. These are the foundations of operating systems, embedded firmware, game engines, and high-performance applications.

---

### 🔷 C

| | |
|:---|:---|
| **Paradigm** | Procedural, Imperative |
| **Created** | 1972 by Dennis Ritchie (Bell Labs) |
| **Current Version** | C23 (ISO/IEC 9899:2024) |
| **Extension** | `.c`, `.h` |

**Overview:** The lingua franca of computing. C provides direct hardware access with minimal runtime overhead, making it the foundation of modern operating systems and embedded systems.

**Domains:** OS kernels, embedded firmware, microcontrollers, compilers, databases, device drivers  
**Why It Matters:** Nearly every major OS (Linux, Windows, macOS) and language runtime is built in C.  
**Notable Users:** Linux Foundation, Apple, Microsoft, NASA, PostgreSQL, Redis

**Setup:**
```bash
# macOS
brew install gcc

# Linux (Debian/Ubuntu)
sudo apt install build-essential

# Windows
winget install MSYS2.MSYS2
# Or install Visual Studio Build Tools
```

**Hello World:**
```c
#include <stdio.h>

int main(void) {
    // Print to standard output
    printf("Hello, World!\n");
    return 0;
}
```

**Run:**
```bash
gcc hello.c -o hello
./hello
# Hello, World!
```

**Resources:** [ISO C Standard](https://www.iso.org/standard/82075.html) • [Learn C](https://www.learn-c.org/) • [cppreference C](https://en.cppreference.com/w/c)

**Pros:** ⚡ Unmatched performance, 🌍 Universal portability, 🔧 Fine hardware control  
**Cons:** 🐛 Manual memory management, 📉 Steep learning curve, ⏱️ Slow development

---

### ➕ C++

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: OOP, Procedural, Generic, Functional |
| **Created** | 1985 by Bjarne Stroustrup (Bell Labs) |
| **Current Version** | C++23 (ISO/IEC 14882:2024), C++26 in draft |
| **Extension** | `.cpp`, `.hpp` |

**Overview:** C's object-oriented successor. C++ combines zero-cost abstractions with high-level features, dominating game engines, browsers, and high-frequency trading systems.

**Domains:** Game engines, browsers, high-frequency trading, systems software, AAA games  
**Why It Matters:** Powers Chrome, Firefox, Unreal Engine, and most AAA video games.  
**Notable Users:** Google, Microsoft, Adobe, Autodesk, Blizzard, Electronic Arts

**Setup:**
```bash
# macOS
brew install gcc  # includes g++

# Linux
sudo apt install g++ cmake

# Windows
winget install Microsoft.VisualStudio.2022.BuildTools --override "--wait --add Microsoft.VisualStudio.Workload.VCTools"
```

**Hello World:**
```cpp
#include <iostream>

int main() {
    // Stream output operator
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

**Run:**
```bash
g++ hello.cpp -o hello -std=c++23
./hello
# Hello, World!
```

**Resources:** [ISO C++](https://isocpp.org/) • [cppreference](https://en.cppreference.com/) • [LearnCpp](https://www.learncpp.com/)

**Pros:** 🚀 Zero-cost abstractions, 🎮 Game industry standard, 📚 Massive ecosystem  
**Cons:** 🔥 Complex syntax, 🐢 Slow compile times, 📖 Steep expertise curve

---

### 🦀 Rust

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Concurrent, Functional, Imperative |
| **Created** | 2010 by Graydon Hoare (Mozilla Research) |
| **Current Version** | 1.86.0 (2026) |
| **Extension** | `.rs` |

**Overview:** Memory safety without garbage collection. Rust's ownership model eliminates data races at compile time, making it the modern choice for systems programming.

**Domains:** Systems programming, WebAssembly, CLI tools, embedded, blockchain, OS development  
**Why It Matters:** The only mainstream systems language with memory safety guarantees.  
**Notable Users:** Mozilla, AWS, Microsoft, Google, Discord, Cloudflare, Meta

**Setup:**
```bash
# All platforms (official installer)
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

# Or via package managers
brew install rustup        # macOS
sudo apt install rustc     # Linux (older)
```

**Hello World:**
```rust
fn main() {
    // Macro for formatted printing
    println!("Hello, World!");
}
```

**Run:**
```bash
rustc hello.rs
./hello
# Hello, World!

# Or using Cargo (recommended)
cargo new hello_project
cd hello_project
cargo run
```

**Resources:** [The Rust Book](https://doc.rust-lang.org/book/) • [Rust by Example](https://doc.rust-lang.org/rust-by-example/) • [crates.io](https://crates.io/)

**Pros:** 🛡️ Memory safety, ⚡ C++-like performance, 🦀 Excellent tooling (Cargo)  
**Cons:** 📈 Steep learning curve (borrow checker), ⏱️ Longer compile times

---

### ⚡ Zig

| | |
|:---|:---|
| **Paradigm** | Imperative, Procedural, Systems |
| **Created** | 2016 by Andrew Kelley |
| **Current Version** | 0.14.0 (2026) |
| **Extension** | `.zig` |

**Overview:** A pragmatic systems language that replaces C with compile-time code execution, explicit memory management, and seamless C interoperability.

**Domains:** Systems programming, game development, embedded, cross-compilation  
**Why It Matters:** First-class cross-compilation and compile-time metaprogramming.  
**Notable Users:** TigerBeetle (database), Bun (JavaScript runtime), Uber (select projects)

**Setup:**
```bash
# macOS / Linux
brew install zig

# Or download from website
# https://ziglang.org/download/
```

**Hello World:**
```zig
const std = @import("std");

pub fn main() void {
    std.debug.print("Hello, World!\n", .{});
}
```

**Run:**
```bash
zig run hello.zig
# Hello, World!
```

**Resources:** [Zig Language Reference](https://ziglang.org/documentation/master/) • [Zig Learn](https://ziglearn.org/) • [Loris Cro's Blog](https://kristoff.it/blog/)

**Pros:** 🔧 Compile-time execution, 🌍 Amazing cross-compilation, 🔗 C interop  
**Cons:** 🚧 Pre-1.0 stability, 📦 Smaller ecosystem, 👥 Smaller community

---

### 🔌 Assembly

| | |
|:---|:---|
| **Paradigm** | Imperative, Unstructured, Machine-specific |
| **Created** | 1949 (EDSAC initial orders) |
| **Current Version** | Architecture-specific (x86-64, ARM64, RISC-V) |
| **Extension** | `.asm`, `.s`, `.nasm` |

**Overview:** The closest human-readable form to machine code. Assembly is essential for bootloaders, firmware, reverse engineering, and extreme optimization.

**Domains:** Firmware, bootloaders, kernel development, reverse engineering, embedded  
**Why It Matters:** Ultimate hardware control and the foundation of all software stacks.  
**Notable Users:** BIOS/UEFI vendors, security researchers, console manufacturers

**Setup:**
```bash
# Linux
sudo apt install nasm gcc

# macOS (uses Clang integrated assembler)
xcode-select --install

# Windows
winget install NASM.NASM
```

**Hello World (x86-64 Linux, NASM):**
```nasm
section .data
    msg db "Hello, World!", 10
    len equ $ - msg

section .text
    global _start

_start:
    mov rax, 1          ; sys_write
    mov rdi, 1          ; stdout
    mov rsi, msg        ; message
    mov rdx, len        ; length
    syscall

    mov rax, 60         ; sys_exit
    xor rdi, rdi        ; status 0
    syscall
```

**Run:**
```bash
nasm -f elf64 hello.asm -o hello.o
ld hello.o -o hello
./hello
# Hello, World!
```

**Resources:** [x86-64 Instruction Reference](https://www.felixcloutier.com/x86/) • [RISC-V Spec](https://riscv.org/technical/specifications/) • [Reverse Engineering for Beginners](https://beginners.re/)

**Pros:** ⚡ Absolute control, 💾 Minimal footprint, 🔍 Hardware transparency  
**Cons:** 📉 Not portable, 🐢 Slow development, 🧠 Extreme complexity

---

### 🛡️ Ada

| | |
|:---|:---|
| **Paradigm** | Structured, OOP, Concurrent, Real-time |
| **Created** | 1980 by Jean Ichbiah (US DoD) |
| **Current Version** | Ada 2022 (ISO/IEC 8652:2023) |
| **Extension** | `.adb`, `.ads` |

**Overview:** Engineered for safety-critical systems. Ada's strong typing, contracts, and Ravenscar profile make it the gold standard for avionics and defense.

**Domains:** Avionics, defense, aerospace, medical devices, rail transport  
**Why It Matters:** Boeing 787, Airbus A380, and Eurofighter Typhoon run Ada.  
**Notable Users:** US DoD, Boeing, Airbus, NASA, Alstom, Lockheed Martin

**Setup:**
```bash
# macOS / Linux
brew install gnat

# Linux (Debian)
sudo apt install gnat

# Windows
# Download GNAT Community from AdaCore
```

**Hello World:**
```ada
with Ada.Text_IO;

procedure Hello is
begin
   Ada.Text_IO.Put_Line("Hello, World!");
end Hello;
```

**Run:**
```bash
gnatmake hello.adb
./hello
# Hello, World!
```

**Resources:** [AdaCore](https://www.adacore.com/) • [Ada Reference Manual](https://www.adaic.org/resources/add_content/standards/22rm/html/RM-TOC.html) • [Learn Ada](https://learn.adacore.com/)

**Pros:** 🛡️ Safety-critical design, 🔒 Strong typing, 📜 Readable syntax  
**Cons:** 📦 Smaller ecosystem, 🏛️ Bureaucratic origins, 👥 Niche community

---

### 🔢 Fortran

| | |
|:---|:---|
| **Paradigm** | Procedural, Imperative, Array-based |
| **Created** | 1957 by John Backus (IBM) |
| **Current Version** | Fortran 2023 (ISO/IEC 1539-1:2024) |
| **Extension** | `.f90`, `.f95`, `.f03`, `.f08`, `.f18` |

**Overview:** The oldest high-level language still in production. Fortran dominates numerical computing, weather prediction, and computational physics due to its native array operations.

**Domains:** High-performance computing (HPC), weather modeling, computational physics, finite element analysis  
**Why It Matters:** Still unbeatable for numerical arrays and scientific computing.  
**Notable Users:** NASA, NOAA, CERN, climate research centers, molecular dynamics labs

**Setup:**
```bash
# macOS
brew install gcc  # gfortran included

# Linux
sudo apt install gfortran

# Windows
# MinGW-w64 or Intel oneAPI
```

**Hello World:**
```fortran
program hello
    implicit none
    character(len=13) :: message
    message = "Hello, World!"
    print *, message
end program hello
```

**Run:**
```bash
gfortran hello.f90 -o hello
./hello
# Hello, World!
```

**Resources:** [Fortran-lang.org](https://fortran-lang.org/) • [Modern Fortran Explained](https://www.elsevier.com/books/modern-fortran-explained/metcalf/978-0-19-881188-6) • [gfortran docs](https://gcc.gnu.org/onlinedocs/gfortran/)

**Pros:** 🧮 Superior array math, ⚡ HPC performance, 📜 Decades of libraries  
**Cons:** 📝 Verbose syntax, 🎨 Limited modern features, 👥 Aging community

---

### 📠 COBOL

| | |
|:---|:---|
| **Paradigm** | Procedural, Imperative, Business-oriented |
| **Created** | 1959 by CODASYL (Grace Hopper et al.) |
| **Current Version** | COBOL 2023 (ISO/IEC 1989:2023) |
| **Extension** | `.cob`, `.cbl`, `.cpy` |

**Overview:** The backbone of global finance. COBOL processes an estimated $3 trillion in daily transactions and powers critical banking infrastructure.

**Domains:** Banking, insurance, government, payroll, transaction processing  
**Why It Matters:** 43% of global banking systems still run COBOL; expertise is scarce and valuable.  
**Notable Users:** IBM, US Social Security Administration, major banks, insurance giants

**Setup:**
```bash
# GnuCOBOL (open source)
brew install gnu-cobol        # macOS
sudo apt install gnucobol     # Linux

# Commercial: Micro Focus, IBM Enterprise COBOL
```

**Hello World:**
```cobol
       IDENTIFICATION DIVISION.
       PROGRAM-ID. HelloWorld.
       PROCEDURE DIVISION.
           DISPLAY "Hello, World!"
           STOP RUN.
```

**Run:**
```bash
cobc -x hello.cob
./hello
# Hello, World!
```

**Resources:** [GnuCOBOL](https://gnucobol.sourceforge.io/) • [COBOL Programming Course](https://github.com/openmainframeproject/cobol-programming-course) • [IBM COBOL](https://www.ibm.com/products/cobol-compiler-family)

**Pros:** 💰 High job demand, 🏦 Financial sector dominance, 📜 Self-documenting  
**Cons:** 🕰️ Perceived as obsolete, 📝 Extremely verbose, 👥 Aging workforce

---

### 🎯 D

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: OOP, Functional, Procedural |
| **Created** | 2001 by Walter Bright (Digital Mars) |
| **Current Version** | 2.110 (2026) |
| **Extension** | `.d` |

**Overview:** C++ reimagined. D offers systems-level control with modern syntax, garbage collection (optional), and powerful metaprogramming.

**Domains:** Systems programming, game engines, web servers, compilers  
**Why It Matters:** Proves systems languages can have modern convenience without Rust's complexity.  
**Notable Users:** eBay (parts of backend), Facebook (select tools), Remedy Entertainment

**Setup:**
```bash
# macOS / Linux
brew install dmd

# Linux (Debian)
sudo apt install gdc

# Or download from dlang.org
```

**Hello World:**
```d
import std.stdio;

void main() {
    writeln("Hello, World!");
}
```

**Run:**
```bash
dmd hello.d
./hello
# Hello, World!
```

**Resources:** [D Language](https://dlang.org/) • [D Tour](https://tour.dlang.org/) • [DUB Package Registry](https://code.dlang.org/)

**Pros:** 🔧 C++ power with better syntax, 🗑️ Optional GC, ⚡ Fast compilation  
**Cons:** 📦 Smaller ecosystem, 👥 Niche community, 🌐 Limited jobs

---

### 👑 Nim

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Imperative, Functional, Metaprogramming |
| **Created** | 2008 by Andreas Rumpf |
| **Current Version** | 2.2.0 (2026) |
| **Extension** | `.nim` |

**Overview:** Python-like syntax with C performance. Nim compiles to C, C++, or JavaScript and features powerful compile-time macros.

**Domains:** Systems tools, game development, web backends, CLI applications  
**Why It Matters:** The most productive systems language for developers coming from Python.  
**Notable Users:** Status.im (messaging), Karax (frontend), various indie games

**Setup:**
```bash
# macOS / Linux
brew install nim

# Linux
sudo apt install nim

# Windows
chocho install nim
```

**Hello World:**
```nim
echo "Hello, World!"
```

**Run:**
```bash
nim compile --run hello.nim
# Hello, World!
```

**Resources:** [Nim Lang](https://nim-lang.org/) • [Nim by Example](https://nim-by-example.github.io/) • [Nim Basics](https://narimiran.github.io/nim-basics/)

**Pros:** 🐍 Pythonic syntax, ⚡ C performance, 🔧 Compile-time metaprogramming  
**Cons:** 🚧 Smaller ecosystem, 🐛 Some instability, 👥 Limited corporate adoption

---

### ✌️ V

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Imperative, OOP, Functional |
| **Created** | 2019 by Alex Medvednikov |
| **Current Version** | 0.4 (2026) |
| **Extension** | `.v` |

**Overview:** A simple, fast, safe language for developing maintainable software. V promises 1-second compilation, no null, and built-in concurrency.

**Domains:** System tools, web backends, GUIs, games  
**Why It Matters:** Radical simplicity with C interop and built-in cross-compilation.  
**Notable Users:** V Language project, select startups, open-source tools

**Setup:**
```bash
# macOS / Linux
git clone https://github.com/vlang/v
cd v && make

# Or via package manager where available
brew install vlang
```

**Hello World:**
```v
fn main() {
    println('Hello, World!')
}
```

**Run:**
```bash
v run hello.v
# Hello, World!
```

**Resources:** [V Language](https://vlang.io/) • [V Docs](https://github.com/vlang/v/blob/master/doc/docs.md) • [V Forum](https://github.com/vlang/v/discussions)

**Pros:** ⚡ Instant compilation, 🛡️ No null, 🔧 Built-in cross-compilation  
**Cons:** 🚧 Pre-1.0, 📦 Very small ecosystem, 🐛 Some rough edges

---

### 💎 Crystal

| | |
|:---|:---|
| **Paradigm** | OOP, Concurrent, Compiled |
| **Created** | 2014 by Ary Borenszweig, Juan Wajnerman |
| **Current Version** | 1.14.0 (2026) |
| **Extension** | `.cr` |

**Overview:** Ruby syntax at C speed. Crystal is statically typed with type inference, channels, and macros, compiling to efficient native code.

**Domains:** Web servers, system tools, real-time applications, APIs  
**Why It Matters:** Brings Ruby's beauty to systems programming without a VM.  
**Notable Users:** Kemal web framework, Lucky framework, various API services

**Setup:**
```bash
# macOS
brew install crystal

# Linux (Debian/Ubuntu)
curl -fsSL https://crystal-lang.org/install.sh | sudo bash

# Windows (WSL recommended)
# Native Windows support in development
```

**Hello World:**
```crystal
puts "Hello, World!"
```

**Run:**
```bash
crystal run hello.cr
# Hello, World!

# Compile
crystal build hello.cr --release
```

**Resources:** [Crystal Lang](https://crystal-lang.org/) • [Crystal API Docs](https://crystal-lang.org/api/) • [Crystal Shards](https://crystalshards.org/)

**Pros:** 💎 Ruby-like syntax, ⚡ Native performance, 🧵 Built-in concurrency  
**Cons:** 🚧 Windows support maturing, 📦 Smaller ecosystem, 👥 Niche

---

## 🏢 Object-Oriented & Enterprise

> Languages designed for large-scale software architecture, business logic, and maintainable codebases across enterprise teams.

---

### ☕ Java

| | |
|:---|:---|
| **Paradigm** | OOP, Class-based, Concurrent |
| **Created** | 1995 by James Gosling (Sun Microsystems) |
| **Current Version** | Java 26 (2026) |
| **Extension** | `.java` |

**Overview:** "Write once, run anywhere." Java's JVM revolutionized portable enterprise software and remains the backbone of Android and massive backend systems.

**Domains:** Enterprise backends, Android apps, big data, financial systems, cloud services  
**Why It Matters:** The JVM ecosystem is unmatched in maturity; Spring Boot dominates microservices.  
**Notable Users:** Google, Amazon, Netflix, LinkedIn, Uber, Spotify, Android

**Setup:**
```bash
# macOS / Linux
brew install openjdk

# Linux (Debian)
sudo apt install default-jdk

# Windows
winget install EclipseAdoptium.Temurin.21.JDK
```

**Hello World:**
```java
public class HelloWorld {
    public static void main(String[] args) {
        // Entry point
        System.out.println("Hello, World!");
    }
}
```

**Run:**
```bash
javac HelloWorld.java
java HelloWorld
# Hello, World!
```

**Resources:** [Oracle Java](https://www.oracle.com/java/) • [OpenJDK](https://openjdk.org/) • [Baeldung](https://www.baeldung.com/) • [Java Brains](https://www.youtube.com/c/JavaBrainsChannel)

**Pros:** 🏢 Enterprise standard, 🌍 Massive ecosystem, 🗑️ Automatic memory management  
**Cons:** 📝 Verbose syntax, 🐢 Slower startup, 🧠 Complex ecosystem

---

### 🔷 C#

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: OOP, Functional, Concurrent |
| **Created** | 2000 by Anders Hejlsberg (Microsoft) |
| **Current Version** | C# 13 (.NET 9/10, 2026) |
| **Extension** | `.cs` |

**Overview:** Microsoft's flagship language. C# combines the power of C++ with the productivity of Visual Basic, driving Windows, Xbox, and cloud development.

**Domains:** Windows apps, game engines (Unity), enterprise software, cloud (Azure), web APIs  
**Why It Matters:** Unity powers 50% of mobile games; .NET Core is cross-platform and high-performance.  
**Notable Users:** Microsoft, Stack Overflow, Unity Technologies, Intuit, Dell

**Setup:**
```bash
# macOS / Linux
brew install dotnet

# Linux (Debian)
wget https://packages.microsoft.com/config/debian/12/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb
sudo apt update && sudo apt install dotnet-sdk-9.0

# Windows
winget install Microsoft.DotNet.SDK.9
```

**Hello World:**
```csharp
using System;

class Program {
    static void Main() {
        Console.WriteLine("Hello, World!");
    }
}
```

**Run:**
```bash
dotnet new console -n HelloApp
cd HelloApp
# Replace Program.cs, then:
dotnet run
# Hello, World!
```

**Resources:** [Microsoft C# Docs](https://learn.microsoft.com/en-us/dotnet/csharp/) • [DotNetPerls](https://www.dotnetperls.com/) • [C# Corner](https://www.c-sharpcorner.com/)

**Pros:** 🎮 Unity integration, 🛠️ Excellent tooling (VS), 🚀 LINQ & async/await  
**Cons:** 🪟 Microsoft-centric history, 📦 Heavy runtime, 📝 Ceremony

---

### 🅺 Kotlin

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: OOP, Functional, Concurrent |
| **Created** | 2011 by JetBrains |
| **Current Version** | 2.1.0 (2026) |
| **Extension** | `.kt`, `.kts` |

**Overview:** Java's modern successor. Kotlin eliminates boilerplate, ensures null-safety, and is the preferred language for Android development.

**Domains:** Android apps, server-side (Ktor/Spring), multiplatform (KMP), data science  
**Why It Matters:** Google-endorsed for Android; 100% interoperable with Java.  
**Notable Users:** Google, JetBrains, Pinterest, Trello, Netflix, Coursera

**Setup:**
```bash
# macOS
brew install kotlin

# Linux (SDKMAN)
curl -s https://get.sdkman.io | bash
sdk install kotlin

# Windows
winget install JetBrains.Kotlin.Complier
```

**Hello World:**
```kotlin
fun main() {
    println("Hello, World!")
}
```

**Run:**
```bash
kotlinc hello.kt -include-runtime -d hello.jar
java -jar hello.jar
# Hello, World!

# Or script mode
kotlin hello.kts
```

**Resources:** [Kotlin Lang](https://kotlinlang.org/) • [Kotlin Docs](https://kotlinlang.org/docs/home.html) • [Kotlin Playground](https://play.kotlinlang.org/)

**Pros:** 🛡️ Null safety, 📝 Concise syntax, 🤝 Java interop  
**Cons:** 🐢 Slower compile than Java, 📚 Smaller library ecosystem, 🧠 New concepts

---

### 🟣 Scala

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: OOP, Functional, Concurrent |
| **Created** | 2004 by Martin Odersky (EPFL) |
| **Current Version** | 3.6.0 (Scala 3, 2026) |
| **Extension** | `.scala`, `.sc` |

**Overview:** Where Java meets Haskell. Scala fuses object-oriented and functional programming on the JVM, powering the largest data pipelines in the world.

**Domains:** Big data (Spark), distributed systems, web backends, reactive systems  
**Why It Matters:** Apache Spark — the standard for big data — is written in Scala.  
**Notable Users:** Twitter, LinkedIn, Netflix, Airbnb, Verizon, Apple (select systems)

**Setup:**
```bash
# macOS / Linux (SDKMAN or Coursier)
curl -fL https://github.com/coursier/launchers/raw/master/cs-x86_64-pc-linux.gz | gzip -d > cs
chmod +x cs && ./cs setup

# Or via brew
brew install scala
```

**Hello World:**
```scala
@main def hello() = {
    println("Hello, World!")
}
```

**Run:**
```bash
scala hello.scala
# Hello, World!
```

**Resources:** [Scala Lang](https://www.scala-lang.org/) • [Scala 3 Book](https://docs.scala-lang.org/scala3/book/introduction.html) • [Scala Center](https://scala.epfl.ch/)

**Pros:** 🧠 Powerful type system, ⚡ JVM performance, 📊 Big data native  
**Cons:** 📈 Steep learning curve, 🐢 Slow compilation, 👥 Smaller job market

---

### 🍎 Swift

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: OOP, Protocol-oriented, Functional |
| **Created** | 2014 by Chris Lattner (Apple) |
| **Current Version** | 6.1 (2026) |
| **Extension** | `.swift` |

**Overview:** Apple's replacement for Objective-C. Swift is safe, fast, and expressive, designed for iOS, macOS, and increasingly server-side Swift.

**Domains:** iOS/macOS apps, server-side, system programming, machine learning (Swift for TensorFlow)  
**Why It Matters:** The only viable path for native Apple ecosystem development.  
**Notable Users:** Apple, Lyft, Airbnb, LinkedIn, Kickstarter, IBM (server-side)

**Setup:**
```bash
# macOS (Xcode)
xcode-select --install

# Linux
wget -q https://download.swift.org/swift-6.0.2-release/ubuntu2204/swift-6.0.2-RELEASE/swift-6.0.2-RELEASE-ubuntu22.04.tar.gz
tar xzf swift-6.0.2-RELEASE-ubuntu22.04.tar.gz

# Windows
winget install Swift.Toolchain
```

**Hello World:**
```swift
print("Hello, World!")
```

**Run:**
```bash
swift hello.swift
# Hello, World!
```

**Resources:** [Swift.org](https://www.swift.org/) • [Swift Docs](https://www.swift.org/documentation/) • [Hacking with Swift](https://www.hackingwithswift.com/)

**Pros:** 🛡️ Memory safety, 🚀 High performance, 🍎 Native Apple integration  
**Cons:** 🍎 Apple-centric, 📦 Smaller cross-platform ecosystem, 🔄 Frequent changes

---

### 🎯 Dart

| | |
|:---|:---|
| **Paradigm** | OOP, Functional, Concurrent |
| **Created** | 2011 by Lars Bak and Kasper Lund (Google) |
| **Current Version** | 3.6.0 (2026) |
| **Extension** | `.dart` |

**Overview:** The language behind Flutter. Dart is optimized for UI development with a reactive framework, compiling to native code or JavaScript.

**Domains:** Cross-platform mobile (Flutter), web, desktop, server-side  
**Why It Matters:** Flutter allows single-codebase iOS, Android, web, and desktop apps.  
**Notable Users:** Google, Alibaba, BMW, eBay, Philips, Square

**Setup:**
```bash
# macOS
brew install dart

# Linux
sudo apt update && sudo apt install dart

# Windows
winget install Google.Dart
```

**Hello World:**
```dart
void main() {
    print('Hello, World!');
}
```

**Run:**
```bash
dart run hello.dart
# Hello, World!
```

**Resources:** [Dart.dev](https://dart.dev/) • [Flutter](https://flutter.dev/) • [DartPad](https://dartpad.dev/)

**Pros:** 📱 Flutter ecosystem, ⚡ Fast development (hot reload), 🎯 Productive  
**Cons:** 📦 Niche outside Flutter, 👥 Smaller community, 🌐 Limited backend use

---

### 🏛️ Eiffel

| | |
|:---|:---|
| **Paradigm** | OOP, Design by Contract |
| **Created** | 1986 by Bertrand Meyer |
| **Current Version** | 23.09 (2026) |
| **Extension** | `.e` |

**Overview:** The academic gold standard for OOP. Eiffel introduced Design by Contract and remains influential in formal software engineering education.

**Domains:** Banking, defense, aerospace, academic research, critical systems  
**Why It Matters:** Design by Contract influenced C#, Ada, and modern assertion libraries.  
**Notable Users:** AXA (insurance), US DoD, various European banks

**Setup:**
```bash
# macOS / Linux
# Download EiffelStudio from https://www.eiffel.com/download/
# Open-source edition available
```

**Hello World:**
```eiffel
class HELLO
create
    make
feature
    make
        do
            print ("Hello, World!%N")
        end
end
```

**Run:** Via EiffelStudio IDE or command-line compiler `ec`.

**Resources:** [Eiffel.com](https://www.eiffel.com/) • [Eiffel Docs](https://www.eiffel.org/doc/) • [Object-Oriented Software Construction](https://www.eiffel.com/book/object-oriented-software-construction/)

**Pros:** 📜 Design by Contract, 🧠 Academic rigor, 🛡️ Reliability focus  
**Cons:** 👥 Tiny community, 📦 Limited libraries, 🏛️ Academic perception

---

### 🖥️ Delphi / Object Pascal

| | |
|:---|:---|
| **Paradigm** | OOP, Structured, Imperative |
| **Created** | 1986 (Turbo Pascal) by Anders Hejlsberg; Delphi 1995 |
| **Current Version** | Delphi 12 Athens (2026) |
| **Extension** | `.pas`, `.dpr` |

**Overview:** Rapid Application Development (RAD) pioneer. Delphi combines visual design with a fast native compiler, still powering legacy enterprise and IoT systems.

**Domains:** Desktop apps, legacy enterprise, IoT, industrial automation, database frontends  
**Why It Matters:** Millions of lines of business-critical code still run on Delphi.  
**Notable Users:** Embarcadero, various industrial automation firms, medical software

**Setup:**
```bash
# Commercial: Embarcadero Delphi
# Free: Free Pascal (FPC) + Lazarus IDE
# macOS/Linux
brew install fpc
```

**Hello World:**
```pascal
program HelloWorld;
begin
    Writeln('Hello, World!');
end.
```

**Run:**
```bash
fpc hello.pas
./hello
# Hello, World!
```

**Resources:** [Embarcadero](https://www.embarcadero.com/products/delphi) • [Free Pascal](https://www.freepascal.org/) • [Lazarus IDE](https://www.lazarus-ide.org/)

**Pros:** 🚀 RAD development, ⚡ Native compilation, 📊 Database integration  
**Cons:** 💰 Expensive licenses, 🕰️ Legacy perception, 👥 Shrinking community

---

### 🟦 VB.NET

| | |
|:---|:---|
| **Paradigm** | OOP, Structured, Event-driven |
| **Created** | 2001 by Microsoft (evolution of Visual Basic) |
| **Current Version** | Part of .NET 9 (2026) |
| **Extension** | `.vb` |

**Overview:** The accessible face of .NET. VB.NET maintains Visual Basic's readable syntax while providing full access to the modern .NET runtime.

**Domains:** Windows business apps, legacy migration, rapid prototyping, Office automation  
**Why It Matters:** Bridges legacy VB6 codebases to modern .NET without full rewrites.  
**Notable Users:** Microsoft, small-to-medium business software vendors

**Setup:**
```bash
# Part of .NET SDK
winget install Microsoft.DotNet.SDK.9   # Windows
brew install dotnet                     # macOS/Linux
```

**Hello World:**
```vb
Module HelloWorld
    Sub Main()
        Console.WriteLine("Hello, World!")
    End Sub
End Module
```

**Run:**
```bash
dotnet new console -lang VB -n HelloApp
cd HelloApp
dotnet run
# Hello, World!
```

**Resources:** [Microsoft VB Docs](https://learn.microsoft.com/en-us/dotnet/visual-basic/) • [VB.NET Tutorial](https://www.tutorialspoint.com/vb.net/) • [.NET Foundation](https://dotnetfoundation.org/)

**Pros:** 📖 Readable syntax, 🤝 .NET ecosystem, 🔄 Legacy migration path  
**Cons:** 🕰️ Declining popularity, 👥 Smaller community, 📝 Less expressive

---

### 🏭 ABAP

| | |
|:---|:---|
| **Paradigm** | OOP, Procedural, Event-driven |
| **Created** | 1983 by SAP |
| **Current Version** | ABAP 2308 / ABAP Cloud (2026) |
| **Extension** | `.abap` |

**Overview:** The proprietary language of SAP. ABAP powers the business logic of 77% of global transaction revenue and virtually all Fortune 500 ERP systems.

**Domains:** SAP ERP, CRM, S/4HANA, business process automation, enterprise reporting  
**Why It Matters:** SAP runs the world's supply chains; ABAP developers are highly paid.  
**Notable Users:** SAP, 90% of Fortune 500 companies, BMW, Nestle, Coca-Cola

**Setup:**
```bash
# ABAP requires SAP system access
# Options: SAP BTP ABAP Environment, SAP CAL, or on-premise NetWeaver
# Local: VS Code with ABAP extension + abapGit
```

**Hello World:**
```abap
REPORT z_hello_world.

START-OF-SELECTION.
    WRITE: 'Hello, World!'.
```

**Run:** Via SAP GUI transaction SE38 or Eclipse ADT.

**Resources:** [SAP ABAP Docs](https://help.sap.com/docs/abap) • [ABAP GitHub](https://github.com/abapGit/abapGit) • [ABAP Community](https://community.sap.com/topics/abap)

**Pros:** 💰 Extremely high demand, 🏭 Enterprise criticality, 📊 Deep SAP integration  
**Cons:** 🔒 SAP lock-in, 📝 Verbose, 🕰️ Legacy codebase weight

---

### 🗄️ RPG

| | |
|:---|:---|
| **Paradigm** | Procedural, Fixed-format |
| **Created** | 1959 by IBM (Report Program Generator) |
| **Current Version** | IBM i 7.5 RPG IV (2026) |
| **Extension** | `.rpgle`, `.rpg`, `.sqlrpgle` |

**Overview:** The language of IBM midrange systems. RPG runs on IBM i (AS/400) and processes core business transactions for manufacturing and logistics.

**Domains:** IBM i systems, manufacturing, logistics, banking on IBM midrange  
**Why It Matters:** IBM i systems are incredibly reliable; many run 24/7 for decades.  
**Notable Users:** IBM, Honda, Toyota, UPS, regional banks, manufacturers

**Setup:**
```bash
# Requires IBM i system or PUB400 (free IBM i account)
# VS Code with RPG extension for editing
```

**Hello World:**
```rpgle
**FREE
dcl-s message varchar(20);
message = 'Hello, World!';
dsply message;
return;
```

**Run:** Via IBM i command line `CALL` or RDi (Rational Developer for i).

**Resources:** [IBM RPG Docs](https://www.ibm.com/docs/en/i/7.5?topic=rpg) • [PUB400 Free IBM i](https://www.pub400.com/) • [RPG2Golang](https://www.rpg2golang.com/)

**Pros:** 🏭 IBM i integration, ⚡ Transaction processing, 🛡️ System stability  
**Cons:** 🕰️ Obscure syntax, 👥 Tiny community, 🔒 IBM hardware lock-in

---

## 🐍 Scripting & Dynamic

> Languages that prioritize developer speed, flexibility, and rapid iteration over compile-time safety.

---

### 🐍 Python

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: OOP, Procedural, Functional |
| **Created** | 1991 by Guido van Rossum (CWI) |
| **Current Version** | 3.13 (3.14 in alpha, 2026) |
| **Extension** | `.py` |

**Overview:** The world's most popular teaching language and a powerhouse in data science, AI, and automation. Python's readability is its superpower.

**Domains:** AI/ML, data science, web backends (Django/FastAPI), automation, scientific computing  
**Why It Matters:** PyTorch and TensorFlow made Python the language of the AI revolution.  
**Notable Users:** Google, Instagram, Netflix, Spotify, NASA, OpenAI, Dropbox

**Setup:**
```bash
# macOS
brew install python

# Linux
sudo apt install python3 python3-pip

# Windows
winget install Python.Python.3.13
# Or https://www.python.org/downloads/
```

**Hello World:**
```python
# Simple and readable
print("Hello, World!")
```

**Run:**
```bash
python3 hello.py
# Hello, World!
```

**Resources:** [Python.org](https://www.python.org/) • [Python Docs](https://docs.python.org/3/) • [Real Python](https://realpython.com/) • [LeetCode](https://leetcode.com/)

**Pros:** 🐍 Readable syntax, 🤖 AI/ML dominance, 📦 Massive ecosystem  
**Cons:** 🐢 Slow execution, 🧵 GIL limitations, 📱 Mobile weakness

---

### 💎 Ruby

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: OOP, Functional, Reflective |
| **Created** | 1995 by Yukihiro "Matz" Matsumoto |
| **Current Version** | 3.4 (2026) |
| **Extension** | `.rb` |

**Overview:** Optimized for programmer happiness. Ruby's elegant syntax and Rails framework revolutionized web development in the 2000s.

**Domains:** Web development (Rails), DevOps (Chef, Vagrant), scripting, prototyping  
**Why It Matters:** Ruby on Rails proved you could build a startup in weeks, not months.  
**Notable Users:** Shopify, GitHub, Airbnb, Stripe, Basecamp, Twitter (historically)

**Setup:**
```bash
# macOS
brew install ruby

# Linux
sudo apt install ruby-full

# Windows
winget install RubyInstallerTeam.Ruby.3.4
```

**Hello World:**
```ruby
puts "Hello, World!"
```

**Run:**
```bash
ruby hello.rb
# Hello, World!
```

**Resources:** [Ruby Lang](https://www.ruby-lang.org/) • [Ruby Docs](https://docs.ruby-lang.org/) • [Ruby on Rails](https://rubyonrails.org/) • [Ruby Koans](http://rubykoans.com/)

**Pros:** 💎 Beautiful syntax, 🚀 Rapid development, 📖 Expressive  
**Cons:** 🐢 Slower than compiled languages, 📉 Declining popularity, 🧵 Concurrency limits

---

### 🐪 Perl

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Functional, Imperative, OOP, Reflective |
| **Created** | 1987 by Larry Wall |
| **Current Version** | 5.40 (2026) |
| **Extension** | `.pl`, `.pm` |

**Overview:** The "duct tape of the Internet." Perl dominated CGI scripting and text processing, with regex capabilities that influenced every language after it.

**Domains:** System administration, text processing, bioinformatics, legacy web  
**Why It Matters:** CPAN was the first great language package repository; Perl regex is universal.  
**Notable Users:** Booking.com, DuckDuckGo, Amazon (historically), bioinformatics labs

**Setup:**
```bash
# macOS (pre-installed, or)
brew install perl

# Linux
sudo apt install perl

# Windows
winget install StrawberryPerl.StrawberryPerl
```

**Hello World:**
```perl
#!/usr/bin/perl
use strict;
use warnings;

print "Hello, World!\n";
```

**Run:**
```bash
perl hello.pl
# Hello, World!
```

**Resources:** [Perl.org](https://www.perl.org/) • [Perl Docs](https://perldoc.perl.org/) • [CPAN](https://www.cpan.org/) • [Modern Perl](http://modernperlbooks.com/)

**Pros:** 📝 Text processing king, 📦 CPAN ecosystem, 🔧 System admin glue  
**Cons:** 🕰️ Legacy perception, 📉 Declining usage, 🧠 "There's more than one way"

---

### 🦋 Raku

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Functional, OOP, Procedural, Concurrent |
| **Created** | 2000-2015 (Perl 6 redesign) by Larry Wall et al. |
| **Current Version** | 2024.09 (2026) |
| **Extension** | `.raku`, `.p6`, `.pl6` |

**Overview:** Perl's ambitious successor. Raku reimagines everything — grammars, junctions, lazy lists — creating one of the most expressive languages ever designed.

**Domains:** Text processing, scripting, language parsing, academic exploration  
**Why It Matters:** Grammar-based parsing is built into the language itself.  
**Notable Users:** Open source community, language researchers, select startups

**Setup:**
```bash
# macOS
brew install rakudo

# Linux
sudo apt install rakudo

# Windows
winget install Rakudo.Rakudo.Star
```

**Hello World:**
```raku
say "Hello, World!";
```

**Run:**
```bash
raku hello.raku
# Hello, World!
```

**Resources:** [Raku Lang](https://www.raku.org/) • [Raku Docs](https://docs.raku.org/) • [Raku Advent](https://raku-advent.blog/)

**Pros:** 🦋 Extremely expressive, 📝 Built-in grammars, 🧠 Advanced features  
**Cons:** 📉 Tiny adoption, 🐢 Slow, 📦 Small ecosystem

---

### 🌙 Lua

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Procedural, Functional, OOP (prototype) |
| **Created** | 1993 by Roberto Ierusalimschy et al. (PUC-Rio) |
| **Current Version** | 5.4.7 (2026) |
| **Extension** | `.lua` |

**Overview:** The embedded scripting champion. Lua's tiny footprint and C API make it the standard for game scripting, embedded systems, and configuration.

**Domains:** Game scripting (Roblox, WoW, Dark Souls), embedded systems, Neovim, Redis, Nginx  
**Why It Matters:** Most scripted games use Lua; it's the fastest interpreted language.  
**Notable Users:** Roblox, Adobe, Nginx, Redis, Neovim, VLC, Wireshark

**Setup:**
```bash
# macOS
brew install lua

# Linux
sudo apt install lua5.4

# Windows
winget install Lua.Lua
```

**Hello World:**
```lua
print("Hello, World!")
```

**Run:**
```bash
lua hello.lua
# Hello, World!
```

**Resources:** [Lua.org](https://www.lua.org/) • [Lua Reference](https://www.lua.org/manual/5.4/) • [Programming in Lua](https://www.lua.org/pil/) • [LuaRocks](https://luarocks.org/)

**Pros:** 🌙 Tiny footprint, ⚡ Fastest interpreted, 🔗 Excellent C API  
**Cons:** 📦 Small standard library, 🧠 1-based indexing surprise, 👥 Niche jobs

---

### 📜 Tcl

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Event-driven, Functional, Imperative |
| **Created** | 1988 by John Ousterhout (UC Berkeley) |
| **Current Version** | 8.6.14 / 9.0 (2026) |
| **Extension** | `.tcl` |

**Overview:** The Tool Command Language. Tcl's embeddable nature and Tk GUI toolkit made it the original rapid GUI prototyping language.

**Domains:** EDA tools (chip design), testing frameworks, GUIs (Tk), embedded scripting  
**Why It Matters:** Synopsys, Cadence, and Mentor Graphics tools are scripted in Tcl.  
**Notable Users:** Cisco, Oracle (TimesTen), EDA vendors, SQLite (testing)

**Setup:**
```bash
# macOS
brew install tcl-tk

# Linux
sudo apt install tcl

# Windows
winget install Magicsplat.Tcl
```

**Hello World:**
```tcl
puts "Hello, World!"
```

**Run:**
```bash
tclsh hello.tcl
# Hello, World!
```

**Resources:** [Tcl Lang](https://www.tcl-lang.org/) • [Tcl Wiki](https://wiki.tcl-lang.org/) • [Tcler's Wiki](https://wiki.tcl-lang.org/page/Tcl)

**Pros:** 🔧 Embeddable, 🎨 Tk GUI toolkit, 📜 Simple syntax  
**Cons:** 🕰️ Dated syntax, 📉 Declining usage, 📦 Limited modern libraries

---

### 🎸 Groovy

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: OOP, Functional, Scripting |
| **Created** | 2003 by James Strachan |
| **Current Version** | 4.0.24 (2026) |
| **Extension** | `.groovy` |

**Overview:** Java's dynamic sibling. Groovy brings closures, DSLs, and scripting to the JVM, powering Gradle builds and Jenkins pipelines.

**Domains:** Build scripts (Gradle), CI/CD (Jenkins), testing, scripting, rapid prototyping  
**Why It Matters:** Gradle is the default Android build system; Jenkins pipelines are Groovy.  
**Notable Users:** Google (Gradle), Netflix, JPMorgan, Target, Walmart

**Setup:**
```bash
# macOS
brew install groovy

# Linux (SDKMAN)
sdk install groovy

# Windows
winget install Apache.Groovy
```

**Hello World:**
```groovy
println "Hello, World!"
```

**Run:**
```bash
groovy hello.groovy
# Hello, World!
```

**Resources:** [Groovy Lang](https://groovy-lang.org/) • [Groovy Docs](https://groovy-lang.org/documentation.html) • [Gradle](https://gradle.org/) • [Jenkins](https://www.jenkins.io/)

**Pros:** 🤝 Java interop, 📝 Concise syntax, 🏗️ Excellent DSL support  
**Cons:** 🐢 Slower than Java, 📉 Declining in new projects, 🧠 Dynamic typing risks

---

### 🐘 PHP

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Imperative, OOP, Functional |
| **Created** | 1995 by Rasmus Lerdorf |
| **Current Version** | 8.4 (2026) |
| **Extension** | `.php` |

**Overview:** The web's workhorse. PHP powers 77% of all websites, including WordPress, and has evolved into a modern language with JIT compilation and attributes.

**Domains:** Web backends, CMS (WordPress, Drupal), e-commerce, server-side scripting  
**Why It Matters:** WordPress alone runs 43% of the entire web; PHP jobs are abundant.  
**Notable Users:** Facebook (HHVM historically), Wikipedia, Slack, Etsy, WordPress.com

**Setup:**
```bash
# macOS
brew install php

# Linux
sudo apt install php

# Windows
winget install PHP.PHP.8.4
```

**Hello World:**
```php
<?php
// PHP requires opening tag
echo "Hello, World!\n";
?>
```

**Run:**
```bash
php hello.php
# Hello, World!
```

**Resources:** [PHP.net](https://www.php.net/) • [PHP Docs](https://www.php.net/docs.php) • [Laravel](https://laravel.com/) • [PHP The Right Way](https://phptherightway.com/)

**Pros:** 🌐 Web dominance, 🚀 Fast development, 📦 Massive hosting support  
**Cons:** 🐘 Inconsistent design, 🧠 Type system history, 📝 "Fractal of bad design" reputation

---

### 🟨 JavaScript

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Event-driven, Functional, OOP, Prototype-based |
| **Created** | 1995 by Brendan Eich (Netscape) |
| **Current Version** | ES2025 (ES16, 2026) |
| **Extension** | `.js` |

**Overview:** The only language native to web browsers. JavaScript has grown from a 10-day hack to the world's most deployed runtime environment.

**Domains:** Web frontend, Node.js backends, mobile (React Native), desktop (Electron), cloud functions  
**Why It Matters:** Every browser runs JS; Node.js made it a full-stack language.  
**Notable Users:** Google, Netflix, Uber, PayPal, Microsoft, virtually every tech company

**Setup:**
```bash
# Built into browsers
# Node.js for server-side
brew install node        # macOS
sudo apt install nodejs  # Linux
winget install OpenJS.NodeJS  # Windows
```

**Hello World:**
```javascript
// Browser or Node.js
console.log("Hello, World!");
```

**Run:**
```bash
node hello.js
# Hello, World!
```

**Resources:** [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript) • [Node.js](https://nodejs.org/) • [JavaScript.info](https://javascript.info/) • [ECMAScript Spec](https://tc39.es/ecma262/)

**Pros:** 🌐 Universal runtime, 📦 npm ecosystem, 🚀 Full-stack capability  
**Cons:** 🧠 Type coercion quirks, 🐢 Single-threaded, 📉 Callback complexity

---

### 📘 TypeScript

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: OOP, Functional, Imperative |
| **Created** | 2012 by Anders Hejlsberg (Microsoft) |
| **Current Version** | 5.8 (2026) |
| **Extension** | `.ts` |

**Overview:** JavaScript with types. TypeScript adds static typing, interfaces, and modern tooling to the world's most popular runtime language.

**Domains:** Large-scale web apps, Node.js backends, libraries, frameworks, enterprise JS  
**Why It Matters:** Most new JS projects use TypeScript; it prevents entire classes of bugs.  
**Notable Users:** Microsoft, Google, Airbnb, Slack, Asana, VS Code (built in TS)

**Setup:**
```bash
# Via Node.js
npm install -g typescript

# Or package managers
brew install typescript
```

**Hello World:**
```typescript
const greeting: string = "Hello, World!";
console.log(greeting);
```

**Run:**
```bash
tsc hello.ts
node hello.js
# Hello, World!

# Or direct execution
npx ts-node hello.ts
```

**Resources:** [TypeScript Lang](https://www.typescriptlang.org/) • [TS Handbook](https://www.typescriptlang.org/docs/handbook/intro.html) • [TS Playground](https://www.typescriptlang.org/play)

**Pros:** 🛡️ Type safety, 🧠 Excellent IDE support, 🤝 JS ecosystem compatibility  
**Cons:** ⏱️ Build step required, 📚 Type complexity, 🐢 Compile time

---

## λ Functional & Declarative

> Languages where functions are first-class citizens, side effects are controlled, and code expresses *what* rather than *how*.

---

### λ Haskell

| | |
|:---|:---|
| **Paradigm** | Purely Functional, Lazy, Statically Typed |
| **Created** | 1990 by Haskell Committee (named after Haskell Curry) |
| **Current Version** | GHC 9.12 (2026) |
| **Extension** | `.hs`, `.lhs` |

**Overview:** The pure functional language. Haskell's type system and lazy evaluation force a fundamentally different — and profoundly powerful — way of thinking about software.

**Domains:** Compilers, financial modeling, formal verification, academia, blockchain (Cardano)  
**Why It Matters:** Influenced Rust, Scala, TypeScript, and modern type systems everywhere.  
**Notable Users:** Facebook (spam filter), Standard Chartered (trading), Galois, IOHK (Cardano)

**Setup:**
```bash
# macOS
brew install ghc cabal-install stack

# Linux
sudo apt install ghc cabal-install

# Windows
winget install GHC.GHC
# Or via Stack: https://get.haskellstack.org/stable/windows-x86_64-installer.exe
```

**Hello World:**
```haskell
main :: IO ()
main = putStrLn "Hello, World!"
```

**Run:**
```bash
ghc hello.hs
./hello
# Hello, World!

# Or interpreted
runhaskell hello.hs
```

**Resources:** [Haskell.org](https://www.haskell.org/) • [Haskell Book](http://haskellbook.com/) • [What I Wish I Knew](https://wiki.haskell.org/Haskell) • [Hackage](https://hackage.haskell.org/)

**Pros:** 🧠 Pure functions, 🛡️ Type safety, 📚 Academic rigor  
**Cons:** 📈 Extremely steep curve, 🐢 Lazy evaluation complexity, 👥 Niche jobs

---

### 📞 Erlang

| | |
|:---|:---|
| **Paradigm** | Functional, Concurrent, Distributed |
| **Created** | 1986 by Joe Armstrong, Robert Virding, Mike Williams (Ericsson) |
| **Current Version** | OTP 27 (2026) |
| **Extension** | `.erl`, `.hrl` |

**Overview:** Built for telecom switches that must never fail. Erlang's actor model and "let it crash" philosophy created the most reliable concurrent runtime in existence.

**Domains:** Telecom, messaging (WhatsApp), distributed systems, real-time services, IoT  
**Why It Matters:** WhatsApp handled 900M users with only 50 engineers thanks to Erlang.  
**Notable Users:** Ericsson, WhatsApp, Cisco, Klarna, Goldman Sachs, RabbitMQ

**Setup:**
```bash
# macOS
brew install erlang

# Linux
sudo apt install erlang

# Windows
winget install Erlang.ErlangOTP
```

**Hello World:**
```erlang
-module(hello).
-export([main/0]).

main() ->
    io:format("Hello, World!~n").
```

**Run:**
```bash
erlc hello.erl
erl -noshell -s hello main -s init stop
# Hello, World!
```

**Resources:** [Erlang.org](https://www.erlang.org/) • [Learn You Some Erlang](https://learnyousomeerlang.com/) • [Erlang Docs](https://www.erlang.org/docs)

**Pros:** 📞 Nine 9s reliability, 🧵 Massive concurrency, 🔥 Hot code swapping  
**Cons:** 📉 Niche syntax, 👥 Small community, 📦 Limited libraries

---

### 💧 Elixir

| | |
|:---|:---|
| **Paradigm** | Functional, Concurrent, Distributed |
| **Created** | 2011 by José Valim (Plataformatec) |
| **Current Version** | 1.18 (2026) |
| **Extension** | `.ex`, `.exs` |

**Overview:** Erlang's modern face. Elixir brings Ruby-like syntax, metaprogramming, and the Phoenix framework to the battle-tested BEAM virtual machine.

**Domains:** Real-time web (Phoenix LiveView), distributed systems, IoT, embedded (Nerves)  
**Why It Matters:** Phoenix LiveView enables real-time web apps without writing JavaScript.  
**Notable Users:** Discord, Pinterest, Bleacher Report, Moz, FarmBot, PepsiCo

**Setup:**
```bash
# macOS
brew install elixir

# Linux
sudo apt install elixir

# Windows
winget install Elixir.Elixir
```

**Hello World:**
```elixir
IO.puts "Hello, World!"
```

**Run:**
```bash
elixir hello.exs
# Hello, World!

# Or compiled
mix new hello
# Edit lib/hello.ex, then mix run
```

**Resources:** [Elixir Lang](https://elixir-lang.org/) • [Elixir Docs](https://hexdocs.pm/elixir/) • [Phoenix Framework](https://www.phoenixframework.org/) • [Elixir School](https://elixirschool.com/)

**Pros:** 💧 Beautiful syntax, 📞 BEAM reliability, 🔥 LiveView real-time web  
**Cons:** 📉 Smaller ecosystem, 🧠 Functional paradigm shift, 🐢 Slower than Go

---

### 🔷 F#

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Functional, OOP, Imperative |
| **Created** | 2005 by Don Syme (Microsoft Research) |
| **Current Version** | F# 9 (.NET 9, 2026) |
| **Extension** | `.fs`, `.fsx` |

**Overview:** Functional programming on .NET. F# combines OCaml-style type inference with full access to the .NET ecosystem, excelling in data analysis and domain modeling.

**Domains:** Financial modeling, data science, machine learning, domain-driven design, web APIs  
**Why It Matters:** F# type providers are unique; its conciseness beats C# for analytical tasks.  
**Notable Users:** Jet.com, Kaggle, BlueMountain Capital, various hedge funds

**Setup:**
```bash
# Part of .NET SDK
brew install dotnet        # macOS/Linux
winget install Microsoft.DotNet.SDK.9  # Windows
```

**Hello World:**
```fsharp
printfn "Hello, World!"
```

**Run:**
```bash
dotnet fsi hello.fsx
# Hello, World!
```

**Resources:** [F# Software Foundation](https://fsharp.org/) • [F# Docs](https://learn.microsoft.com/en-us/dotnet/fsharp/) • [F# for Fun and Profit](https://fsharpforfunandprofit.com/) • [Fable](https://fable.io/)

**Pros:** 🧠 Type inference, 🤝 .NET ecosystem, 📊 Data analysis power  
**Cons:** 👥 Niche community, 📝 C# interop friction, 📉 Limited jobs

---

### 🌿 Clojure

| | |
|:---|:---|
| **Paradigm** | Functional, Lisp, Concurrent |
| **Created** | 2007 by Rich Hickey |
| **Current Version** | 1.12 (2026) |
| **Extension** | `.clj`, `.cljs`, `.cljc` |

**Overview:** Lisp for the JVM. Clojure brings immutable data structures, software transactional memory, and Lisp macros to modern enterprise environments.

**Domains:** Distributed systems, data processing, web services, financial systems, DSLs  
**Why It Matters:** Immutable-by-default data eliminates an entire class of concurrency bugs.  
**Notable Users:** Netflix, Amazon, Walmart, Puppet Labs, Nubank, CircleCI

**Setup:**
```bash
# macOS / Linux
brew install clojure/tools/clojure

# Linux
curl -L -O https://github.com/clojure/brew-install/releases/latest/download/linux-install.sh
chmod +x linux-install.sh && sudo ./linux-install.sh

# Windows
winget install ClojureTools.Clojure
```

**Hello World:**
```clojure
(println "Hello, World!")
```

**Run:**
```bash
clojure -M hello.clj
# Hello, World!
```

**Resources:** [Clojure.org](https://clojure.org/) • [Clojure Docs](https://clojure.org/reference/documentation) • [Clojure for the Brave](https://www.braveclojure.com/) • [Clojars](https://clojars.org/)

**Pros:** 🌿 Lisp macros, 🛡️ Immutable data, 🔧 JVM ecosystem  
**Cons:** 📉 Parentheses syntax, 🧠 Steep learning curve, 👥 Niche market

---

### 🐫 OCaml

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Functional, OOP, Imperative |
| **Created** | 1996 by INRIA (descendant of Caml, 1985) |
| **Current Version** | 5.3 (2026) |
| **Extension** | `.ml`, `.mli` |

**Overview:** The pragmatic functional language. OCaml's powerful module system and type inference have influenced Rust, F#, and Scala.

**Domains:** Compilers, theorem provers, financial systems, systems programming, web (OCaml)  
**Why It Matters:** The Rust borrow checker was directly inspired by OCaml's region-based memory.  
**Notable Users:** Jane Street (trading), Facebook (Flow, pfff), Bloomberg, Docker (historically)

**Setup:**
```bash
# macOS
brew install ocaml opam

# Linux
sudo apt install ocaml opam

# Windows (WSL or OCaml for Windows)
winget install OCaml.OCaml
```

**Hello World:**
```ocaml
print_endline "Hello, World!"
```

**Run:**
```bash
ocaml hello.ml
# Hello, World!

# Or compile
ocamlc -o hello hello.ml && ./hello
```

**Resources:** [OCaml.org](https://ocaml.org/) • [Real World OCaml](https://dev.realworldocaml.org/) • [OCaml Packages](https://ocaml.org/packages)

**Pros:** 🧠 Powerful type system, ⚡ Fast native code, 🔧 Module system  
**Cons:** 👥 Niche community, 📦 Smaller ecosystem, 📝 Syntax quirks

---

### 🎹 Scheme

| | |
|:---|:---|
| **Paradigm** | Functional, Minimalist, Lisp |
| **Created** | 1975 by Gerald Sussman and Guy Steele (MIT) |
| **Current Version** | R7RS-small (2013), various implementations (Guile 3.0, Chicken 5.4) |
| **Extension** | `.scm`, `.ss` |

**Overview:** Lisp distilled to its essence. Scheme's minimalism and elegant design make it the preferred teaching language for computer science fundamentals.

**Domains:** Education, scripting (Guile), embedded extension languages, research  
**Why It Matters:** SICP (Structure and Interpretation of Computer Programs) is a rite of passage.  
**Notable Users:** GNU Guile (GNU tools), GIMP (Script-Fu), various universities

**Setup:**
```bash
# macOS
brew install guile

# Linux
sudo apt install guile-3.0

# Windows
# Use WSL or install Chicken Scheme
```

**Hello World:**
```scheme
(display "Hello, World!")
(newline)
```

**Run:**
```bash
guile hello.scm
# Hello, World!
```

**Resources:** [Scheme.org](https://www.scheme.org/) • [R7RS Spec](https://small.r7rs.org/) • [SICP](https://mitp-content-server.mit.edu/books/content/sectbyfn/books_pres_0/6515/sicp.zip/full-text/book/book.html) • [Guile](https://www.gnu.org/software/guile/)

**Pros:** 🧠 Minimalist beauty, 🎓 Educational gold standard, 🔧 Macros  
**Cons:** 📉 Fragmented implementations, 📦 Small libraries, 👥 Academic niche

---

### 🎾 Racket

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Functional, OOP, Logic, Meta |
| **Created** | 1995 by Matthias Felleisen (PLT Inc.) |
| **Current Version** | 8.15 (2026) |
| **Extension** | `.rkt` |

**Overview:** A language for making languages. Racket's macro system and language-oriented programming make it the premier platform for language design and education.

**Domains:** Language research, education, DSL creation, web development, scripting  
**Why It Matters:** The best language for studying programming language implementation.  
**Notable Users:** Brown University, Northeastern University, various research labs

**Setup:**
```bash
# macOS
brew install racket

# Linux
sudo apt install racket

# Windows
winget install Racket.Racket
```

**Hello World:**
```racket
#lang racket
"Hello, World!"
```

**Run:**
```bash
racket hello.rkt
# Hello, World!
```

**Resources:** [Racket Lang](https://racket-lang.org/) • [Racket Docs](https://docs.racket-lang.org/) • [How to Design Programs](https://htdp.org/) • [Beautiful Racket](https://beautifulracket.com/)

**Pros:** 🎾 Language creation, 🎓 Excellent education, 📚 Rich documentation  
**Cons:** 👥 Academic focus, 📦 Niche ecosystem, 🐢 Slower than compiled langs

---

### 🦁 Common Lisp

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Functional, OOP, Imperative, Meta |
| **Created** | 1984 (ANSI standard), descended from Lisp (1958) |
| **Current Version** | SBCL 2.5, Clozure CL 1.13 (2026) |
| **Extension** | `.lisp`, `.lsp`, `.cl` |

**Overview:** The programmable programming language. Common Lisp's unmatched introspection, conditions/restarts, and runtime mutability make it uniquely powerful.

**Domains:** AI research, complex simulations, rapid prototyping, complex business logic  
**Why It Matters:** The only language where you can debug and patch a running space probe.  
**Notable Users:** NASA (Deep Space 1), Grammarly (historically), ITA Software (Google Flights)

**Setup:**
```bash
# macOS
brew install sbcl

# Linux
sudo apt install sbcl

# Windows
winget install SBCL.SBCL
# Or Portacle (portable CL environment)
```

**Hello World:**
```lisp
(format t "Hello, World!~%")
```

**Run:**
```bash
sbcl --script hello.lisp
# Hello, World!
```

**Resources:** [Common Lisp Hyperspec](http://www.lispworks.com/documentation/HyperSpec/Front/index.htm) • [Practical Common Lisp](http://www.gigamonkeys.com/book/) • [Quicklisp](https://www.quicklisp.org/beta/) • [CL Cookbook](https://lispcookbook.github.io/cl-cookbook/)

**Pros:** 🦁 Ultimate flexibility, 🔥 Hot code reloading, 🧠 Macros  
**Cons:** 📉 Niche community, 📝 Historical baggage, 📦 Library gaps

---

### 🧩 Prolog

| | |
|:---|:---|
| **Paradigm** | Logic, Declarative |
| **Created** | 1972 by Alain Colmerauer and Philippe Roussel |
| **Current Version** | ISO Prolog, SWI-Prolog 9.3 (2026) |
| **Extension** | `.pl`, `.prolog` |

**Overview:** Programming in logic. Prolog lets you state facts and rules, then queries the inference engine to derive conclusions — ideal for AI and constraint problems.

**Domains:** AI research, expert systems, natural language processing, constraint solving, semantic web  
**Why It Matters:** The original AI language; still unbeatable for rule-based reasoning.  
**Notable Users:** IBM Watson (historical), various expert system vendors, academic research

**Setup:**
```bash
# macOS
brew install swi-prolog

# Linux
sudo apt install swi-prolog

# Windows
winget install SWI-Prolog.SWI-Prolog
```

**Hello World:**
```prolog
:- initialization(main).
main :-
    write('Hello, World!'), nl.
```

**Run:**
```bash
swipl -q -f hello.pl -t main
# Hello, World!
```

**Resources:** [SWI-Prolog](https://www.swi-prolog.org/) • [Learn Prolog Now](http://www.learnprolognow.org/) • [Prolog Wiki](https://en.wikipedia.org/wiki/Prolog) • [ISO Prolog](https://www.iso.org/standard/21413.html)

**Pros:** 🧩 Declarative power, 🤖 AI native, 🔍 Pattern matching  
**Cons:** 📉 Niche use, 🐢 Performance, 🧠 Unfamiliar paradigm

---

### 🌳 Elm

| | |
|:---|:---|
| **Paradigm** | Functional, Reactive |
| **Created** | 2012 by Evan Czaplicki |
| **Current Version** | 0.19.1 (2026) |
| **Extension** | `.elm` |

**Overview:** A delightful language for reliable web apps. Elm compiles to JavaScript with no runtime exceptions and a friendly compiler that acts like a tutor.

**Domains:** Frontend web apps, interactive UIs, reliable JavaScript generation  
**Why It Matters:** The "no runtime exceptions" guarantee is unique among frontend languages.  
**Notable Users:** NoRedInk, Culture Amp, various European startups

**Setup:**
```bash
# macOS / Linux
npm install -g elm

# Or via installer
curl -L -o elm.gz https://github.com/elm/compiler/releases/download/0.19.1/binary-for-linux-64-bit.gz
gunzip elm.gz && chmod +x elm && sudo mv elm /usr/local/bin/
```

**Hello World:**
```elm
import Html exposing (text)

main =
    text "Hello, World!"
```

**Run:**
```bash
elm init
# Place in src/Main.elm
elm reactor
# Open browser at http://localhost:8000
```

**Resources:** [Elm Lang](https://elm-lang.org/) • [Elm Guide](https://guide.elm-lang.org/) • [Elm Packages](https://package.elm-lang.org/) • [Elm Discourse](https://discourse.elm-lang.org/)

**Pros:** 🛡️ No runtime exceptions, 🎓 Friendly compiler, 🌳 Reliable  
**Cons:** 📉 Small ecosystem, 🔒 Opinionated architecture, 🧠 Learning curve

---

### 📦 PureScript

| | |
|:---|:---|
| **Paradigm** | Purely Functional, Haskell-like |
| **Created** | 2013 by Phil Freeman |
| **Current Version** | 0.15.15 (2026) |
| **Extension** | `.purs` |

**Overview:** Haskell for the browser. PureScript compiles to readable JavaScript with strict type checking, row polymorphism, and effect tracking.

**Domains:** Type-safe frontend, functional web apps, React alternatives, academic  
**Why It Matters:** Brings Haskell's type safety to web development without a runtime.  
**Notable Users:** SlamData, various functional programming enthusiasts

**Setup:**
```bash
# Via npm
npm install -g purescript spago

# Or via binary release
```

**Hello World:**
```purescript
module Main where

import Effect.Console (log)

main = log "Hello, World!"
```

**Run:**
```bash
spago init
# Place in src/Main.purs
spago run
# Hello, World!
```

**Resources:** [PureScript.org](https://www.purescript.org/) • [PureScript Docs](https://github.com/purescript/documentation) • [PureScript by Example](https://book.purescript.org/) • [Pursuit](https://pursuit.purescript.org/)

**Pros:** 🛡️ Strict types, 📦 Readable JS output, 🧠 Advanced type features  
**Cons:** 📉 Tiny community, 🐢 Compilation, 📚 Limited libraries

---

## 🌐 Web & Browser

> Languages that power the visual and interactive layer of the internet, from markup to WebAssembly.

---

### 🌐 HTML / CSS

| | |
|:---|:---|
| **Paradigm** | Markup (HTML), Declarative styling (CSS) |
| **Created** | HTML 1993 (Tim Berners-Lee); CSS 1996 (Håkon Wium Lie) |
| **Current Version** | HTML5.3, CSS4 (modular, 2026) |
| **Extension** | `.html`, `.htm`, `.css` |

**Overview:** The structural and presentational layers of the web. HTML provides semantic document structure; CSS controls visual rendering across devices.

**Domains:** Web pages, emails, documentation, UI layouts, responsive design  
**Why It Matters:** Every web page ever built uses HTML; CSS enables the modern visual web.  
**Notable Users:** Every website, browser, and web application in existence

**Setup:** No installation needed — any text editor and browser suffice.

**Hello World:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Hello</title>
    <style>
        body {
            font-family: system-ui, sans-serif;
            color: #333;
            display: grid;
            place-items: center;
            height: 100vh;
            margin: 0;
        }
        h1 { color: #0066cc; }
    </style>
</head>
<body>
    <h1>Hello, World!</h1>
</body>
</html>
```

**Run:** Open `hello.html` in any browser.

**Resources:** [MDN HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) • [MDN CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) • [HTML Spec](https://html.spec.whatwg.org/) • [CSS Tricks](https://css-tricks.com/)

**Pros:** 🌐 Universal support, 📱 Responsive design, 🎨 Visual power  
**Cons:** 🐛 Browser inconsistencies, 📉 Not Turing complete alone, 📝 Verbose

---

### ☕ CoffeeScript

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm, compiles to JavaScript |
| **Created** | 2009 by Jeremy Ashkenas |
| **Current Version** | 2.7.0 (2026) |
| **Extension** | `.coffee` |

**Overview:** JavaScript's prettier cousin. CoffeeScript introduced significant whitespace, arrow functions, and classes that later influenced ES6.

**Domains:** Legacy web apps, rapid prototyping, Node.js scripts  
**Why It Matters:** Many ES6 features (arrow functions, destructuring) originated in CoffeeScript.  
**Notable Users:** GitHub (historically), Dropbox (historically), Basecamp

**Setup:**
```bash
npm install -g coffeescript
```

**Hello World:**
```coffeescript
console.log "Hello, World!"
```

**Run:**
```bash
coffee hello.coffee
# Hello, World!
```

**Resources:** [CoffeeScript.org](https://coffeescript.org/) • [CoffeeScript Docs](https://coffeescript.org/#documentation)

**Pros:** ☕ Clean syntax, 📝 Less boilerplate, 🔄 JS interop  
**Cons:** 🕰️ Largely superseded by ES6, 📉 Declining usage, 🔧 Build step

---

### 🔶 Rescript

| | |
|:---|:---|
| **Paradigm** | Functional, OOP, compiles to JavaScript |
| **Created** | 2020 (evolution of BuckleScript/ReasonML) |
| **Current Version** | 11.1 (2026) |
| **Extension** | `.res`, `.resi` |

**Overview:** OCaml's pragmatism for JavaScript developers. Rescript offers sound typing, fast compilation, and zero-cost JS output without runtime overhead.

**Domains:** Type-safe frontend, React apps, Node.js tools, design systems  
**Why It Matters:** The fastest compiler from typed source to JavaScript.  
**Notable Users:** Various startups, design system teams, React communities

**Setup:**
```bash
npm install -g rescript
```

**Hello World:**
```rescript
Js.log("Hello, World!")
```

**Run:**
```bash
rescript build
node src/hello.bs.js
# Hello, World!
```

**Resources:** [Rescript Lang](https://rescript-lang.org/) • [Rescript Docs](https://rescript-lang.org/docs/manual/latest/introduction) • [Rescript React](https://rescript-lang.org/docs/react/latest/introduction)

**Pros:** ⚡ Fastest compiler, 🛡️ Sound types, 📦 Zero-cost JS  
**Cons:** 📉 Niche adoption, 📝 Different syntax, 👥 Small community

---

### 📄 PostScript

| | |
|:---|:---|
| **Paradigm** | Stack-based, Concatenative, Page description |
| **Created** | 1982 by Adobe Systems (John Warnock, Chuck Geschke) |
| **Current Version** | PostScript 3 (1997), Level 3 |
| **Extension** | `.ps`, `.eps` |

**Overview:** The original vector graphics language. PostScript is a full Turing-complete stack language that describes page layouts for printers and displays.

**Domains:** Printer control, vector graphics, PDF precursor, embedded rendering  
**Why It Matters:** PDF is essentially "frozen" PostScript; it revolutionized desktop publishing.  
**Notable Users:** Adobe, printer manufacturers, prepress industry

**Setup:** Use Ghostscript interpreter or Adobe tools.

**Hello World:**
```postscript
%!PS
/Courier findfont 24 scalefont setfont
100 700 moveto
(Hello, World!) show
showpage
```

**Run:**
```bash
gs hello.ps
# Renders "Hello, World!" in a viewer
```

**Resources:** [PostScript Language Reference](https://www.adobe.com/products/postscript/pdfs/PLRM.pdf) • [Ghostscript](https://www.ghostscript.com/) • [ThinkJS (PostScript interpreter)](https://github.com/bbirchnz/thinkjs)

**Pros:** 📄 Precise graphics, 🔧 Device independent, 📜 Historic importance  
**Cons:** 🕰️ Superseded by PDF, 🧠 Stack-based complexity, 📉 Niche usage

---

### ⚙️ WebAssembly / WAT

| | |
|:---|:---|
| **Paradigm** | Stack-based, Binary instruction format |
| **Created** | 2015 by W3C WebAssembly Group |
| **Current Version** | WebAssembly 2.0 (2026) |
| **Extension** | `.wasm` (binary), `.wat` (text) |

**Overview:** The assembly language of the web. WebAssembly enables near-native performance in browsers and is expanding to servers (WASI) and embedded systems.

**Domains:** Browser games, video editing, CAD, scientific visualization, serverless (WASI)  
**Why It Matters:** The first new universal binary format since Java bytecode; supported by all browsers.  
**Notable Users:** Unity, AutoCAD, Figma, Adobe Photoshop Web, Docker + Wasm

**Setup:**
```bash
# Install wasmtime (runtime) or use browser
brew install wasmtime

# Or wabt (toolkit)
brew install wabt
```

**Hello World (WAT):**
```wat
(module
  (import "console" "log" (func $log (param i32)))
  (memory (export "mem") 1)
  (data (i32.const 0) "Hello, World!")
  (func (export "hello")
    i32.const 0
    i32.const 13
    call $log
  )
)
```

**Run:** Via browser JS API or wasmtime runtime.

**Resources:** [WebAssembly.org](https://webassembly.org/) • [MDN WebAssembly](https://developer.mozilla.org/en-US/docs/WebAssembly) • [WASI](https://wasi.dev/) • [Wasmtime](https://wasmtime.dev/)

**Pros:** ⚡ Near-native speed, 🌐 Universal runtime, 🔒 Sandboxed  
**Cons:** 🧠 Low-level, 📦 Limited direct use, 📝 Complex tooling

---

## 📊 Data, Math & Query

> Languages designed for statistics, numerical computation, data manipulation, and database queries.

---

### 📈 R

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Functional, OOP, Array-based, Statistical |
| **Created** | 1993 by Ross Ihaka and Robert Gentleman (Auckland) |
| **Current Version** | 4.4.2 (2026) |
| **Extension** | `.r`, `.R` |

**Overview:** The lingua franca of statistics. R's vectorized operations and ggplot2 visualization make it indispensable for academic research and data analysis.

**Domains:** Statistical analysis, bioinformatics, econometrics, data visualization, academic research  
**Why It Matters:** CRAN has 20,000+ packages; R is the standard for reproducible research.  
**Notable Users:** Harvard, Stanford, FDA, Pfizer, Bank of America, New York Times

**Setup:**
```bash
# macOS
brew install r

# Linux
sudo apt install r-base

# Windows
winget install RProject.R
```

**Hello World:**
```r
print("Hello, World!")
```

**Run:**
```bash
Rscript hello.R
# [1] "Hello, World!"
```

**Resources:** [R Project](https://www.r-project.org/) • [CRAN](https://cran.r-project.org/) • [R for Data Science](https://r4ds.had.co.nz/) • [ggplot2](https://ggplot2.tidyverse.org/)

**Pros:** 📊 Statistical dominance, 📈 Excellent visualization, 📦 CRAN ecosystem  
**Cons:** 🐢 Slow for general programming, 🧠 Steep for programmers, 📉 Memory hungry

---

### 🧮 MATLAB

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Imperative, Functional, Array-based |
| **Created** | 1984 by Cleve Moler (MathWorks) |
| **Current Version** | R2025a (2026) |
| **Extension** | `.m` |

**Overview:** The engineer's calculator. MATLAB dominates numerical computation, control systems, and signal processing with its matrix-native syntax and Simulink integration.

**Domains:** Engineering, control systems, signal processing, image processing, numerical analysis  
**Why It Matters:** Every engineering curriculum uses MATLAB; Simulink is the standard for model-based design.  
**Notable Users:** NASA, Boeing, automotive OEMs, universities worldwide

**Setup:**
```bash
# Requires MathWorks license
# Download from https://www.mathworks.com/
# Student/academic licenses available
```

**Hello World:**
```matlab
disp('Hello, World!')
```

**Run:** Via MATLAB IDE or command window.

**Resources:** [MathWorks](https://www.mathworks.com/) • [MATLAB Docs](https://www.mathworks.com/help/matlab/) • [MATLAB Academy](https://matlabacademy.mathworks.com/)

**Pros:** 🧮 Matrix-native, 🔧 Simulink integration, 🎓 Academic standard  
**Cons:** 💰 Expensive licenses, 📝 Proprietary lock-in, 🐢 Slow for general tasks

---

### 🟥 Wolfram Language

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Symbolic, Functional, Rule-based |
| **Created** | 1988 by Stephen Wolfram (Mathematica) |
| **Current Version** | 14.2 (2026) |
| **Extension** | `.wl`, `.m` |

**Overview:** The most comprehensive knowledge-based language. Wolfram Language integrates computation, data, visualization, and natural language understanding into a single coherent system.

**Domains:** Scientific computing, symbolic math, data science, knowledge representation, education  
**Why It Matters:** Wolfram|Alpha and Mathematica power serious scientific research.  
**Notable Users:** Wolfram Research, Apple Siri (historical), Samsung, various research labs

**Setup:**
```bash
# Requires Mathematica or Wolfram Engine (free for developers)
# https://www.wolfram.com/engine/
```

**Hello World:**
```wolfram
Print["Hello, World!"]
```

**Run:** Via Mathematica notebook or WolframScript.

**Resources:** [Wolfram Language](https://www.wolfram.com/language/) • [Wolfram Docs](https://reference.wolfram.com/language/) • [Wolfram U](https://www.wolfram.com/wolfram-u/)

**Pros:** 🧠 Symbolic computation, 📚 Built-in knowledge, 🎨 Powerful visualization  
**Cons:** 💰 Proprietary, 📝 Unusual syntax, 🐢 Heavy runtime

---

### 📊 SAS

| | |
|:---|:---|
| **Paradigm** | Procedural, Data-driven |
| **Created** | 1976 by Anthony Barr, James Goodnight (SAS Institute) |
| **Current Version** | SAS 9.4M8 / Viya 4 (2026) |
| **Extension** | `.sas` |

**Overview:** The enterprise standard for analytics. SAS has dominated regulated industries (pharma, banking) for decades with its certified, validated statistical procedures.

**Domains:** Clinical trials, banking risk, government reporting, enterprise analytics  
**Why It Matters:** FDA submissions often require SAS; it's the safest choice for regulated stats.  
**Notable Users:** FDA, pharmaceutical companies, major banks, US Census Bureau

**Setup:** Requires SAS license (SAS OnDemand for Academics is free).

**Hello World:**
```sas
data _null_;
    put 'Hello, World!';
run;
```

**Run:** Via SAS Studio or SAS Enterprise Guide.

**Resources:** [SAS.com](https://www.sas.com/) • [SAS Docs](https://documentation.sas.com/) • [SAS OnDemand](https://odamid.oda.sas.com/)

**Pros:** 🏢 Enterprise standard, 🛡️ Regulated industry trust, 📊 Certified procedures  
**Cons:** 💰 Very expensive, 📝 Proprietary, 🐢 Legacy syntax

---

### 🗄️ SQL

| | |
|:---|:---|
| **Paradigm** | Declarative, Query language |
| **Created** | 1974 by Donald Chamberlin and Raymond Boyce (IBM) |
| **Current Version** | SQL:2023 (ISO/IEC 9075:2023), PostgreSQL 17, MySQL 9.0 |
| **Extension** | `.sql` |

**Overview:** The universal language of data. SQL allows declarative manipulation of relational databases and has remained dominant for 50 years despite NoSQL challengers.

**Domains:** Database queries, data analysis, backend development, business intelligence, ETL  
**Why It Matters:** Every application uses SQL; it's the most valuable language for data careers.  
**Notable Users:** Every company with a database (which is all of them)

**Setup:**
```bash
# PostgreSQL
brew install postgresql        # macOS
sudo apt install postgresql    # Linux

# MySQL
brew install mysql
# Or use SQLite for file-based
brew install sqlite
```

**Hello World:**
```sql
SELECT 'Hello, World!' AS greeting;
```

**Run:**
```bash
psql -c "SELECT 'Hello, World!' AS greeting;"
#  greeting
# -------------
# Hello, World!
```

**Resources:** [PostgreSQL Docs](https://www.postgresql.org/docs/) • [MySQL Docs](https://dev.mysql.com/doc/) • [SQLZoo](https://sqlzoo.net/) • [Mode SQL Tutorial](https://mode.com/sql-tutorial/)

**Pros:** 🗄️ Universal standard, 📊 Data analysis power, 🏢 Enterprise ubiquity  
**Cons:** 📝 Dialect fragmentation, 🧠 Set-based thinking, 🐢 Complex queries

---

### 🔣 APL

| | |
|:---|:---|
| **Paradigm** | Array-based, Symbolic, Tacit |
| **Created** | 1966 by Kenneth Iverson (IBM) |
| **Current Version** | Dyalog APL 19.0, GNU APL 1.9 (2026) |
| **Extension** | `.apl`, `.dyalog` |

**Overview:** The most concise language ever created. APL uses special symbols to perform powerful array operations in a single line of code.

**Domains:** Financial modeling, actuarial science, scientific computing, array manipulation  
**Why It Matters:** Iverson notation influenced J, K, and modern array languages (NumPy, Julia).  
**Notable Users:** Morgan Stanley, various hedge funds, actuarial departments

**Setup:**
```bash
# Dyalog (free for personal use)
# Download from https://www.dyalog.com/
# Or GNU APL:
brew install gnu-apl
```

**Hello World:**
```apl
'Hello, World!'
```

**Run:** Via APL interpreter or REPL.

**Resources:** [Dyalog APL](https://www.dyalog.com/) • [APL Wiki](https://aplwiki.com/) • [TryAPL](https://tryapl.org/) • [Mastering Dyalog APL](https://masteringdyalogapl.com/)

**Pros:** 🔣 Extreme conciseness, 🧮 Array power, 🧠 Elegant mathematics  
**Cons:** 📉 Cryptic symbols, 👥 Tiny community, 📝 Requires special keyboard

---

### 🔤 J

| | |
|:---|:---|
| **Paradigm** | Array-based, Functional, Tacit |
| **Created** | 1990 by Kenneth Iverson and Roger Hui |
| **Current Version** | J9.6 (2026) |
| **Extension** | `.ijs` |

**Overview:** APL's ASCII successor. J retains array programming power while using only standard keyboard characters, making it more accessible than APL.

**Domains:** Data analysis, mathematical exploration, array algorithms, tacit programming  
**Why It Matters:** Proves array thinking doesn't require special symbols.  
**Notable Users:** Academic researchers, array programming enthusiasts

**Setup:**
```bash
# macOS / Linux
brew install j

# Or download from https://www.jsoftware.com/
```

**Hello World:**
```j
'Hello, World!'
```

**Run:**
```bash
jconsole -js "echo 'Hello, World!' exit ''"
# Hello, World!
```

**Resources:** [J Software](https://www.jsoftware.com/) • [J Primer](https://www.jsoftware.com/help/primer/contents.htm) • [J Wiki](https://code.jsoftware.com/wiki/Main_Page) • [Learn J](https://www.jsoftware.com/help/learning/contents.htm)

**Pros:** 🔤 ASCII APL, 🧮 Array power, 🧠 Tacit programming  
**Cons:** 👥 Tiny community, 📉 Niche use, 🧠 Steep paradigm

---

### 🔑 K / Q

| | |
|:---|:---|
| **Paradigm** | Array-based, Functional, Query |
| **Created** | 1993 by Arthur Whitney (K); Q is K4 with SQL-like syntax |
| **Current Version** | K4 (kdb+ 4.1), Q 3.0 (2026) |
| **Extension** | `.k`, `.q` |

**Overview:** The language of high-frequency finance. K and Q power the world's fastest time-series databases and trading systems with extreme conciseness.

**Domains:** High-frequency trading, time-series databases, market data, analytics  
**Why It Matters:** kdb+ processes millions of ticks per second; Q developers earn $500K+.  
**Notable Users:** Goldman Sachs, JPMorgan, Citadel, Deutsche Bank, NASA

**Setup:**
```bash
 # Requires kdb+ license (free 32-bit version available)
 # https://kx.com/kdb-personal-edition-download/
```

**Hello World (Q):**
```q
"Hello, World!"
```

**Run:** Via q console.

**Resources:** [KX Systems](https://kx.com/) • [Q for Mortals](https://code.kx.com/q4m3/) • [Kdb+ Docs](https://code.kx.com/home/) • [Q Insight Pad](https://www.qinsightpad.com/)

**Pros:** ⚡ Extreme performance, 🔑 Time-series native, 💰 High salaries  
**Cons:** 💰 Expensive licenses, 🔒 Proprietary, 🧠 Extremely steep curve

---

### 🔬 Julia

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Technical, Functional, OOP, Multiple dispatch |
| **Created** | 2012 by Jeff Bezanson, Stefan Karpinski, Viral Shah, Alan Edelman (MIT) |
| **Current Version** | 1.11 (2026) |
| **Extension** | `.jl` |

**Overview:** The speed of C with the ease of Python. Julia's multiple dispatch and JIT compilation make it the rising star of scientific computing.

**Domains:** Scientific computing, machine learning, differential equations, optimization, physics  
**Why It Matters:** Solves the "two-language problem" — no need to rewrite in C for speed.  
**Notable Users:** NASA, CERN, MIT, BlackRock, various national labs

**Setup:**
```bash
# macOS
brew install julia

# Linux
wget https://julialang-s3.julialang.org/bin/linux/x64/1.11/julia-1.11.0-linux-x86_64.tar.gz
# Or use juliaup
curl -fsSL https://install.julialang.org | sh

# Windows
winget install JuliaComputing.Julia
```

**Hello World:**
```julia
println("Hello, World!")
```

**Run:**
```bash
julia hello.jl
# Hello, World!
```

**Resources:** [Julia Lang](https://julialang.org/) • [Julia Docs](https://docs.julialang.org/) • [JuliaHub](https://juliahub.com/) • [JuliaAcademy](https://juliaacademy.com/)

**Pros:** ⚡ C-like speed, 🧮 Mathematical syntax, 🔬 Scientific ecosystem  
**Cons:** 🐢 JIT warm-up, 📦 Smaller ecosystem than Python, 🧠 Multiple dispatch complexity

---

## 🐚 Shell & Automation

> Languages that orchestrate operating systems, automate tasks, and glue programs together.

---

### 🐚 Bash

| | |
|:---|:---|
| **Paradigm** | Command, Scripting, Imperative |
| **Created** | 1989 by Brian Fox (GNU Project) |
| **Current Version** | 5.2 (2026) |
| **Extension** | `.sh`, `.bash` |

**Overview:** The default shell of Linux and macOS. Bash scripts automate system administration, build pipelines, and daily developer workflows.

**Domains:** System administration, CI/CD, build scripts, automation, DevOps  
**Why It Matters:** Every Linux server runs Bash; it's the universal glue of Unix systems.  
**Notable Users:** Every Linux user, Google, Amazon AWS, GitHub Actions

**Setup:** Pre-installed on Linux/macOS. Windows via WSL or Git Bash.

**Hello World:**
```bash
#!/bin/bash
# Shebang line specifies interpreter
echo "Hello, World!"
```

**Run:**
```bash
chmod +x hello.sh
./hello.sh
# Hello, World!

# Or direct
bash hello.sh
```

**Resources:** [GNU Bash](https://www.gnu.org/software/bash/) • [Bash Reference Manual](https://www.gnu.org/software/bash/manual/bash.html) • [ShellCheck](https://www.shellcheck.net/) • [Bash Academy](http://www.bash.academy/)

**Pros:** 🐚 Universal availability, 🔧 System integration, ⚡ Quick automation  
**Cons:** 🐛 Error-prone syntax, 🧠 Quoting hell, 📉 Not for complex apps

---

### 🐚 Zsh

| | |
|:---|:---|
| **Paradigm** | Command, Scripting, Interactive |
| **Created** | 1990 by Paul Falstad (Princeton) |
| **Current Version** | 5.9 (2026) |
| **Extension** | `.zsh` |

**Overview:** Bash's powerful successor. Zsh offers superior tab completion, globbing, and theming (Oh My Zsh), and is the default shell on macOS since Catalina.

**Domains:** Interactive shell, scripting, customization, developer productivity  
**Why It Matters:** Oh My Zsh and Powerlevel10k transformed terminal aesthetics and productivity.  
**Notable Users:** Apple (macOS default), most power users, developers worldwide

**Setup:** Pre-installed on macOS. Linux via package manager.

**Hello World:**
```zsh
#!/bin/zsh
echo "Hello, World!"
```

**Run:**
```bash
zsh hello.zsh
# Hello, World!
```

**Resources:** [Zsh.org](https://www.zsh.org/) • [Oh My Zsh](https://ohmyz.sh/) • [Zsh Docs](https://zsh.sourceforge.io/Doc/) • [Zsh Wiki](https://zshwiki.org/)

**Pros:** 🎨 Customization, 🔧 Better completion, 🐚 Bash compatibility  
**Cons:** 📉 Slightly slower, 🧠 More complex, 📦 Plugin dependency

---

### 🖥️ PowerShell

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Command, Scripting, OOP, Functional |
| **Created** | 2006 by Jeffrey Snover (Microsoft) |
| **Current Version** | 7.5 (PowerShell Core, 2026) |
| **Extension** | `.ps1` |

**Overview:** The sysadmin language of the modern era. PowerShell pipes objects (not text) and provides seamless access to .NET, COM, and WMI.

**Domains:** Windows administration, cross-platform automation, Azure, DevOps, configuration management  
**Why It Matters:** The only shell that passes structured objects through pipelines.  
**Notable Users:** Microsoft, Azure teams, enterprise Windows shops, NASA

**Setup:**
```bash
# macOS / Linux
brew install powershell

# Linux (Debian)
sudo apt install powershell

# Windows
winget install Microsoft.PowerShell
```

**Hello World:**
```powershell
Write-Output "Hello, World!"
```

**Run:**
```bash
pwsh hello.ps1
# Hello, World!
```

**Resources:** [Microsoft PowerShell](https://learn.microsoft.com/en-us/powershell/) • [PowerShell Gallery](https://www.powershellgallery.com/) • [PowerShell.org](https://powershell.org/) • [PSKoans](https://github.com/vexx32/PSKoans)

**Pros:** 🖥️ Object pipelines, 🤝 .NET integration, 🌐 Cross-platform (Core)  
**Cons:** 📝 Verbosity, 🧠 Windows-centric history, 🐢 Startup time

---

### 🐟 Fish

| | |
|:---|:---|
| **Paradigm** | Interactive, Command, Scripting |
| **Created** | 2005 by Axel Liljencrantz |
| **Current Version** | 4.0 (2026) |
| **Extension** | `.fish` |

**Overview:** The friendly interactive shell. Fish features syntax highlighting, autosuggestions, and web-based configuration out of the box.

**Domains:** Interactive shell, scripting, developer productivity, beginners  
**Why It Matters:** The most user-friendly shell for developers new to the terminal.  
**Notable Users:** Individual developers, educational environments

**Setup:**
```bash
# macOS
brew install fish

# Linux
sudo apt install fish

# Windows (via WSL or Cygwin)
```

**Hello World:**
```fish
echo "Hello, World!"
```

**Run:**
```bash
fish hello.fish
# Hello, World!
```

**Resources:** [Fish Shell](https://fishshell.com/) • [Fish Docs](https://fishshell.com/docs/current/index.html) • [Fish Cookbook](https://github.com/jorgebucaran/fish-cookbook)

**Pros:** 🐟 User-friendly, 🎨 Syntax highlighting, 🔮 Autosuggestions  
**Cons:** 📝 Not POSIX compliant, 📦 Smaller ecosystem, 🐚 Bash incompatibility

---

### ✂️ AWK

| | |
|:---|:---|
| **Paradigm** | Data-driven, Stream processing |
| **Created** | 1977 by Alfred Aho, Peter Weinberger, Brian Kernighan (Bell Labs) |
| **Current Version** | gawk 5.3, mawk 1.3.4 (2026) |
| **Extension** | `.awk` |

**Overview:** The original text processing tool. AWK excels at columnar data manipulation, log analysis, and one-liner data transformations.

**Domains:** Log processing, data extraction, reporting, CSV manipulation, bioinformatics  
**Why It Matters:** Every sysadmin knows AWK; it's the fastest way to process columnar text.  
**Notable Users:** Unix sysadmins, bioinformatics pipelines, log analysis teams

**Setup:** Pre-installed on virtually all Unix systems.

**Hello World:**
```awk
BEGIN {
    print "Hello, World!"
}
```

**Run:**
```bash
awk -f hello.awk
# Hello, World!

# Or inline
awk 'BEGIN { print "Hello, World!" }'
```

**Resources:** [GNU AWK](https://www.gnu.org/software/gawk/) • [AWK Book (Kernighan)](https://ia902309.us.archive.org/26/items/pdfy-MgN0H1joIoD-Tlii/The%20AWK%20Programming%20Language.pdf) • [Gawk Docs](https://www.gnu.org/software/gawk/manual/)

**Pros:** ⚡ Lightning fast for text, 🔧 Universal availability, 📝 One-liner power  
**Cons:** 🧠 Cryptic syntax, 📉 Limited to text, 🕰️ Aging

---

## 🚀 Emerging & Specialized

> New languages pushing boundaries in AI, blockchain, game development, and systems design.

---

### 🪨 Carbon

| | |
|:---|:---|
| **Paradigm** | Systems, Procedural, C++ successor |
| **Created** | 2022 by Google (Richard Smith et al.) |
| **Current Version** | 0.0 (experimental, 2026) |
| **Extension** | `.carbon` |

**Overview:** Google's experimental successor to C++. Carbon aims to provide seamless C++ interoperability while fixing its accumulated complexity and safety issues.

**Domains:** Systems programming, C++ migration path, performance-critical code  
**Why It Matters:** If successful, it could be the path off C++ for Google's massive codebases.  
**Notable Users:** Google (experimental), open source contributors

**Setup:**
```bash
# Experimental only
# https://github.com/carbon-language/carbon-lang
# Requires Bazel build system
```

**Hello World:**
```carbon
package Hello api;

fn Main() -> i32 {
    Print("Hello, World!");
    return 0;
}
```

**Run:** Via Carbon toolchain (in development).

**Resources:** [Carbon Lang](https://github.com/carbon-language/carbon-lang) • [Carbon Docs](https://docs.carbon-lang.dev/) • [Carbon Explorer](https://github.com/carbon-language/carbon-lang/tree/trunk/explorer)

**Pros:** 🔧 C++ interop, 🛡️ Memory safety goals, 🚀 Modern syntax  
**Cons:** 🚧 Extremely experimental, 📉 No production use, 📝 Early stage

---

### 🔥 Mojo

| | |
|:---|:---|
| **Paradigm** | Systems, AI/ML, Python superset |
| **Created** | 2023 by Modular (Chris Lattner et al.) |
| **Current Version** | 24.6 / 25.1 (2026) |
| **Extension** | `.mojo`, `.🔥` |

**Overview:** Python's speed layer. Mojo is a superset of Python with systems programming features, enabling AI developers to write performance-critical code without leaving Python's ecosystem.

**Domains:** AI/ML infrastructure, high-performance Python, accelerators (GPU/TPU/ASIC)  
**Why It Matters:** The first language to combine Python's usability with C++ performance and MLIR compiler power.  
**Notable Users:** Modular AI, early AI infrastructure startups

**Setup:**
```bash
# Install Modular CLI
curl https://get.modular.com | sh
modular install mojo
```

**Hello World:**
```mojo
fn main():
    print("Hello, World!")
```

**Run:**
```bash
mojo hello.mojo
# Hello, World!
```

**Resources:** [Modular Mojo](https://www.modular.com/mojo) • [Mojo Docs](https://docs.modular.com/mojo/) • [Mojo Playground](https://playground.modular.com/)

**Pros:** 🐍 Python compatible, ⚡ C++ speed, 🔥 AI-native  
**Cons:** 🚧 Early stage, 📦 Limited ecosystem, 💰 Vendor controlled

---

### ✨ Gleam

| | |
|:---|:---|
| **Paradigm** | Functional, Statically typed, Concurrent |
| **Created** | 2019 by Louis Pilfold |
| **Current Version** | 1.7 (2026) |
| **Extension** | `.gleam` |

**Overview:** A friendly language for building type-safe systems that scale. Gleam compiles to Erlang (BEAM) and JavaScript with no runtime exceptions.

**Domains:** Web backends, distributed systems, type-safe Erlang/Elixir alternative  
**Why It Matters:** Brings Rust-level type safety to the BEAM ecosystem.  
**Notable Users:** Early adopters, Elixir community, various startups

**Setup:**
```bash
# macOS / Linux
brew install gleam

# Or via shell script
curl -s https://gleam.run/install.sh | sh
```

**Hello World:**
```gleam
import gleam/io

pub fn main() {
  io.println("Hello, World!")
}
```

**Run:**
```bash
gleam run
# Hello, World!
```

**Resources:** [Gleam.run](https://gleam.run/) • [Gleam Docs](https://gleam.run/documentation/) • [Gleam Packages](https://packages.gleam.run/) • [Gleam Discord](https://discord.gg/Fm8Pwmy)

**Pros:** 🛡️ No runtime exceptions, 🤝 BEAM/JS targets, ✨ Friendly syntax  
**Cons:** 🚧 Young ecosystem, 👥 Small community, 📦 Limited libraries

---

### 🗿 Roc

| | |
|:---|:---|
| **Paradigm** | Functional, Pure, Statically typed |
| **Created** | 2019 by Richard Feldman |
| **Current Version** | Pre-alpha (2026) |
| **Extension** | `.roc` |

**Overview:** A fast, friendly, functional language for building applications. Roc aims to be as easy as Python but as reliable as Haskell.

**Domains:** Command-line tools, web servers, data transformation, applications  
**Why It Matters:** Richard Feldman (Elm core team) brings Elm's philosophy to general-purpose programming.  
**Notable Users:** Early adopters, functional programming community

**Setup:**
```bash
# Install script
curl -s https://raw.githubusercontent.com/roc-lang/roc/main/www/public/install.sh | bash
```

**Hello World:**
```roc
app "hello"
    packages { pf: "https://github.com/roc-lang/basic-cli/releases/download/0.7.0/bkGrvO_3.zip" }
    imports [pf.Stdout]
    provides [main] to pf

main =
    Stdout.line "Hello, World!"
```

**Run:**
```bash
roc run hello.roc
# Hello, World!
```

**Resources:** [Roc Lang](https://www.roc-lang.org/) • [Roc Tutorial](https://www.roc-lang.org/tutorial) • [Roc Zulip](https://roc.zulipchat.com/)

**Pros:** 🗿 Friendly functional, ⚡ Fast compiler, 🛡️ Type safety  
**Cons:** 🚧 Pre-alpha, 📦 Very small ecosystem, 👥 Experimental

---

### 🌾 Grain

| | |
|:---|:---|
| **Paradigm** | Functional, WebAssembly-first |
| **Created** | 2017 by Philip Blair, Oscar Spencer, et al. |
| **Current Version** | 0.6 (2026) |
| **Extension** | `.gr` |

**Overview:** A functional language that compiles to WebAssembly. Grain brings academic type theory to the web with zero runtime overhead.

**Domains:** WebAssembly apps, browser-based tools, educational functional programming  
**Why It Matters:** One of the first languages designed specifically for the WebAssembly era.  
**Notable Users:** WebAssembly enthusiasts, educational projects

**Setup:**
```bash
# Via npm
npm install -g @grain/cli

# Or binary releases
```

**Hello World:**
```grain
print("Hello, World!")
```

**Run:**
```bash
grain hello.gr
# Hello, World!
```

**Resources:** [Grain Lang](https://grain-lang.org/) • [Grain Docs](https://grain-lang.org/docs/) • [Grain Stdlib](https://grain-lang.org/docs/stdlib)

**Pros:** 🌾 WASM native, 🛡️ Type safety, 🧠 Academic rigor  
**Cons:** 🚧 Early stage, 📦 Tiny ecosystem, 👥 Niche

---

### 🐦 Wren

| | |
|:---|:---|
| **Paradigm** | Object-oriented, Scripting, Embedding |
| **Created** | 2013 by Bob Nystrom |
| **Current Version** | 0.4.0 (2026) |
| **Extension** | `.wren` |

**Overview:** A small, fast, class-based scripting language designed for embedding in games. Wren is like Lua but with classes and a cleaner design.

**Domains:** Game scripting, embedding, education, configuration  
**Why It Matters:** The scripting language for developers who want Lua's speed with Python-like classes.  
**Notable Users:** Indie game developers, hobby projects

**Setup:**
```bash
# Clone and build
git clone https://github.com/wren-lang/wren.git
cd wren && make
```

**Hello World:**
```wren
System.print("Hello, World!")
```

**Run:**
```bash
wren hello.wren
# Hello, World!
```

**Resources:** [Wren.io](https://wren.io/) • [Wren Docs](https://wren.io/) • [Wren GitHub](https://github.com/wren-lang/wren)

**Pros:** 🐦 Small & fast, 🎓 Class-based, 🔧 Embeddable  
**Cons:** 📦 Tiny ecosystem, 👥 Niche, 🚧 Pre-1.0

---

### 🔴 Red

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: Imperative, Functional, Symbolic, Reactive |
| **Created** | 2011 by Nenad Rakocevic (Full Stack Technologies) |
| **Current Version** | 0.6.4 (2026) |
| **Extension** | `.red`, `.reds` |

**Overview:** The world's first full-stack language. Red combines systems programming, high-level scripting, and cross-platform GUI in a single executable under 1MB.

**Domains:** System tools, GUIs, DSLs, cross-platform apps, embedded  
**Why It Matters:** Rebol's spiritual successor with native compilation and zero dependencies.  
**Notable Users:** Rebol community, select cross-platform tool developers

**Setup:**
```bash
# Download from https://www.red-lang.org/p/download.html
# Or build from source
```

**Hello World:**
```red
Red [
    Title: "Hello"
]
print "Hello, World!"
```

**Run:**
```bash
red hello.red
# Hello, World!
```

**Resources:** [Red Lang](https://www.red-lang.org/) • [Red Docs](https://github.com/red/docs/blob/master/en/SUMMARY.adoc) • [Red Gitter](https://gitter.im/red/red)

**Pros:** 🔴 Full-stack in one language, 📦 Tiny binaries, 🎨 Built-in GUI  
**Cons:** 🚧 Pre-1.0, 👥 Small community, 📦 Limited libraries

---

### ⛓️ Move

| | |
|:---|:---|
| **Paradigm** | Imperative, Resource-oriented, Verification |
| **Created** | 2019 by Diem Association (Meta/Libra), now maintained by Aptos/Sui |
| **Current Version** | Move 1.0 (Aptos), Sui Move (2026) |
| **Extension** | `.move` |

**Overview:** A language for safe digital assets. Move uses a resource-oriented model where assets can never be accidentally copied or lost — ideal for blockchain.

**Domains:** Blockchain smart contracts, digital assets, DeFi, NFTs  
**Why It Matters:** The first language where "resources" are a first-class concept, preventing double-spend bugs.  
**Notable Users:** Aptos, Sui, Starcoin, various DeFi protocols

**Setup:**
```bash
# Install Aptos CLI or Sui CLI
brew install aptos
# Or via cargo
cargo install aptos-cli
```

**Hello World:**
```move
module hello::hello_world {
    public fun hello(): vector<u8> {
        b"Hello, World!"
    }
}
```

**Run:** Via Move CLI or blockchain testnet.

**Resources:** [Aptos Move](https://aptos.dev/) • [Sui Move](https://docs.sui.io/) • [Move Book](https://move-book.com/) • [Move Lang](https://github.com/move-language/move)

**Pros:** ⛓️ Resource safety, 🛡️ Prevents asset bugs, 🔧 Formal verification  
**Cons:** 📉 Blockchain-specific, 👥 Niche, 🚧 Evolving standard

---

### 🔺 Cairo

| | |
|:---|:---|
| **Paradigm** | Imperative, STARK-provable |
| **Created** | 2020 by StarkWare |
| **Current Version** | Cairo 2.9 (2026) |
| **Extension** | `.cairo` |

**Overview:** A language for provable computation. Cairo programs generate STARK proofs, enabling blockchain scaling and verifiable computation.

**Domains:** ZK-rollups, verifiable computation, blockchain scaling, STARK proofs  
**Why It Matters:** Powers StarkNet and enables computation to be proven correct without re-execution.  
**Notable Users:** StarkWare, StarkNet, various ZK-proof projects

**Setup:**
```bash
# Install via asdf or Starknet CLI
asdf plugin add cairo
asdf install cairo latest
```

**Hello World:**
```cairo
fn main() {
    println!("Hello, World!");
}
```

**Run:**
```bash
cairo-run hello.cairo
# Hello, World!
```

**Resources:** [Cairo Book](https://book.cairo-lang.org/) • [StarkNet Docs](https://docs.starknet.io/) • [Cairo Lang](https://github.com/starkware-libs/cairo)

**Pros:** 🔺 Provable computation, ⚡ ZK-rollup native, 🛡️ Cryptographic safety  
**Cons:** 📉 Extremely niche, 🧠 Complex paradigm, 👥 Tiny community

---

### 🔗 Solidity

| | |
|:---|:---|
| **Paradigm** | OOP, Contract-oriented, Statically typed |
| **Created** | 2014 by Gavin Wood, Christian Reitwiessner, et al. (Ethereum) |
| **Current Version** | 0.8.28 (2026) |
| **Extension** | `.sol` |

**Overview:** The dominant language for Ethereum smart contracts. Solidity compiles to EVM bytecode and controls billions of dollars in DeFi protocols.

**Domains:** Smart contracts, DeFi, NFTs, DAOs, Ethereum ecosystem  
**Why It Matters:** Solidity developers shape the decentralized financial infrastructure of the future.  
**Notable Users:** Ethereum Foundation, Uniswap, Aave, OpenSea, Chainlink

**Setup:**
```bash
# Via npm
npm install -g solc

# Or via framework
npm install hardhat
# Or Foundry: curl -L https://foundry.paradigm.xyz | bash
```

**Hello World:**
```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.28;

contract HelloWorld {
    function hello() public pure returns (string memory) {
        return "Hello, World!";
    }
}
```

**Run:** Deploy to testnet or local Hardhat/Foundry network.

**Resources:** [Solidity Lang](https://soliditylang.org/) • [Solidity Docs](https://docs.soliditylang.org/) • [CryptoZombies](https://cryptozombies.io/) • [OpenZeppelin](https://www.openzeppelin.com/)

**Pros:** 🔗 Ethereum standard, 💰 High salaries, 🏗️ Rich tooling  
**Cons:** 🐛 Security critical, 📝 Immutable bugs = lost funds, 🧠 Complex gas optimization

---

### 🎮 GDScript

| | |
|:---|:---|
| **Paradigm** | OOP, Imperative, Scripting |
| **Created** | 2014 by Juan Linietsky (Godot Engine) |
| **Current Version** | 4.3 (Godot 4.3, 2026) |
| **Extension** | `.gd` |

**Overview:** The Python-like scripting language of Godot Engine. GDScript is designed specifically for game development with built-in node signals and scene integration.

**Domains:** Game development (Godot), interactive applications, 2D/3D games  
**Why It Matters:** Godot is the fastest-growing open-source game engine; GDScript is its native tongue.  
**Notable Users:** Indie game developers, studios adopting Godot, educational institutions

**Setup:** Download Godot Engine from [godotengine.org](https://godotengine.org/).

**Hello World:**
```gdscript
extends Node

func _ready():
    print("Hello, World!")
```

**Run:** Attach to a Node in Godot and run the scene.

**Resources:** [Godot Engine](https://godotengine.org/) • [GDScript Docs](https://docs.godotengine.org/en/stable/tutorials/scripting/gdscript/gdscript_basics.html) • [GDQuest](https://www.gdquest.com/)

**Pros:** 🎮 Godot integration, 🐍 Python-like, 🎨 Built-in signals  
**Cons:** 📦 Godot-only, 👥 Smaller ecosystem than C#, 📝 Not general purpose

---

### 🎲 Haxe

| | |
|:---|:---|
| **Paradigm** | Multi-paradigm: OOP, Functional, Metaprogramming |
| **Created** | 2005 by Nicolas Cannasse (Motion-Twin) |
| **Current Version** | 4.3.6 (2026) |
| **Extension** | `.hx` |

**Overview:** The universal translator. Haxe compiles to JavaScript, C++, Java, Python, Lua, PHP, and more from a single codebase.

**Domains:** Cross-platform games, web apps, mobile, desktop, tools  
**Why It Matters:** Write once, compile to everything — ideal for game engines and frameworks.  
**Notable Users:** Dead Cells (Motion Twin), Papers Please, Shiro Games, various indie studios

**Setup:**
```bash
# macOS
brew install haxe

# Linux
sudo apt install haxe

# Windows
winget install HaxeFoundation.Haxe
```

**Hello World:**
```haxe
class Main {
    static function main() {
        trace("Hello, World!");
    }
}
```

**Run:**
```bash
haxe -main Main --interp
# Hello, World!
```

**Resources:** [Haxe.org](https://haxe.org/) • [Haxe Docs](https://haxe.org/documentation/) • [HaxeLib](https://lib.haxe.org/) • [Heaps Engine](https://heaps.io/)

**Pros:** 🎲 Multi-target, ⚡ Fast compilation, 🎮 Game dev popular  
**Cons:** 📉 Niche community, 📦 Smaller ecosystem, 📝 Complex tooling

---

### 🏛️ Vala

| | |
|:---|:---|
| **Paradigm** | OOP, Imperative, GObject-based |
| **Created** | 2006 by Jürg Billeter, Raffaele Sandrini (GNOME) |
| **Current Version** | 0.56 (2026) |
| **Extension** | `.vala` |

**Overview:** C# syntax with C performance. Vala compiles to C and GObject, making it ideal for GNOME applications and Linux desktop development.

**Domains:** Linux desktop apps, GNOME ecosystem, system tools, GTK apps  
**Why It Matters:** Powers GNOME apps like Files, Terminal, and Shotwell without GObject boilerplate.  
**Notable Users:** GNOME Project, elementary OS, various Linux desktop apps

**Setup:**
```bash
# macOS
brew install vala

# Linux
sudo apt install vala

# Windows (MSYS2)
pacman -S mingw-w64-x86_64-vala
```

**Hello World:**
```vala
void main () {
    print ("Hello, World!\n");
}
```

**Run:**
```bash
valac hello.vala -o hello
./hello
# Hello, World!
```

**Resources:** [Vala Docs](https://valadoc.org/) • [Vala Tutorial](https://wiki.gnome.org/Projects/Vala/Tutorial) • [Vala GitLab](https://gitlab.gnome.org/GNOME/vala)

**Pros:** 🏛️ GNOME integration, ⚡ C performance, 📝 C#-like syntax  
**Cons:** 🐧 Linux-centric, 📦 Limited cross-platform, 👥 Niche

---

## 🎭 Esoteric & Educational

> Languages designed to challenge, entertain, or educate rather than solve practical problems.

---

### 🧠 Brainfuck

| | |
|:---|:---|
| **Paradigm** | Esoteric, Imperative, Turing tarpit |
| **Created** | 1993 by Urban Müller |
| **Current Version** | 1.0 (stable, unchanged) |
| **Extension** | `.bf`, `.b` |

**Overview:** The ultimate minimalist language. With only 8 commands, Brainfuck operates on a tape of memory cells and challenges every assumption about programming syntax.

**Domains:** Education, puzzles, code golf, compiler construction exercises  
**Why It Matters:** Proves Turing completeness with just `><+-.,[]`.  
**Notable Users:** Computer science students, esoteric programming enthusiasts

**Setup:** Any interpreter will do.

**Hello World:**
```brainfuck
++++++++[>++++[>++>+++>+++>+<<<<-]>+>+>->>+[<]<-]>>.>---.+++++++..+++.>>.<-.<<.+++.------.--------.>>+.>++.
```

**Run:**
```bash
# Using any Brainfuck interpreter
bf hello.bf
# Hello, World!
```

**Resources:** [Brainfuck Wiki](https://esolangs.org/wiki/Brainfuck) • [Brainfuck Interpreter](https://copy.sh/brainfuck/) • [Brainfuck Visualizer](https://fatiherikli.github.io/brainfuck-visualizer/)

**Pros:** 🧠 Minimalist beauty, 🎓 Educational value, 🏆 Code golf champion  
**Cons:** 📝 Unreadable, 🐢 Slow, 📉 Useless for production

---

### 👿 Malbolge

| | |
|:---|:---|
| **Paradigm** | Esoteric, Self-modifying, Encryption-inspired |
| **Created** | 1998 by Ben Olmstead |
| **Current Version** | 1.0 (stable, cursed) |
| **Extension** | `.mb` |

**Overview:** The hardest programming language. Malbolge is self-modifying, encryption-inspired, and was designed to be nearly impossible to use.

**Domains:** Esoteric challenges, programming masochism, computer science folklore  
**Why It Matters:** The "hello world" program took two years to write; it represents the outer limit of language design.  
**Notable Users:** Masochists, puzzle solvers, computer science historians

**Setup:** Use online interpreters.

**Hello World:** The first valid program was not written until 2002. Most users rely on generators.

**Run:** Via online interpreter or specialized tools.

**Resources:** [Malbolge Wiki](https://esolangs.org/wiki/Malbolge) • [Malbolge Interpreter](https://www.malbolge.does.it/) • [Lothar's Malbolge Page](http://www.lscheffer.com/malbolge.shtml)

**Pros:** 👿 Ultimate challenge, 🏆 Bragging rights, 🎓 CS folklore  
**Cons:** 📝 Impossible to use, 🐢 Self-modifying madness, 📉 Literally useless

---

### 🎮 Befunge

| | |
|:---|:---|
| **Paradigm** | Esoteric, Two-dimensional, Stack-based |
| **Created** | 1993 by Chris Pressey |
| **Current Version** | Befunge-93 / Befunge-98 |
| **Extension** | `.bf` |

**Overview:** Code in 2D space. Befunge instructions execute on a grid where the instruction pointer can move in any direction, creating visual programs.

**Domains:** Esoteric art, 2D code visualization, puzzles, education  
**Why It Matters:** The first two-dimensional programming language; inspires visual programming thinking.  
**Notable Users:** Esoteric programming community, visual language researchers

**Setup:** Online interpreters or Befunge-93 compilers.

**Hello World:**
```befunge
64+"!dlroW ,olleH">:#,_@
```

**Run:** Via Befunge interpreter.

**Resources:** [Befunge Wiki](https://esolangs.org/wiki/Befunge) • [Befunge Playground](https://www.bedroomlan.org/tools/befunge-playground) • [Esolangs](https://esolangs.org/)

**Pros:** 🎮 2D fun, 🎓 Visual programming, 🏆 Creative  
**Cons:** 📝 Unreadable, 🐢 Useless, 📉 Niche

---

### ⬜ Whitespace

| | |
|:---|:---|
| **Paradigm** | Esoteric, Stack-based, Imperative |
| **Created** | 2002 by Edwin Brady and Chris Morris (Durham University) |
| **Current Version** | 1.0 (stable) |
| **Extension** | `.ws` |

**Overview:** Programs written in invisible characters. Whitespace uses only spaces, tabs, and newlines — making it the ultimate steganographic language.

**Domains:** Steganography, jokes, education, code obfuscation  
**Why It Matters:** Any program written in Whitespace is invisible in normal text editors.  
**Notable Users:** Pranksters, security researchers, esolang enthusiasts

**Setup:** Any Whitespace interpreter.

**Hello World:** (Not displayable in text — consists solely of spaces, tabs, and linefeeds)

**Run:** Via Whitespace interpreter.

**Resources:** [Whitespace Wiki](https://esolangs.org/wiki/Whitespace) • [Whitespace Interpreter](https://vii5ard.github.io/whitespace/) • [Durham Whitespace](https://web.archive.org/web/20151108084710/http://www.dur.ac.uk/d.j.h.morris/)

**Pros:** ⬜ Invisible code, 🎓 Steganography, 🏆 Ultimate obfuscation  
**Cons:** 📝 Unwritable, 🐢 Debugging nightmare, 📉 Completely useless

---

### 📟 INTERCAL

| | |
|:---|:---|
| **Paradigm** | Esoteric, Procedural, Unconventional |
| **Created** | 1972 by Donald Woods and James Lyon (Princeton) |
| **Current Version** | C-INTERCAL 0.31 (2026) |
| **Extension** | `.i` |

**Overview:** The original esoteric language. INTERCAL's "COME FROM" statement, polite syntax requirements, and word-based operators parody programming conventions.

**Domains:** Parody, education, computer history, entertainment  
**Why It Matters:** The first intentionally difficult language; invented the esoteric genre.  
**Notable Users:** Computer historians, language enthusiasts, jokesters

**Setup:**
```bash
# C-INTERCAL
brew install intercal    # if available
# Or build from source
```

**Hello World:**
```intercal
DO ,1 <- #13
PLEASE DO ,1 SUB #1 <- #238
DO ,1 SUB #2 <- #108
DO ,1 SUB #3 <- #112
DO ,1 SUB #4 <- #0
DO ,1 SUB #5 <- #64
DO ,1 SUB #6 <- #194
DO ,1 SUB #7 <- #48
PLEASE DO ,1 SUB #8 <- #26
DO ,1 SUB #9 <- #244
DO ,1 SUB #10 <- #168
DO ,1 SUB #11 <- #24
DO ,1 SUB #12 <- #16
DO ,1 SUB #13 <- #162
PLEASE READ OUT ,1
PLEASE GIVE UP
```

**Run:** Via C-INTERCAL compiler.

**Resources:** [INTERCAL Wiki](https://esolangs.org/wiki/INTERCAL) • [C-INTERCAL](http://www.catb.org/esr/intercal/) • [INTERCAL Manual](http://www.muppetlabs.com/~breadbox/intercal-man/)

**Pros:** 📟 Historic, 🎓 Parody value, 🏆 Original esolang  
**Cons:** 📝 Absurd syntax, 🐢 Useless, 📉 Obsolete

---

### 🎨 Piet

| | |
|:---|:---|
| **Paradigm** | Esoteric, Visual, Stack-based |
| **Created** | 2002 by David Morgan-Mar |
| **Current Version** | 1.0 (stable) |
| **Extension** | `.png`, `.gif` (image files) |

**Overview:** Programs are pictures. Piet uses color transitions in pixel art to represent instructions, making code literally visual.

**Domains:** Visual art, esoteric programming, creative coding, education  
**Why It Matters:** The most visually striking esoteric language; programs are genuine pixel art.  
**Notable Users:** Digital artists, esolang community, creative coders

**Setup:** Piet interpreters process image files.

**Hello World:** A pixel art image with specific color transitions.

**Run:** Via Piet interpreter (e.g., `npiet`).

**Resources:** [Piet Wiki](https://esolangs.org/wiki/Piet) • [npiet](https://www.bertnase.de/npiet/) • [Piet IDE](https://piet.bubbler.space/)

**Pros:** 🎨 Visual programming, 🎓 Creative coding, 🏆 Unique  
**Cons:** 📝 Image editing required, 🐢 Slow, 📉 Useless

---

### 🐢 Logo

| | |
|:---|:---|
| **Paradigm** | Educational, Functional, Procedural |
| **Created** | 1967 by Wally Feurzeig, Seymour Papert, Cynthia Solomon (MIT) |
| **Current Version** | Various implementations (UCBLogo, FMSLogo, MSWLogo) |
| **Extension** | `.lgo` |

**Overview:** The original educational programming language. Logo's turtle graphics introduced generations of children to computational thinking.

**Domains:** Education, turtle graphics, children's programming, geometry  
**Why It Matters:** The ancestor of Scratch and all block-based educational languages.  
**Notable Users:** Schools worldwide, MIT Media Lab, educational researchers

**Setup:** Use FMSLogo or UCBLogo.

**Hello World:**
```logo
print [Hello, World!]
```

**Run:** Via Logo interpreter.

**Resources:** [Logo Foundation](https://el.media.mit.edu/logo-foundation/) • [FMSLogo](https://fmslogo.sourceforge.io/) • [UCBLogo](https://people.eecs.berkeley.edu/~bh/logo.html)

**Pros:** 🐢 Educational gold standard, 🎨 Turtle graphics, 🎓 Child-friendly  
**Cons:** 🕰️ Obsolete, 📉 Limited use, 📝 Simple only

---

### 🧩 Scratch

| | |
|:---|:---|
| **Paradigm** | Visual, Block-based, Event-driven |
| **Created** | 2007 by Mitchel Resnick, Lifelong Kindergarten Group (MIT Media Lab) |
| **Current Version** | Scratch 3.0 (2026) |
| **Extension** | `.sb3` |

**Overview:** The world's most popular visual programming language. Scratch uses drag-and-drop blocks to teach 50+ million children computational thinking.

**Domains:** Education, children's programming, animations, games, storytelling  
**Why It Matters:** The entry point for a generation of programmers; available in 70+ languages.  
**Notable Users:** MIT, schools worldwide, Code.org, LEGO Education

**Setup:** Browser-based at [scratch.mit.edu](https://scratch.mit.edu/).

**Hello World:** (Visual blocks — "When Green Flag clicked" → "Say Hello, World!")

**Run:** Click the green flag in the Scratch IDE.

**Resources:** [Scratch MIT](https://scratch.mit.edu/) • [Scratch Wiki](https://en.scratch-wiki.info/) • [Scratch Jr](https://www.scratchjr.org/)

**Pros:** 🧩 Visual, 🎓 Educational, 🌍 Massive community  
**Cons:** 📝 Not text-based, 📉 Limited scope, 🐢 Performance

---

## 📝 Markup, Config & Formats

> Languages that structure, configure, and serialize data rather than execute algorithms.

---

### 📝 Markdown

| | |
|:---|:---|
| **Paradigm** | Markup, Lightweight |
| **Created** | 2004 by John Gruber (with Aaron Swartz) |
| **Current Version** | CommonMark 0.31, GitHub Flavored Markdown |
| **Extension** | `.md`, `.markdown` |

**Overview:** The universal plain-text formatting syntax. Markdown powers documentation, READMEs, notes, and static site generators across the internet.

**Domains:** Documentation, READMEs, note-taking, static sites, blogging, comments  
**Why It Matters:** GitHub, Reddit, Stack Overflow, and millions of tools use Markdown.  
**Notable Users:** GitHub, GitLab, Reddit, Stack Overflow, Notion, Obsidian

**Setup:** Any text editor. VS Code has built-in preview.

**Hello World:**
```markdown
# Hello, World!

This is **bold** and this is *italic*.

- Item 1
- Item 2

[Link](https://example.com)
```

**Run:** Rendered by any Markdown viewer or static site generator.

**Resources:** [CommonMark Spec](https://commonmark.org/) • [GitHub Markdown](https://docs.github.com/en/get-started/writing-on-github) • [Markdown Guide](https://www.markdownguide.org/) • [Daring Fireball](https://daringfireball.net/projects/markdown/)

**Pros:** 📝 Human-readable, 🌍 Universal, ⚡ Zero tooling  
**Cons:** 📝 No standard (flavors vary), 📉 Limited formatting, 🐛 Parsing inconsistencies

---

### 📦 JSON

| | |
|:---|:---|
| **Paradigm** | Data serialization, Structured |
| **Created** | 2001 by Douglas Crockford |
| **Current Version** | ECMA-404 (2026), JSON5, JSON Schema |
| **Extension** | `.json` |

**Overview:** The universal data interchange format. JSON's simplicity made it the default for APIs, configuration, and NoSQL databases.

**Domains:** APIs, configuration files, data storage, NoSQL, web services  
**Why It Matters:** Replaced XML as the dominant data format; every modern API uses JSON.  
**Notable Users:** Every web service, REST API, MongoDB, VS Code settings

**Setup:** Built into every modern programming language.

**Hello World:**
```json
{
    "message": "Hello, World!",
    "language": "JSON",
    "year": 2026
}
```

**Run:** Parse with any JSON parser.

**Resources:** [JSON.org](https://www.json.org/) • [JSON Schema](https://json-schema.org/) • [JSON5](https://json5.org/) • [ECMA-404](https://ecma-international.org/publications-and-standards/standards/ecma-404/)

**Pros:** 📦 Universal, 📝 Human-readable, ⚡ Language agnostic  
**Cons:** 📝 No comments, 🐢 No schema (without JSON Schema), 📉 Verbose

---

### 📋 YAML

| | |
|:---|:---|
| **Paradigm** | Data serialization, Configuration |
| **Created** | 2001 by Clark Evans, Ingy döt Net, Oren Ben-Kiki |
| **Current Version** | YAML 1.2 (2026) |
| **Extension** | `.yaml`, `.yml` |

**Overview:** JSON for humans. YAML's indentation-based syntax is ideal for configuration files, CI/CD pipelines, and Kubernetes manifests.

**Domains:** DevOps, CI/CD, Kubernetes, Ansible, Docker Compose, configuration  
**Why It Matters:** Kubernetes, GitHub Actions, and Ansible all use YAML as their native tongue.  
**Notable Users:** Kubernetes, GitHub, GitLab, Docker, Ansible, CloudFormation

**Setup:** Built into most modern tools.

**Hello World:**
```yaml
message: "Hello, World!"
language: YAML
year: 2026
features:
  - readable
  - indentation-based
```

**Run:** Parse with any YAML parser.

**Resources:** [YAML Spec](https://yaml.org/) • [YAML Lint](http://www.yamllint.com/) • [Learn YAML](https://learnxinyminutes.com/docs/yaml/)

**Pros:** 📋 Human-friendly, 📝 Comments allowed, 🏗️ Great for config  
**Cons:** 🐢 Whitespace sensitive, 📝 Complex spec, 🧠 Surprising edge cases

---

### ⚙️ TOML

| | |
|:---|:---|
| **Paradigm** | Configuration, Data serialization |
| **Created** | 2013 by Tom Preston-Werner (GitHub co-founder) |
| **Current Version** | TOML 1.0.0 (2026) |
| **Extension** | `.toml` |

**Overview:** The config file format that doesn't surprise you. TOML is explicit, simple, and increasingly the default for Rust and Python tools.

**Domains:** Configuration, package manifests, build tools, Rust Cargo, Python pyproject.toml  
**Why It Matters:** `pyproject.toml` and `Cargo.toml` made TOML the standard for modern tool configuration.  
**Notable Users:** Rust (Cargo), Python (PEP 518), Hugo, Poetry, Black

**Setup:** Built into modern tools.

**Hello World:**
```toml
[message]
text = "Hello, World!"
language = "TOML"
year = 2026
```

**Run:** Parse with any TOML library.

**Resources:** [TOML Spec](https://toml.io/en/) • [TOML Wiki](https://github.com/toml-lang/toml/wiki) • [TOML Lint](https://www.toml-lint.com/)

**Pros:** ⚙️ Explicit and simple, 📝 No indentation gotchas, 📦 Standard for Rust/Python  
**Cons:** 📉 Less universal than JSON, 📝 Verbose for nested data, 🐢 Limited features

---

### 🗂️ XML

| | |
|:---|:---|
| **Paradigm** | Markup, Data serialization, Document format |
| **Created** | 1998 by W3C (derived from SGML) |
| **Current Version** | XML 1.1 (W3C), XML Schema 1.1 |
| **Extension** | `.xml` |

**Overview:** The extensible markup language. XML provides structured, self-describing data with validation via DTDs and schemas.

**Domains:** Enterprise systems, SOAP, RSS, SVG, Office documents, configuration, sitemaps  
**Why It Matters:** Still the backbone of enterprise integration, document formats, and publishing.  
**Notable Users:** Microsoft Office, OpenDocument, RSS, SVG, Maven, Android layouts

**Setup:** Built into virtually all platforms.

**Hello World:**
```xml
<?xml version="1.0" encoding="UTF-8"?>
<<root>
    <message>Hello, World!</message>
    <language>XML</language>
</root>
```

**Run:** Parse with any XML parser.

**Resources:** [W3C XML](https://www.w3.org/XML/) • [XML Schema](https://www.w3.org/XML/Schema) • [MDN XML](https://developer.mozilla.org/en-US/docs/Web/XML)

**Pros:** 🗂️ Self-describing, 🛡️ Schema validation, 🏢 Enterprise standard  
**Cons:** 📝 Verbose, 🐢 Parsing overhead, 📉 Losing ground to JSON

---

### 📐 LaTeX

| | |
|:---|:---|
| **Paradigm** | Markup, Document preparation, Macro-based |
| **Created** | 1984 by Leslie Lamport (built on TeX by Donald Knuth, 1978) |
| **Current Version** | LaTeX2e / 2024 release |
| **Extension** | `.tex`, `.latex`, `.sty` |

**Overview:** The gold standard for scientific documents. LaTeX produces publication-quality typesetting for mathematics, physics, and academia.

**Domains:** Academic papers, theses, scientific publishing, books, presentations (Beamer)  
**Why It Matters:** No other system matches LaTeX's mathematical typesetting quality.  
**Notable Users:** ACM, IEEE, arXiv, universities, mathematicians, physicists

**Setup:**
```bash
# macOS
brew install --cask mactex

# Linux
sudo apt install texlive-full

# Windows
winget install TeXLive.TeXLive
# Or MiKTeX
```

**Hello World:**
```latex
\documentclass{article}
\begin{document}
Hello, World!
\end{document}
```

**Run:**
```bash
pdflatex hello.tex
# Generates hello.pdf
```

**Resources:** [LaTeX Project](https://www.latex-project.org/) • [Overleaf](https://www.overleaf.com/) • [TeX StackExchange](https://tex.stackexchange.com/) • [CTAN](https://ctan.org/)

**Pros:** 📐 Perfect typesetting, 🧮 Math excellence, 📚 Academic standard  
**Cons:** 📝 Steep learning curve, 🐢 Compile cycle, 🧠 Macro complexity

---

## 📈 Trends & The Future

The programming language landscape in 2026 is defined by several converging trends:

| Trend | Impact | Languages |
|-------|--------|-----------|
| **AI-Native Development** | Languages are integrating LLM assistance and vector operations | Python, Mojo, Julia, Rust |
| **Memory Safety Mandates** | Governments and enterprises requiring memory-safe languages | Rust, Swift, Go, Ada |
| **Functional Resurgence** | Immutability and type safety gaining enterprise adoption | Haskell, Elm, Gleam, F# |
| **WebAssembly Expansion** | Beyond the browser to servers, edge, and embedded | Rust, Zig, Grain, AssemblyScript |
| **Blockchain Specialization** | Domain-specific languages for smart contracts and ZK proofs | Solidity, Move, Cairo |
| **C++ Succession** | Multiple contenders vying to replace C++ | Rust, Carbon, Zig, CPP2 |
| **Two-Language Problem Solved** | Single languages spanning prototyping to production | Julia, Mojo, Nim, Rust |
| **Visual & Educational** | Block-based and visual languages expanding to all ages | Scratch, Blockly, Logo |

> **Prediction:** By 2030, we expect Rust to enter the top 3 most-used languages, Python to remain the AI standard, and at least one new language (possibly Mojo or Carbon) to break into mainstream enterprise use.

---

## 🤝 How to Contribute

We welcome contributions to expand this documentation! To add a new language:

1. **Fork** this repository
2. **Add** your language following the established template:
   - Header with emoji
   - Metadata table (Paradigm, Created, Version, Extension)
   - Overview, Domains, Why It Matters, Notable Users
   - Setup instructions for all three platforms
   - Hello World example with correct syntax highlighting
   - Run commands and expected output
   - 3-4 curated resources
   - Pros & Cons
3. **Verify** all version numbers and links are current as of 2026
4. **Submit** a Pull Request with a clear description

**Contribution Guidelines:**
- Be factual and neutral — no language wars
- Include runnable code examples
- Provide official documentation links
- Update the category table and TOC
- Ensure accessibility (alt text, clear structure)

---

## 📜 License

<div align="center">

This work is licensed under the **Creative Commons Attribution-ShareAlike 4.0 International License**.

[![CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg?style=flat-square)](https://creativecommons.org/licenses/by-sa/4.0/)

You are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:
- **Attribution** — You must give appropriate credit
- **ShareAlike** — If you remix, you must distribute under the same license

</div>

---

<div align="center">

**⭐ Star this repository if you found it useful!**

*Compiled with ❤️ by the global developer community. Last updated: May 2026.*

```
    ╔══════════════════════════════════════════════════════════╗
    ║     "Talk is cheap. Show me the code." — Linus Torvalds  ║
    ╚══════════════════════════════════════════════════════════╝
```

</div>
```
