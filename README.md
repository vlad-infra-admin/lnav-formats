# Log format description files for lnav
http://lnav.org is a powerful log file reader, designed to take multiple log files and order them by date. It understands log file formats using regular expresions and can highlight sections of line, find errors and warnings, and more.

This repository is for the log file format descriptions I've written so far.

# Installation for FortiSIEM Log format
1. Create a directory in your home directory if you don't have one 
`mkdir -p ~/.lnav/formats`
3. Download and place a log file(`fortisiem_phoenix.json`) in to the directory you created earlier
`mv fortisiem_phoenix.json ~/.lnav/formats/`
4. Lnav should find the new format the next time you run it. You can manually load and install, run command 
`lnav -i ~/.lnav/formats/fortisiem_phoenix.json`

# Phoenix Log Preview
![Image](images/fortisiem-phoenix-log-preview.png)
