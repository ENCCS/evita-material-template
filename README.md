# Note for Course Developers Using This Template



## Documents requested from course developers
- `index.md`
- `instructor-guide.md`
- `reference-for-learners.md`
- a `episodes` directory containing
	- Jupyter notebooks (also possible to provide Markdown and reStructuredText files)
	- images used in jupyter notebooks (Markdown and reStructuredText files)
	- code examples that are included in jupyter notebooks (Markdown and reStructuredText files)
	- qustions and quiz for summative assessment
	- slides for each episode for teaching



## The `index.md` file
- title of this module
- general description of this module (1-3 paragraphs)
- **prerequisites**
	- (preparatory) reading materials before taking this module in a course
- links to module episodes in correct order
	- must use the `toctree` syntax
	- at least three sessions should be provided:
		- 1) **Software setup** to describe how to setup programming environments
		- 2) **Lesson episodes** to include all episodes for teaching
		- 3) **Reference** to include notes for instructors and additional references
- **Learning outcomes** according to strict guide (Blooms taxonomy *etc.*) 
	- the target learners of this module and practical skills that could be mastered after taking this module (course)
	- **links to leaves in the skill tree**
	- optionally, also mention other related topics which are NOT covered in the course and link them to the skill tree
- **Credit**
	- <mark>should be reformulated asap</mark>
- **License**
	- <mark>should be reformulated asap</mark>



## One Jupyter notebook for **Setting Up Programming Environment**
- it is possible to provide Markdown and reStructuredText files
- provide at least two sessions to setup programming environment
- **local installation of programming environment**
	- provide specific version of used packages (such as a `requirements.txt` or a `environment.yml`)
	- detailed instructions for win, mac, and linux users
	- it is also possible to setup container
- **setting up programming environment on HPC cluster**
	- instructions valid for any specific supercomputer, preferably an EuroHPC cluster
	- provide specific version of used packages (such as a `requirements.txt` or a `environment.yml`)
	- it is also possible to setup container
	- example SLURM job batch script for running the hands-on exercises
- if a dataset is needed for exercises, provide dataset if it is smaller than 100 MB, otherwise provide instructions to download it from external data archives



## Jupyter notebooks for teaching materials 
- a general description of this episode
- **objectives** for learners of this episode
- **instructor-note** provide suggested time for teaching, code demonstration, code type alone, exercises, *etc.*
- at least one `Discussion`, `Code for demonstration` or `Exercise` (and the corresponding `Solution`) in between major sections within the episode
- some notifications like `Note`, `Caution`, `Attention` should be provided
	- more notifications are provided at Jupyter Notebook **Reference for course authors**
- images should be included to illustrate certain concepts, making them easier to understand
	- these images should be stored at another directory **images**
- if videos are required to illustrate a continuous process, the developer should provide them directly.
	- alternatively, links to relevant YouTube videos may be supplied
- code examples are expected to be available at a **code** folder and provide links to these examples
- **Keypoints** at the end summarizing this episode 
- **See also** to provide additional materials for reading



## Quiz
- Summative assessment: provide questions which can be tested either in a supervised or unsupervised setting
- Format: 
	- Multiple choice questions
	- Coding tasks



## Instructor guide
- teaching hours and number of participants
- mode of teaching and exercising
- hardware requirements, HPC
- learner personas
- ...



## Reference for learners
- Glossary
- External resources for further reading

