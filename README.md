iconv-for-windows
=================

iconv library for Windows (Microsoft Visual Studio Compiler) based on libiconv 1.14

Soltion file is compatible with Visual Studio 2012 only.

With pre-built configurations:

Release Win32  
Release Static Win32  
Debug Win32  
Debug Static Win32  
Release x64  
Release Static x64  
Debug x64  
Debug Static x64

It is built in "C:\git\iconv-for-windows"

Remember to use paths like  
ICONV_SOURCE, ICONV_SRC or ICONV_PATH = C:\git\iconv-for-windows  
and add it to the system/build variables:  
INCLUDE = C:\git\iconv-for-windows\include  
LIB = C:\git\iconv-for-windows\lib (or C:\git\iconv-for-windows\lib64)

All this code based on this article: http://www.codeproject.com/Articles/302012/How-to-Build-libiconv-with-Microsoft-Visual-Studio  
Thank you Youngho, you're great!