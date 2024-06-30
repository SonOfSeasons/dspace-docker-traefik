# Notes on API

The configuration from the DSpace repository needs to be mounted into this container to get the confuration needed.

To migrate, use the instructions in the official DSpace documentation about [data migration](https://wiki.lyrasis.org/display/DSDOC7x/Migrating+DSpace+to+a+new+server).

I was unable to clean the database using the recommended DSpace commands, so I had to manually remove the database from the db container. The I followed the instruction to create the database and to populate it using the steps in the [documentation](https://wiki.lyrasis.org/display/DSDOC7x/Installing+DSpace).