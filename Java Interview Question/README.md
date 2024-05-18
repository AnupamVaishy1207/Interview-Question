# Java Interview Questions

Welcome to the Java Interview Questions repository! This repository contains a curated list of frequently asked questions about Java, which can help you prepare for interviews and understand key concepts in Java programming.

## Table of Contents

1. [Is Java Platform Independent? If then how?](#1-is-java-platform-independent-if-then-how)
2. [How is Java platform independent?](#2-how-is-java-platform-independent)
3. [Why is Java platform-independent but JVM platform-dependent?](#3-why-is-java-platform-independent-but-jvm-platform-dependent)

## 1. Is Java Platform Independent? If then how?

Yes, Java is a platform-independent language. Unlike many programming languages, the `javac` compiler compiles the program to form bytecode or a `.class` file. This file is independent of the software or hardware running but needs a JVM (Java Virtual Machine) preinstalled in the operating system for further execution of the bytecode.

Although the JVM is platform-dependent, the bytecode can be created on any system and can be executed on any other system despite the hardware or software being used, which makes Java platform-independent.

## 2. How is Java platform independent?

### Step-by-Step Execution of Java Program:

1. **Write the Program**: When a program is written in Java, the `javac` compiler compiles it.
2. **Compilation**: The result of the Java compiler is a `.class` file or bytecode, not the machine’s native code (unlike the C compiler).
3. **Bytecode Execution**: The bytecode generated is a non-executable code and needs an interpreter to execute on a machine. This interpreter is the JVM, and thus the bytecode is executed by the JVM.
4. **Program Execution**: Finally, the program runs to give the desired output.

## 3. Why is Java platform-independent but JVM platform-dependent?

- **JVM Dependency**: In Java, the main point is that the JVM depends on the operating system. For example, if you are running macOS, you will have a different JVM than if you are running Windows or another operating system.
- **Platform-Specific JVMs**: This fact can be verified by trying to download the JVM for your particular machine. When downloading, you will be given a list of JVMs corresponding to different operating systems, and you will choose the JVM targeted for the operating system you are running. Therefore, we can conclude that the JVM is platform-dependent, which is why Java can become "platform-independent".


