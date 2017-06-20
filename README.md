# linuxTricks
A Note Bene list of useful Linux commands, properties and configuration


## Bash Configurations
Two modes of interacting with the kernel and each uses different config files

        1. "login" as a user
            - uses .profile, .login, .zlogin, .bash_profile, etc..
            - Special case: In MacOS, opening the terminal utilizes a login shell (uses .bash_profile)
        2. "Interactive mode" via a terminal
            - uses .bashrc, .tcshrc, .zshrc, etc...
            
These files can be used to configure session-wide environment variable
    
## Useful Commands
To set a environment variable:

        export VAR=FOO
        
To order files in a folder in their file size

        ls -lhS
        
To see disk partition and usage

        df
