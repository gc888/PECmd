# PECmd

Go here for more info

http://binaryforay.blogspot.com/2016/01/pecmd-v0600-released.html

Prefetch Explorer Command Line

    PECmd version 0.5.0.0
    
    Author: Eric Zimmerman (saericzimmerman@gmail.com)
    https://github.com/EricZimmerman/PECmd
    
    d               Directory to recursively process. Either this or -f is required
    f               File to search. Either this or -d is required
    k               Comma separated list of keywords to highlight in output. By default, 'temp' and 'tmp' are highlighted. Any additional keywords will be added to these.
    json            Directory to save json representation to. Use --pretty for a more human readable layout
    pretty          When exporting to json, use a more human readable layout
    
    Examples: PECmd.exe -f "C:\Temp\CALC.EXE-3FBEF7FD.pf"
    PECmd.exe -f "C:\Temp\CALC.EXE-3FBEF7FD.pf" --json "D:\jsonOutput" --jsonpretty
    PECmd.exe -f "C:\Temp\CALC.EXE-3FBEF7FD.pf" -k "system32, fonts"
    PECmd.exe -d "C:\Windows\Prefetch"


# Note: If you are running less than Windows 8 you will NOT be able to process Windows 10 prefetch files.

Open Source Development funding and support provided by the following contributors: [SANS Institute](http://sans.org/) and [SANS DFIR](http://dfir.sans.org/).
