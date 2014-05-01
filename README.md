#how to remove the novel excerpts you accidentally checked into your work github repository

###back on the master branch my changes are not visible

I find it hard to imagine that I am the only web developer out there who also spends his pomodoro time writing lists, essays and creative fiction. If like me your git workflow consists of a lot of ```git add .``` when you are under pressure for a fix or simply building out the early stages of a project with no set structure, then it's highly likely you have checked in a file by mistake.

Usually this is not a problem, even if you don't notice until several commits later. Junk files can be removed, and the next time you run add -A your file will be removed from the working tree. 

The beauty of git is it's metadata of course. One day you might find that you wanted your deleted file, and if you could remember how you had tagged it, or could guess within a certain period when you may have checked it in, then you can simple look through your github repository history until you find the file.

This is a great feature and the main reason a git based workflow has become almost ubiquitous amongst the programming community in recent years. The trouble comes when the file is something you really don't want your boss to see, the mysql password for her website say, or a drunken hachette job you wrote in the bar after work one day.