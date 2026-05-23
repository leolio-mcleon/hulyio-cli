# MAIN-REQUIREMENTS.md - hulyio-cli

**Status**: Active (Milestone 1.0)  
**Project**: hulyio-cli – Lightweight CLI Installation Helper  
**Philosophy**: CIAO / CIAO-Lite (Caution • Intentional • Anti-fragile • Over-engineered)

## 1. Purpose
This is the **Single Source of Truth** for the entire `hulyio-cli` project.

## 2. Core Project Principles (CIAO / CIAO-Lite)
- **Caution**: Assume nothing.
- **Intentional**: Every function and behavior is documented.
- **Anti-fragile**: Survives minimal environments and `curl | sh`.
- **Over-protect**: Verbose comments, Protection Zones, safe defaults.

## 3. Non-Negotiable Rules
- Single executable `/bin/sh` script for `curl | sh` compatibility.
- All output must go through centralized output system.
- Backup before any modification.
- Start with installation helper as primary feature.

**Protection Rule**: Any AI assistant MUST consult this file and all linked requirements before making changes.