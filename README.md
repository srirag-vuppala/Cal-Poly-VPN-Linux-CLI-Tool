# Cal Poly VPN Linux CLI tool

A simple and easy way to connect to the Cal Poly VPN.

## Description

Unfortunately there is ~~minimal~~ **NO** support for the Cal Poly's VPN for linux users so I wrote a simple script that'll be able to start, stop and check the status of the VPN. 
* Additionally it'll work without having to give it my credentials every single time.

## Getting Started

### Installing
* Download the shell script from this repository 
* Enter in your cal poly user name and password in the starting of the file

```
...
USERNAME: <enter in here>
PASSWORD: <enter in here>
...
```
* Change the file permission to become a executable
```
chmod +x cpvpn
```
* Move it to your /usr/local/sbin
```
mv ./cpvpn /usr/local/sbin
```

### Executing program

This script must be run as a sudo user
* To start
```
sudo cpvpn start
```
* To check status of VPN 
```
sudo cpvpn status 
```
* To stop
```
sudo cpvpn stop
```

## Help

On the offchance that stopping it doesn't work try turning off your wifi and turn it back on.

* If you want to contribute to this script and make it better open a pull request with your suggestion. :rocket:
* If anything doesn't work go ahead and open an issue. :rotating_light:

## Version History

* 0.1
    * Initial Release
* 0.2
    * Added status checker

## License

This project is licensed under the GNU General Public License v3.0 - see the LICENSE.md file for details

