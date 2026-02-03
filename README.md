# wafer-shift-monitoring
## Problem
Wafer defect pattern analysis is often subjective and manual.

## Goal
Detect changes in wafer defect pattern distribution over time using unsupervised methods.

## Data
Public wafer map dataset. Each sample represents one wafer (0=pass, 1=fail).

## Approach
- Convert wafer maps into interpretable spatial features
- Separate center and edge regions using radial masks
- Track pattern distribution shifts over time

## Current Status
- Center/Edge masking implemented
- Defect ratios calculated

## How this would be used
This framework highlights time windows where process or tool investigation is required.
