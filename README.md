# BenchmarkAI

A benchmarking framework for AI engines with a focus on:

- **Difficult tasks** - Problems that challenge the limits of current AI capabilities
- **Incomplete knowledge** - Scenarios where information is partial, ambiguous, or uncertain

## Purpose

This project aims to provide rigorous, reproducible benchmarks that test AI systems on real-world problem characteristics often underrepresented in standard evaluations.

## Tests

- [patents/](patents/) - Visualize and model patents from technical descriptions

## Structure

- `patents/cappiani/` - Source data for the Cappiani patent analysis
- `patents/cappiani/analysis/<model>/` - Analysis results organized by AI model and version (e.g., `analysis/claude-opus-4.5/`)
