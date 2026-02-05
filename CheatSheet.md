# 🛠️ Java Workshop Cheat Sheet

A quick reference guide for your first Java steps.

## 1. The Structure 🏗️

Every Java application consists of a **Class** and a **Main Method**.

```java
public class HelloApp {                  // The Container (Class)
    public static void main(String[] args) { // The Door (Entry Point)
        System.out.println("Text");      // The Command
    }
}

## 2. Key Terminology 📖

| Term | Definition |
| :--- | :--- |
| **Class** | A container for your code. Think of it as a box. |
| **Main Method** | The entry point. The JVM starts executing code here. |
| **JVM** | Java Virtual Machine. The engine that runs your code. |
| **Compiler** | A translator that turns your code (human-readable) into bytecode (machine-readable). |
| **Sout** | IntelliJ shortcut for `System.out.println()`. |

## 3. Engineering Rules ⚠️

### 🔹 Rule #1: File Integrity
The name of the public class **must match** the filename exactly.
* **Class:** `HelloApp`
* **File:** `HelloApp.java`
* **Why?** So the ClassLoader can find the bytecode.

### 🔹 Rule #2: Syntax Precision
Java is **Case-Sensitive**.
* ✅ **Correct:** `System.out.println`
* ❌ **Wrong:** `system.out.println`

### 🔹 Rule #3: The Static Context
The `main` method must be `static`.
* **Why?** It allows the JVM to run the method **without creating an object instance** first.

## 4. IntelliJ Shortcuts ⚡

* Type `main` + `Enter` → Generates `public static void main(String[] args)`
* Type `sout` + `Enter` → Generates `System.out.println()`
* `Ctrl` + `F9` (Windows) / `Cmd` + `F9` (Mac) → Build Project
* `Shift` + `F10` (Windows) / `Ctrl` + `R` (Mac) → Run App
