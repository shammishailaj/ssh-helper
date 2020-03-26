# Introduction

helps in interacting with the SSH configs stored.

TODO:
- add support for "configs" which are folders in the ~/.ssh folder which contain 
  identity files and their associated SSH config block
- these are loaded to create the ssh config file
- add a refresh command


- add maintenance mode, which allows ssh-helper to maintain the SSH config file. It will be
  marked with a specially formatted comment. This implies the file is autogenerated by ssh-helper
- if config file already exists, allow ssh-helper to make a backup of it, generate configs based off 
  it, and generate configs from it

