# Rumba Release 0.1.10                    
1. Refactor MIME type lookup
2. Implement issue #34, issue #35 and issue #36

# Rumba Release 0.1.9 2020-08-14 10:45:03
1. GetCurrentUTCHTTPDate use .NET on Windows
2. Added new image mime types to lookup file

# Rumba Release 0.1.8 2020-06-10 16:05:35
1. Remove improper error guard from ParseParameters
2. Add IsQuery and IsFragment to ParseURI

# Rumba Release 0.1.7 2020-05-29 08:25:44
1. Remove documentaton menu and pages from web admin
2. Add NewURI as a synonym for ParseURI
3. Remove obsolete function Admin.StartServer
4. Move documentation to wiki
5. Touch up testing framework
6. Issues #21, #22, #23, #24, #25, #27 and #.28
7. Update README.md
8. Latest change to GetCongaDllPath withdrawn
9. GetCongaDllPath now checks the current dir first, then the project folder
10. SCM events added plus some improvements
11. X509 server property replaced by new properties, help improved and a couple of bug fixes
12. Help pages added for Certificates; Test server now RIDEable
13. Bug fix in Core.LogHTTPToSession
14. Tests for WindowsServices are back
15. Help system updated and typos fixed
16. Formatting corrected and ]ADOC-compatible info added

# Rumba Release 0.1.6 2019-10-14 15:06:56
1. Update acre config file

# Rumba Release 0.1.5 2019-10-09 13:39:51
1. Add Dev Folder param to acre config

# Rumba Release 0.1.4 2019-09-28 03:08:27
1. Add URL to acre config file
2. Removed redundant APLTreeUtils and stopped using NGET to read text due to normalizaion of line feeds
3. Default header Date and log entries now gets a true UTC time from conga
4. Change file download test to check for decoded content match
5. Added ability to set custom conga directory path.
6. add conga.dws to project source and add mac lib
7. Updated tests to use temp directory getter
8. Replaced default test directory with sub directory
9. Updates to conga runtime and tests
10. Minor changes
11. Improved details on server start.

# Rumba Release 0.1.3 2019-08-27 16:02:08
1. Added support for Conga3.1 for Dyalog 17 and Conga3.2 for Dyalog 17.1
2. Added conga3.2 to Win32 and Linux file assets

# Rumba Release 0.1.2 2019-08-27 12:41:26
1. Updated windows conga 64bit dll.
2. Added path validation test when obtaining conga.dll folders.
3. Use new folder structure for mime.csv source.
4. Fixed folder spelling
5. Use new DRC.Error function instead of DRC.ErrorTable
6. Refactored conga.dws to get Conga namespace from conga.dws source on init.
7. Update GetCongaDllPath-909.aplf

# Rumba Release 0.1.1 2019-08-26 11:24:17
1. Updated file directory structure.
2. Updated test certificates from Dyalog v17.1
3. Update NewClient-9.aplf
4. Update ClientLoop-41.aplf
5. Update Host-1.charlist
6. Latest Help system plus a couple of typos and '\''Host'\'' property changed

# Rumba Release 0.1.0 2019-05-21 10:05:58
1. Updated Conga to 3.1 and fixed minor bugs.
2. Assign name to Rumba threads.

# Rumba Release 0.0.0 2019-01-12 14:40:15
1. Rename to new extensions
2. Added AcreTools dependency requirement
3. Update gitignore
4. Added version to config file.
5. added comment to foo
6. Acre didnt properly readin crlf from a matrix.
7. CrLf optimization
8. Use static CRLF optimization
9. enhanced sesion logging
10. Update samplefile.txt
11. Added native file send and tests
12. Kai's test for secure get
13. Add IP to session logging
14. Test for empty form post
15. Handle empty post
16. Unnecessary to create secure sever
17. Added quadvars.   Acre was not proroperly propogating in nix.
18. Cleanup SSL initiation code.
19. Disable gzip when TLS is enabled
20. Save point
21. Introduce code to create a HTTPS server
22. SSL TLS Support for Client
23. Fix path for logging to be OS independent
24. Refactor CreateFolder to use native dyalog.
25. Updated config file
26. Modified acreconfig file.
27. Conga is no longer a required project dependency,
28. Added conga 3.0 for linux
29. Allow correct language detection
30. latest dyalog update to fix memory leaks
31. dyapp file to start the project using defualt system dyalog version
32. ignore and remove help cache file
33. Updated to latest Conga 3.0.1337.0
34. Conga 3 and Dlls import
35. Deleted obsolete files
36. Wholesale Changes
37. Wholesale changes
38. Changes
39. Added Files Folder
40. Initial commit
