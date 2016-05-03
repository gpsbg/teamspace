# TestRepository
28.04.2016 This repository is a part of the "Java Course".

Repositories: Задачи

1 - Да се създаде проект с GIT #

2 - Да се направят промени и да се commit-нат #

3 - Да се създаде нов branch. Да се направят промени в него и след това branch-a да се слее (merge) с master'a #

4 - Да се направи rebase и merge с конфликти, които да се ресолвнат и да се определят разликите между 2'та подхода: 6.

5 - Да се създаде tag #

6 - Да се изследва и установи каква е разликата между rebase и merge #

Merging is nice because it’s a non-destructive operation. 
The existing branches are not changed in any way. 
This avoids all of the potential pitfalls of rebasing.
Merging can make it hard for other developers to understand the history of the project.

The major benefit of rebasing is that you get a much cleaner project history.
Rebasing also results in a perfectly linear project history—you can follow the project all the way to the beginning without any forks.
Rebasing makes it easier to navigate your project with commands like git log, git bisect, and gitk.
If you don’t follow the "Golden Rule of Rebasing", re-writing project history can be potentially catastrophic for your collaboration workflow.
***The golden rule of git rebase is to never use it on public branches.***
Rebasing loses the context provided by a merge commit—you can’t see when upstream changes were incorporated into the newBranch.

7 - Да се check out-не проекта на друго място #

8 - Да се определят разликите между централизирана и дистрибутирана система за управление на кода #

Централизирана:
All the revision control functions take place on a shared server.
If two developers try to change the same file at the same time, without some method of managing access the developers may end up overwriting each other's work. Centralized revision control systems solve this problem in one of two different "source management models": file locking and version merging.

- File Locking: 
 Only one developer at a time has write access to the central "repository" copies of those files. 
 Once one developer "checks out" a file, others can read that file, but no one else may change that file until that developer "checks in" the updated version (or cancels the checkout).
- Vresion Merging:
 Most version control systems allow multiple developers to edit the same file at the same time.
 The first developer to "check in" changes to the central repository always succeeds. 
 The system may provide facilities to merge further changes into the central repository, and preserve the changes from the first developer when other developers check in.

Дистрибутирана:
It conducts synchronization by exchanging patches (change-sets) from peer to peer. 
Common operations (such as commits, viewing history, and reverting changes) are fast, because there is no need to communicate with a central server.
Each working copy effectively functions as a remote backup of the codebase and of its change-history, providing inherent protection against data loss.

9 - Да се разгледат инструментите на GitHub за комуникация между разработчици (pull requests,issues, branches,tags, merging). #
