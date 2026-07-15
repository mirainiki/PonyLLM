# PonyLLM

**PonyLLM** is a repository-native reasoning model built for software architecture analysis, codebase comprehension, and execution tracing.

## Vision

PonyLLM helps developers understand unfamiliar repositories by reconstructing architecture, identifying execution paths, mapping dependencies, and explaining design decisions.

### Features

- Repository-level reasoning
- Architecture & dependency mapping
- Entry-point and execution flow tracing
- Multi-file code comprehension
- Large-context repository analysis
- Optimized for developer workflows

## Model Variants

| Model | Context | Strength |
|--------|---------|----------|
| pony-mini | 128k | Fast code navigation |
| pony | 1M+ | Repository understanding |
| pony-pro | 2M+ | Large monorepos & architecture |
| pony-max | 8M+ | Enterprise-scale reasoning |

## Quick Start

```bash
pip install ponyllm

ponyllm login
ponyllm analyze https://github.com/owner/repository
```

## Example

```bash
$ ponyllm analyze torvalds/linux

✓ Repository Summary
✓ Architecture Map
✓ Dependency Graph
✓ Execution Flow
✓ Key Components
✓ Entry Points
```
