Java Install
http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html (Check for operating system bit in Control Panel\System and Security\System, probably 64 bit)

Git Install
Install Git https://git-scm.com/download/win
Can right click to start git bash

For adding already created public/private key pair
In Git bash type
"eval $(ssh-agent -s)"

Then add your private key to the ssh-agent
"ssh-add ~/.ssh/id_rsa"

Or you can create a config file and add details of the host, private key e.g
 host github.cartrawler.com
 HostName hostNameUrl(to be safe use the same name as the host)
 IdentityFile ~/.ssh/git_private
 User git
 IdentitiesOnly yes
 
 There are alternate answers here which are good
 http://stackoverflow.com/questions/4565700/specify-private-ssh-key-to-use-when-executing-shell-command-with-or-without-ruby
 
 
 Install Maven Here
 http://maven.apache.org/install.html
 Use apache-maven-3.*.*-bin.zip
 Extract to a folder in program File e.g ProgramFiles/Maven
 
 
