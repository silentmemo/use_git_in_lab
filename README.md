# use_git_in_lab

### Introduction
Working on a research project may span over years, e.g. PhD projects 3-4 years. Keeping track of changes of project probably the most laborious task. To keep track of rationale and associated with the different edits to the documents will be near impossible. To facilitate the proper documentation of records, which is directly related to reproducibility of the work. Also, projects may take efforts from several individuals, using git and github helps everyone to get involved on the same project. Lastly, I think it is cool to be able to put down the url to a code repository of your work in the “Code availability” section, instead of just a vague statement. 

---

### What is git?

Git is a version control system. Version control means to manage and track changes to a project. It's a blend of the project itself together with the changelog. A common pattern in every project is that we focus on the final product itself, but ignored the project development progress which entails the rationale of the decisions that shapes each and every part of the project.  

Git is a distributed version control system, you can work on the same project on different machines, and all edits to the same repository can be combined.  This feature is beneficial for both working solo or in collaboration. Sometimes, you may need to computational resources on a HPC to work on some task, you can track changes on that if you use git. In other instance, say you are on vacation, and you want to stay completely offline while working on your project. You can do that with git. You can choose when to integrate your edits.  

Git is a popular version control system. If you search a random bioinformatics article in any journal, chances are you will find a github repository. 

---

### What is Github 

Git is not Github. Github is an online platform that host git repositories of different projects. It's like a cloud drive that store the data of the git repository ( docuemnts, codes, data files, etc ). Think of it as OneDrive or Google Drive. 

It is also a social network for developers, where you and your collaborator and strangers on the internet can view and comment and contribute to your project ( if you allow it).   

Github also have some features that enhance productivity, such as Actions and projects. If you configure it properly, you can automate tasks. For example, for each edits you may want the concensus of all your collaborator. Using github action you can configure that. Another example is related to projcet management, repo admin can assign tasks to collaborator, which helps the division of labour. But all these features are suited more to a larger projects, such as project that involves more than a dozen of people.   


--- 

### Git concept 
![git concept](./git_concept.webp)
image credit to : 
```
https://medium.com/@myitcerts995/git-cheat-sheet-guys-f26e2d96732c
```

---

### Applying Git in a project

__Disclaimer: Use git as a tool, make the tools works for you, not the other way around.__

Let say I have a project, that will be one repository (directory or folder in my file explorer). Every data file, such as source code, documentation, or even my NGS fastq files will be stored or linked in that directory.   

I will plan out the project in the README.md in the root directory. This document maybe your project proposal, the index of your thesis. 

I have to work on different part on the projcet. For each part, I will start a new branch. This is to allow myself to work freely in this branch, knowing that the main branch remains unaltered until I merge the change in this branch to the main branch. Plus it avoid conflits with your collaborator, like in the case if you have to edit the same file. The task can be like a section in an article. 

It usually takes days , if not weeks,  to finish working a section. So along the way I will have to save file, which will be commit with a message.  

