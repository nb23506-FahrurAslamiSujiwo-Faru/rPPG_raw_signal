# Investigating the Effectiveness of Filter in rPPG Methods Across Various Skin Tones

## Authors
Fahrur Aslami\* · Peeraya Sripian†  
1. Shibaura Institute of Technology, Tokyo, Japan  
\* Corresponding author: nb23506@shibaura-it.ac.jp  
† JSKE Member

## Abstract
This study evaluates the effectiveness of Elliptic, Chebyshev1, and Butterworth filters in remote photoplethysmography (rPPG) signal processing across various skin tones. Using video recordings and fingertip PPG from 19 subjects of diverse ethnic backgrounds, signals were extracted and filtered. Results show that the Elliptic filter yielded the best performance (RMSE: 1.751, SNR: 5.536), followed by Chebyshev1 and Butterworth. Among rPPG methods, ICA and PCA showed the highest accuracy. The study highlights the importance of selecting appropriate filters and methods to ensure accurate heart rate estimation across different skin tones.

## Keywords
Remote Photoplethysmography (rPPG) · Signal Filter · Skin Tone · Heart Rate · ICA · PCA

## Highlights
- **Purpose**: Investigates filter performance (Elliptic, Chebyshev1, Butterworth) on rPPG signal quality.
- **Subjects**: 19 participants, ages 20–32, with diverse skin tones.
- **Methodology**: Facial ROI extracted from video; signals filtered and analyzed for RMSE & SNR.
- **Findings**: Elliptic filter had best performance; ICA and PCA were most accurate rPPG methods.
- **Implication**: Enhancing rPPG robustness across skin tones is crucial for inclusive remote health monitoring.

## Dataset & Preprocessing
- Facial video data recorded using webcam.
- Finger-tip PPG data used as ground truth.
- Face detection and signal extraction via ROI on each frame.
- Applied filters: Butterworth, Chebyshev1, Elliptic.
- Data avaibility is shared here: https://gofile.me/7cVIZ/OJA9wVbfY

## Results
| Filter      | RMSE  | SNR   |
|-------------|-------|-------|
| Elliptic    | 1.751 | 5.536 |
| Chebyshev1  | 1.768 | 3.066 |
| Butterworth | 3.411 | 1.699 |

## Citation
```bibtex
@article{aslami202Xfilter,
  title={Investigating the Effectiveness of Filter in rPPG Methods Across Various Skin Tones},
  author={Aslami, Fahrur and Sripian, Peeraya},
  journal={Journal of [TBD]},
  year={20XX},
  publisher={J-STAGE},
  note={Advance online publication}
}
