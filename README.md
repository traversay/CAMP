# CAMP
Cygwin Apache-Mysql-PHP [ install | remove | start | stop | status ] shell script

Having trouble finding out how to run an AMP server from Cygwin ?
Look no further: camp will handle it !

Quick start
-----------

camp is a simple shell script.

It checks that at a minimum, Cygwin packages 'httpd', 'mysqld' and 'httpd-mod_php5'
are installed, so you will have to install them first with the Cygwin Setup program.

To install, run from a Cygwin Terminal:

    lynx -source https://github.com/traversay/CAMP/raw/master/camp >/usr/local/bin/camp

or

    wget https://github.com/traversay/CAMP/raw/master/camp -O /usr/local/bin/camp

then

    chmod +x /usr/local/bin/camp

To use, you may need to start camp with Administrator privileges if in Windows Vista and later.

You can do this by righ-clicking on the Cygwin Terminal icon and choosing "Run as Administrator".

The basic commands are:

    camp install	# to install the required cygserver as a Windows service
    camp remove		# to remove the cygserver Windows service (need to 'stop' first)
    camp start		# to start CAMP
    camp stop		# to stop CAMP
