# OSTI Publication Analysis
[OSTI](https://www.osti.gov/) provides a [public API](https://www.osti.gov/api/v1/docs) that contains all public research information resulting from DOE research funding. The API returns a variety of metadata including authors, research orgs, subjects, description, and more.

This project proposes to analyze this data in the following potentially approaches:
- Develop graph of co-authors within a specific national lab or across all national labs
    - Find communities of expertise based on co-authorship and subject areas/descriptions
    - Use Graph Convolutional Network (GCN) to infer subject area of document based on metadata
    - Investigate appropriate visualization techniques for large graph data sets (d3.js, networkx, etc.)
- Identify subject areas of expertise/interest to different national laboratories based on publications
- Identify how subject areas/interest change over time
- Generate description/abstract based on subject area(s) using Generative Adversarial Network, [GPT-2](https://github.com/openai/gpt-2), etc.
- Which communities publish most often? Why?
- Are there authors with high degree centrality? Why?
- Other interesting analysis of OSTI data not outlined here yet (Ideas welcomed)
