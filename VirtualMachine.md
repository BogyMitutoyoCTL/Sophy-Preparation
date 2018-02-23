# Virtuelle Maschine

Eine virtuelle Maschine ist ein simulierter PC, der auf einem echten PC läuft. Das ermöglicht zum Beispiel, dass man Linux ausprobieren kann, obwohl man zu Hause nur einen PC mit Windows besitzt. Das Linux läuft dann in einem Fenster von Windows.

Damit der virtuelle PC seine eigene Festplatte bekommt, braucht man etwas Platz: etwa 12 GB solltet ihr dem virtuellen PC zuweisen. Die virtuelle Festplatte wird in einer Datei von Windows gespeichert (Endung VDMK oder VDI). Wenn Du den virtuellen PC löschst, kannst Du die Datei mit der Festplatte auch löschen und die 12 GB stehen Dir wieder zur Verfügung.

Es gibt mehrere Produkte, die einen virtuellen PC bereitstellen können:

* [VirtualBox](https://www.virtualbox.org/) (kostenlos, Extension Pack kostenlos für Privatnutzung) ([Downloads](https://www.virtualbox.org/wiki/Downloads))
* [VMWare Player](https://www.vmware.com/products/workstation-player.html) (kostenlos für Privatgebrauch) ([Downloads](https://my.vmware.com/de/web/vmware/free#desktop_end_user_computing/vmware_workstation_player/12_0)) 

Unser Raspberry verwendet Raspbian als Betriebssystem. Raspbian ist eine Abwandlung von Debian. Installiert wird ein Betriebssystem von einer virtuellen CD oder DVD, die im ISO Dateiformat bereitgestellt wird.

Downloads:

* [Debian mit Raspberry Oberfläche](https://www.raspberrypi.org/downloads/raspberry-pi-desktop/) (kostenlos), ca. 2300 MB, zum selbst installieren für VirtualBox
* [Debian CD](https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/debian-9.3.0-amd64-xfce-CD-1.iso) (kostenlos), ca. 650 MB, incl. XFCE Desktop zum selbst installieren für VirtualBox
* [Debian Virtual PC](https://www.osboxes.org/debian/) (kostenlos), ca. 1050 MB, fertig installierter virtueller PC für VMWare Player