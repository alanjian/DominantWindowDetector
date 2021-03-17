# FocusedWindowDetector(FWD)
* An easy way to retrieve the window switching event based on Go programing language


# Data Structure:
* The following informaiton will be collected by the FWD
1.  PK      : Primary key (IPAdr_SDa_STm)
2.  SDa     : Window start focused date (YYYY-MM-DD)
3.  STm     : Window start focused time (HH:MM:SS)
4.  FWinHWND: Focused Window HWND(Handle to a window)
5.  FTm     : Window Focused Time
6.  FWinTit : Focused Window Title
7.  EDa     : Window end focused date (YYYY-MM-DD)
8.  ETm     : Window end focused time (HH:MM:SS)
9.  ScnZL   : Screen zoom level (1 = Normal, 1.5 = 150% Zoom in)
10. FWinPX  : Focused Window X coordinate start position
11. FWinPY  : Focused Window Y coordinate start position
12. FWinWid : Focused Window Width
13. FWinHei : Focused Window Heigh
14. IFType  : InternetFaceType (e.g., Ethernet or Wifi)
15. IPAdr   : InternetProtocolAddress
16. CompUUID: Computer Universally Unique Identifier

* Still not clear? Let's look at an example👇
* {"PK":"10.20.15.82_2021-03-17_11:34:42.73300", "SDa":"2021-03-17", "STm":"11:34:42.73300", "FWinHWND":"526862", "FTm":"0.93886", "FWinTit":"New Page - Google Chrome", "EDa":"2021-03-17", "ETm":"11:34:43.70078", "ScnZL":"1.50", "FWinPX":"-10", "FWinPY":"-10", "FWinWid":"2582", "FWinHei":"1403", "IFType":"Ethernet", "IPAdr":"10.20.15.82", "CompUUID":"707c296f-9e06-4198-b6b2-683c305f70e5"}


# Try it Now!
* X64 Version with CMD window
  * https://drive.google.com/file/d/1R3m52DCuTUqmgrssojrrBCQW3PcT1LpG/view?usp=sharing
