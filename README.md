# Log format description files for lnav
http://lnav.org is a powerful log file reader, designed to take multiple log files and order them by date. It understands log file formats using regular expresions and can highlight sections of line, find errors and warnings, and more.

This repository is for the log file format descriptions I've written so far.

# Installation for FortiSIEM Log format
1. Download the log file
2. Create a directory in your home directory if you don't have one
3. Place the log file(`fortisiem_phoenix.json`) in to the directory you created earlier.
Lnav should find the new format the next time you run it.

Commands bellow:
```shell
wget https://raw.githubusercontent.com/vlad-infra-admin/lnav-formats/main/fortisiem_phoenix.json
ls ~/.lnav/formats/installed/ || mkdir -p ~/.lnav/formats/installed/
mv fortisiem_phoenix.json ~/.lnav/formats/installed
```

4.(OPTIONAL)  You can manually load and install, run command  
`lnav -i fortisiem_phoenix.json`

# Phoenix Log Preview
![Image](images/fortisiem-phoenix-log-preview.png)
