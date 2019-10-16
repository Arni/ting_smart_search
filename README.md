# Ting smart search

This is a module that allows manipulation of the search results coming from the well.

To work optimally the module uses data from Webtrekk. The data feed from Webtrekk is
very large so Randers Bibliotek hosts an intermediary webservice which parses the files.
The code for the webservice is included in the extras folder.

The module uses a 20 MB data file to put the most relevant materials first in search
results. In order to have top performance the data file is saved as php array and
use the include statement to read it. For optimal performance a 20 MB increase to your
opcode cache maybe required.