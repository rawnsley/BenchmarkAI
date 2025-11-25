# Patents Benchmark

This benchmark tests an AI model's ability to understand and visualize patent documents.

## Task

For each patent, the AI must produce:

1. **Infographic** - A clear visual explanation of the patent's key concepts and innovations
2. **Engineering drawings** - Technical drawings where appropriate (e.g., orthographic views, cross-sections, exploded views)
3. **3D model** - A glTF format model of any physical parts described in the patent

## Evaluation

Each generated artefact is evaluated on how well it matches the original patent:

- Accuracy of technical details
- Completeness of information
- Visual comparison with patent diagrams
- Correctness of dimensions and proportions (where specified)
