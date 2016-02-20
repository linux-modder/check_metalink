# check_metalink
A script to check metalink contents.

Please run ./check_metalink --help for an overview of all arguments.

More documentation will follow.


## Modes of operation

The script has two modes of operation:

- It can check the master mirrors if the metalink content is up-to-date with master mirror contents.
For this, use the --check-master flag.

- It can check the mirrors provided in the metalink whether they have a valid repomd.
For this, use the --check-mirrors flag.

- IRC support,  if experiencing   repeated  misses on dnf update || dnf upgrade run with  fpaste and  share the link.  Sample  cmd code:

./check_metalinks |fpaste  
 /exec -o {prefix}/.check_metalink {--check-masters|--check-mirrors} |fpaste  // running this  in IRC  client  runs the  command with fpaste  and  outputs link directly  into chat room (for some clients like Konversation or  webchat the -o does not have support in which case use solely  /exec {prefix}/.check_metalink {--check-masters| --check-mirrors} | fpaste, sample  path would be  like ~/Git/check_metalink/.check_metalink
