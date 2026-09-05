# MergeIA

### AI-Powered Git Merge Conflict Resolution for VS Code

MergeIA is an AI-powered Visual Studio Code extension that assists developers in resolving Git merge conflicts. It analyzes conflicting code along with its surrounding context and uses an LLM to recommend or generate an appropriate merge solution.

The goal is to reduce manual effort, prevent accidental code loss, and help developers identify potential issues before completing a merge.

---

## Overview

Git merge conflicts occur when multiple developers modify overlapping parts of a codebase. Traditional Git conflict resolution provides options such as accepting the current change, accepting the incoming change, or accepting both changes.

These options do not understand the intent or behavior of the code.

**MergeIA** introduces an AI-assisted workflow that analyzes the conflicting changes and provides context-aware recommendations.

### Traditional Workflow

```text
Merge Conflict
      ↓
Manual Code Analysis
      ↓
Choose Current / Incoming / Both
      ↓
Resolve Conflict
      ↓
Build / Test
