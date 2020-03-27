How to add your local repository to Github using visual studio code

1) First login to your github account in a broser and create a repository 
    into which the files must be uploaded and stored.
2) Copy the link of the repository and execute the below given following commands -

3) git init		<!-- Navigate to the local project directory and create a local git repository -->
4) git remote add origin https://github.com/YourAccountName/YourRepositoryName	 <!--maps the remote repo link to local git repo -->
5) git remote -v					  <!-- this is to verify the link to the remote repo -->
6) git add FILE_name/FOLDER_name			<!-- adding the files or folders to be commited -->
7) git commit -m "initial commit" 			<!-- commting the files with a comment "initial commit" -->
8) git push -u origin master				<!-- pushes the commit-ed changes into the remote repo -->
