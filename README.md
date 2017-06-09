# linuxTricks
A Note Bene list of useful Linux commands, properties and configuration


## Bash Configurations
Two modes of interacting with the kernel and each uses different config files

        1. "login" as a user
            - uses .profile, .login, .zlogin, .bash_profile, etc..
        2. "Interactive mode" via a terminal
            - uses .bashrc, .tcshrc, .zshrc, etc...
            
These files can be used to configure session-wide environment variable
    
## Useful Commands
To set a environment variable:

        export VAR=FOO
