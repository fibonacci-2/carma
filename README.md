k---
license: mit
language:
- ar
tags:
- Mental
- Health
- mental-health
size_categories:
- 1B<n<10B
---
# Dataset Card for CARMA

<!-- Provide a quick summary of the dataset. -->
CARMA is the first comprehensive dataset for mental health analysis in Arabic. The data encompasses seven mental health conditions, some of which have never been explored previously in Arabic literature, such as OCD, PTSD, and ADHD.

A sample of the dataset is provided publicly. Full access is granted upon signing a Data Usage Agreement specifying the intended use of the data.

## Uses

<!-- Address questions around how the dataset is intended to be used. -->
CARMA supports the analysis and detection of several mental health conditions prevalent in Arabic-speaking communities. The inclusion of a control group enables further experimentation and serves as a foundation for detecting diagnosed conditions based on linguistic patterns.

## Dataset Structure

The dataset follows a post-level structure, where each row represents a unique post with its text, metadata, author information, and the ground truth label (obtained through a self-reported diagnosis algorithm).  
For privacy reasons, the provided sample omits certain columns.

### Source Data

The dataset was curated from the most active Arabic-speaking communities on Reddit.

#### Data Collection and Processing

Data underwent a rigorous preprocessing pipeline to remove noisy and non-Arabic content. Explicit or identifiable mental health content was also excluded to preserve user privacy and ensure dataset integrity.

