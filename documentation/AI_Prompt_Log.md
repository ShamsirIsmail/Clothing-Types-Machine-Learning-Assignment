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

## Phase 02 — Data Preprocessing

**Notebook:** 02_data_preprocessing.ipynb  
**AI Tool:** ChatGPT

The following entries are retrospective summaries of the AI coding assistance used during Phase 2.

### Prompt 07 — Exploratory Data Analysis

**Purpose:** Understand dataset characteristics.

**Prompt Summary:**

Provide Python code to analyze image dimensions, aspect ratios, colour modes, brightness, and contrast. Generate descriptive statistics and suitable visualizations.

### Prompt 08 — Label Encoding and Data Splitting

**Purpose:** Prepare numerical labels and balanced dataset partitions.

**Prompt Summary:**

Encode the five clothing classes and perform stratified 70:15:15 dataset splitting using a fixed random seed. Verify class distributions and check for image overlap.

### Prompt 09 — Image Resizing and Normalization

**Purpose:** Standardize images for machine learning.

**Prompt Summary:**

Compare image resizing methods and resize images to 224 × 224 pixels while preserving their aspect ratios. Implement pixel normalization compatible with MobileNetV2.

### Prompt 10 — Data Augmentation

**Purpose:** Increase training image diversity.

**Prompt Summary:**

Implement controlled online data augmentation using horizontal flipping, rotation, brightness, and contrast adjustments. Apply augmentation to training data only and validate the results.

### Prompt 11 — Final Validation and Export

**Purpose:** Verify dataset integrity and reproducibility.

**Prompt Summary:**

Validate processed images, numerical labels, dataset partitions, and preprocessing configurations. Export the processed dataset, validation reports, and library version information.

### Human Verification

The generated code was executed in Google Colab, and the resulting outputs were inspected.

- All 600 processed images passed integrity validation.
- All 18 final preprocessing validation checks passed.
- No exact image overlap was detected between dataset partitions.
- The original cleaned dataset was preserved.
- Data augmentation was configured for training only.
- The processed dataset was successfully exported and its archive integrity was verified.
