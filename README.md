# Vowel phonemes Analysis and Classification by means of OCON rectifiers Deep Learning Architectures
*Stefano Giacomelli - Master Degree Thesis in Sound Technology (A.Casella Conservatory, L'Aquila, Abruzzo, Italy)*

updated during 1st year of PhD in Information and Communication Technologies - DISIM Dept. of University of L'Aquila (2023-2024)

## TO-DO list
### Feature extraction
- LPC formants estimation (Parselmouth VS PyTorch LPA implementation)
- New Features "backbone" processing (via pseudo-NAS)
### Complex MLP-OCON model
- Test other Datasets (PB, TIMIT, UCLAPhonetics, AudioSet etc.)
- Learning assessment "scaling coefficients"

## REFERENCES
```
@INPROCEEDINGS{Acce2406:OCON,
AUTHOR="Stefano Giacomelli and Claudia Rinaldi and Marco Giordano",
TITLE="The {OCON} Model: An Old but Gold Solution for Distributable Supervised Classification",
BOOKTITLE="2024 IEEE Symposium on Computers and Communications (ISCC):
29th IEEE Symposium on Computers and Communications - workshop on
Next-Generation Multimedia Services at the Edge: Leveraging 5G and Beyond (NGMSE2024)",
ADDRESS="Paris, France",
PAGES=7,
DAYS=25,
MONTH=jun,
YEAR=2024,
KEYWORDS="Artificial Intelligence (AI); Deep Learning (DL); Neural Networks (NNs);
Digital Signal Processing (DSP); Speech Communication; Phonetics",
ABSTRACT="This paper introduces to a structured application of the One-Class approach and the One-Class-One-Network
model for supervised classification tasks, specifically addressing a vowel phonemes classification case study within
the Automatic Speech Recognition research field. Through pseudo-Neural Architecture Search and Hyper-Parameters
Tuning experiments conducted with an informed grid-search methodology, we achieve classification accuracy comparable
to nowadays complex architectures (90.0 - 93.7%). Despite its simplicity, our model prioritizes generalization of
language context and distributed applicability, supported by relevant statistical and performance metrics."}
```
