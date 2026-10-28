# Contributing Guide
This guide applies to all technical documentation repositories under Humanchem(Guangzhou Human New Material Science and Technology Co., Ltd.) organization.
All submissions must comply with brand, advertising compliance and data accuracy requirements.

## Repository Structure Rule
We follow a unified folder structure across all product repositories:
- `README.md`: Repository landing page / product hub
- `assets/`: Images, charts, certificate thumbnails. No external CDN temporary links.
- `docs/blog/`: Independent technical articles in Markdown (.md) for SEO & technical reference
- `docs/pdf/`: TDS, whitepaper, specification PDF files. Version number is required in filename.

### Naming Standard
- Folder & file names: lowercase, use hyphen `-` as separator, no space / uppercase / Chinese characters
  Example: `wvtr-test-comparison.jpg`, `grease-resistance-guide.md`, `paper-barrier-tds-v1.1.pdf`
- Image requirement: JPG / PNG / SVG, single file ≤ 200KB.
- Relative path reference (for markdown):
  - Root README: `![image](assets/xxx.jpg)`
  - Article inside docs/blog: `![image](../../assets/xxx.jpg)`

## Content & Compliance Rules (Critical)
1. All performance data, test results must match official TDS. Ambiguous or unvalidated data is forbidden.
2. Anonymous competitor comparison is NOT allowed. Only blank sample comparison is permitted, with clear labeling of test conditions.
3. All content shall be for technical reference only. The unified disclaimer must be kept at the bottom of README.
4. Do NOT include price, MOQ, confidential internal formula, unpublished non-public project information.
5. Customer logos cannot be added without written authorization.

## Submission & Review Workflow
1. Do NOT commit directly to the `main` branch. All changes must be submitted via Pull Request (PR).
2. PR content will be reviewed by the brand team for compliance, technical accuracy and format check.
3. PR needs at least one approval before merge.
4. If you update PDF / images, update the corresponding link in README or article at the same time.

## What We Do NOT Accept
- Content violating advertising law or fair competition regulation
- Broken links, expired parameter, blurry oversized images
- Hard-coded external links that may become invalid (prefer assets storage inside repo)

## Contact for Review
For questions about contribution rules and content review, contact the brand management team of Humanchem.
