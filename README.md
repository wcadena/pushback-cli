# pushback-cli

A dead-simple PushBack Client, written in PHP.

This tool was written to demonstrate PushBack email alerts in Nagios, as described in <https://www.booleanworld.com/guide-monitoring-servers-nagios/>.

la idea es usar:

#Instalacion del cliente pushback 
wget https://github.com/wcadena/pushback-cli/archive/main.zip
unzip -d /opt main.zip
cd /opt/pushback-cli-main
composer install
```
echo "Message Body" | /opt/pushback-cli-main/pushback-cli.php "Message Subject"
```
## License

The contents of this repository is under: <https://creativecommons.org/publicdomain/zero/1.0/legalcode>
