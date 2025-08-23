# Note for Course Developers Using This Template



## Required documents from course developers

Course developers are expected to provide the following:
- `index.md`
- `instructor-guide.md`
- `reference-for-learners.md`
- An episodes directory containing
	- Jupyter notebooks (Markdown and reStructuredText files are also acceptable)
	- Images used in the notebooks
	- Code examples referenced in the notebooks
	- Questions and quizzes for summative assessment
	- Slides for each episode



## The `index.md` file

The `index.md` file should include:
- Title of this module
- General description (1–3 paragraphs)
- **Prerequisites**
	- Reading materials or other preparation required before starting this module
- Links to module episodes in correct order
	- Must use the toctree syntax
	- At least three sessions should be included:
		- 1) **Software setup** -- instructions for configuring the programming environment
		- 2) **Lesson episodes** -- teaching content
		- 3) **Reference** -- notes for instructors and additional resources
- **Learning outcomes** (following Bloom’s Taxonomy guidelines)
	- Target learners and practical skills they will gain
	- **links to relevant leaves in the skill tree**
	- Optionally, mention related topics not covered in this module and link them to the skill tree
- **Credit** (to be reformulated ASAP)
- **License** (to be reformulated ASAP)



## Jupyter Notebook: **Setting Up Programming Environment**

Provide a dedicated notebook (Markdown or reStructuredText also acceptable) with at least two sessions covering environment setup:
- **Local installation**
	- Specify package versions (*e.g.*, via `requirements.txt` or `environment.yml`)
	- Detailed setup instructions for Windows, macOS, and Linux users
	- Optionally provide a containerized setup
- **HPC cluster installation**
	- Instructions valid for a specific supercomputer (preferably an EuroHPC cluster)
	- Specify package versions (as above)
	- Optionally provide a containerized setup
	- Example SLURM batch script for running exercises
- **Datasets**
	- If a dataset is required and smaller than 100 MB, include it directly
	- If larger, provide instructions for downloading it from an external archive



## Jupyter Notebooks for Teaching Materials

Each episode should include:
- A general description
- **Objectives** for learners
- **Instructor note** (suggested time allocation, code demos, exercises, etc.)
- At least one of the following between major sections:
	- `Discussion`
	- `Code for demonstration`
	- `Exercise` (with corresponding `Solution`)
- Highlighted notifications such as `Note`, `Caution`, `Attention`, *etc.*
	- See the Jupyter Notebook **Reference for Course Developers** for more options
- **Images** to illustrate key concepts (stored in an images directory)
- **Videos** if needed to demonstrate continuous processes
	- Videos may be provided directly or linked from YouTube
- **Code examples** stored in a code directory, with references in the notebook
- **Keypoints** at the end of the episode, summarizing its content
- **See also** with additional reading materials



## Quiz

- Provide summative assessment questions suitable for supervised or unsupervised evaluation
- Formats may include:
	- Multiple-choice questions
	- Coding tasks



## Instructor Guide

The instructor guide should include:
- Recommended teaching hours and participant numbers
- Mode of teaching and exercises
- Hardware requirements (including HPC if applicable)
- Learner personas
- Additional teaching recommendations



## Reference for Learners

- Glossary of terms
- External resources for further study

