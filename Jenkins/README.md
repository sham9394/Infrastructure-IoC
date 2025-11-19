🔐 1. Fix Jenkins SSH HostKey Checking

Create the SSH config file: vi /var/lib/jenkins/.ssh/config

Insert: Host * StrictHostKeyChecking no UserKnownHostsFile=/dev/null

Restart Jenkins: sudo systemctl restart jenkins
