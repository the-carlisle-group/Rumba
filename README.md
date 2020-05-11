# Rumba

Rumba is an HTTP/1.1 web server and client libary written in Dyalog APL. See the wiki for user documentation.
This ReadMe discusses issues related to working on Rumba itself.

Rumba is based on the 6 RFCs for HTTP/1.1: RF7230-7235.

Rumba is written on top of Dyalog Conga dll. When Rumba was first written, Conga supported TCP/IP, but not HTTP. Rumba does not currently take advantage of the relatively new HTTP support of Conga. though it may in the future.
