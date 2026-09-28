# Java Pro Class Runner

Simple dark-themed Swing GUI tool to edit, compile and run single Java class files.

## Features
- Dark theme editor + output panel
- Open / Save / Compile / Run
- Project folder support (`compiled/` + `libraries/`)
- JAR library adding
- Automatic package detection
- Class name is read from source (not only filename)
- Auto-save before compile/run

## How to run
```bash
chmod +x start.sh
./start.sh
```

Or compile yourself:
```bash
javac Java_Pro_class_runner.java
java Java_Pro_class_runner
```

## Requirements
- Java JDK (javac + java)
