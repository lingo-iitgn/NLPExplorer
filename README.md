# NLPExplorer: Exploring the Universe of NLP Papers

Understanding the current research trends, problems, and their innovative solutions remains a bottleneck due to the ever-increasing volume of scientific articles. In this paper, we propose NLPExplorer, a completely automatic portal for indexing, searching, and visualizing Natural Language Processing (NLP) research volume. NLPExplorer presents interesting insights from papers, authors, venues, and topics. In contrast to previous topic modelling based approaches, we manually curate five course-grained non-exclusive topical categories namely Linguistic Target (Syntax, Discourse, etc.), Tasks (Tagging, Summarization, etc.), Approaches (unsupervised, supervised, etc.), Languages (English, Chinese, etc.) and Dataset types (news, clinical notes, etc.). Some of the novel features include a list of young popular authors, popular URLs and datasets, list of topically diverse papers and recent popular papers. Also, it provides temporal statistics such as yearwise popularity of topics, datasets, and seminal papers. To facilitate future research and system development, we make all the processed dataset accessible through API calls.

NLPExplorer is available at: https://lingo.iitgn.ac.in/nlpexplorer/  

This repository hosts the dataset used in "NLPExplorer: Exploring the Universe of NLP Papers" accepted at 42nd European Conference on Information Retrieval 2020 (ECIR 2020) in demonstration track.  

The dataset is build using the data provided at ACL Anthology website. The current data snapshot on this page is updated till 2019.  


----------

The data has been split into smaller json files. To combine the data please use the cat and piping commands on Linux systems as follows -

```
cat filepPrefix* > finalFilename.json

# For example to combine the data of the papers from papers directory, use the following command:
# cat papers* > fullPapers.json
```


--------
### Paper - [Link](https://link.springer.com/chapter/10.1007/978-3-030-45442-5_61)
### Presentation - [Link](https://www.youtube.com/watch?v=U2yWvnFx624)

For any queries, feel free to reach out to [us](mailto:singh_shruti@iitgn.ac.in).

-------
### Cite

```@inproceedings{parmar2020nlpexplorer,
  title={NLPExplorer: exploring the universe of NLP papers},
  author={Parmar, Monarch and Jain, Naman and Jain, Pranjali and Sahit, P Jayakrishna and Pachpande, Soham and Singh, Shruti and Singh, Mayank},
  booktitle={European Conference on Information Retrieval},
  pages={476--480},
  year={2020},
  organization={Springer}
}
