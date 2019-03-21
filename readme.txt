
--------------------------------

Adding users for ssh connection

--------------------------------


1. Please make sure you ahve enabled ssh logging for the internal GIT repository.

2. Go to roles/add-users/vars/main.yml. Add relevant values for the following variables.

     - private_git_repo - Git URL of the private Repo. Please use SSH url. 
                          Eg: git@github.com:xxxx/xxxx.git

     - git_ssh_key_location - Git private key. Private key for the git repository

     - repo_directory - Repository for the Git clone.

     - user_playbook - Playbook file inside Git repository.
