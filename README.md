# Open Research Assistant
An automated tool for discovering insights from research papaer corpora

![Screenshot of the home page of the Open Research Assistant Tool](https://github.com/ai8hyf/OpenResearchAssistant/blob/main/assets/Screenshot-search-home.png)
![Screenshot of the search result page of the Open Research Assistant Tool](https://github.com/ai8hyf/OpenResearchAssistant/blob/main/assets/Screenshot-search-result.png)

## Problems to solve
- Exponential growth of papers outpacing human review capacity
- Challenges in retrieving papers from rapidly evolving domains
- Inability to construct and contrast arguments across multiple papers
- Propagation of problematic claims due to incomplete reviews

## Our approach to accelerate the paper searching process
We process each documents once and index the extracted key points for search. The users only need to read the full documents that are almost guaranteed to contain relevant information. This saves both users' time and compute. Each user interaction is only a simple embedding and cosine similarity match (maybe rarank).

![High level system architecture of the Open Research Assistant Tool](https://github.com/ai8hyf/OpenResearchAssistant/blob/main/assets/openra-architecture.png)

## Datasets
- [ACL 2023 Paper in Markdown after OCR](https://huggingface.co/datasets/yifeihu/ACL-23-Paper-OCR-Markdown) - This dataset contains 2150 papers in markdown format from Association for Computational Linguistics (ACL) 2023

## What's coming next?
- Clean up the current code base and upload the key components (frontend, backend, data pipeline)
- Buy a domain and design a landing page
- Host a public demo (GCP credit secured)
- Publish the first draft of technical report / paper
- Process ACL, NAACL, EMNLP, EACL papers (2022, 2023, 2024) for the public demo
- Release the first public dataset
- Publish the first “delve-deep” report
- ... (I have a long list)

## How to contribute/collaborate
Please allow me to release all the draft frontend and backend code. Then I will make a plan to gather all the efforts from the open-source community.

## About the author
My name is Yifei Hu, a Ph.D. Candidate at Purdue University. I study NLP and HCI. You can follow me on X: [https://x.com/hu_yifei](https://x.com/hu_yifei)
