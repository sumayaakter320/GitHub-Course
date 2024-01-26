# History of Git Commits

- `git log` - Show all the commits with commit ID, Author, & Date
  - To exit git log - `q`
- `git log –oneline` - Show all the commit messages with 7 characters of id [Without other details]
- `git show / git show HEAD​` - Show the HEAD commit in detail​
- `git show commitId` - Show the commit of given in detail. Note: The whole id or only the first 7 characters of id can be taken​
- `git show HEAD~Number​` - To show previous commit according the number from HEAD commit [in details]​
- `git checkout commitId` - Delete the HEAD commit and HEAD is transfer to the given commit id and if there are more commit between HEAD commit and given id commit then all the commit will be deleted between HEAD and given id commit. [its kind of soft delete of commit]​
- `git checkout master/main` - Get back the deleted commit​
