# Adding-SSH-KEY-GEN

To skip the passwords for logging into the remote machine or HPC/Clusters

- step_1 - ssh-keygen-t rsa (Generate the ssh key, if you are doing it for the first time.)
- step_2 - ssh-copy-id user@ip.address( ip address of the remote machine)
- step_3 - Enter the password for the remote machine once, and key gen will be generated.
