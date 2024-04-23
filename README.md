
This tool can be used to parse an OpenStreetmap **.osm** file, possibly saved from josm
and write all nodes with a **fixme** tag to a GPX file.

This GPX file can then be used on a GPS Receiver or with OSMAnd.

Usage
=====

	./osm-fixme-to-gpx -i markers.osm -o markers.gpx

Dependencies
============

	apt-get install libgetopt-long-descriptive libxml-treepp-perl
	
