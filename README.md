# Distilling Large Language Models using Skill-Occupation Graph Context for HR-Related Tasks
This repository is the implementation for the paper "[Distilling Large Language Models using Skill-Occupation Graph Context for HR-Related Tasks](https://arxiv.org/pdf/2311.06383)"

![alt text](https://github.com/megagonlabs/rjdb/blob/main/figs/overview.png)

---
## 🛠️ **Dataset Construction Process**

### 1. **Skill-Occupation Graph Creation**
- **Base Graph:** Started with the publicly accessible **Skill-Occupation Graph** from **[DICE](https://www.dice.com/)**.  
- **Extension:** Expanded using job titles from the **[US Bureau of Labor Statistics (BLS)](https://www.bls.gov/)**.  
- **Skill Generation:** Used **GPT-4** to infer required skills for each job title.  
- **Skill Filtering:** Applied statistical filtering using aggregated insights from **proprietary Indeed skill-occupation graphs**.

### 2. **Sample Generation**
- Utilized **GPT-4** to generate resumes and job descriptions guided by the refined Skill-Occupation Graph.

---

## 📝 **Data Source Attribution**

This dataset incorporates data from the following sources:

1. **DICE Skill-Occupation Graph**  
   - Source: [kaggle](https://www.kaggle.com/datasets/PromptCloudHQ/us-technology-jobs-on-dicecom)  
   - License: **[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)**

2. **US Bureau of Labor Statistics (BLS)**  
   - Source: [BLS Website](https://www.bls.gov/)  
   - License: **Public Domain**

3. **Indeed Skill-Occupation Graph (Statistical Insights)**  
   - Source: [Indeed Hiring Lab](https://www.hiringlab.org/)  
   - License: **Proprietary Data**

**Please refer to the respective sources for detailed licensing terms.**

---

## 🤖 **AI-Generated Content Disclaimer**

Parts of this dataset, including resume and job description samples, were **generated using OpenAI's GPT-4 model**.  
- The content adheres to OpenAI's [Usage Policies](https://openai.com/policies/terms-of-use).  
- Outputs were reviewed and refined to align with the dataset's objectives.  
- No prohibited use cases or violations of OpenAI's terms are present in this dataset.

Please ensure compliance with OpenAI's policies if redistributing or modifying this dataset.

---

## 🧠 **Usage Guidelines**

- Use this dataset for **research and educational purposes**.  
- Commercial use may require additional permissions depending on source licenses.  

---

## ⭐ **Citation**

If you would like to cite our work, the bibtex is:

    @article{pezeshkpour2023distilling,
    title={Distilling Large Language Models using Skill-Occupation Graph Context for HR-Related Tasks},
    author={Pezeshkpour, Pouya and Iso, Hayate and Lake, Thom and Bhutani, Nikita and Hruschka, Estevam},
    journal={arXiv preprint arXiv:2311.06383},
    year={2023}
    }

---

## 📜 **Disclosure**
Embedded in, or bundled with, this product are open source software (OSS) components, datasets and other third party components identified below. The license terms respectively governing the datasets and third-party components continue to govern those portions, and you agree to those license terms, which, when applicable, specifically limit any distribution. You may receive a copy of, distribute and/or modify any open source code for the OSS component under the terms of their respective licenses, which may be CC license and Apache 2.0 license. In the event of conflicts between Megagon Labs, Inc., license conditions and the Open Source Software license conditions, the Open Source Software conditions shall prevail with respect to the Open Source Software portions of the software. You agree not to, and are not permitted to, distribute actual datasets used with the OSS components listed below. You agree and are limited to distribute only links to datasets from known sources by listing them in the datasets overview table below. You are permitted to distribute derived datasets of data sets from known sources by including links to original dataset source in the datasets overview table below. You agree that any right to modify datasets originating from parties other than Megagon Labs, Inc. are governed by the respective third party’s license conditions. All OSS components and datasets are distributed WITHOUT ANY WARRANTY, without even implied warranty such as for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE, and without any liability to or claim against any Megagon Labs, Inc. entity other than as explicitly documented in this README document. You agree to cease using any part of the provided materials if you do not agree with the terms or the lack of any warranty herein. While Megagon Labs, Inc., makes commercially reasonable efforts to ensure that citations in this document are complete and accurate, errors may occur. If you see any error or omission, please help us improve this document by sending information to contact_oss@megagon.ai.
