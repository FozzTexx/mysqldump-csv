Copyright 2015 by Chris Osborn <fozztexx@fozztexx.com>
http://insentricity.com

Quick & dirty script to output all tables from a mysql database in
CSV format. Data is output from mysql as tab separated and a Python
script converts TSV to CSV. After dumping all tables everything is
zipped up and left in the current directory. Makes no attempt to
actually parse the arguments.

call like:
  mysqldump-csv --user=user --password=password dbname

==========  
  mysqldump-csv is free software; you can redistribute it and/or
  modify it under the terms of the GNU General Public License as
  published by the Free Software Foundation; either version 2, or (at
  your option) any later version.

