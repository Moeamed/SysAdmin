#Description
ggroupssetspamml is a bash script that fetch the full list of the Google Groups and bulk set the Spam Moderation Level

#Requirements
This script requires GAM configure to access a Google Apps account via OAUTH
http://code.google.com/p/google-apps-manager/
You need to plage the gam.py script in a common path i.e. /usr/bin

The 'cadaver' tool and 'python v2.5+' need to be installed in order for the script to work.
'cadaver' needs a .netrc file with WebDav's authentication information to be placed on the user's home folder.

ggroups2confluence requires a .gginfo file to be placed in path reachable by the user that will execute the script i.e. the homefolder, and its path need to defined in the ggroups2confluence script (~/.gginfo by default)

#Usage
It's advised to place the script in a common path i.e. /usr/bin.
When executed the script do not need any command-line parameter as it sources them from the .netrc and the .gginfo

#TODO
- Add the possibility to define command-line parameters to override/ignore the information in the .gginfo file
- Add the possibility to define command-line parameters to override/ignore the information in the .netrc file
- Add the '-v' (--version) parameter
- Add the '-h' (--help) parameter that shows the list of parameters and the usage examples

#License and Author
Author: Marco Massari Calderone (mmassari@inviqa.com)

Copyright (C) 2013 Inviqa UK Ltd

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.

