<div align="center">

<img src="logo.png" alt="Vex" width="120">

### A multi-paradigm systems language
##### high-level to write · low-level enough to boot a machine

<p>
  <img src="https://img.shields.io/badge/interpreted-VM-6C4AB6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/JIT-native-1E88E5?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AOT-no%20runtime-2E7D32?style=for-the-badge" />
</p>
<p>
  <img src="https://img.shields.io/badge/Windows-PE-555?logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-ELF-555?logo=linux&logoColor=white" />
  <img src="https://img.shields.io/badge/paradigm-imperative_·_OOP_·_functional-777" />
</p>

<br>

**One source, three ways to run it.**

</div>

<br>

<table align="center">
<tr align="center">
  <td width="270">🧩<br><b>Interpreted</b><br><sub>register-based bytecode VM</sub></td>
  <td width="270">⚡<br><b>JIT</b><br><sub>compiled to native code</sub></td>
  <td width="270">🚀<br><b>AOT</b><br><sub>standalone native · no runtime</sub></td>
</tr>
</table>

<br>

<div align="center">

Vex combines the control of **C**, the object model of **Java** and the ergonomics of **Python**
in a single statically-typed language.<br>
The same code scales from a script to an operating system — down to kernels, drivers and
firmware — because that's a *deployment* choice, not a different language.

</div>

<br>

```cpp
u64 fib(u64 n) {
    if (n < 2) return n;
    return fib(n - 1) + fib(n - 2);
}

i32 main(string[] args) {
    println("fib(10) = ${fib(10)}");
    return 0;
}
```

<br> <div align="center">
🛠  One language, one toolchain
Everything in-house — no external toolchain required.

<p> <img src="https://img.shields.io/badge/Compiler-263238" /> <img src="https://img.shields.io/badge/Virtual_Machine-263238" /> <img src="https://img.shields.io/badge/Language_Server-263238" /> <img src="https://img.shields.io/badge/Package_Manager-263238" /> <img src="https://img.shields.io/badge/Debugger-263238" /> <img src="https://img.shields.io/badge/Native_Codegen-263238" /> </p> <br> <a href="https://github.com/vex-language/vex"> <img src="https://img.shields.io/badge/→%20%20Get%20started-vex--language%2Fvex-6C4AB6?style=for-the-badge" /> </a>
<br><br>

<sub><i>One language, from a script to a kernel.</i></sub>

</div> 
