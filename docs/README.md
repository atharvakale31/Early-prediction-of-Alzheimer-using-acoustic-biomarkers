# Alzheimer's Disease Early Detection using Acoustic Biomarkers

## Overview
The goal of this project is to develop models that predict Alzheimer's disease and related dementias (AD/ADRD) using audio recordings. Early detection through vocal features can enable timely care and reduce healthcare disparities.

### Why Audio Data?
- **Non-invasive & Cost-effective**: Audio-based screening is simple and affordable.
- **Early Detection**: Identifying cognitive decline through speech patterns allows for earlier intervention.

---
## Data Description
The dataset includes audio recordings from 2,058 individuals diagnosed with varying levels of cognitive decline. It contains:

### Key Data Details:
- **Raw Audio Files**: Available via TalkBank.
- **Pre-generated Features**: 88 audio features like pitch, speech rate, and more, extracted using the OpenSMILE toolkit.

### Metadata Columns:
- `uid`: Unique participant ID
- `age` & `gender`: Participant details
- `split`: Dataset split (train/test)
- `filesize_kb`: Audio file size

---
## Labels
Three possible diagnoses for each individual:
- **Control**: Healthy individual
- **MCI**: Mild Cognitive Impairment (risk of dementia)
- **ADRD**: Advanced decline (e.g., Alzheimer's Disease)


