# Patient-Clustering-and-Software
This tool provides a user-friendly interface for sorting patients into groups based on proximity and medical care needs.

#Algorithm main ideas:
Given a table with names, addresses and medical care needs (coded 0 if no needs and 1 if needs), we're looking to create groups to plan nurses' shifts. 
Each  group $G$ is defined as follows: 
- Two people $a$ and $b$ are in $G$ if and only if the time to go from $a$ to $b$ is less than a parameter, noted here as "walk_time".
- This gives us $n$ groups $G_1,...,G_n$.
- We rank each group $G_1,...,G_n$ one below the other in relation to the number of patients requiring medical care in each group.

![Gradio Interface Screenshot](screenshot_demo.png)

