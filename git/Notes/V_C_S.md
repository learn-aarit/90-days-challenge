# _V_C_S_ _(Version Control System )_

### Tool in software development and colaborative projects to track and manage changes to source code.

### It allows developer to -

* Record and track each update to the codespace / code base .
* collab with friends working on same project without over writing same thing again .
* keep each and every change save to retirve old form if modification brakes .
* maintain detailed and structred history of the projects evolution .
* alow keep track of what changes made by which user .


### Features 

* branching - make seprated copy of projects keeping original project safe.
* centralized version control -
* collaboration - helps to work on same project with many user simultanously
* conflicts -
* repositories -  files which store project in git a whcih can be access by links and so .
* code review -

### Components of Version Control Systems
Version Control Systems work using a few core concepts that help teams manage code changes and collaborate efficiently.

* Repository: A central location that stores all project files along with their complete change history and metadata like author and commit message.
* Revision: A specific saved version of a file or project, identified using a unique ID such as a hash or number.
* Branch: A separate copy of the codebase used to develop features or fix bugs without affecting the main code.
* Merging: The process of combining changes from one branch into another, which may sometimes require resolving conflicts.
* Commit: A snapshot of changes made to the codebase at a specific time, used to track and manage project history.


### Types of Version Control Systems

There are three main types of Version Control Systems:
---
### 1. <ins> Local Version Control Systems </ins> (Local VCS) </br>
A Local Version Control System operates entirely on your personal machine without any connection to a remote repository. All changes and version history are stored in a local database on your computer.

In this setup, there is only a single user, with no collaboration or sharing of changes. Local VCS stores versions in a local database, not in a repository that others can clone.

Characteristics:

1. No internet or server dependency.
2. Useful for individual projects.
3. Limited to single-user environments.</br>

--- 
### 2. Centralized Version Control Systems </br>
In a Centralized Version Control System, all the files and their version history are stored in a single central server. Developers connect to this server to access or modify files.

The typical workflow is:

Update/Checkout: A developer pulls the latest version of the files from the central server.
Make Changes: A developer works on the files.
Commit: A developer saves ("commits") their changes directly back to the central server, making them immediately available to everyone else.

Pros & Cons:

The benefit of CVCS (Centralized Version Control Systems) is that it makes collaboration among developers while providing insight into what everyone else is doing on the project.
It allows administrators to have fine-grained control over who can do what. It has some downsides as well which led to the development of DVCS.
The most obvious drawback is the single point of failure represented by the centralized repository. If the repository goes down, you would not be able to collaborate or save changes.

---

### 3. Distributed Version Control Systems
Distributed version control systems contain multiple repositories. Each user has his or her own repository and working copy. Just committing your changes will not give others access to your changes. This is because a commit will reflect those changes in your local repository and you need to push them in order to make them visible to the central repository.

Similarly, When you update, you do not get others changes unless you have first pulled those changes into your repository. 

The key difference is the two-step process for sharing changes:

Commit: You save your changes to your own local repository. At this point, the changes are only on your machine; no one else can see them.
Push: You upload ("push") your committed changes from your local repository to the central repository (e.g., GitHub).
To get changes from others, the process is:
* Fetch/Pull: You download ("pull") the latest changes from the central repository to your local repository.
The most popular distributed version control systems are Git and Mercurial. They help us overcome the problem of single point of failure. 

Popular Version Control Systems </br>
Below are five most widely used free VCS tools, perfect for individuals and teams. Each of these version control systems serves different needs, and the choice depends on the project size, team collaboration style and workflow preferences.

1. Git  </br> 
Git is the most widely used Distributed Version Control System, developed by Linus Torvalds in 2005 for managing the Linux kernel. It is highly efficient, supports branching and merging, and has a fast, decentralized workflow. Git is the backbone of services like GitHub, GitLab and Bitbucket, making it a popular choice for developers worldwide.

Features of Git:

* Lightweight, fast and efficient.
* Branching and merging are simple and non-destructive.
* Provides powerful commands like git clone, git pull and git push.


2. Subversion (SVN) </br>
Subversion is a popular centralized version control system. While it is not as commonly used in open-source projects today, SVN is still widely used by many organizations and enterprises for its simplicity and centralized structure.

Features of SVN:

* Single central repository.
* Supports branching and tagging but it is less flexible than Git.
* Versioning of files and directories.

3. Mercurial </br>
Mercurial is a distributed version control system similar to Git but with a simpler interface. It is well-suited for both small and large projects and is used in various open-source and enterprise projects.

Features of Mercurial:

* Simple, fast and scalable.
* Supports branching and merging.
* Includes tools for managing project history and changes.


4. CVS (Concurrent Versions System) </br>
CVS is one of the earliest and most influential centralized version control systems. It was widely adopted in the late 1990s and early 2000s and helped shape how modern VCS tools operate. Though largely outdated today, CVS laid the foundation for later tools like Subversion and Git.

Features of CVS:

* Centralized repository architecture.
* Tracks changes to individual files over time.
* Allows multiple developers to work on the same codebase.
* Basic support for branching and tagging, though more limited than modern alternatives.


5. Bazaar
Bazaar is a distributed version control system developed by Canonical, the creators of Ubuntu. Unlike Git or Mercurial, Bazaar supports both centralized and distributed workflows, making it a flexible choice for teams with varied needs. Although it's no longer actively developed, Bazaar was once used by major projects like Ubuntu and MySQL.

Features of Bazaar:

* Supports both centralized and distributed version control models.
* Easy to learn and beginner-friendly.
* Human-readable command structure (e.g., bzr commit, bzr push).
* Cross-platform compatibility (Linux, Windows, macOS).
* Version control systems are vital for modern software development, enabling teams or solo developers to track changes, collaborate efficiently, and maintain stable, testable code. Among various types, distributed systems like Git are the most popular, offering flexibility, powerful features, and seamless collaboration.



### 1. Centralized Version Control (CVCS) </br>
Centralized Version Control (CVCS) is a system where there is a central repository that stores all the code, and developers access this repository to make changes. Popular examples of CVCS include Subversion (SVN) and CVS.

### Features of Centralized Version Control:
* Single Central Repository: All project files are stored in a central location, and every developer gets a copy of the latest version of the code.
* Version History: The version history of the project is managed centrally, making it easy to track changes and revert to older versions.
* Real-Time Collaboration: Developers can work on the same codebase, with access to the latest code and updates from others.
* Simple Setup: CVCS systems are relatively simple to set up and understand.


### Use Cases for Centralized Version Control
* Smaller teams or projects where developers work in close proximity.
* Projects where developers need real-time access to the latest codebase.
* Enterprises that require strict control over access and code management.


### Distributed Version Control (DVCS)
Distributed Version Control (DVCS) is a system where every developer has a complete local copy of the entire project, including its history, and they can work offline. Changes can be made locally, and later synchronized with other developers’ versions. Popular DVCS systems include Git, Mercurial, and Bazaar.

* Features of Distributed Version Control
* Complete Local Repositories: Every developer has the full history of the project on their local machine. This allows them to work offline and make changes even without internet access.
* Branching and Merging: DVCS makes it easy to create branches, work on features in isolation, and merge changes back into the main codebase.
* No Single Point of Failure: Since every developer has the complete project history, there is no single point of failure. If the central repository is lost or damaged, the history can be recovered from any local copy.
* Collaboration: Developers can share changes with each other through push/pull mechanisms, allowing for decentralized collaboration.


Use Cases for Distributed Version Control
* Large teams or projects where developers are spread across different locations.
* Open-source projects where contributors work from various environments.
* Projects requiring frequent branching, merging, and experimentation with code.













