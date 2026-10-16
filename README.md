peek by blue: 1.4 @ October 15, 2026

peek {folders} [args]

-h|--help           shows usage
-v|--version        shows version
-a|--archive        archive files
-o|--old            find old files above 200 days to archive
-s|--status         get status of main and archive
-i|--inspect <file> get info on file (archived,size,etc)
-e|--exclude <dir>  exclude a directory

works only under ~/folders
drive file shifting

peek -a .
moves files from drive 1 to drive 2 (archive)

peek .
moves mirror files from drive 2 back to drive 1 (temporary usage)
