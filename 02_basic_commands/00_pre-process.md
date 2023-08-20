FIRST TIME GIT SETUP:

git config - Git comes with a tool called git config that lets you get and set configuration variables that control all aspects of how Git looks and operates.

Set up global configuration variables: So that the other developers know who is checking the code in and out and making the changes.

You need to do this only once if you pass the --global option, because then Git will always use that information for anything you do on that system. If you want to override this with a different name or email address for specific projects, you can run the command without the --global option when you’re in that project.

    - git config --global user.name "prabhashj07"
    - git config --global user.email "prabhashj07@gmail.com"
    - git config --list
            : To check the values
Stored in : ~/.gitconfig or ~/.config/git/config file

These variables can be stored in three different places:

1) (Above method) ~/.gitconfig or ~/.config/git/config file: Values specific personally to you, the user. You can make Git read and write to this file specifically by passing the --global option, and this affects all of the repositories you work with on your system.

2) /etc/gitconfig file: Contains values applied to every user on the system and all their repositories. If you pass the option --system to git config, it reads and writes from this file specifically. (Because this is a system configuration file, you would need administrative or superuser privilege to make changes to it.)

3) config file in the Git directory (that is, .git/config) of whatever repository you’re currently using: Specific to that single repository. You can force Git to read from and write to this file with the --local option, but that is in fact the default. (Unsurprisingly, you need to be located somewhere in a Git repository for this option to work properly)


- git help config OR git config --help :
        To see info about a verb (ex: config)
