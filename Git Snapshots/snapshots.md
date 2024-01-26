# What are the snapshots?

Now, as I mentioned already, the term snapshot means in Git actually a commit, so it is the same thing. But now, you know when you come across the term snapshot what it actually means. It means that Git does not store single file differences with a commit. Instead, Git creates a snapshot of all your files, with every commit. Now important to know is that it creates for every snapshot respectively for every commit a hash value.

![snapshot 4](../images/snapshots_4.png)

That hash value is a 40 characters long string that looks similar like this one. Such a hash value identifies a snapshot respectively a commit. This means that the hash value can be used to check out a specific commit from your repository. Checking out a specific commit can be useful when you look at the history of your code, then you can see what was actually the state of your code with that commit.

![snapshot 1](../images/snapshots_1.png)
![snapshot 2](../images/snapshots_2.png)
![snapshot 3](../images/snapshots_3.png)
