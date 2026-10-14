# Animal Farm

A Java object-oriented project that models animals and farm infrastructure using a small domain model.

## Overview

The source defines animal types including cattle, goats, horses and sheep, alongside concepts for barns, cages, buildings, dimensions, volume, freight and milking.

## Concepts Demonstrated

- Inheritance and shared animal behaviour
- Modelling farm buildings and animal enclosures
- Interfaces and capability-oriented types
- Separating domain entities into small, focused classes

## Technology

- **Language:** Java
- **Entry point:** `src/Main.java`
- **Domain classes:** `src/farm/`

## Run Locally

Requirements: a Java Development Kit (JDK) and a Java IDE or terminal.

1. Clone the repository:
   ```bash
   git clone https://github.com/MihailKanev01/tu-varna-java-terminal-animal-farm.git
   cd tu-varna-java-terminal-animal-farm
   ```
2. Open the project in IntelliJ IDEA, or compile and run it from the repository root:
   ```bash
   javac -d out src/Main.java src/farm/*.java
   java -cp out Main
   ```

## Project Status

An educational project focused on Java class design, inheritance and modelling a simple farm domain.
