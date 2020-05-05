# How to to completely remove VSCode from mac

## VSCode has be the choice of editor for lot of programmers now , be it for Python,JS,Scala or Java editing/coding

Undoubtedly this is one of the best IDEs in recent times and Microsoft would be proud of their work. Even I use this charm of en editor as my daily driver.

Recently, I was trying to change some user settings to enable different formatter, in-process I messed up markdown preview, I realised I spent about 45 mins - 1 hour and still was not able to get it back to running.

Then I decided to uninstall VSCode and install again. I did the same but still the issue persisted , I was not able to able to preview markdown files.

After going through lot of stackoverflow questions I realised lot of poeple have faced the same issue , solutions being different , I chose to reset it and use my time to code instead of trying to get to the bottom of this problem.

Finally I was able to get it back to running.

This is how I did it.

1. Remove the VS Code settings from<br>
  `rm -rf $HOME/Library/Application\ Support/Code`

2. Remove all the settings and extensions<br>
  `rm -rf $HOME/.vscode`

That's it , no need to uninstall or install if you only need to just remove settings. Restart VSCode and everytihng should work normally.

If required you can do standard install again after uninstalling.
