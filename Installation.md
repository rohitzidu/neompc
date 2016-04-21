## Requirements ##

  * PC configured to run Music Player Daemon (MPD).

  * PC configured to run a web server (Apache or Lighttpd) with PHP and (optionally) GD library support. This can be the same machine as the MPD server.


## Installation Steps ##

  * Download and extract the NeoMPC archive to the www directory on your web server.

```
 $ tar -xjvf neompc-0.4.tar.bz2
```

  * Check the permissions on the imagecache and smarty/templates\_c directories and assign 777 permissions to them both if not already there.

```
 $ cd neompc
 $ chmod 777 imagecache
 $ chmod 777 smarty/templates_c
```

  * Edit the configuration file to reflect your system and preferences. Information about each configuration option is available in the config file itself.

```
 $ nano config/config.inc.php
```

  * Navigate to NeoMPC with your webbrowser!


## Troubleshooting ##

(to be done)