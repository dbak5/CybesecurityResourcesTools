## <img width="441" alt="sss" src="placeholder" />

---

title: "Digital Forensics and Incident Response Tools and Resources"
tags: ["threat hunting", "windows", "event logs", "evtx", ]

---

# Tools

## Kali Linux Purple

Linux OS with pre-insatlled defensive tools \
https://www.kali.org/blog/kali-linux-2023-1-release/#kali-purple

## Volatility

https://blog.onfvp.com/post/volatility-cheatsheet/ \
https://www.osforensics.com/tools/volatility-workbench.html \
https://beguier.eu/nicolas/articles/security-tips-3-volatility-linux-profiles.html

## FTK Imager

Validating digital evidence

## Eric Zimmerman Tools

https://ericzimmerman.github.io/#!index.md

## Chainsaw

https://github.com/WithSecureLabs/chainsaw

## EVTX

A cross-platform parser for the Windows XML EventLog format \
https://github.com/omerbenamram/evtx

## EventFinder

Finds event logs between two time points. Useful for support/malware analysis \
https://github.com/BeanBagKing/EventFinder2

## Hayabusa

Windows event log fast forensics timeline generator and threat hunting tool \
https://github.com/Yamato-Security/hayabusa

## SANS Investigative Forensic Toolkit (SIFT) Workstation

https://www.sans.org/tools/sift-workstation/

## Event Log Explorer

For viewing, analyzing and monitoring events recorded in Microsoft Windows event logs \
https://eventlogxp.com/

## Autopsy

Open-source digital forensics platform \
https://www.autopsy.com/

## SOC Multitool

Browser extension with range of features and capabilities \
https://github.com/zdhenard42/SOC-Multitool

## SleuthKit

A library and collection of command line tools that allow you to investigate disk images \
https://www.sleuthkit.org/sleuthkit/index.php

## ssdeep

A program for computing context triggered piecewise hashes (CTPH), AKA fuzzy hashes \
https://ssdeep-project.github.io/ssdeep/index.html \

https://redis.com/blog/what-is-fuzzy-matching/

## PhishTool

Free forensic phishing analysis \
https://www.phishtool.com/

# Resources

## SIEMs

### Splunk

### Elastic (ELK Stack)

### SumoLogic

### LogRhythm

## Awesome Incident Response

Compilation of tools and resources \
https://github.com/meirwah/awesome-incident-response

## Notepad

Look at notepad history \
%localappdata%\Packages\Microsoft.WindowsNotepad_8wekyb3d8bbwe\LocalState\TabState

## List of File Signatures

https://en.wikipedia.org/wiki/List_of_file_signatures

## Registry Files

From registry files contained in: \
%SystemRoot%\System32\Config\

Registry files:

- Sam – HKEY_LOCAL_MACHINE\SAM
- Security – HKEY_LOCAL_MACHINE\SECURITY
- Software – HKEY_LOCAL_MACHINE\SOFTWARE
- System – HKEY_LOCAL_MACHINE\SYSTEM

### Timezones

Timezones are an important factor in digital forensics - need to be mindful of timezones. \
Further reading: \
https://kb.digital-detective.net/display/BF/Identification+of+Time+Zone+Settings+on+Suspect+Computer \
https://www.digital-detective.net/time-zone-identification/

System Registry File -> Root -> ControlSet001 -> Control -> TimeZoneInformation \
Easier to read using RegRipper!

### Network data

System Registry File -> Root -> Services -> Tcpip -> Parameters

### Computer name

System Registry File -> Root -> ControlSet001 -> Control -> ComputerName -> ComputerName

### Default size for the Windows EventLogs

System Registry File -> Root -> ControlSet001 -> Services -> EventLog -> Application -> MaxSize

Value is in bytes, need to convert to MB or GB

### Windows OS

Software Registry File -> Root -> Microsoft -> Windows NT -> CurrentVersion -> ProductName

## Windows Event IDs

https://www.ultimatewindowssecurity.com/securitylog/encyclopedia/default.aspx?i=j \
https://www.socinvestigation.com/windows-rdp-event-ids-cheatsheet/ \
https://ss64.com/ps/syntax-eventids.html \
https://alparslanakyildiz.medium.com/windows-event-ids-for-incident-response-cases-f3a069b8309f \
https://medium.com/@rajeevranjancom/windows-event-log-analysis-incident-response-guide-739af79b518b \

# Learn!

## TryHackMe Digital Forensics Room
