# 14-Nov-2016
Installed LAME to allow encoding of WAV sound files to MP3.

{code}
wget https://slackbuilds.org/slackbuilds/14.1/libraries/lame.tar.gz
wget http://downloads.sourceforge.net/lame/lame-3.99.5.tar.gz
wget https://slackbuilds.org/slackbuilds/14.1/libraries/lame.tar.gz.asc
md5sum lame-3.99.5.tar.gz
tar zxvf lame.tar.gz
cd lame
mv ../lame-3.99.5.tar.gz .
./lame.SlackBuild
mv /tmp/lame-3.99.5-arm-1_SBo.tgz .
installpkg lame-3.99.5-arm-1_SBo.tgz
{code}

# Previous
Machine is a Raspberry Pi 2 (I think) and is running Slackware 14.1.  Is connected to two HDDs, ONE IS NTFS AND NEEDS REPLACING.

It's a straightforward "[Slackware ARM on a Raspberry Pi](http://sarpi.fatdog.eu/index.php?p=downloads)" install.
