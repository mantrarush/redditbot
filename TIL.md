1. Issue with ```pip install praw --```

Problem:
Existing six installation deprecated, does not work on El Capitan, throws exception error during uninstallation attempt. 

Solution:
```terminal
sudo -H pip install praw --upgrade --ignore-installed 	six
```
