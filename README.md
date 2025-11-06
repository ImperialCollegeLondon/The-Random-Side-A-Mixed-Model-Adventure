<!--
This README template is designed with dual purpose.

It should help you think about and plan various aspects of your
exemplar. In this regard, the document need not be completed in
a single pass. Some sections will be relatively straightforward
to complete, others may evolve over time.

Once complete, this README will serve as the landing page for
your exemplar, providing learners with an outline of what they
can expect should they engage with the work.

Recall that you are developing a software project and learning
resource at the same time. It is important to keep this in mind
throughout the development and plan accordingly.
-->

<!-- Your exemplar title. Make it sound catchy! -->
# The Random Side of R: A Mixed Model Adventure 

<!-- A brief description of your exemplar, which may include an image -->
Mixed models, also known multilevel/hierarchical models, are a type of statistical model that include fixed effects and/or random effects. Traditional linear models assume all observations are independent, but that's rarely true. For example, patients from the same hospital, students from the same classroom, or multiple measurements from the same individual, have a specific structure that if ignored, it can lead to biased estimates, underestimated variability, and
invalid conclusions. In this project, I plan to offer a practical introduction to mixed effects models in R, focusing on their use for analysing data with grouped/hierarchical structures. I will cover when and why to use mixed models, explain the difference between fixed and random effects, and walk through examples using specific R packages

<!-- Author information -->
This exemplar was developed at Imperial College London by (Valentina Quintero Santofimio) in
collaboration with (Saranjeet Kaur Bhogal and Miruna Serian) from Research Software Engineering and
(John Pinney) from Research Computing & Data Science at the Early Career
Researcher Institute.


<!-- Learning Outcomes. 
Aim for 3 - 4 points that illustrate what knowledge and
skills will be gained by studying your ReCoDE exemplar. -->
## Learning Outcomes 🎓

After completing this exemplar, students will:

- Understand the foundation of linear mixed-effects models (LMMs)
- Know when and why to use mixed models over simple linear regression
- Implement mixed models in R 
- Interpret fixed and random effects, variance components, and model fit statistics
- Visualize and validate model 
- Extend to generalized mixed models (GLMMs) and crossed/nested designs

<!-- Audience. Think broadly as to who will benefit. -->

## Target Audience 🎯
The primary focus is to work with large (usually epidemiological) data. Mixed models are useful when working with repeated measures,
nested data, or simply when we want to account for variability across groups. 

These models however, can be applicable to any large dataset (any discipline), that has sufficient grouping or hierarchical structure, ensuring accurate interpretation and conclusions.

## Requirements
## Academic 📚
It would be very useful to take some courses offered by the Graduate School at Imperial College London, either as an introduction or a refresher:

Research Computing & Data Science Skills Courses

-   [Data Exploration and Visualisation](https://www.imperial.ac.uk/students/academic-support/graduate-school/professional-development/doctoral-students/research-computing-data-science/courses/data-exploration-visualisation/)
-   [Introduction to R](https://www.imperial.ac.uk/students/academic-support/graduate-school/professional-development/doctoral-students/research-computing-data-science/courses/r-programming/)
-   [Data Processing with R](https://www.imperial.ac.uk/students/academic-support/graduate-school/professional-development/doctoral-students/research-computing-data-science/courses/data-processing-with-r/)

## Software Tools 🛠️
In this project we will be using R and RStudio:

R (the statistical programming language): 4.5.1. 
RStudio (the IDE/GUI for R): 2025.09.2

We will also use the following R packages:
- _lme4_ for fitting the model
- _lmerTest_ for advanced models 
- _performance_, _see_, and _parameters_ for diagnostics, fit checks, and parameter extraction

<!-- Quick Start Guide. Tell learners how to engage with the exemplar. -->
## Getting Started 🚀

- Start by reading the ReCoDE main page.
- Complete the `Introduction` section (video lecture, reading materials)
- Continue with `Data Curation`(get your data ready for a mixed model analysis)
- Conduct a `Mixed model analysis I`
- Take your analysis to the next level by attempting the extension task `Mixed model analysis II` (Advanced exercise)

## Roadmap 🗺️

### Core 🧩

- [ ] Understanding mixed models 
    * [ ] Correct type of data 
- [ ] Organise your data 
    * [ ] With worked example
- [ ] Basic visualisation 
    * [ ] Mini-project: "Visualise your groups"
- [ ] Data Analysis
    * [ ] What R packages should I use?
    * [ ] Run different mixed models 
- [ ] Results
    * [ ] Understanding my results 
    * [ ] Visualisating results
    * [ ] Is my model good enough?

### Extensions 🔌

- [ ] Advanced mixed-models
    * [ ] Using complex data 

<!-- Data availability (remove this section if no data used) -->
## Data 📊
For this exercise, a synthetic data set will be generated resembling large epidemiological data with different sites (clusters).

<!-- Estimate the time it will take for a learner to progress through the exemplar. -->
## Estimated Time ⏳

| Task       | Time    |
| ---------- | ------- |
| Pre-session material| 3 hours |
| Data curation| 2 hours |
| Analysis | 2-3 hours |
| Interpretation of results| 2 hours |

<!-- LICENCE.
Imperial prefers BSD-3. Please update the LICENSE.md file with the current year.
-->
## Licence 📄

This project is licensed under the [BSD-3-Clause license](LICENSE.md).
