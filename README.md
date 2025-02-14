# BMED365: Computational imaging, modeling and AI in biomedicine (2025)


<img src="./assets/GPT-MedAI.png" width="500"> <br>
If you have a subscription to [ChatGPT Plus](https://openai.com/blog/chatgpt-plus), you can also try out the [**Medical AI Assistant (UiBmed - ELMED219 & BMED365)**](https://chat.openai.com/g/g-d90dfN17H-medical-ai-assistant-uibmed-elmed219-bmed365) and see if you can get it to answer some of your questions.

----

The [course](https://www.uib.no/en/course/BMED365) is offered by the [Department of Biomedicine](https://www.uib.no/en/biomedisin) (UiB) in collaboration with the [Department of Computer science, Electrical engineering and Mathematical sciences](https://www.hvl.no/en/about/management/faculty-of-engineering-and-science/department-of-computer-science-electrical-engineering-and-mathematical-sciences-ny-side) at the Western Norway University of Applied Sciences (HVL), and the Medical AI group at [Mohn Medical Imaging and Visualization Center](https://mmiv.no) (MMIV).

<img src="./assets/elmed219_logo.png" width="700"> <br>

The objective and content of the course address: The computational mindset, imaging, modeling, machine learning, and AI in future medicine, as well as ethical and regulatory aspects of AI. 

The course, consisting of **two blocks** (1st block is joint with ELMED219), is a guided "journey" with a hands-on component through selected computational modeling techniques within biomedical and clinical applications. Examples, demonstrations, and tasks will be related to in vivo imaging (MRI) and segmentation, biomarkers and prediction, [network analysis](https://pmc.ncbi.nlm.nih.gov/articles/PMC11321866) ("patient similarity networks"), [multimodal data](https://www.nature.com/articles/s41591-022-01981-2), as well as large language models ("[foundation models](https://en.wikipedia.org/wiki/Foundation_model)") within medicine and health. 

Throughout the course, students will use principles and modern tools for data analysis, machine learning, and generative AI (e.g. [ChatGPT](https://chatgpt.com), [Gemini](https://gemini.google.com), [Claude](https://claude.ai)) within medical applications. The course will give the students an introduction to Python and [Jupyter notebooks](https://docs.jupyter.org), use of [AI-assisted coding](https://github.com/resources/articles/ai/ai-coding-tools), and the "cloud" for access to open data, calculations, and knowledge, as well as insight into and rationale for "open science" and "reproducible research". 

The **second block** will focus on computational biomedical imaging (MRI, IMC, ...) and modelling. 

Between the first and second blocks, the students will **work on their project, defined by the student herself** within the scope of the course. 

All course material is openly available on this GitHub repository. (See also [ELMED219](https://github.com/MMIV-ML/ELMED219))


- This repository contains most of the course material. Students enrolled in the course will also find some practical information at [MittUiB](https://mitt.uib.no/courses/50785).

-  For **academic questions** about the course, contact course coordinator [Arvid Lundervold](https://www.uib.no/en/persons/Arvid.Lundervold) (UiB).

- For **practical or administrative inquiries**, contact the Studies Section at the Department of Biomedicine at studie.biomed@uib.no


<img src="./assets/cc_by_sa.png" width="75"> The content for the course is offered with a <b><a href="http://creativecommons.org/licenses/by-sa/4.0">CC BY-SA 4.0</a></b> license unless otherwise stated.

--------

# Tentative time schedule

(See also [here](https://mitt.uib.no/calendar?include_contexts=course_50785#view_name=agenda&view_start=2024-12-29))

| **TIME**                    | ACTIVITY                                                                               |
| --------------------------- | -------------------------------------------------------------------------------------- |
| **WEEK 1:<br> Fri, Jan 3**   |                                                                                        |
| _On your own_               | Get an [overview of the course](https://docs.google.com/presentation/d/e/2PACX-1vRs-_1Tr_iXzIfy8207VlKuBjr_hCIpQqrI65YM9Q6TcQMUt4R-4aPVPzfL6fwDkmB8UkcPyfyiL9TU/pub?start=false&loop=false&delayms=3000); installation of software and/or test out Google Colab   |
|                             | Follow the instructions at [**setup.md**](./setup.md) and  [MittUiB](https://mitt.uib.no/courses/50716)                |
| **WEEK 2:<br> Mon, Jan 6**   |                                                                                        |
| 10:15-14:00<br>BB Hist 1    | Information [About the course](https://docs.google.com/presentation/d/e/2PACX-1vRs-_1Tr_iXzIfy8207VlKuBjr_hCIpQqrI65YM9Q6TcQMUt4R-4aPVPzfL6fwDkmB8UkcPyfyiL9TU/pub?start=false&loop=false&delayms=3000) <br> Motivation lectures<br>&nbsp;- [Computational medicine](https://docs.google.com/presentation/d/e/2PACX-1vQdrVW4qt8doyqbxRiZwZNQmGUN1qfML7wP-jYxp4aOJI5B6g8wn4HYNjcJ18w93IUzQBg4yMngsbNl/pub?start=false&loop=false&delayms=3000) <br>&nbsp;- [Medical AI]()  <br> &nbsp;- [SW-installation](./setup.md)<br> &nbsp;- [Tools](https://docs.google.com/presentation/d/e/2PACX-1vTodZumHibZQgoZVaGnSn6K6Swisbz9NA2PHIdLvp95vByPLrdYbv23CDM2B1HLU9tKC8ofhDzPeetg/pub?start=false&loop=false&delayms=3000) 
|                             | *Arvid and Alexander Lundervold*                                                                     |                                |
| **Wed, Jan 8**    |                                                                                        |
| 14:15-16:00<br>BB Hist 1    | [AI-driven innovation in healthcare](AI-innovation.md) & [About the course project](./Project)                |
|                             | *Arvid and Alexander Lundervold*                                                                     |                                |
| **Fri, Jan 10**    |                                                                                                 |
| 10:15-11:30<br>BB Hist 1    | [LAB 0: Introduction to theory and tools for machine learning](./Lab0-ML)        |
|                             | *Alexander Lundervold*                                                      |
| 11:45-13:00<br>BB Hist 1    | [LAB 1: Network science and patient similarity networks (PSN)](./Lab1-NetworkSci-PSN)        |
|                             | *Arvid Lundervold*                                                                     |
| **WEEK 3:<br>Tue, Jan 14**    |                                                                                       |
| 09:15-13:00<br>BB Hist 1    | [AI-assisted innovation cont.](AI-innovation.md) & Python programming; recap of Lab0, Lab1     |
|                             |  *Arvid and Alexander Lundervold*                                                                     |
| **Fri, Jan 17**   |                                                                                                  |
| 08:15-13:00<br>BB Hist 1    |  [Lab 2: Deep learning](./Lab2-DL)                                                     |
|                             | *Arvid Lundervold*                                        |
| **WEEK 4:<br>Team project**  |  Joint with BMED365 - Working on the course project in interdisciplinary teams (during the week)  |
| **Tue, Jan 21**   |                                                                                        |
| 09:15-12:00<br>BB Hist 1    | [Lab 3: Generative AI and Large Language Models](https://www.dropbox.com/scl/fi/5dt9xj09935kyehqmjrwi/ELMED219-2025-3-LLMs.pdf?rlkey=mfyt91chrjz151bsj0gm6kank&st=ehqnnbg9&dl=1)                           |
|                             | *Alexander Lundervold*                                                                     |
| 13:15-16:00<br>BB Hist 1    | Meet-up for team project brainstorming and coaching                                    |
|                             | *Arvid and Alexander Lundervold*                                                              |
|  **WEEK 5:<br>Tue, Jan 28**  |                                                                                        |
| 08:15-10:00<br>BB Hist 1    | Project presentations by team  (jointly with ELMED219)                                  |
|                             | *Arvid and Alexander Lundervold*                                                      |
| **Thu, Jan 30**   |                                                                                        |
| 16:00                       | Deadline for the Team Project Report - joint with ELMED219 (hand in via MittUiB)        |
| **Fri, Jan 31**   |                                                                                        |
| 08:15-10:00                 | Motivation lecture - [Computational imaging](https://docs.google.com/presentation/d/e/2PACX-1vRN7-O_W_fPgto-JMJZdl4kM1KnLKWhATgUSjpmz0e8RwjC2yYi9o_9Kz92RxpacRLTT3fMviDOMUmf/pub?start=false&loop=false&delayms=3000)      |
|                             | *Arvid Lundervold*                                                                 |
| **WEEK 6:<br>Mon, Feb 03<br>- Fri, Feb 07** |  [Individual project](./Individual-project) during the week  |
| **WEEK 7:<br>Mon, Feb 10<br>- Fri, Feb 14** |  [Individual project](./Individual-project) during the week |
| **WEEK 8:<br>Mon, Feb 17**   |    |
| 08:15-10:00 | [Lab 4: Computational imaging](./Lab4-Comp-Imag)    |
|                             | *Arvid Lundervold*                                        |
| **Wed, Feb 19** |   |
| 08:15-12:00 | [Individual project](./Individual-project) presentation ("digital speed poster") Upload poster (only) to MittUiB the day before |
| **Fri, Feb 21** |     |
| 14:15-16:00 | Motivation lecture - Computational modeling  |
|                             | *Arvid Lundervold*                                        |
| **WEEK 9:<br>Mon, Feb 24**|     |
| 08:15-10:00 |  [Lab 5: Computational modeling](.) |
|        | _Arvid Lundervold_ |
| **Fri, Feb 28** |  |
| 08:15-10:00 | Summing up / reflections     |
|                             | *Arvid Lundervold*                 |
| **WEEK 10:**  |  |
| **Mon, Mar 03** |[**Home exam**](./Exam#readme): Duration: 3 hours;  <br>Assignment is handed out: 03.03.2025, 09:00; <br>Submission deadline: 03.03.2025, 12:00; <br>Examination system: Inspera Digital exam


### Previous versions of the BMED365 course
_"Computational imaging, modelling and AI in biomedicine"_

| **Year**                    | Link             |
| --------------------------- |  --              | 
|2024 |https://github.com/MMIV-ML/BMED365-2024 |


### Previous versions of the ELMED219 course
_"Artificial intelligence and computational medicine"_

| **Year**                    | Link             |
| --------------------------- |  --              | 
|2024 |https://github.com/MMIV-ML/ELMED219-2024       |
|2023 |https://github.com/MMIV-ML/ELMED219-2023       |
|2022 |https://github.com/MMIV-ML/ELMED219-2022  |
|2021 |https://github.com/MMIV-ML/ELMED219-2021  |
|2020 |https://github.com/MMIV-ML/ELMED219-2020  |
|2019 |https://github.com/MMIV-ML/ELMED219x-2019 |

### Previous versions of the BMED360 course
_"In Vivo Imaging and Physiological Modelling"_

| **Year**                    | Link             |
| --------------------------- |  --              | 
|2021 |https://github.com/computational-medicine/BMED360-2021 |
|2020 |https://github.com/computational-medicine/BMED360-2020 |


