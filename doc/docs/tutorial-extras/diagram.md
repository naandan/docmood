---
title: Diagram
---

## Process
Process is a sequence of activities that are performed to achieve a specific goal.
```mermaid
graph TD
    A[Start] --> B[Process]
    B --> C[End]
```

## Decision
Decision is a process that allows to make a decision based on a condition.
```mermaid
graph TD
    A[Start] --> B{Decision}
    B -->|One| C[Right]
    B -->|Two| D[Wrong]
```

## Loop
Loop is a process that allows to repeat a process.
```mermaid
graph TD
    A[Start] --> B[Loop]
    B --> C[End]
```

## Parallel
Parallel is a process that allows to perform multiple processes at the same time.
```mermaid
graph TD
    A[Start] --> B[Parallel]
    B --> C[End]
```