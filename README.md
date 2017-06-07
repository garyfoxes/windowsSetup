# Java Install

http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html (Check for operating system bit in Control Panel\System and Security\System, probably 64 bit)

# Git Install

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
 
 
# Install Maven Here

 http://maven.apache.org/install.html
 
 Use apache-maven-3.*.*-bin.zip
 
 Extract to a folder in program File e.g ProgramFiles/Maven
 
 
# Install Ruby Here
 
 https://rubyinstaller.org/
 
 
# Envionment Variables:
 
 Set JAVA_HOME M2_HOME to the location of the packages, for Java its the jdk, for maven its the root directory e.g .C:\Program        Files\Maven\apache-maven-3.3.9
 
 In the path variable add the %JAVA_HOME%\bin;%M2_HOME%\bin
 
# Using Putty and Pagent(Used it with source tree for using ssh keys)
 https://www.digitalocean.com/community/tutorials/how-to-use-pageant-to-streamline-ssh-key-authentication-with-putty
 
# Install Python

 https://www.python.org/downloads/
 
 Install version 2.7
 
# If having problems with npm install do the following
 run in administrator privileged command prompt window
 
 npm install --global --production windows-build-tools
 
 npm install --python=python2.7
 
 
# Installing Node 
https://nodejs.org/en/download/

If having problems with node run
git config list -l
git config set cache C:\Users\gfox\AppData\Roaming\npm-cache
set the prefix in programfiles\node\nodemodules\npmrc to C:\Users\gfox\AppData\Roaming\npm
set environment variable path to C:\Users\gfox\AppData\Roaming\npm


 # Installing Android SDK
 Install Android Studio here https://developer.android.com/studio/index.html?gclid=CjwKEAjwq5LHBRCN0YLf9-GyywYSJAAhOw6mxkgZYqmyZYtwuDsIzdzirlrF7MvxqW3sD6Ho4sU30RoCtZTw_wcB
 
 On Mac if you cannot launch the dmg can launch through the command line via https://apple.stackexchange.com/questions/73926/is-there-a-command-to-install-a-dmg
 
 There is a sdk manager and avd manager in there when you install.
 
 Alternatively you can down load the command line tools here at the same link(located at the bottom of the page)
 
 Create environment variables for where sdk is located (if use android studio it is located in C:\Users\gfox\AppData\Local\Android\sdk)
 
 Add Environment Variables set ANDROID_HOME to C:\Users\gfox\AppData\Local\Android\sdk
 And add to path %ANDROID_HOME%\tools %ANDROID_HOME%\platform_tools 
 
 If you cannot use Haxm when creating an avd start up the BIOS on reboot either f1 or f11 -> go to BIOS and in one of the tabs there is an option for enabling Hardware acceleration.
 
 https://support.lenovo.com/ie/en/solutions/ht500006 for setup with lenovo
