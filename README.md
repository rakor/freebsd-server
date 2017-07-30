# freebsd-desktop
Script to setup a FreeBSD machine for server-use

This script is meant to be run once after a fresh installation of
FreeBSD. It will do an update of the system, install some packages
and setup some stuff you could like to have on a server machine such as
languagesettings, tmp-cleanup, ntp, OpenSMTPd, vim-lite, etc.

To get all benefits out of this script you should _not_ add a user during installation, but after having this script added some config-files to the homedir-skeleton. If you have added users nevertheless, the script will ask you to remove them in order to re-add them afterwards.


## Using this script
After having done a freh installation of FreeBSD (I'd recommend not to add a user during installation, but after this script has done its work) log in as root and download the script like this:
<pre><code>fetch --no-verify-peer https://raw.githubusercontent.com/rakor/freebsd-server/master/freebsd-server</code></pre>

If the script has done its job and everything went well reboot into your new desktop
<pre><code>reboot</code></pre>
