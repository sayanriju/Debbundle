Debbundle is an Offline Installation tool for Ubuntu to help users who do not have Internet at there desktop/laptop and want to try an One-Click type installation for Linux systems.

This github repository is a fork of the original project (by Narendra Sisodiya) which is hosted at googlecodes.
## Download ##

   + svn checkout http://debbundle.googlecode.com/svn/trunk/ debbundle 

## How to create bundle ##
$ ./OneClickInstall_Deb_Creator? OutPutFilename? PackageList?

        EX $ ./OneClickInstall_Deb_Creator GFTP gftp gftp-common gftp-gtk gftp-text
        EX $ ./OneClickInstall_Deb_Creator Vim vim-gtk
        EX $ ./OneClickInstall_Deb_Creator KDE-Full-Package kde-desktop

this will download all necessary files and packages into single files called .OneClickInstall? file

## How to install bundle ##

   + From GUI - Just click on .OneClickInstall? File and click on "Run in Terminal"
   + From Console - ./Package.x86-64.OneClickInstall? 

        EX $ ./GFTP.x86-64.OneClickInstall
        EX $ ./KDE-Full-Package.x86-64.OneClickInstall

## Blog and Tutorials ##

   + [http://blog.narendrasisodiya.com/2011/05/how-to-install-software-package-on.html](http://blog.narendrasisodiya.com/2011/05/how-to-install-software-package-on.html)
   + [http://permalink.gmane.org/gmane.user-groups.linux.delhi/26596](http://permalink.gmane.org/gmane.user-groups.linux.delhi/26596)

## See Also ##

[Debshare](http://sayanriju.co.cc/debshare.html)
