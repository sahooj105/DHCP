DHCP Server/Client for INET/INETManet 
=====================================

2014-03-26 Juan Carlos Maureira
	Refactored as an independent omnet++ project
	removed some "cout" log messages
	corrected example code 
	checked against INET-2.2.0

2013-08-22  ------ inet-2.2.0 released ------

2013-06-12  Zoltan Bojthe

	dhcp: NF_INTERFACE_IPv4CONFIG_CHANGED was fired without interface entry
	as argument

2013-04-16  Levente Meszaros

	Support for Lifecycle operations.

2013-01-30  ------ inet-2.1.0 released ------

2012-08-07  ------ inet-2.0.0 released ------

2012-06-28  Zoltan Bojthe

	Several fixes to the HDCP application. Added support to
	work with both ethernet and wirless interfaces.

2012-06-25  ------ inet-1.99.5 released ------

2012-06-11  Rudolf Hornig

	Added the DHCP protocol implementation.

	Code takeover from INETMANET-2.0.
	The original code is coming from https://github.com/jmaureir/DHCP
	written by Juan Carlos Maureira that was merged into
	INETMANET 2.0 by Alfonso Ariza Quintana
