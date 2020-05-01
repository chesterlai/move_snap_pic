easy tool to solve daily problem<br>
run below on crontab<br>
need to consider about the path<br>
it will move the snapshot which located in desktop to another folder<br>
0 10-17 * * 1-5 /Users/chester_lai/cron/move_snap_pic.sh<br>

* If there is "Operation not permitted" Error in MacOS,
  please grant /usr/sbin/cron into permission list.
  https://apple.stackexchange.com/questions/372768/on-catalina-how-can-a-cronjob-get-permission-to-touch-files-on-a-usb-disk
