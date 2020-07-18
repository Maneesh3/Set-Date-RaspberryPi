# Set-Date-RaspberryPi

#### Shelll script to set date and time in Raspberry Pi / any Linux distro.
Specially used for Raspberry pi, the hardware clock is not perfect.
This script will get get the date using `wget`, web-get-request to website `duckduckgo.com` (can be changed).
_Note:Requires Internet Connection_


## Installation & Useage

```bash
# clone the repo
$ git clone https://github.com/Maneesh3/Set-Date-RaspberryPi.git
# change the file permission to executable
$ sudo chmod +x Set-Date-RaspberryPi/setDatePi.sh
# run the script
$ ./Set-Date-RaspberryPi/setDatePi.sh
```
**or**
```bash
#copy and run the file setDatePi.sh contents in terminal
```

## TODO:
- [ ] Make the script auto run when the Pi is Powered ON

