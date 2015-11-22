BNT_TDMS extends the CSPP_Core package of the CS++-Project. 

It contains a derived classes of
- CS++BaseActor

Refer to https://github.com/HB-GSI/CSPP for CS++ project overview, details and documentation.

LabVIEW 2015 is the currently used development environment.

Related documents and information
=================================
- README.md
- EUPL v.1.1 - Lizenz.pdf
- Contact: Holger.Brand@BrandNewTechnologies.de
- Download, bug reports... : http://github.com/HB-BNT/BNT_TDMS
- Documentation:
  - Refer to package folder

GIT Submodules
==============
This package can be used as submodule
- Packages\BNT_TDMS:
  - TDMSActor
  - TDSMContainer
  - TDMSData
  - Update TDMS-Data Msg

External Dependencies
---------------------
- CSPP_Core: http://github.com/HB-GSI/CSPP_Core

Getting started:
=================================
- Add BNT_TDMS.lvlib into your own LabVIEW project.
- You need to override the "Write Data to TDMS File Core.vi" in your derived class of TDMS-Actor-lvclass.
- You need to extend your actor classes to launch your derived TDMS-Actor class instance.
- You need to create your derived TDMS-Data.lvclass and override the corresponding dynamic dispatch VIs.
- You need to call a override the "Update TDMS-Data Msg.lvclass:Do.vi" in order to send data to yout derived TDMS-Actor class instance.


Author: Holger.Brand@BrandNewTechnologies.de

Copyright 2015  Brand New Technologies

Dr. holger Brand, Asternweg 12a, 64291 Darmstadt, Germany

Lizenziert unter der EUPL, Version 1.1 oder - sobald diese von der Europäischen Kommission genehmigt wurden - Folgeversionen der EUPL ("Lizenz"); Sie dürfen dieses Werk ausschließlich gemäß dieser Lizenz nutzen.

Eine Kopie der Lizenz finden Sie hier: http://www.osor.eu/eupl

Sofern nicht durch anwendbare Rechtsvorschriften gefordert oder in schriftlicher Form vereinbart, wird die unter der Lizenz verbreitete Software "so wie sie ist", OHNE JEGLICHE GEWÄHRLEISTUNG ODER BEDINGUNGEN - ausdrücklich oder stillschweigend - verbreitet.

Die sprachspezifischen Genehmigungen und Beschränkungen unter der Lizenz sind dem Lizenztext zu entnehmen.