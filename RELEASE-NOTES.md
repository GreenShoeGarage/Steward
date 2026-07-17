# STEWARD v2.2 Release Notes

## Workflow Consolidation and Cleanup

STEWARD v2.2 reorganizes the application around five lifecycle stages:

**Define → Investigate → Decide → Operate → Document**

The sidebar now contains only those stages and the Decision Dashboard. Individual tools appear in a stage-specific work bar, preserving all previous capability without forcing the user to scan a long navigation tree.

## Principal Changes

- Consolidated sidebar with five lifecycle stages
- Stage-specific local navigation for individual tools
- Remembered last-used tool within each stage
- Stage completion summaries
- Simplified top toolbar
- New Workspace menu for data and advanced tools
- Patterns and reasoning checks moved into Investigate
- Relationship tracing, baselines, maps, reports, archive, and recovery grouped under Document
- Duplicate dashboard workflow and next-action panels removed
- Record editors collapse once records exist
- Editor collapse state persists
- Calmer cards and reduced visual noise
- Improved mobile stage navigation
- Horizontal overflow corrected
- Consistent module naming

## Compatibility

Version 2.2 does not change the STEWARD data schema. Version 2.1 JSON workspaces remain compatible.

## Core Principle

STEWARD continues to refuse a single ethics score. Workflow completion indicates that analysis was performed, not that a decision is ethically cleared.
