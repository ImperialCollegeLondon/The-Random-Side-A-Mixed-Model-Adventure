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
Mixed models, also known multilevel/hierarchical models, are a type of statistical model that include both fixed effects and/or random effects. Traditional linear models assume all observations are independent (but that's rarely true). For example, patients nested in hospitals, students within classrooms, or multiple measurements from the same individual, have a specific structure that if ignored, it can lead to biased estimates, underestimated variability, and
invalid conclusions. In this project I plan to offer a practical introduction to mixed effects models in R, focusing on their use for analysing data with grouped/hierarchical structures. I will cover when and why to use mixed models, explain the difference between fixed and random effects, and walk through examples using specific R packages

<!-- Author information -->
This exemplar was developed at Imperial College London by (Valentina Quintero Santofimio) in
collaboration with (Saranjeet Kaur and Miruna Serian) from Research Software Engineering and
(John Pinney) from Research Computing & Data Science at the Early Career
Researcher Institute.


<!-- Learning Outcomes. 
Aim for 3 - 4 points that illustrate what knowledge and
skills will be gained by studying your ReCoDE exemplar. -->
## Learning Outcomes 🎓

After completing this exemplar, students will:

- Understand the foundation of linear mixed-effects models (LMMs)
- Know when and why to use mixed models over traditional regression
- Implement mixed models in R 
- Interpret fixed and random effects, variance components, and model fit statistics
- Visualize and validate model 
- Extend to generalized mixed models (GLMMs) and crossed/nested designs

<!-- Audience. Think broadly as to who will benefit. -->
## Target Audience 🎯
The primary focus is to work with large (usually epidemiological) data. Mixed models are useful when working with repeated measures,
nested data, or simply want to account for variability across groups. 

These models however, can be applicable to other disciplines that involves multiple collection of data at different time points. This ensures accurate interpretation and conclusions of your data.

<!-- Requirements.
What skills and knowledge will students need before starting?
e.g. ECRI courses, knowledge of a programming language or library...

Is it a prerequisite skill or learning outcome?
e.g. If your project uses a niche library, you could either set it as a
requirement or make it a learning outcome above. If a learning outcome,
you must include a relevant section that helps with learning this library.
-->

<!-- Quick Start Guide. Tell learners how to engage with the exemplar. -->
## Getting Started 🚀

1. Start by reading the ReCoDE main page.
2. Complete the `Introduction` section (video lecture, reading materials)
3. Continue with `Data Curation`(get your data ready for a mixed model analysis)
4. Conduct a `Mixed model analysis I`
5. Take your analysis to the next level by attempting the extension task `Mixed model analysis II` (Advanced exercise)


## Project Structure 🗂️

Overview of code organisation and structure.

```
.
├── src
│ ├── file1.qmd
│ ├── file2.qmd
│ ├── ...
│ └── data
├── docs
└── test
└── _quarto.yml
```

Code is organised into logical components:

- `src` for core code, potentially divided into further modules
- `data` within `src` for datasets
- `docs` for documentation
- `test` for testing scripts
- `_quarto.yml` for Quarto configuration


<!-- Roadmap.
Identify the project core (a minimal working example). This
is what you should develop first, ideally by week 6. Defining
a core helps ensure that, despite a tight timeline, we will end
up with a complete project.

Identify project extensions. These are additional features that
you will implement after the core of the project is finished; you
could also propose extensions as open-ended exercises for the ReCoDE
audience.

Outline the process of creating the exemplar as a project roadmap
with individual steps. This will help you with defining the scope of 
the project. When you think about this, imagine that you are explaining
it to a new PhD student. Assume that this student is from a related (but
not necessarily same) discipline. They can code but have never undertaken
a larger project. The steps should follow logical development of the
project and good practice. Each will be relatively independent and contain
its own learning annotation and links to other learning materials if
appropriate. The learning annotation is going to form a significant portion
of your efforts.

Learning annotations will evolve as we go along but planning now will be useful
in defining your exemplar steps. Remember that active learning is generally more
valuable than just reading information, so small exercises that build on previous
steps can really help your students to understand the software development process.
You can include videos, text, charts, images, flowcharts, storyboards, or anything
creative that you may think of.

Completed tasks are marked with an x between the square brackets.
-->
## Roadmap 🗺️

### Core 🧩

- [ ] Understanding mixed models 
    * [ ] Correct type of data 
- [ ] Organise your data 
    * [ ] With worked example
- [ ] Basic visualisation 
    * [ ] Mini-project: "Visualise your groups"
- [ ] Data Analysis I
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
