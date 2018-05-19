# hub-new-repo
Create a GitHub repository from command line tool.

## Settings
Please add the content of the .gitconfig in this replsitory to yours by copy and paste.
Also replace the <username> and the <token your-github-token> by yours.
  
You can get a GitHub token from here. 
https://github.com/settings/tokens

```
$ cat ~.gitconfig
```

After you added and replaced it, run following command.

```
$ source ~.gitconfig
```

## Usage
Please run the follwoing command in the local directory where you want to upload to GitHub.

```
$ git hub-new-public-repo
```

Then you can create the new repository in your GitHub. The repository name will be same as the directory that you are in.

Also you can create private repository.

```
$ hub-new-private-repo
```
