@title[Introduction]


# Managing software in Research

Dr Paddy Tobias, eResearch Analyst
Intersect Australia

---
- Software = `source code`
- Text file programs

---
## Software in Research: Context

- Increasing support for research data
- Still little support for research software code
- But software management tools on the rise in research

+++

![Perkel, J 2016](assets/image/nature_toolbox_github-influence_06.10.2016_WEB.png)

+++

|Mention type|Count (%)|
|--|--|--|
|Cite s.w. publication|105 (37%)|
|In-text s.w. name only|90 (31%)|
|Instrument s.w.|53 (19%)|
|Cite project name or website|15 (5%)|
|Cite s.w. URL|13 (5%)|
|Cite user’s manual|6 (2%)|
|Not even name|4 (1%)|
|--|--|--|

*n* = 286 

[Howison, J, Bullard, J, 2016]("https://onlinelibrary.wiley.com/doi/abs/10.1002/asi.23538")

---
## Software management: Why?

- Improving your workflow |
- Coordinating group research |
- Scientific reproducibility |
- External engagement |
- Co-authorship opportunities |

+++ 

Things to consider:
- Writing your code |
- Version control |
- Managing contributions |
- Develop documentation |
- Issues register |
- Licensing |

+++ 

### Git, GitHub, GitLab, Git-everything...


<img src="assets/image/git_logo.jpg" alt="Git" style="width: 20px;"/>

![GitHub](assets/image/github_logo2.png =20x)
![GitLab](assets/image/gitlab_logo.png =20x)

[More options here](https://software.ac.uk/resources/guides/choosing-repository-your-software-project)

Note:
Alternative code repositories:
- BitBucket
- GitHub
- SourceForge

---

## Software management: How?
```
if *coding by yourself*:
    then ...
```
+++

### Writing your code
- If adapting code from someone else, don't! Write you're own and copy/paste the chunks you want
- Have a plan for your code before you start writing. What do you want it to do?
- Draw your plans... before you write your code
- Where to start? What are your **inputs** and **outputs**?
- Comment your code

Note: 
* there are formal design architecutres you can follow (e.g., Unified Modeling Language), but you don't have to use/learn these. Just come up with a conceptual way to explain what you what your program.
* more so, draw these concepts before you begin coding. 
* take into account your inputs and outputs. what goes into your program and what do you want to come out

+++
### Version control
- Make regular commits 
- Meaningfully describe major commits, not every commit
- Git repos make this easy to do. Add >> Commit >> Push

---

## Software management: How?
```
else if *collaborating with others*:
    then ...
```
+++
### Managing contributions



+++ 
### Documentation 

- Create a README.md file
- [Learn Markdown] (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- Use Atom
- consider user guides as well

<iframe class="stretch" data-src="https://github.com/atom/atom"></frame>

Note: 
use Atom

+++ 
### Issues register

---

## Software management: How?
```
else if *publishing your code*:
    then ...
```
+++
### Software Citation Principles

- Software should be considered a legitimate and citable product of research
- Software citations should facilitate giving scholarly credit, attribution to all contributors
- Software citations should have recognized unique identifiers, machine actionable, interoperable
- These unique identifiers and metadata describing the software should persist
- Software citations should facilitate access to the software and use of it
- Software citations should specify the version that was used


+++
### Software citation and licensing

-  Zenodo and minting DOI




---

## Git vocabulary

```
git push  <REMOTENAME> <BRANCHNAME>
git clone https://github.com/<USERNAME>/<REPOSITORY>.git 
git fetch <REMOTENAME> 
git merge <REMOTENAME>/<branchname>
git pull <REMOTENAME> <branchname>
```
@[1](`push` to push or publish commits to your code repository)
@[2](`clone` to grab a complete copy of another user's repository)
@[3](`fetch` to retrieve new work done by other people)
@[4](`merge` combines your local changes with changes made by others)
@[5](`pull` completing both *git fetch* and *git merge* in the same command)

---

## Benefits
- Research Impact and Engagement: who are your end users?


---
## Where to next?

Come to the class next week: 9.30-12.30, 8th May

Code for this presentation: https://github.com/paddytobias/research-software-management

+++
## Bibliography

Perkel, J, "Democratic databases: science on GitHub", *Nature* 538, 127–128, October 6, 2016, doi:10.1038/538127a

Howison, J, Bullard, J, "Software in the Scientific Literature: Problems with Seeing, Finding, and Using Software Mentioned in the Biology Literature", *Journal of the Assoc. for Information Science and Technology*, 67(9), 2137-2155, https://onlinelibrary.wiley.com/doi/abs/10.1002/asi.23538

Smith, AM, Katz, DS, Niemeyer, KE, FORCE11 Software Citation Working Group, 2016,  "Software citation principles", *PeerJ Computer Science*, 2(86) https://doi.org/10.7717/peerj-cs.86




