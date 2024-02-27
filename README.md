# learn-git-branching
## Objective: To learn how to interact with Git with the help of useful git commands.
### Steps to cover in today's assignment

- Introduction Sequence: Understanding the basics of Git with simple and foundational exercises.
- Ramping Up: A Deep dive into branching and learning how to manage multiple lines of work.
- Moving Work Around: Learning advanced techniques to manipulate the history and branches.

- ### Screenshot of completed exercise!
- <img width="960" alt="image" src="https://github.com/uxeeCoder/learn-git-branching/assets/148591312/1f00e433-ce1e-4483-81ba-2bc9176dc90e">

 ## Take aways from the exercise:
 ### Git Commits
- A commit in a git repository records a snapshot of all the (tracked) files in your directory.
- It's like a giant copy and paste, commits are like snapshots of the project. Commits are very lightweight and switching between them is fast and easy!
  ### Git Branches
- Branches in Git are incredibly lightweight as well. They are simply pointers to a specific commit -- nothing more.
- A branch essentially includes the work of recent commit and all parent commits.
 ### Branches and Merging
- Its a way of combining the work from two different branches together. It allows to branch off, develop a new feature, and then combine it back in.
  ### Git Rebase
- Another way of combining work between branches is rebasing. Rebasing essentially takes a set of commits, "copies" them, and plops them down, the advantage of rebasing is that it can be used to make a nice linear sequence of commits.
  ### HEAD
- HEAD is the symbolic name for the currently checked out commit -- it's essentially what commit someone is working on top of.
- HEAD always points to the most recent commit which is reflected in the working tree. Most git commands which make changes to the working tree start by changing HEAD.
