# Operating Systems

## Development
I use WSL2 (Windows Subsystem for Linux) for development. It's a Linux kernel running on Windows. I use Ubuntu 22.04 for the most part, because it is compatible with most things and is very stable. Lots of people like Fedora or Arch for dev - if that suits your fancy then more power to you. Refer to the terminal page for more info on that.

### Setup: [Microsoft Docs](https://learn.microsoft.com/en-us/windows/wsl/install)

## Deployment
I generally prefer Rocky 9 for deploying stuff. It is a fork of RHEL9, the leading (paid) stable distro. Rocky is free, and is a drop-in replacement for RHEL. I swapped to Rocky after Red Hat killed CentOS and have had almost no problems. You can pretty easily find support for RHEL, and it will all work with Rokcy without a hitch. You can just select Rocky when firing up your VMs. You can also very easily use AWS' operating system , AL2/AL2023. I have had a lot of experience with it and have not had any problems.