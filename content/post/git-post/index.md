---
title: Version Control System. Git.
subtitle: This is a post for stage 2 of individual project.

# Summary for listings and search engines
summary: Version Control Systems (VCS) are used when several people work on one project.

# Link this post with a project
projects: []

# Date published
date: '2023-10-03T00:00:00Z'

# Date updated
lastmod: '2023-10-03T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - Academic

categories:
  - Stage2
---

## Version Control System. Git.

Version Control Systems (VCS) are used when several people work on one project. Typically, the main project tree is stored in a local or remote repository, to which access is configured for project participants. When making changes to the content of the project, the version control system allows you to record them, combine changes made by different project participants, and roll back to any earlier version of the project, if required.

Classic version control systems use a centralized model, which involves a single repository for storing files. Most version control functions are performed by a dedicated server. Before starting work, a project participant (user) receives the version of files he needs using certain commands. After making changes, the user posts the new version to the repository. However, previous versions are not deleted from the central storage and can be returned to at any time. The server can not save the full version of the changed files, but perform so-called delta compression - saving only changes between successive versions, which allows reducing the amount of stored data.

Version control systems support the ability to track and resolve conflicts that may arise when multiple people are working on the same file. You can combine (merge) changes made by different participants (automatically or manually), manually select the desired version, discard changes altogether, or lock files for change. Depending on the settings, the lock prevents other users from obtaining a working copy or prevents the working copy of the file from being modified by the OS file system, thus providing privileged access to only one user working with the file.

Version control systems can also provide additional, more flexible functionality. For example, they can support multiple versions of a single file, maintaining a shared history of changes up to the point of a version branch and each branch's own history of changes. In addition, information is usually available about which participants made what changes, when, and what changes. Typically this type of information is stored in a change log, access to which can be restricted.

Unlike classic ones, in distributed version control systems a central repository is not required.

Among the classic VCS, the most famous are CVS, Subversion, and among the distributed ones - Git, Bazaar, Mercurial. The principles of their operation are similar; they differ mainly in the syntax of the commands used in their work.


