remotetest.unidata.ucar.edu host now combined with thredds-test server 
====
** This method of updating the remotetest server is defunct and should not be used! **

The remotetest.unidata.ucar.edu is no longer a standalone host.  

The `dts.war` and `d4ts.war` files are hosted on the same tomcat instance as the thredds-test server. 

* The `defunct` directory contains the old files and documentation for updating this host.
* The `thredds` directory contains the data used by this host.

Please reference the `threddstest/catalog.xml` file for `threddstest/remotetest` directory for more information.
