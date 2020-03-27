How to add your local repository to Github using visual studio code

1) > First login to your github account in a broser and create a repository 
     into which the files must be uploaded and stored.
     
2) > Copy the link of the repository and execute the below given following commands -

3) > Navigate to the local project directory and create a local git repository.

```git init```

4) > Maps the remote repo link to local git repo.

```git remote add origin https://github.com/YourAccountName/YourRepositoryName```

5) > This is to verify the link to the remote repo.

```git remote -v```

6) > Adding the files or folders to be commited.

```git add file_name/FOLDER_name```

7) > Commting the files with a comment "initial commit"

```git commit -m "initial commit" ```

8) > Pushes the commit-ed changes into the remote repo

```git push -u origin master```
