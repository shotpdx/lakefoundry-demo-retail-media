# Retail, Media & Entertainment Demo

**AI-DLC Stage: Improve**

Use case: Content Supply Chain - Automated metadata generation and QC

## Demo Flow

1. Show existing content tagging pipeline with known issues
2. Run improvement agent against MLflow traces
3. Watch agent identify patterns (e.g., poor genre classification for documentaries)
4. Review proposed prompt/skill improvements
5. Show before/after quality metrics

## What's Built

- Pipeline: content ingestion → metadata extraction → QC flags
- Gold tables: content_metadata, qc_issues
- MLflow: traces showing tagging failures
- Improvement: agent proposals ready to demo

Part of the Lakefoundry AI-DLC demo suite.
