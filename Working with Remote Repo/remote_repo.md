# Working with Remote repo

![remote repo](../images/remote_repo.png)

1. Create a new repository

    ![creating remote repository [part-1]](../images/create_remote_repo.png)

    ![creating remote repository [part-2]](../images/create_remote_repo_2.png)

    ![creating remote repository [part-3]](../images/create_remote_repo_3.png)

2. Remote repo is created

    ![creating remote repository [part-4]](../images/create_remote_repo_4.png)

3. To push your code to the remote repository follow the following steps/commands
    - `git remote add origin remote-repository-link`
    - `git push -u origin main`
    - `git remote`
    - `git remote -v`
    ![git remote -v](../images/create_remote_repo_5.png)
    - push to the remote repo
        - `git push origin main` or
        - `git push -u origin main` - this means next time you don not need to write `origin main` only `git push` will work
        ![git push -u origin main](../images/create_remote_repo_6.png)
    - Now refresh the browser.
    ![remote-repository](../images/create_remote_repo_7.jpg)
