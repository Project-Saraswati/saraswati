# Project Saraswati
_Laying the groundwork for accessible healthcare pricing data._

## What This Project Is

This is an early-stage, open-source project focused on **hospital pricing data transparency**.

Right now, the work here is foundational: collecting and organizing hospital-published pricing files so they can be stored reliably, inspected, and used in future processing and analysis.

The long-term goal is to make hospital pricing data easier to understand for people—and easier to build on for the health-tech community. This repository represents the **first step** in that process.

---

## Current Status 

At the moment, this repository is focused on:

- Uploading hospital-published pricing files to **AWS S3**
- Preserving files in their original, unmodified form
- Establishing a clear, auditable storage structure for raw data


---

## Why Start Here?

Before pricing data can be:

- Cleaned  
- Standardized  
- Compared  
- Or explained  

It needs to be **reliably stored and accessible**.

This repository exists to ensure the raw data is:

- Centralized  
- Versionable  
- Inspectable  
- Ready for downstream processing  

Good transparency starts with good foundations.

---
### What You Can Help With Right Now

- Uploading hospital-published pricing files  
- Verifying file completeness and source URLs  
- Following established naming and storage conventions  

### How Access Works

Uploading files requires:
- An AWS IAM user with limited S3 permissions  
- Access to the project’s upload instructions and hospital list  

To keep credentials secure, AWS access is **not granted automatically**.

If you’d like to contribute:
1. Reach out via the project’s Slack workspace (or contact listed in this repo)
2. We’ll share:
   - Upload instructions
   - The current hospital list
   - Temporary or scoped AWS credentials, as appropriate


## What’s Coming Next

Planned future work includes:

- Parsing and validating hospital pricing files  
- Schema standardization across hospitals  
- Documentation of pricing fields and billing logic  
- Processed datasets designed for reuse by developers and researchers  

As each piece is added, this README will be updated to reflect reality—not aspiration.



