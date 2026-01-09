# ucd-patient-pathway-analysis
K-Means clustering for unscheduled care pathways 
# UCD Patient Pathway Clustering (AI4BI CDT Project 1)

**Live K-Means analysis of unscheduled care bottlenecks**  
Simulating Public Health Scotland UCD dataset (NHS24→Ambulance→ED→Admission)

## Cluster Results
![Pathway Bottlenecks](ucd_pathway_clusters.png)

**Interactive Colab Demo**: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1q_NlmHdadoVZNHJ9knrlzZN42mUhMn6n?usp=sharing)

## 🔍 Key Findings
| Cluster | ED Wait | Admission | Deprivation | Policy Action |
|---------|---------|-----------|-------------|---------------|
| 0 | 105 min | 12% | 2.0 | Standard triage |
| 1 | **146 min** | **45%** | **2.5** | **Fast-track** |
| 2 | 118 min | 28% | 2.2 | Monitor |
| 3 | 132 min | 35% | 2.4 | Capacity |

## 🎯 AI4BI Project 1 Alignment
- **K-Means clustering** → Patient pathway types & bottlenecks
- **Sankey-ready heatmap** → Visualisation foundation
- **Deprivation analysis** → Health equity insights
- Scalable to real UCD (2.8M pathways/year)
