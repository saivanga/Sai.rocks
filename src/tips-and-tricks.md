---
layout: post-minimal.njk
title: Tips And Tricks
eleventyExcludeFromCollections: true
---

- While using JavaScript to set a font family, if your font includes a number, then make sure to add quotation marks (" ").

- To find out the details of your operating system use this command: `cat /etc/os-release`

Example output from my Ubuntu machine

```
NAME="Ubuntu"
VERSION="21.04 (Hirsute Hippo)"
ID=ubuntu
ID_LIKE=debian
PRETTY_NAME="Ubuntu 21.04"
VERSION_ID="21.04"
HOME_URL="https://www.ubuntu.com/"
SUPPORT_URL="https://help.ubuntu.com/"
BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
VERSION_CODENAME=hirsute
UBUNTU_CODENAME=hirsute
```

- To figure out the architecture of your computer, use this command:
  `uname -a`

Example

```
Linux sala 5.11.0-25-generic #27-Ubuntu SMP Fri Jul 9 23:06:29 UTC 2021 x86_64 x86_64 x86_64 GNU/Linux
```

- To get the SHORTER version of the architechure of your computer, use THIS command: `uname -i`.

```
uname -i

Example
x86_64
```

- To run docker, use this command: `sudo docker run --rm -it <image-name> bash`.

- To find a file inside the current directory: `find . -name "<file-name>"`.

- To make your system power off after 5 minutes of inactivity, in Linux, go to Settings >Power > and then change blank screen to 5 minutes.

- To find all folders with specific name in current directory use: `find . -name "<folder-name>" -type d`

Input:
`find . -name "node_modules" -type d | wc -l`

Output:

```
11
```

- To find all files with specific name in current directory use: `find . -name "<file-name>" -type f | wc -l`

Input: `find . -name "findme" -type f | wc -l`

Output:

```
1
```
