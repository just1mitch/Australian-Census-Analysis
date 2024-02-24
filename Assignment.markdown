<h5>CITS2402 Practical Assignment, Semester 2 2023</h5><br>

# Exploring Trends in Australian Census Data

### Aim

The aim of this assignment is to examine trends, or changes, in Australia's demographics from 1996 to 2021 using ABS Census data.

You may choose what census topic you are most interested in from the data, providing it is not one that we have addressed in the lecture or lab case studies \(such as age, number of children, or travel to work\). For best results, you should also choose a topic with multiple categories \(not, for example, binary categories\). You may focus on particular categories of interest.

You may choose which geographical region within Australia you wish to explore.

To focus the assignment you may find it useful to frame it as a _question that you are seeking to answer_ \(or for those familiar with the terminology, an hypothesis that you seek to prove or disprove\). You should clearly state in your opening paragraphs what it is that you are seeking to answer.

It is important to understand at the outset that, while the programming is of course important, this is not just a "coding exercise". The context and rationale, sound and replicable use of data, and presentation of results in a clear and compelling way, are equally a part of the assignment.

### Learning Outcomes

This assignment demonstrates competencies in:

- sourcing information from \(authoritative\) public data repositories
- extracting and cleaning information needed to answer a question or hypothesis about the data
- analysing and interpreting the data
- visualising data to aid understanding and communicate results
- scientific communication

### Authorship

The assignment may be done individually, or in groups of up to three students. Each student's name and student number \(whether completed by one or more students\) must be provided in the declaration at the top of the assignment template \(`Australian_Trends_template.ipynb`\).

Where the assignment has been completed by more than one student, only one copy should be provided for collection so that it is clear which version to mark.

The suffix "`_template`" should be _removed from the final copy_ \- that is, the file `Australian_Trends.ipynb`, in one student's assignment directory, will be marked.

The submission must be the student\(s\) own work. Any material used in the assignment from other sources, whether human or software/AI, must be clearly stated and referenced.

### Data

Data should be drawn from Australian Census' between 1996 and 2021.

Where possible, data should be drawn from Datapacks in `csv` format. The metadata in the spreadsheets (`.xlsx` format) should be used to identify the relevant tables for your investitation. Only the individual tables in csv format (not the entire Datapack) should be uploaded to CoCalc.

Where Datapacks are not available, you may wish to export the data from a spreadsheet to `csv` format, before uploading to CoCalc. \(Alternatively you may upload tables in `.xlsx` format and use python to read in the data from that format if you wish.\)

Your report should provide sufficient explanation on how and where you located the relevant data that was uploaded to CoCalc, such that the reader would be able to replicate your steps and obtain their own raw data to test your code.

#### Submission and Format

Your report, including all explanations and code, must be provided in a single CoCalc notebook `Australian_Trends.ipynb`, duplicated from the template provided, in the assignment directory. \(Again, the suffix "`_template`" should be removed from the final copy of the group member making the submission so that the correct version is collected for marking.\)

The notebook should contain headings and explanations in _markdown cells_, and executable code in python _code cells_ \(as is done in the lab sheets\).

_Nothing else in the directory will be marked._

No further action is required for submission \- notebooks will be collected at the due date.

It is recommended that you download a backup of your final completed submission directory for your own records.

#### Code

The code will be executed with a fresh kernel for marking, so (as usual) you should ensure that it runs with a clean kernel prior to submission.

Any supporting data must be in a text (or .xlsx) files in the same directory. Data files should not be more than 1MB.

It is recommended that development is done in the notebooks \- in the past students have had code fail due to pasting from other environments.

#### Packages

The following packages, _only_, may be imported and used in this project:

Compulsory

* matplotlib/pyplot

Optional \(only for those who wish to use them, there are no marks attached to use of these\)

* csv
* numpy
* seaborn
* re

#### Deadline

The deadline is **11:59pm, Monday 11th September**.

## Rubric

The assignment contributes 25% of the 30% practical work component.

The assignment will be marked for clarity and professionalism of both the exposition and the coding.

It is recommended that you structure the report in a way that is consistent with the data lifecycle. You may wish to use headings to help structure your report.

Markers will be giving attention to the following components (in roughly equal weighting).

#### Context and Data

- Adequate context has been provided to understand the question and why it is important.
- The question \(or hypothesis\) you seek to understand is clearly stated.
- It is clear what data is used and its provenance. Instructions allow the reader to easily source the data \(to make the work replicable\). 
- Relevant differences between the data from different sources, and assumptions you have to make for comparison, are clearly described.

#### Data lifecycle, structure, and presentation

- The route from the data to the results is clearly set out and steps explained.
- It is clear what format the raw data took, what is extracted and why.
- Any data cleaning and conversion is clearly and concisely outlined. 
- The processing or analysis necessary to extract and compile the results is clearly explained.

#### Results, Visualisation and Conclusion

- The results are clearly stated and connected back to the original data and assumptions.
- Appropriate and informative choices are made for visualisation\(s\) \(plots\).
- The visualisations are clearly and professionally presented.
- Conclusions are connected to relevant features of the visualisations.

#### Coding

- Code is _clear_, easy to read and comprehend. Considerations should include:
  - use of meaningful variable names
  - use of comments and/or docstrings for key steps/blocks \(you do not need to comment every line, this tends to obscure the key steps\)
  - use of functions \(see below\)

- Code is appropriately _concise_. \(Code should not be pared down to a bare minimum at the expense of clarity and readability. However you should try to avoid extraneous code that is unnecessary.\)

- Code is reasonably _efficient_. \(It is not necessary to achieve ultimate efficiency at the expense of writing clear logical code. However you should avoid obvious unnecessary inefficiencies.\)

- Code is well _structured_. Functional decomposition is used to separate tasks into meaningful components.

#### Professionalism and Challenge

- Overall the report forms a compelling and illuminating narrative.
- The report is not unnecessarily long or repetitive and provides all the information in a complete but concise way.
- The report reveals aspects of the data that are not trivially obvious.
- The report is of a quality that an employer would be comfortable showing to a client.

