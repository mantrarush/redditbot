Issue with pip install praw --
Problem:
Existing six installation deprecated, does not work on El Capitan, throws exception error during uninstallation attempt. 
Solution:
sudo -H pip install praw --upgrade --ignore-installed 	six
