

Evan Hughes' First DBC Blog

Week1 - Command Line, Git, and GitHub

11/20/14

First of all, hello everyone, and welcome to my first blog post for Dev Bootcamp Phase 0!  It's been a really interesting week diving into this new material, and I'm excited to showcase some of the things I'm learning on this blog.

I think that Dev Bootcamp has set us up really well in this first week.  Instead of starting right into the code, we learned about using the command line, version control software, git, GitHub, Twitter, and other industry standard stuff.  In seeing how often I have used git and GitHub just in this first week, I can tell we're going to be using them A LOT, so a good understanding of how they work and why we use them is important.

Version control software (like git) keeps track of all the changes your make to a file. If you have a file that’s working great, then you add something that screws everything else up, you can simply go back to the previous version, and save youself a ton of time.  In one of our lessons they mentioned the analogy of a "checkpoint" in a video game.

So in this way, git is a very good resource for keeping track of the changes you make to a project.  Git is a program that runs locally on your computer (you don't need internet to use it), and is run through the command line.

GitHub by comparison, lives remotely (in internet-land).  So, how do you connect the two?  I started by forking (making a copy) of DevBootcamp's Phase-0 Unit-1 page on GitHub.  This essentially makes an exact copy, but to your GitHub profile, so that you can tinker with it all you want without changing the original.  You want to now clone this page to your drive, bringing it from internet-land to harddrive-land (GitHub to git).  Open your command line, cd to the place you want to drop the files, and type git clone (forkedURL).  Now you can work with the files on your computer.

The three  stages of a git tracked file are (you check this by typing git status)
  1.  untracked or modified (stuff has been changed, nothing's been done about it)
  2.  git add (filename) - ready to be commited
  3.  git commit -m (message) - saved as a version

Once you are happy with your changes, and they have been commited in git, you want to bring them back up to GitHub.  This is done by "pushing" them up to GitHib from your computer.  You do this by using a remote.  Type git remote -v to see which remotes you have available.  Type git push (remote_name) (branch_name) and you should be prompted for you username and password.  Once it's finished, check GitHub and the file that you were just working in on your computer is now up on GitHub!  Magic!  Or just really smart people creating really smart things.

In this way, git and GitHub are a really great way for multiple people to be working on the same thing, without everyone losing they're mind in trying to organize it all.  Say you have 500 lines of code, and everything is working great.  You get up to pee and your cat steps on your computer typing a ";" somewhere and messing everything up.  Type git status, notice something weird has happened, and revert back to the earlier version - and hours of pointless staring has been avoided.

Now imagine your working with 5 people in 5 different countries on a project.  GitHub makes it easy for everyone to see what the other person is doing, fetching everyone elses changes to make sure your version is current.  And checking to see that everything is working together.

It's hard to imagine it any other way right?

I have to say, a couple days ago, the whole idea of git and GitHub made ZERO sense to me.  And in just reading what seems like my semi-technical jargon, I'm just a little bit proud of myself.

Thanks for reading!  Hopefully this makes sense!  Fiddler Crabs represent.
-Evan