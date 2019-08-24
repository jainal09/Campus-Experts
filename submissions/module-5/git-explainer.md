﻿﻿﻿![enter image description here](https://user-images.githubusercontent.com/1790822/44394793-fc50cd80-a52f-11e8-83ae-8df071d56b4b.png)

# Git Explainer
![enter image description here](https://img.devrant.com/devrant/rant/r_208395_eyoBm.jpg)

## So What is Git You may ask?
![enter image description here](https://lh3.googleusercontent.com/MvUu-KBcLx7Is8scDWDfDVraEnsnMjt6W5GEsQq0p4szdYGzhqHkFu9Ey2A9HYDO9MMv2V53hwZT4Q)

Well, Git is the widely used and most popular Version Control System or V.C.S that you might say, which is available to a developer. Git is the Best Friend of the Developer.
It is Widely used For The Following purpose:

 - Version Control
 - Project Management
 - Team Collaboration
 - Open Source Development/Contribution
 ### But, what do you mean by version control?

A version control can be seen as a system which keeps a track of your code changes, allows you to work in a collaborative environment, allows you to know who made what changes and when to the code base , and most importantly, allows you to revert any changes and go back to a previously saved state.
Because as humans we make errors!

 Git is The Premiere for the Open Source Movement The World has Ever Seen. 
Git/Github has made our life much and more easier and awesome! Every good developer has an idea of how hard life would have been without GIT and GitHub. But, the most common thing that is noticed in the novice developers is the fear of GIT CLI tool.

*So Lets Start sailing sailor!*
 So You might be having this question and its quite natural let me clear it for you!
 
## GitHub — Where software is built

![enter image description here](https://cdn-images-1.medium.com/max/1600/0*6FETDgCn09uY2C4t.jpg)

**GitHub**  is a web-based hosting service for version control using git. It offers all of the distributed version control and source code management (SCM) functionality of Git as well as adding its own features. But instead of commiting code to your machine using GitHub you are commiting your code to the secure servers of GitHub. It also  provides access control and several collaboration features such as bug tracking, feature requests, task management, and wikis for every project.

![enter image description here](https://memegenerator.net/img/instances/64255815/please-i-beg-you-speak-in-english.jpg)
## Ok! Ok! - Let me simplify what is said above for you!

You can upload and manage your code on GitHub, if you have a team and you are working on a project, you can work together, you can make some open source contributions, or make your own open source projects/softwares, form your own tech community, or join an existing one, find other people’s projects, follow the people you feel are sound in their domain and much more.   
To be honest, I am more active on **GitHub** than on Facebook.

![enter image description here](https://res.cloudinary.com/hy4kyit2a/f_auto,fl_lossy,q_70/learn/modules/git-and-git-hub-basics/work-with-the-git-hub-workflow/images/17cdcf6d5135213b505e04eb6c7be614_4-collaborate.png)

**Are GIT and GitHub same thing?**

![enter image description here](https://media.giphy.com/media/yhdPkvBsV4DIc/giphy.gif)

**GIT** is a version control system, or basically a tool to manage your code history, while **GitHub** is a hosting service for GIT repositories. Clearly, they are not the same things.  
In short, **GIT** is a tool, and **GitHub** is a service for projects that use GIT.

## Now What is Repository?
In simple words, A repository is a digital directory or storage space where you can access your project, its files, and all the versions of its files that Git saves.

Something is missing you might ask right!
He is just speaking and speaking and not showing anything
# Lets Create our First GitHub Repository
![enter image description here](https://media.giphy.com/media/3oz8xYfQd5358zpL0s/giphy.gif)

So To Do that head To [GitHub](github.com)

![enter image description here](https://lh3.googleusercontent.com/gBr4W7O6ee83Y5E1lZhEFV6-woq01X25yyS62iOYYZIaK0aVzGseFbfTA8Sxnx-yFHlIPN7LlhTv9w)

## Sign Up/ Login
![enter image description here](https://lh3.googleusercontent.com/_MXW9tR9i46EgeNnhUAWBdQs505dFSUQCB9i0GEujMfyBj7EDFjq_DyLhQwGFpNX_Tq-0T2SHmBDBA)

- ## This What You will see after Log in 

![enter image description here](https://lh3.googleusercontent.com/G3V0zBEys7DCOxLbmUuadzA3DR_xPhZqZIQjbj0XNZGj1d_FElzDpKU4u4M0nqCcvuu2dAqSOmincA)

- ## Click on New Repository

![enter image description here](https://lh3.googleusercontent.com/yR4j4Lk9bWpH8loXhG5VMvN7Ddk3dam4dlkL1m7JudpAe4mtkCOoa-7B_cnlMDZRri2-VRlgWHc_Qw)

- Enter repository name and a little Description and You are good to go.

![enter image description here](https://lh3.googleusercontent.com/C0azNhWXM79Y-L6ybL-U9p3dCohWTIZ9qvy4_eOlrpmiqWgOORN8lReiobRjUsnmB6dc16HfKeCSFw)

## So here is our Repository now lets Create and Add some code to it using GIT!

![enter image description here](https://github.githubassets.com/images/modules/site/home-illo-team.svg)

# 1. Using Git & GitHub From CLI

## Configuring Git
So before we start using we first Configure The Git CLI Tool! And here is How?
We first need to configure user information for all the local repositories.
So Fire up a Terminal or Command Prompt and enter the following commands

![enter image description here](https://lh3.googleusercontent.com/KbOUuGq8_ltSN0_iiYeHH5JlM5TWzv-sArJa5t3UiTrbzRFMtkbewwS1lumjY1_gevNI4buBtvB1PQ)

    $ git config --global user.name "YOUR NAME"
    $ git config --global user.email "YOUR EMAIL"
    

>   user. name  — 	Sets the name you want attached to your commit transactions  
>   user.email — 	Sets the email you want attached to your commit transactions

You can check the entered User Name and Email Through this Command 

    $ git config --global user.name
    $ git config --global user.email
   So Before Diving Further Lets Understand Some Terminologies!
   
  

  # Creating Our First GIT REPOSiTORY


> **But Before We Begin There Is Some Terminologies to be Understand!**

![enter image description here](https://lh3.googleusercontent.com/M6O5kEF0vChEhFQa_SIyS6K4oTSOrtK-NekHy5oC9EvErYVYIUThKE63Null8XIRegxZKKGYCihakA)

# What is remote in Git?
A remote in Git is a common repository that all team members use to contribute and commit their work. Then the Code is Stored on Remote Repositories of GitHub.

## Now Lets Start

![enter image description here](https://lh3.googleusercontent.com/oyOZNAoUuOVfjB9Wc4TyaoSbAI9CPuvnVc7zaXwXPGVvLQIs_9QHc-IT8D9fAT3lD1kd7w8or-n_og)

 We can create repositories, start a new repository, or obtain one from an existing URL.
In our case we have already created a Repository named Learning Git and Github.

So Lets create a project directory inside our local machine.

![enter image description here](https://lh3.googleusercontent.com/bNz7kDXYPxM14rF0kpTr7VoOA_YdVZKdsA4xS2ZtkgUDAPnhYffPLfXa6xt1c9foMOVBSVwBo0y76g)

    $ mkdir git_start
    $ cd git_start


- Now We need to clone the Repository we created on GitHub
> Confused all will make sense just follow me, sailor!

![enter image description here](https://lh3.googleusercontent.com/Z0dhgMna_XBoUoXH1VgKwOKpk_Kh_43U8aUY8jcZlkfBYioO6VghYlZ8BoSEJ2k0VXFHlZa3ZuLzkA)

So In simple terms, you have Downloaded that Repository and Now onwards Any change you make into this folder will be watched by the GIT and Constantly checked with the remote repository.

## Now lets Start Commit into these Repository!

![enter image description here](https://github.com/jainal09/Learnig-Git-and-Github/blob/master/zen.gif?raw=true)

As seen from above 
1. We will edit our code i.e here README. md
2. Then We will type in:

` $ git add`
  

> This command snapshots the file in preparation for versioning. Instead of adding the files individually, we can add all of them by adding a `.` after add. `$ git add .`

  

`$ git commit -m "commit message"`

  

>  Records file snapshots permanently in the version history.

`$ git push [remote]  [branchname]`

> Here we are writing git push origin master

Here origin is the same repository which we have cloned and master is the branch to push

  

And Thus we have commited our code!!

  

![enter image description here](https://media.giphy.com/media/3ohhwjrt6CQrBYm5Ec/giphy.gif)

## Now Before we move Further we need to understand some more GIT topics:

![enter image description here](https://github.com/jainal09/Learnig-Git-and-Github/blob/master/ezgif-2-e0a74937cbcc.gif?raw=true)

## Branching 

![enter image description here](https://sdlambert.github.io/img/git-nodes.png)

So imagine you are working big Code Base with many fellow Developers:
But here You cannot commit directly into the master Code i.e the master Branch
It can Result into many bugs and some times runtime errors can cause software crashes!
So we create a new branch which will be the **copy of the Code-Base** and you will be committing into this branch and testing out your code and this is known as **Branching** and finally after successful Q/A you will Merge Our new Branch into the Master Branch and this is known as **Merging!** 

## So let's see this stuff in action!

![enter image description here](https://github.com/jainal09/Learnig-Git-and-Github/blob/master/zen%20%281%29.gif?raw=true)

    $ git branch [branch name]
    
This Creates a New Branch in your Local Machine 
    
    $ git checkout [branch name]
The New Branch Is selected as Your Branch to Work
    
    $ git add . 
All the files are Indexed to be commited

    $ git commit -m "Commit message"
All the files are committed

    $ git push origin [branch name]
 New Branch is Created on GitHub and the code is added

## Now lets merge this 2 Branching!

![enter image description here](https://ucf6da7b9424f368e0d81d856ce8.dl.dropboxusercontent.com/cd/0/get/Afn9qICBBWRKihbeW1LABgj4vHsJc9ARZeIoJRpPZfdwE-nZlH--0e1FIU0PM-V10sujma-7-N57eL7B_cMO09D3PFKLyGbPqiIaeptfaZqJbg/file?dl=1#)

    $ git status 

Shows the status of the current working Branch

    $ git checkout
    $ git merge [Branch name]
   This will merge the current branch with the [Branch name] 

## Now lets see on Github if they are properly merged or not!

![enter image description here](https://lh3.googleusercontent.com/tiAuZp-XAY-oYvv2KTKudo8GXZREpSkngxI1G3vnoFMUhlN-SeBSGnE-zJt-zH-Wws49ktaXmt_VWw)

## Some times We can also have Merge Conflicts!!

![enter image description here](https://media.giphy.com/media/cFkiFMDg3iFoI/giphy.gif)

## So what are Merge Conflicts and when can they happen:

Say I have a Repository and I had added a Text file.
1.  I added "1" to the text file and committed it to master.
    
2.  Then I Created a new branch from master and appended "2".
    
3.  Finally, created a branch from master and appended "3".

you will have a conflict if you merge:

-   `branch2`  to  `master`  (no conflict)
-   `branch3`  to  `master`  (conflict):

That is because:

-   The common ancestor would be  `master`  (with a second line empty)
-   the source content is  `branch3`  (with a second line including "3")
-   the destination content is on latest of  `master`  (with a second line including "2", from the merge of  `branch2`  to  `master`)
Git will ask you to choose which content to keep ("3", "2", or both).

First, do the merges after:

```
git config merge.conflictstyle diff3
```

# Lastly Lets Understand The 3 Stages of GIT

![enter image description here](https://slideplayer.com/slide/14099824/86/images/4/git+concepts+%E2%80%93+3+states+&+workflow.jpg)

Git has three main states that your files can reside in it. They are Committed, Modified, Staged. What are they? and how does the git workflow go?

## Committed

The data is safely stored in your local Git database. The database is located in the Git directory, which stores the metadata and object database for the whole project. It is what you push/clone a repository to/from another computer.

## Modified

The file has been changed but not committed to Git database yet, the modified file is in the working directory, where it's a single checkout of one version of the project. These files are pulled out of the compressed database in the Git directory and placed on disk for you to use or modify.

## Staged

The file has been marked in the current version and will go into the next commit snapshot. Staged file has snapshots stores in the staging area, where it's a file, stores information about what will go into your next commit. It's sometimes referred to as the 'index', but it's also common to refer to it as the staging area. It is contained in your Git directory

## How does the basic Git workflow go?

1. You init or clone a project, one of version goes to the working directory  
2. You modify files stay in the working directory.  
3. You stage the files, adding snapshots of them to your staging area.  
4. You do a commit, which takes the files as they are in the staging area and stores that snapshot permanently to your Git directory.

If a particular version of a file is in the Git directory, it's considered committed.

If a file is modified but has been added to the staging area, it is staged.

While if it was changed since it was checked out but not yet staged, it is modified.

# *So that's all for today I hope you understand GIT and GitHub Today!!*
![enter image description here](https://media.giphy.com/media/349qKnoIBHK1i/giphy.gif)


