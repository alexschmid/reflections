**What happens when you initialize a repository? Why do you need to do it?**

A `.git` repository is created. To allow Git to track changes to a repository's files.

**How is the staging area different from the working directory and the repository? What value do you think it offers?** 

The staging area is for nomimnating files for any given commit. It allows you to track only files you intend to have tracked.

**How can you use the staging area to make sure you have one commit per logical change?**

By using the staging area to only add files that are part of a logical change.

**What are some situations when branches would be helpful in keeping your history organized? How would branches help?**

When adding new features or making large changes. Branches would help keep the master branch working normally.

**How do the diagrams help you visualize the branch structure?**

By showing branch lineage (parents).

**What is the result of merging two branches together? Why do we represent it in the diagram the way we do?**

Combining new features or changes with the production code base only when ready. To show that it is an offshoot of a certain parent commit.

**What are the pros and cons of Git’s automatic merging vs. always doing merges manually?**

Automatic merging is timesaving for easy merges, manual merges give you more control over resulting merged code.
