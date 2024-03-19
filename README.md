# DS207: Introduction to Natural Language Processing

**Instructor**: [Danish Pruthi](https://danishpruthi.com/)

**Term**: January 2024 – May 2024

**Time**: Tuesdays & Thursdays (10-11:30)

**Venue**: CDS 102

**Credits**: 3:1

**Outline**: This course is a graduate-level introduction to the field of Natural Language Processing (NLP), which involves building computational systems to handle human languages. We interact with NLP systems on a daily basis—such systems answer the questions we ask (using Google, or other search engines), curate the content we read, autocomplete words we are likely to type, translate text from languages we don’t know, flag content on social media that we might find harmful, etc. Such systems are prominently used in industry as well as academia, especially for analyzing textual data. 

**Prerequisites**: The class is intended for graduate students and senior undergraduates. We do not plan to impose any strict requisites on IISc courses that one should have completed to register for this course. However, students are expected to know the basics of linear algebra, probability, calculus, and neural networks. Programming assignments would require proficiency in Python.  



## Announcements 

- Feb 27, 2024: [Assignment #3](https://colab.research.google.com/drive/1LUbHW5wf2l2WjMTtEg4dc5vij8fOJecG) is out now, due on Mar 22, 16:59 IST.

- Feb 11, 2024: Included the [template for the project](project_template).

- Feb 6, 2024: A few broad project directions are [here](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EVUnxcJFuGVFrS9gZf6CFr4B6ttpBMs8CUI04TO76ABitg?e=9dsLT8). 

- Feb 6, 2024: [Assignment #2](https://colab.research.google.com/drive/1ajI3TIiQaPn9o1mnxw8RaOvQnKzyEG_Z?usp=sharing) is out now, due on Feb 23, 16:59 IST.

- Jan 22, 2024: [Assignment #1](https://colab.research.google.com/drive/1G3Ku8c2_iag1koSV1GIXtf-dzfHVb5Ws?usp=sharing) is out now, due on Feb 6, 16:59 IST.

- Jan 20, 2024: The class on Thursday (Jan 25) will happen at EE B-308. 

- Jan 9, 2024: The quiz to assess the pre-requisites would be held in CDS 102 ~~CDS 202~~ (and if required CDS rooms 419 and 208) during the class hours on Thursday (Jan 11). The quiz will be conducted through google forms, so don't forget to carry your laptop or phone. 

## Course Schedule

The course schedule is as follows. This is subject to changes based on student feedback and pace of the instruction. 


| Date     | Topic  | Reading Material | 
| -------- | ------- | ------- | 
| Jan 9  |  [Course introduction](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EaSkggc_yGFNtZV7CDm_recB5XIjSg-8oZTsC35J9tVv7w?e=grXwzl)   | | 
| Jan 11 |  [Text classification](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EVjPYOtuVpdNhtIagdzJ14wBusdaHy_OtI3TMmBmq2Qa3w?e=vrib6a)   + In-class quiz   | [Eisenstein Sec 2-2.1](https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf) | 
| Jan 16 |  [Generative Naive Bayes Classification](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EXAmTCtOPhxClDUqipUgSH0BD8h627S_Vrp5NBKzO8DBfA?e=xc8Mng)  w/ [annotations](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EYNPlbIE72JBuxq_dgGASQQBtYEZ4ygYNz21YPQ85i_odg?e=Hq5UAw) | [Eisenstein Sec 2.2](https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf), [J & M Chapter 4](https://web.stanford.edu/~jurafsky/slp3/4.pdf) |
| Jan 18 | [Discriminative Classifiers & Word Representations](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/ETyb-bLUSndOrMSbmaVYAMwB4gCgtjuIwVZJ0mLoRMgnpg?e=dYG5I7) w/ [annotations](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EbZA43JrNrFNn8vtlbS6UYwB8glRy40hVehE1NbS04gd_A?e=bhfR7A) |  Word2Vec: [1](https://arxiv.org/abs/1402.3722), [2](https://arxiv.org/abs/1301.3781); [J & M Chapter 6](https://web.stanford.edu/~jurafsky/slp3/6.pdf) |
| Jan 23 | [Word Representations + n-gram models](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/ETMHG4KvHHxJhAEZC8m2BYwBUOMyBOoDV7J0Ly3EqpFpsA?e=D8c2Iv)  | [J& M Ch 3](https://web.stanford.edu/~jurafsky/slp3/3.pdf) | 
| Jan 25 | [LMs + Neural Nets](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EZ7lGZ9U63tPjJycu4BDsGgB3WKx05JvCb060BL3UfW4Mw?e=oDxdy3) w/ [annotations](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EQ9zRu8dnoZHhpj80P864gEBqhJlXbM7VphJrAo0apUuDw?e=EdDOZD) | J & M Chapters [3](https://web.stanford.edu/~jurafsky/slp3/3.pdf) & [7](https://web.stanford.edu/~jurafsky/slp3/7.pdf) | 
| Jan 30 | [Tutorial on PyTorch](pytorch_tutorial/pytorch_tutorial.ipynb) |  | 
| Feb 1 | No class |  | 
| Feb 6 | [Neural Nets (RNNs) + Applications](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EWvZtWy1GgRKosWQy3MPl-ABXXpOqA5N2qEGWXbD9jPDig?e=sskRWE)  w/ [annotations](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EVpmEiaW8rdPpPuPTiINNeUBzhS5mtoOVxbo-5tnsez3DA?e=SxRPWU) | [J & M Chapter 7](https://web.stanford.edu/~jurafsky/slp3/7.pdf) | 
| Feb 8 | [RNNs, LSTMs & Attention](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EfIr_d_g9qdGpobmcqeZHUUBJkRCkYy-e3AzoaCQAxvlmA?e=jpoNz7)  | [J & M Chapter 9](https://web.stanford.edu/~jurafsky/slp3/9.pdf) | 
| Feb 13 | [Discussion on Research Projects](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EZZrDz63SnZIgzAskK_cowEBCw0q0AT6LI2FUp-FZBKlRA?e=TNqBrl)  | | 
| Feb 15 | [Attention & Transformers](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EU0e5RKwMhFOsQshQUb92fQBE_FTAFMLBk0ubVDC-4RfIw?e=aXAgTw)  | Transformers [1](https://arxiv.org/abs/1706.03762), [2](https://nlp.seas.harvard.edu/annotated-transformer/), [J & M Ch 10](https://web.stanford.edu/~jurafsky/slp3/10.pdf) | 
| Feb 20 | [Transformers & Pre-training](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EdOfpwFwTThDlAI8CxkMDB0BzupeCIwH-2sOHT7PMcVGfA?e=P3Rvyc)  | [BERT paper](https://arxiv.org/abs/1810.04805) | 
| Feb 22 | [Transformers & Pre-training II](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EYn6mvC4-1FNm9JA1MsvOtwByUG07vfIZGhQ6DGGKBe1rg?e=HsKBiZ)  | [1](https://arxiv.org/abs/1906.04341), [2](https://arxiv.org/abs/1905.10650) | 
| Feb 27  | No Class |  | 
| Feb 29  | [Tokenization](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EZukCbM3kjtIjOF_KCBmMfEBuiqrF1mAlkZRf7Rhsgl3Zw?e=5XdQXs) (by Rankit Kachroo)  | | 
| Mar 5  | [Pre-trained Decoders + Post-Training](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EbdKyliqfqBMvmfxai-rhuMB6dwFiqyO2KHI4_C2RiiTpA?e=HcU9yF) | GPT [1](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf), [2](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) & [3](https://arxiv.org/abs/2005.14165) | 
| Mar 7  | [Tagging + HMMs](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/ESwtmTzRe61Ju-javj1uJeEBQY0uYFLosSZwo7INQTlezA?e=iAlzuX) | [Notes from Michael Collins](https://www.cs.columbia.edu/~mcollins/hmms-spring2013.pdf) | 
| Mar 12  | CRFs ([class work](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EbvIZsb5otFJhJ0G6DkrOeoBh4jNlbRslvPRzaLG6Scu4w?e=tS6GC4))| [A tutorial on CRFs](https://arxiv.org/abs/1011.4088) |
| Mar 14  | Guest Lecture (by Saurabh Garg; CMU) | |
| Mar 19  | No class | |
| Mar 21  | Fairness, biases & ethical considerations | |
| Mar 26  | AI X Community (by Shachi Dave; Google Research) | |
| Mar 28  | Multilinguality (by Prof. Monojit Choudhury; MBZUAI)) | |
| Apr 2  | External guest lecture | |
| Apr 4  | External guest lecture | |
| Apr 9  | Poster Session #1 |  |
| Apr 11  | Poster Session #2 |  |
| | | | 

## Course Evaluation

The evaluation comprises 3 programming assignments (3 x 15% = 45% of the overall score), 2 exams (2 x 10% of the overall grade), and final group course project (which is worth 35% of the overall grade).  


The two exams aim to evaluate the student’s learning acquired through lectures and assignments. One of these two exams would be administered towards the middle of the semester and the second one towards the end. Each exam is worth 10% of the grade. 


### Projects 

The course project constitutes 35% of the overall score, where students—in groups of three—get a chance to apply the acquired knowledge for an application of their choice. Projects would typically involve human languages and deep learning. The project includes three milestones: (1) initial proposal (which will require a rough action plan and associated timelines); (2) a mid-term report and (3) a final report.  Towards the end of the course, students would get a chance to showcase their research through poster presentations. 

Each team would get three late days for projects, no extensions will be offered (please don't even ask). After your late days expire, you can still submit your project but your obtained score would be divided by 2 if submitting after 1 day, and will be divided by 4 if submitting after 2 days. No submissions would be entertained after that.


Some project directions are availabe [here](https://indianinstituteofscience-my.sharepoint.com/:b:/g/personal/danishp_iisc_ac_in/EVUnxcJFuGVFrS9gZf6CFr4B6ttpBMs8CUI04TO76ABitg?e=9dsLT8). Please note that these directions are only suggestive, students should not limit their explorations to just these directions.

**New:** Included the [template for the project](project_template) that also includes a few guidelines.

**Important dates**: 

- ~~**Feb 13, 16:59**~~ **Feb 15, 16:59** Project proposals due 
- **Mar 14, 16:59** Mid-term report due
- **Apr 16, 16:59** Final project reports to be submitted


### Assignments 

The three programming assignments will involve building systems for (1) text classification and learning word representations; (2) language modeling; (3) TBD (possibly machine translation and/or named entity recognition). The assignments will be implemented using interactive Python notebooks intended to run on Google’s Colab infrastructure. This allows students to use GPUs for free and with minimal setup. The notebooks will contain instructions interleaved with code blocks for students to fill in.

These assignments are meant to be solved individually. For a total of three assignments, you would get **three late days**, no extensions will be offered (please don't even ask). There are no restrictions on how the late days can be used, for example, you can use all the three late days for one assignment. If you run out of late days, you can still submit your assignment, but your obtained score would be divided by 2 if submitting after 1 day, and by 4 if submitting after 2 days. No submissions would be entertained after that.

**Important dates**: 
- [Assignment #1](https://colab.research.google.com/drive/1G3Ku8c2_iag1koSV1GIXtf-dzfHVb5Ws?usp=sharing) (Out: Jan 22. Due: Feb 6, 16:59)
- [Assignment #2](https://colab.research.google.com/drive/1ajI3TIiQaPn9o1mnxw8RaOvQnKzyEG_Z?usp=sharing) (Out: Feb 6. Due: Feb 23, 16:59)
- [Assignment #3](https://colab.research.google.com/drive/1LUbHW5wf2l2WjMTtEg4dc5vij8fOJecG) (Out: Feb 27. Due: Mar 22, 16:59)


## Discussions & (Anonymous) Feedback

We will use Teams for all discussions on course-related matters. Registered students should have received the joining link/passkey.

If you have any feedback, you can share it (anonymously or otherwise) through this link: http://tinyurl.com/feedback-for-danish


## Teaching Staff

1. Debarpan Bhattacharya (OH: Thursdays 3 PM - 4 PM; Venue: CDS 208; [notify them](mailto:debarpanb@iisc.ac.in?subject=Will%20visit%20office%20hours%20this%20week)) 
2. Kinshuk Vasisht (OH: Wednesdays 10 AM - 11 AM; Venue: CDS 208; [notify them](mailto:kinshukv@iisc.ac.in?subject=Will%20visit%20office%20hours%20this%20week))
3. Navreet Kaur (OH: Tuesdays 4 PM - 5 PM; Venue: CDS 208; [notify them](mailto:navreetkaur@iisc.ac.in?subject=Will%20visit%20office%20hours%20this%20week))
4. Nicy Scaria (OH: Tuesdays 11:30 AM - 12:30 PM; Venue: CDS 208; [notify them](mailto:nicyscaria@iisc.ac.in?subject=Will%20visit%20office%20hours%20this%20week))
5. Rankit Kachroo (OH Wednesdays 4 PM - 5 PM; Venue: CDS 208; [notify them](mailto:rankitk@iisc.ac.in?subject=Will%20visit%20office%20hours%20this%20week))
6. Danish Pruthi (OH: Fridays 10 AM - 11 AM; Venue: CDS 401; [notify them](mailto:danish@hey.com?subject=Will%20visit%20office%20hours%20this%20week))


## Reference Books

1. [Speech and Language Processing](https://web.stanford.edu/~jurafsky/slp3/) (3rd ed. draft) by Dan Jurafsky and James H. Martin
2. [Introduction to Natural Language Processing](https://github.com/jacobeisenstein/gt-nlp-class/blob/master/notes/eisenstein-nlp-notes.pdf) by Jacob Eisenstein 
3. Neural Network Methods for Natural Language Processing by Yoav Goldberg


