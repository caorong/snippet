# install crontab

yum install vixie-cron

And then start it with:

    service crond start

To make it persistent, so that it starts on boot, use:

    chkconfig crond on
