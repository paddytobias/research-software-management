@title[Introduction]


# Managing source code in Research

### Paddy Tobias, eResearch Analyst, Intersect Australia

---

## Software in Research: *Context*

- Increasing support for research data
- Still little support for research software code
- But software management tools on the rise in research

![Growing influence of GitHub](assets/image/nature_toolbox_github-influence_06.10.2016_WEB.png)
Perkel, J, *Democratic databases: science on GitHub*, Nature 538, 127–128, October 6, 2016, doi:10.1038/538127a

+++


[[ insert diagram "https://docs.google.com/presentation/d/1LNinarnFfgLRfmF_IiqrZcaoJkTVTsapJN9W3o5Qfgg/mobilepresent?slide=id.g263136810c_0_0"]]

---
## Software management: *Why?*

- Improving your workflow
- Scientific reproducibility
- External engagement
- Co-authorship opportunities

+++ 

Things to consider:
- Writing your code
- Version control
- Managing contributions
- Develop documentation
- Issues register
- Licensing


+++ 

### Git and gitlab.une.edu.au

<iframe class="stretch" data-src="https://gitlab.une.edu.au/"></iframe>

Alternative code repositories:
- BitBucket
- GitHub
- SourceForge

[More options here](https://software.ac.uk/resources/guides/choosing-repository-your-software-project)

---

## Software management: *How?*
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

## Software management: how?
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

## Software management: how?
```
else if *publishing your code*:
    then ...
```
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
