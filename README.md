# Biomedical research data, funding, and evidence

I work at the intersection of biomedical research policy and data science. This collection brings together research software and exploratory analyses of data resources, research funding, and evidence-assisted classification.

The projects emphasize traceable sources, explicit interpretation rules, and a clear distinction between software verification and empirical validation.

## Explore the work

| Project | Purpose | Starting point |
|---|---|---|
| [dbGaP Metadata Atlas](https://github.com/conroyriodss/dbgap-metadata-atlas) | Analyze public study metadata, recorded access activity, linked literature, and repository relationships. | [Scope and workflow](https://github.com/conroyriodss/dbgap-metadata-atlas#readme) · [Validation](https://github.com/conroyriodss/dbgap-metadata-atlas/blob/main/docs/validation.md) |
| [NIH RePORTER MCP](https://github.com/conroyriodss/nih-reporter-mcp) | Query NIH funding and linked research outputs with explicit counting rules, retrieval limits, and evidence bundles. | [Tools and quickstart](https://github.com/conroyriodss/nih-reporter-mcp#readme) · [Evaluation](https://github.com/conroyriodss/nih-reporter-mcp/blob/main/eval/README.md) |
| [Resource Tracker](https://github.com/conroyriodss/tracker) | Inspect a published resource catalog, its structured relationships, supporting claims, and provenance. | [Published artifacts](https://github.com/conroyriodss/tracker/tree/main/docs) · [Snapshot manifest](https://github.com/conroyriodss/tracker/blob/main/docs/data/manifest.json) |
| [DATMM Explorer](https://github.com/conroyriodss/datmm-explorer) | Explore a source-attributed research graph using a notebook and a self-contained HTML browser. | [Scope and use](https://github.com/conroyriodss/datmm-explorer#readme) · [Releases](https://github.com/conroyriodss/datmm-explorer/releases) |
| [NITRD Categorization MCP Suite](https://github.com/conroyriodss/nitrd-categorization-mcp) | Connect research evidence, classification suggestions, and a demonstration human-review workflow. | [Submission map](https://github.com/conroyriodss/nitrd-categorization-mcp#submission-map-three-public-repositories) · [Evaluation evidence](https://github.com/conroyriodss/nitrd-categorization-mcp/blob/main/eval/README.md) |

The NITRD suite links to a separate [evaluation workflow](https://github.com/conroyriodss/uac-nitrd) and [witness records](https://github.com/conroyriodss/uac-witness). These supporting repositories serve different evidentiary roles.

## Understand and audit a project

Start with its question, scope, methods, and validation status. Identify the code revision and the associated data snapshot separately. Some projects depend on external inputs or environments; their availability affects what can be reproduced.

Metadata links, model suggestions, demonstration outputs, and validated findings are distinct. Missing information is not a supported negative, and passing software checks does not establish scientific validity. Read each project’s interpretation limits before using its outputs.

For technical questions or corrections, use the relevant repository’s issue tracker where enabled. Include the commit or release, the affected artifact, and supporting public evidence. Reuse terms are documented separately by project.

This is a personal research and software portfolio. Repository content should not be interpreted as official NIH policy, classification, or endorsement.
