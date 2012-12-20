#Setup

1. Create github account (send me the username so I can add you to the project as owner). No need to setup repositories or git.

2. Install [Aptana Studio 3](http://aptana.com/) (extract wherever)

3. Generate sshkey and add to your github account. See: [generating keys](https://help.github.com/articles/generating-ssh-keys)  
	**IMPORTANT**: Make a backup of your ~/.ssh/id_rsa and ~/.ssh/id_rsa.pub They are your keys. id_rsa	is the private one, don't share it with others, id_rsa.pub is public, you can share it. Leave them both in the ~/.ssh folder, Aptana will look for them there.

4.	In Aptana, import project (from git), address is `git@github.com:makeagame/the-game.git` 
For the workspace, when we start developping it will have to be in htdocs folder of the server installation (XAMPP) for deployment. See: [Setting up external server to preview PHP](https://wiki.appcelerator.org/display/tis/Setting+up+an+external+web+server+to+preview+PHP+and+other+non-HTML+pages). For now it doesn't really matter.
	
5.	In Aptana, in the App Explorer tab, you will see blue cog wheels. This is the button to use Git.
	* To get latest files from the repository, use ***pull***
	* To mark files as ready to be commited, use ***stage***.
	* To commit files, use ***commit***. You can also stage files from there (move from unstaged to staged area). A commit is like a push, except it will only be on your machine until you push it to the	repo. Think of it as a checkpoint/quicksave?
	* To send your changes to the repo, ***push*** (It will send the commits "checkpoints" to the repo). After that, there are other stuff like branches and merging files that we will have to figure out, but for now this is enough to get started.

## Some links
* [What stage means in git](http://programmers.stackexchange.com/questions/119782/what-stage-means-in-git-source-control)
* [Intro to Distributed Version Control](http://betterexplained.com/articles/intro-to-distributed-version-control-illustrated/)
* [Setting up external web server](https://wiki.appcelerator.org/display/tis/Setting+up+an+external+web+server+to+preview+PHP+and+other+non-HTML+pages )
* [PHP dev in Aptana](https://wiki.appcelerator.org/display/tis/PHP+Development)
* [Markdown](https://en.wikipedia.org/wiki/Markdown)
