# JamaaSMPP
Jamaa SMPP Client is a .NET implementation of the SMPP protocol that focuses on providing an easy-to-use and robust SMPP client library for .NET developers. This project is intended to be used by developers who want to integrate SMS functionalities in their applications as well as students who are learning the SMPP protocol.

## Based On
This is created based on  https://jamaasmpp.codeplex.com/

### [Wiki](https://github.com/AdhamAwadhi/JamaaSMPP/wiki)

## [NuGet](https://www.nuget.org/packages/JamaaSMPP) ![#](https://img.shields.io/nuget/v/JamaaSMPP.svg)
	Install-Package JamaaSMPP


## SMPP Server Simulator
- Downlad from [http://www.seleniumsoftware.com/downloads.html](http://www.seleniumsoftware.com/downloads.html)
- Read User Guide [http://www.seleniumsoftware.com/user-guide.htm](http://www.seleniumsoftware.com/user-guide.htm)

# What's new?
- Support sending concatenated messages
- Fix Unicode Languages [issue #2](https://github.com/AdhamAwadhi/JamaaSMPP/issues/2). Allow user to set UCS2 encoding in SMPPEncodingUtil
 
        SMPPEncodingUtil.UCS2Encoding = Encoding.BigEndianUnicode; 