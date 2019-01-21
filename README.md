# MYSQL Utilities 1.6.5 Mysqldiff patch.  

Mysqldiff tool in MYSQL Utilities 1.6.5(latest version) has serious bug with connector, which prevents authentication with MYSQL Server 8.0+. I made changes to mysql python connector.


## Error message:
`Authentication plugin 'caching_sha2_password' is not supported`


# Usage

Copy and paste these files into utilities folder where mysqldiff.exe/mysqdiff.bat is located. 
