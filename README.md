# Urban Audio Sensing

[![GitHub](https://img.shields.io/badge/GitHub-urbanaudiosensing-blue.svg)](https://github.com/urbanaudiosensing)

**Urban Sensing of Pedestrians through Integrated, Cost-effective, and Scalable Audio Sensor Networks**

This project investigates the usefulness of microphones for estimating pedestrian traffic using machine learning methods for music and audio content analysis applied to urban sound recordings.

## Overview

Urban Audio Sensing is a research initiative that explores how audio technology can be leveraged to sense and analyze pedestrian movement in urban environments. The project experiments with off the shelf hardware components in pedestrian heavy campus environments to assess the possibilities for scaling up audio based urban sensing.

### Key Features

- **Large-scale audio dataset**: ASPED (Audio Sensing for PEdestrian Detection) with over 2,600 hours of audio data
- **Multi-modal data**: Audio recordings paired with video frames and pedestrian count annotations
- **Two environment types**: Campus (vehicle free) and urban (with vehicular noise) datasets
- **Machine learning**: Applied music and audio content analysis techniques
- **Open-source**: Models and datasets available for research use

## ASPED Dataset

**ASPED** (Audio Sensing for PEdestrian Detection) is a large-scale audio and video dataset prepared for pedestrian detection using sound.

### ASPED.a
- **2,600+ hours** of audio recordings
- **3.4+ million** continuous video frames
- **Pedestrian count annotations** for each audio and video segment
- Collected in a **vehicle-free campus environment**
- Published and presented at IEEE ICASSP 2024

### ASPED.b
- Second round of collected data
- Features data collected amidst **vehicular noise**
- Investigating differences in pedestrian sensing performance between environments

### Download
- [Dataset Overview](https://urbanaudiosensing.github.io/ASPED.html)
- [ASPED.a Dataset](https://urbanaudiosensing.github.io/ASPEDa.html)
- [ASPED.b Dataset](https://urbanaudiosensing.github.io/ASPEDb.html)

## Project Structure

```
urbanaudiosensing.github.io/
├── index.html              # Main landing page
├── team.html               # Team information
├── ASPED.html              # Dataset overview
├── ASPEDa.html             # ASPED.a download page
├── ASPEDb.html             # ASPED.b download page
├── publication.html        # Publications and presentations
├── about.html              # Project details
├── assets/                 # CSS, JS, and other assets
├── images/                 # Project images and photos
│   ├── ASPED/             # Dataset-related images
│   └── StreetPhotos/      # Street photography
└── publications/          # Research papers and metadata
    ├── 2024_ICASSP_ASPED.pdf
    ├── ASPEDvA-Metadata.xlsx
    └── ASPEDvB-Metadata.xlsx
```

## Team

### Research Centers
- **[Center for Spatial Planning Analytics and Visualization (CSPAV)](https://cspav.gatech.edu/)**: Develops and applies geospatial technologies for community planning
- **[Center for Music Technology](https://gtcmt.gatech.edu/)**: Transforms music creation and experience through technology

### Key Researchers
- **Subhro Guhathakurta** - Professor, School of City and Regional Planning
- **Alexander Lerch** - Professor, Center for Music Technology
- **Chaeyeon Han** - Research Scientist
- **Yonghyun Kim** - Graduate Researcher
- **Tyler Morgan** - Undergraduate Research Assistant
- **Akash Sarode** - Undergraduate Research Assistant

## Publications

1. **Seshadri, P., Han, C., Koo, B., Posner, N., Guhathakurta, S., & Lerch, A. (2024)**. ASPED: An Audio Dataset for Detecting Pedestrians. IEEE ICASSP 2024.
   - [Download PDF](publications/2024_ICASSP_ASPED.pdf)
   - [arXiv](https://arxiv.org/abs/2309.06531)

2. **Han, C., Seshadri, P., Ding, Y., Posner, N., Koo, B. W., et al. (2024)**. Understanding pedestrian movement using urban sensing Technologies: the promise of audio-based sensors. Urban Informatics.
   - [arXiv](https://arxiv.org/pdf/2406.09998)

## Links

- **Website**: [urbanaudiosensing.github.io](https://urbanaudiosensing.github.io)
- **GitHub**: [github.com/urbanaudiosensing](https://github.com/urbanaudiosensing)
- **Models Repository**: [github.com/urbanaudiosensing/Models](https://github.com/urbanaudiosensing/Models)

## Acknowledgments

This research is supported by the National Science Foundation (NSF) EAGER program and conducted at the Georgia Institute of Technology.