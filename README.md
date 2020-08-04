This is a short HOWTO
to install audio-recorder on Linux Solus. Audo-recorder can be retreived via a ppa. Solus does not support that.

* Open http[:]//ppa.launchpad.net/audio-recorder/ppa/ubuntu/pool/main/a/audio-recorder/
* Download most current version (actually ... 3.1.3focal_amd64.deb)
* Unpack the deb file
* You will get 3 files: control.tar.gz, data.tar.gz, debian-binary
* Unpack data.tar.gz
* <b>Important: Check if merging will overwrite / modify any existing data on your OS!</b> This can damage your system
* Merge the content of usr folder into /usr.
* You can use rsync -a /path/to/source/ /path/to/destination
* Run glib-compile-schemas /usr/share/glib-2.0/schemas/
* Invoke audio-recorder (should run now)
* You also should have a starter in multimedia


