---
Title: Plan of work
Date: 07.02.2018
---

# Open Data Alliance: Public Records Analysis, Governance, and Standards

**Description**   
My sponsors for the project are David Doyle and Will Saunders. David is from the City of Seattle, and Will is from the State of Washington. I will also be working closely with David Christiansen, from Seattle Public Libraries. The project I would hope to undertake is to collect, collate, and share data about public records requests (PRRs).

My partner on this project is Leslie Denning, who will be working in parallel with me to complete the 'charter' portion of the project. We intend the charter to be a body of recommendations for intra-governmental data sharing.

Across Washington, there are several institutions of different sizes that wish to become more data-driven with regard to their public records. They want to better understand how they can efficiently and effectively address customer needs, without opening themselves up to unnecessary risk. The Open Data Alliance (ODA), a project started by Will Saunders, is in the nascent stages of bringing institutional partners together to share knowledge about open data, but they need some assistance formalizing their meeting structure and keeping participant interest.

The goal of the project is to understand the kinds of records requests that state/city/country government offices get, and with what frequency. If we know that there is a broad interest in a topic (or series of topics), we can productively and preemptively make disclosures for our citizens. This saves time; citizens won't have to submit as many requests for data. In broad strokes, this entails:

- Understanding sources of data, and producing governance and standards around data
- Analysis of trends in the data sources

The ultimate outcome of this project is to use data analysis help reinforce participation in the ODA. Insight from the data cleaning process will be used in the formulation of a good faith agreement, a charter document that ODA members will be expected to sign.

**Goals**     

There has already been some cursory work using various natural language processing (NLP) techniques to mine Seattle public records for information. I hope to achieve the following with my work:

- Expand on existing code for generating word clouds from public records data, porting it from R to Python

- Use Latent Dirichlet Allocation (LDA) to model topics within the corpus of text

- Use other NLP packages to determine cosine similarity between vocabulary items, uncovering whether different words/senses of words are used to mean similar things within a record request

- Export all of this data to Tableau for easy manipulation and interaction for end-users, with an eventual goal of making a Tableau Public sheet for staff or members of the public to use

- *Stretch goal*: If there's time, see if it possible to use topic modeling in conjunction with machine learning to predict whether a request is associated with a particular department

**Deliverables**    

Related to the goals above, this project will produce the following items as output:

- A commented jupytr notebook containing the code I used to clean and structure the data

- A Tableau notebook containing visualizations of trends in the data, in order to understand the 'aboutness' of PRRs across Western Washington

- A charter for future members of the Open Data Alliance, helping them understand best practices for working with their data

*Interim*

Leslie and I will document the work we do on a weekly basis to ensure that people can follow what we are working on. We will also track our progress using Trello, and regularly communicate with our project leads via Slack.

Managing deliverables will be based on understanding the possible data sources that the State and City have access to. After dialogue with intra-governmental stakeholders and a survey of the number and complexity of the data sources, we can start cleaning, standardizing, and analyzing data.

Since we are working with a number of different data sources in different forms, I will be creating a data dictionary that identifies metadata for each field in each data source, as well as how these data are transformed throughout the cleaning process so they can be analyzed properly. An outline of this work will be contained in the jupytr notebook I provide at the end of the project.

The interim deliverables for the project will include a collated series of interviews with stakeholders; a blog post detailing the outcomes of these interviews and how they will inform our analyses; and cursory visual and numerical analysis of curated data sources.

*End of project*

The data-related deliverable for the project includes a visualization of trends in the data via a Tableau project file, supported by a series of files (probably CSVs) that will contain mappings (on a jurisdiction or department-level) of the relationship between a particular word or noun-phrase and its representation as a vector. These files will be generated by the code written in the jupytr notebook.

It will also include a body of standards and guidelines for the governance of open government data, in the form of a charter. The charter will be influenced by the outcome of the work with data--we can't make recommendations about what the data should look like, or how institutions can work with it, without understanding the travails that come from working with disparate data sources.

**Plan for Sustainability**      

At the end of the project, I will submit well-documented code and a standards document, to ensure that people that might continue the project can pick up where I left off. All of the code I write will be published on both the ODL GitHub repo, as well as on my personal GitHub repo. Other than the Tableau platform, I will not use any proprietary software in the development of my analysis. Upon completion, everything I write in the course of this project will be available under a MIT license, so institutions of all sizes can use my code without purchasing a license.

**Milestones**    

In broad strokes, these are the different things we intend to undertake as part of this project.

Weeks 1-2: Set up interviews; collect datasets; conduct interviews; project planning and logistics
Weeks 3-4: Conduct interviews; clean data; conduct cursory analyses; write blog post
Weeks 5-6: Start work on reproducible visualizations; review interview data--understand and articulate needs of new ODA signatories
Weeks 7-8: Draft of final projects (visualizations/backend code/charter); final blog post; structure/goals for next ODA meeting

**TODOs**

Add line-item `Issues` that support the completion of milestones
