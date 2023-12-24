# myfirst-fullpipeline-project-in-cicd
Git to Kubernetes
## STEPS FOR SSH or Cloning a Github repo in EC2 instance

```ssh-keygen```

Generating public/private rsa key pair.
Enter file in which to save the key (/home/ubuntu/.ssh/id_rsa): 
Enter passphrase (empty for no passphrase): 
Enter same passphrase again:
JUST PRESS ENTER for above 3

```cat ~/ .ssh/id_rsa.pub```

Then copy those RSA key of ec2 and paste in Github > Setting>ssh keys
Then we can clone it.

