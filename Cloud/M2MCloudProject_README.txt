Explanation : 

openHab must be placed on /opt/openhab
Item contains item values taken by the broker (temp, humidity, uv)
Sitemap is the definition of the dashboard
Rules is uses to send mail notification at user given

To launch openhab, go on /opt/openhab directory
make "sudo ./start.sh"

An osgi terminal is started launching item, sitemap, rules and broker.
Wait for event, as soon as an event occured, a log is write on osgi terminal.

You can acces to dashboard by your network ip:8080/openhab.app

