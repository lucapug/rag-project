This repository is a quickstart to setup Mage ai orchestrator plus Elastic Search (this last one to create a vector db) all in a multi-container portable environment. This working environment is used to experiment with the content of [Module 5 - orchestration of LLM-zoomcamp 2024 cohort](https://github.com/DataTalksClub/llm-zoomcamp).

In particular, a beta feature named RAG pipeline from Mage AI is used, offered to the learners of the course.

The RAG pipeline is made of two components: Data preparation and Inference

only the first component is experimented with in the course.

##### Notes on the execution

First, once launched the working environment with script.sh, th execution of the following steps is done throgh the Mage GUI.

We create a new pipeline of type RAG, and the code corresponding to the blocks is under rager folder.

In particular, runic_oblivion.py under data_loaders serves for the data ingestion from a github web address where documents.json is archived.

In transformers folder, radiant_photon.py is responsible of chunking the documents.
