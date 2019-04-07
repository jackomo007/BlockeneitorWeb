<p align="center"><img width="200" src="https://dmitrypeleshenko.files.wordpress.com/2016/03/python.jpg"></p>
<p align="center"><img width="200" src="http://www.phoenixts.com/wp-content/uploads/2014/06/909852786_1357508933.png"></p>
<p align="center">BlockeneitorWeb</p>

## Windows:
1. Change the extension of the script, for example: web_block.pyd
2. Open Task Scheduler and create a new task to run with all the privileges 
3. Set the script and make that begin with the start up

## Linux or Mac:
1. Add the execution of this script to the CRON Table using the command: sudo crontab -e
2. Add in the end of the file: @reboot python3 /home/YOUR_NAME_SESSION/LOCATION_WHERE_PASTE_THE_FILE/web_block.py
3. Reboot

## Licence:
Open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

