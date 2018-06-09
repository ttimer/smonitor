# smonitor
Java monitor to show server states - for Apache2, MySQL etc... - but also for start- and system monitoring - SMonitor

======================================= 

Already created for Ubuntu/i386:

sudo snap install smonitor

Feel free to transform ...

To 'snapcraft' the ttimer two folders, BIN and SNAP, and these five files had been used only:

    snap/snapcraft.yaml
    bin/smonitor.desktop
    bin/icon.png
    bin/smonitor
    bin/monitor
    smonitor.html (x3)

The monitor file is a shell script with a jar file as payload.
