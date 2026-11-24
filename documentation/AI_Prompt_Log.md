# AI Prompt Log

**Project:** Clothing Types Image Classification  
**Course:** SAIA 2113 — Machine Learning  
**AI tools:** ChatGPT and Claude  
**Phase:** 01 — Data Collection and Cleaning  
**Notebook:** `01_data_collection.ipynb`

## Phase 1 — Data Collection and Cleaning

The entries below are retrospective summaries of AI coding assistance, not verbatim prompts or a complete conversation record. Original conversations and the Claude prompt should be retained for verification.

### P01 — Dataset Collection

**Tool:** ChatGPT  
**Purpose:** Dataset acquisition and organization.

**Prompt summary:** Provide Python code to download the Clothing Dataset (Small), select five clothing classes, and organize the images into separate folders in Google Drive.

### P02 — Automated Data Cleaning

**Tool:** ChatGPT  
**Purpose:** Technical image quality assessment.

**Prompt summary:** Write Python code to detect corrupted images, low-resolution images, exact duplicates and potential near-duplicates. Save the results without deleting original images.

### P03 — Interactive Image Reviewer

**Tool:** ChatGPT and Claude  
**Purpose:** Human label verification.

**Prompt summary:** Create an interactive reviewer in Google Colab that allows users to keep, reject or flag clothing images and automatically saves their decisions to a CSV file.

### P04 — AI-Assisted Label Screening

**Tool:** ChatGPT  
**Purpose:** Reduce manual inspection workload.

**Prompt summary:** Use a pretrained CLIP model to screen potentially mislabeled clothing images and provide a batch review interface while preserving existing human decisions.

### P05 — Final Dataset Selection and Validation

**Tool:** ChatGPT  
**Purpose:** Curate and validate the final dataset.

**Prompt summary:** Provide Python code to select up to 120 human-approved images per class, exclude uncertain images, check duplicates and validate the final dataset against its manifest.

### P06 — Visualization and Reproducibility

**Tool:** ChatGPT  
**Purpose:** Dataset visualization, documentation and export.

**Prompt summary:** Generate code to visualize class distribution and sample images, export the cleaned dataset and record dataset provenance, random seeds and library versions.

## Additional AI Assistance

AI assistance also covered dataset comparison, debugging Google Colab and Google Drive errors, preliminary visual auditing, notebook planning with Claude, and GitHub documentation. These activities are not fully represented by the six coding summaries above. Retain the original prompts, dates, outputs and relevant changes in the original conversation records.

## Human Verification and Academic Integrity

The final dataset contains 600 selected images across five classes. CLIP was used for candidate screening, not automatic ground-truth labeling. Dataset inclusion was based on recorded human approval. Eight configured final validation checks passed.

Confirm that the use of CLIP for dataset screening complies with the lecturer's AI-use policy before submission. The prompt summaries must not be represented as the exact prompts originally submitted.

## Phase 2 — Data Preprocessing

Prompt records will be added as implementation progresses.
