## [Most Dominant Metabolomic Biomarkers Identification for Lung Cancer](https://www.sciencedirect.com/science/article/pii/S2352914821002872)
[![Author](https://img.shields.io/badge/author-utshabkg-red)](https://github.com/utshabkg/)
[![Co Author](https://img.shields.io/badge/co--author-fuad021-yellow)](https://github.com/fuad021/)
[![Co Author](https://img.shields.io/badge/co--author-NahianAlindo-yellow)](https://github.com/NahianAlindo/)
[![MIT](https://img.shields.io/badge/license-MIT-5eba00.svg)](https://github.com/utshabkg/LungCancer_Biomarker/blob/master/LICENSE)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-blue.svg?style=flat)](https://github.com/utshabkg/LungCancer_Biomarker/)
[![Stars](https://img.shields.io/github/stars/utshabkg/LungCancer_Biomarker?style=social)](https://github.com/utshabkg/LungCancer_Biomarker/stargazers)

<p align="justify">Metabolomic biomarkers play a vital role in the early identification and prediction of cancer. It is possible to save numerous lives if biomarkers are used to assist medical providers in diagnosing their patients faster. Many researchers have been trying to identify the crucial biomarkers in the early diagnosis of diseases. This paper presents several steps divided into two phases for determining the most important metabolomic biomarkers in the blood for lung cancer prediction using Plasma and Serum samples. We used the Shapiro–Wilk Test, Bartlett’s Test, Levene’s Test, Student’s t-Test, and Kruskal–Wallis Test in the first phase to determine the potential biomarkers. Recursive Feature Elimination with Random Forest was used to identify the final most dominant metabolomic biomarker at the second phase. Lastly, we ended with Ridge Classifier and XGBoost Classifier to assess the consistency of our approaches. Despite the declining number of metabolites up to a greater level, our prediction accuracy was 100% and 90.91% for Plasma and Serum samples, respectively which is higher than the state-of-the-art method. Finally, we made some analysis using the most dominant metabolites that can serve as a source of inspiration for our work.</p>


### Setup the Project after git clone.
1. Open the directory: <b>~/final and best approach/</b>. You will find mainly 2 approaches I have applied.
2. First, we go with <b>Approach 1</b>.
3. Read and run these notebooks one after another by this sequence:
    - <b><i>plasma_test_final.ipynb</i></b>
    - <b><i>serum_test_final.ipynb</i></b>
    - <b><i>specific_metabolics_accuracy_final.ipynb</i></b>
4. Now it's time for <b>Approach 2</b>.
5. Read and run this notebook: <b>exploratory_analysis.ipynb</b>.
6. For the mixed up approach, which have been added as a merge(apporaches 1 and 2), simply run the notebook: <b>mixed_up.ipynb</b>.

Thank you. Please let us know, if you find any mistake or way of development in this repo. Cheers!

### Read our [Published Journal Research Paper](https://www.sciencedirect.com/science/article/pii/S2352914821002872) based on this repository. Cite if this helps your work:
```
    @article{ghosh2022most,
    title={Most dominant metabolomic biomarkers identification for lung cancer},
    author={Ghosh, Utshab Kumar and Al Abir, Fuad and Rifaat, Nahian and Shovan, SM and Sayeed, Abu and Hasan, Md Al Mehedi},
    journal={Informatics in Medicine Unlocked},
    volume={28},
    pages={100824},
    year={2022},
    publisher={Elsevier}
    }
```
