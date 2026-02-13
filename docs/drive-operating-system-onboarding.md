# Drive Operating System — 2-Minute Collaborator Onboarding

## Goal

Make files easy to find for both people and AI.

## The only root folders you should use

- `00_INBOX` (temporary only)
- `01_WORK`
- `02_RESEARCH`
- `03_PERSONAL`
- `98_SHARED_SHORTCUTS` (shortcuts only)
- `99_ARCHIVE` (do not edit)

## The 3-step intake rule (always)

When you create or receive a file:

1. Put it in `00_INBOX`
2. Rename it with the standard
3. File it into the correct final folder

## File naming standard (required)

`YYYY-MM-DD__Entity__DocType__Topic`

Examples:

- `2026-02-13__ClientA__MTGNOTES__Weekly-Checkin`
- `2026-Q1__SalesOps__PIPELINE__REPORT__Weekly`
- `2026-02-13__SalesOps__PIPELINE__EXPORT__LinkedInRecruiter`

## Non-negotiable rules

- No permanent files in root
- No duplicate "(1)/(2)/(7)" file naming
- One **Source of Truth** per dataset
- Exports are dated snapshots, not canonical data

## Where things go (quick map)

- Client work: `01_WORK/01_Clients/<Client>/...`
- Sales data canonical: `01_WORK/03_SalesOps_Analytics/00_Source_of_Truth/`
- Sales exports: `01_WORK/03_SalesOps_Analytics/01_Exports_Staging/`
- Research papers/code/data: `02_RESEARCH/...`
- Personal tax/photos/recipes: `03_PERSONAL/...`

## Meeting notes minimum format

Include these sections at top:

- Date
- Attendees
- Agenda
- Decisions
- Action Items (Owner - Due - Task)
- Risks/Blockers

## Link safety rule

If a file might be used by dashboards, Slack, or client links:

1. Create a shortcut in the new location first
2. Verify links still work
3. Move file only after verification

## Weekly maintenance (10 minutes)

- Empty `00_INBOX`
- Rename unclear files
- Move files out of root
- Confirm active client meeting folders are current

## If unsure

Do not invent a new folder pattern. Put the file in `00_INBOX` and ask the owner.
