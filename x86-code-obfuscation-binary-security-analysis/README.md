# LOCO — x86 Code Obfuscation & Binary Security Analysis

## Project Overview

This project focuses on the analysis of **LOCO**, an x86 code obfuscation and de-obfuscation toolkit used for software protection, reverse engineering research, and binary-level security analysis.

LOCO is designed to make compiled binaries harder to understand, analyze, and reverse engineer while preserving the original functionality of the program. The project explored how obfuscation techniques affect security analysis, malware investigation, binary protection, and software assurance.

This project was completed as part of a 4-person security research team, with emphasis on understanding how attackers and defenders interact with protected or intentionally confusing executable code.

## Why This Project Matters

Cybersecurity analysts often deal with suspicious files, malware samples, protected binaries, and code that has been intentionally modified to hide its behaviour. Understanding obfuscation helps analysts recognize when code is being used to delay investigation, hide malicious intent, or protect intellectual property.

This project connects directly to security analyst work because it involves:

- Reverse engineering awareness
- Malware analysis concepts
- Binary protection techniques
- Threat investigation
- Security research
- Technical documentation
- Explaining complex security topics clearly

## Tools & Technologies

- LOCO
- LANCET GUI
- DIABLO link-time binary rewriting framework
- x86 binaries
- Control-flow graph analysis
- Binary security research
- Code obfuscation concepts
- Technical presentation and documentation

## Key Security Concepts Covered

- Code obfuscation
- De-obfuscation
- Reverse engineering resistance
- Control-flow graph transformation
- Control-flow flattening
- Opaque predicates
- Fine-grained obfuscation
- Software watermarking
- Binary rewriting
- Malware analysis awareness
- Software protection

## What I Worked On

- Researched LOCO as an x86 code obfuscation and de-obfuscation toolkit.
- Analyzed how LOCO uses a graphical interface to support interactive binary analysis.
- Studied how LANCET visualizes control-flow graphs to help users inspect executable structure.
- Examined how DIABLO supports link-time binary rewriting and code transformation.
- Connected obfuscation techniques to real cybersecurity use cases such as malware analysis, software protection, and reverse engineering.
- Presented findings in a structured security research format.

## Technical Summary

LOCO operates as an interactive environment for applying and studying code obfuscation techniques on x86 binaries. Instead of working only with source code, LOCO focuses on compiled binaries, making it useful for understanding how security analysts and researchers interact with real executable programs.

The tool combines:

- A visual interface for inspecting control flow
- Binary rewriting support
- Obfuscation transformations
- De-obfuscation and analysis support
- Research-focused experimentation

This makes LOCO valuable for learning how obfuscation changes the structure of a program without changing its intended functionality.

## Security Techniques Analyzed

### Control-Flow Flattening

Control-flow flattening changes the natural structure of a program by restructuring the execution flow. This makes the program harder to follow during reverse engineering because the original logic is no longer easy to read.

### Opaque Predicates

Opaque predicates are conditional expressions that always evaluate in a predictable way but are difficult to understand by static analysis. They can add confusing branches, dead code, and misleading execution paths.

### Fine-Grained Obfuscation

Fine-grained obfuscation allows transformations to be applied at a detailed level, giving analysts more control over where and how code is modified.

### Watermarking

Watermarking techniques can embed identifying information into software, helping with copyright protection, ownership verification, and software integrity tracking.

## Security Analyst Relevance

This project aligns with cybersecurity analyst responsibilities because it demonstrates the ability to:

- Analyze suspicious or protected code behaviour
- Understand how attackers may hide malicious logic
- Recognize techniques that complicate reverse engineering
- Explain binary security concepts clearly
- Support threat investigation and malware analysis workflows
- Document technical findings in a professional format

## Job-Relevant Skills Demonstrated

- Cybersecurity analysis
- Threat investigation awareness
- Malware analysis fundamentals
- Reverse engineering concepts
- Binary security research
- Security documentation
- Technical communication
- Analytical thinking
- Software protection awareness
- Incident investigation support

## Example Resume Bullet Points

- Collaborated in a 4-person security research team to analyze LOCO, an x86 code obfuscation and de-obfuscation toolkit used to protect compiled binaries from reverse engineering while preserving application functionality.

- Assessed LOCO’s architecture using LANCET for control-flow graph visualization and DIABLO for link-time binary rewriting, strengthening practical understanding of binary analysis, code transformation, and software protection.

- Researched and presented obfuscation techniques including control-flow flattening, opaque predicates, fine-grained obfuscation, and watermarking, connecting them to malware analysis, reverse engineering, and threat investigation.

## What I Learned

This project improved my understanding of how binary-level security tools work and how obfuscation can be used both defensively and offensively. It also helped me understand why cybersecurity analysts need to recognize hidden or intentionally confusing code structures when investigating suspicious programs.

## Disclaimer

This project was completed for educational and defensive security research purposes only. No unauthorized systems were accessed, tested, or modified.
