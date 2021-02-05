README

NLP TEST TASK

GOALS: we want to build a text classifier that determines for a given school bond ballot text what the bond funds will be used for. In the end, there should be a small number of categories (perhaps 3-10) that a bond might fall into. For example, one bond might be used for constructing new classrooms and a science lab, while another might be used for buying a community pool and repairing a roof. We may want to have categories such as "expand capacity", "renovate", and "upgrade"; and a bond may fall into none, one, or several of these categories.
The goal is to come up with appropriate categories and classify bonds into these categories, where "appropriate" means that they are meaningful in the context of facility quality, different enough from one another, and can classify most bonds in the data.

DATA: to build the classifier, we use the data in ballottext_bonds_CA.csv, which shows the ballot texts for almost 2,000 bonds in California over the last several decades. This is about 10% of all of the text data we have for this project.

TASKS: There are at least three sub-tasks:
1. Find categories that are broadly applicable and appropriate, as describe under GOALS.
2. Classify all bonds in the data into these categories.
3. Summarize simple criteria how well your classifier works (e.g. how many bonds fall into at least one category? How many categories apply to at least 1% of bonds?)

SUBMISSION: If you are interested in completing the test task and to be considered for this position, please submit code that builds, runs, and tests a classifier. This code can be written in whatever language you prefer, although python is likely to be most convenient. Please add comments that clearly explain what you are doing.

EXPECTED SCOPE/DEPTH: While it is possible to spend weeks or months on this task (and if you are selected, you will!), the idea here is for you to do something very simple that demonstrates you understand and/or can acquire basics such as how to load data using code, how to apply functions, and how to work with text as data. We expect no more than 100 lines of code to demonstrate this. If you use auxiliary files besides code (e.g. hand-coding some categories), that is fine too. This test task serves to see whether this project is a good fit for you, in terms of your interests and skills.