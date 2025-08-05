# Rumba

Rumba is an HTTP/1.1 web server and client library written in Dyalog APL.

See the wiki for user documentation.

Rumba is based on the 6 RFCs for HTTP/1.1: RF7230-7235.

Rumba is written on top of Dyalog's Conga dll. When Rumba was first written, Conga supported TCP/IP, but not HTTP.
Thus Rumba has code (now obsolete) that parses incoming text streams into HTTP messages. 
This is still the default behavior. This will eventually be removed.
In the meantime the server has a  `UseCongaHTTP` property that may be set to use Conga's built-in HTTP parsing. 
