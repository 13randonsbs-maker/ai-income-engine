# Naming Conventions (Minimum Standard)

## Repository Files
- Lowercase with underscores:
  - ai_autonomous_income_engine.md
  - state_master.md
- Agent files:
  - agents/{role}_agent.md (e.g., qa_agent.md)

## Candidate IDs
Format:
- KDP: KDP-YYYYMMDD-### (e.g., KDP-20251226-001)
- MERCH: MERCH-YYYYMMDD-### (e.g., MERCH-20251226-001)
- TREND: TREND-YYYYMMDD-### (e.g., TREND-20251226-001)

## SKU Naming (Internal Tracking)
Format:
- {ASSET_TYPE}-{NICHE_SLUG}-{VARIANT}-{YYYYMMDD}
Examples:
- KDP-adhd_planner-v1-20251226
- MERCH-blue_collar_humor-v2-20251226

## Folder Structure
- /agents = prompts and role specs
- /templates = checklists and standards
- state_master.md = single source of truth
