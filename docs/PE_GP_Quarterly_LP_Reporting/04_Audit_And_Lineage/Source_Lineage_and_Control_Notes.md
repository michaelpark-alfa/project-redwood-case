# Source Lineage and Control Notes

This package demonstrates the full GP quarterly LP reporting workflow.

## Lineage principles
- Every reported operating metric must reference a source document and extracted value.
- Every fund-level metric must reference the fund administrator workbook or fund accounting model.
- Every calculated metric must preserve formula logic.
- Every narrative claim must be source-backed or marked as AI-generated and subject to human approval.
- Missing values remain missing until an authorized reviewer approves an override.

## Intentional exceptions
- Pulse Biosciences EBITDA is not disclosed.
- Lumina Health gross margin is missing.
- The workflow is designed to make those gaps visible rather than silently estimating them.
