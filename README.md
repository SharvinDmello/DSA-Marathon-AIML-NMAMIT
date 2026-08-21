# Java DSA Training

This repository contains my Data Structures & Algorithms (DSA) practice and training work, implemented in **Java**. It's used to learn, solve, and revise core DSA concepts as part of placement/interview preparation.

More problems and topics will keep getting added as the training progresses.

---

## Prerequisites

You need the **Java Development Kit (JDK)** installed to compile and run the code in this repo. Any recent LTS version works — **JDK 21** or **JDK 25**.

Recommended distribution: **[Eclipse Temurin](https://adoptium.net/temurin/releases/)** (free, no login required, available for Windows and Linux).

---

## Installing Java on Windows

1. Go to **[adoptium.net](https://adoptium.net/temurin/releases/)** and download the **JDK 21 (LTS)** `.msi` installer for **Windows x64**.
2. Run the installer.
   - On the "Custom Setup" screen, make sure **"Set JAVA_HOME variable"** and **"Add to PATH"** are enabled (they usually are, by default).
3. Finish the installation.
4. Verify it worked — open **Command Prompt** (or PowerShell) and run:
   ```bash
   java -version
   javac -version
   ```
   You should see version output like `openjdk version "21.x.x"` for both commands.

If `java`/`javac` isn't recognized, restart your terminal (or PC), or manually add the JDK's `bin` folder (e.g. `C:\Program Files\Eclipse Adoptium\jdk-21.x.x\bin`) to your **PATH** environment variable.

---

## Installing Java on Linux

### Debian/Ubuntu (apt)
```bash
sudo apt update
sudo apt install openjdk-21-jdk -y
```

### Fedora/RHEL (dnf)
```bash
sudo dnf install java-21-openjdk-devel -y
```

### Arch
```bash
sudo pacman -S jdk21-openjdk
```

### Verify installation
```bash
java -version
javac -version
```

> Alternatively, download the Linux `.tar.gz` build directly from [adoptium.net](https://adoptium.net/temurin/releases/), extract it, and add its `bin` folder to your `PATH`.

---

## Compiling & Running a Java File

Once Java is installed, from inside any problem's folder:

```bash
javac FileName.java   # compiles FileName.java -> FileName.class
java FileName          # runs it
```

---

## Notes

- Recommended IDE: **IntelliJ IDEA (Community Edition)** or **VS Code** with the Java Extension Pack — both work well with just the JDK installed above.
- This repo is a personal training log — code here favors clarity and understanding over production-level polish.
