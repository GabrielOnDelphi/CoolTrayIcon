This zip-file contains the two Delphi components, CoolTrayIcon and TextTrayIcon (tray icon components).
Refer to CoolTrayIcon.chm and install.txt for documentation.
See also convert_cti_projects.txt if you're upgrading from a previous version of CoolTrayIcon/TextTrayIcon.

If you redistribute this package, please include all original files.
Original site: http://subsimple.com/delphi.php http://www.songbeamer.com/delphi/


 Code updates 01.2023
 by GabrielMoraru.com

    Brought up to date for Delphi 10.4 and Delphi 11
    Code cleanup
    Reformatting
    Safer code
    Fixed some issue
    Added two extra functions
    Better documentation about how to use the components
    Let user know if MainFormOnTaskbar is True.

 Known issues
    1. It doesn work if Application.MainFormOnTaskbar= true. The requirement is to set MainFormOnTaskbar = false before Application.Run() is called.
    2. The TTrayIcon doesn't work properly if we call it during app start up. We can use a timer to check a bit later if the application needs to start minimized.

