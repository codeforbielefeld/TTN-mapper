# Wir bauen uns einen TTN Mapper:
## Meetup zu The Things Network

Wie flächendeckend ist unser Netz von The Things Network (TTN) in Bielefeld? Um diese Frage zu beantworten, hilft der TTN Mapper https://ttnmapper.org/ Die dargestellten Datenpunkte werden durch die Community gesammelt, dafür werden sogenannte Tracker z.B. beim Wandern oder Radfahren mitgeführt. 

Am Montag, 13. März 2023 wird Christoph uns die Funktionsweise dieser Tracker-Geräte erklären und uns zeigen, wie wir selber einen zusammenbauen können. 

Wenn ihr Hands-On dabei sein möchtet, bringt bitte mit: 

Hardware: [ESP32 LoRa SX1276 0.96 Inch OLED Display Development Board](https://amzn.eu/d/6haTsAN) (Anbieter für Einzelboards haben wir leider nur auf Amazon gefunden, es ist aber kein Muss bei Amazon einzukaufen, es ist auch kein Affiliate-Link). 
Für die Software bringt ihr bitte die Arduino IDE auf euren Rechnern mit und die Software hier aus dem Repo.

## Ein paar mehr Infos zum TTN Mapper:
Auf der Seite https://ttnmapper.org/ wird die Abdeckung des TTN-Netzes weltweit abgebildet. Die dargestellten Datenpunkte stammen von Trackern, die man mit sich führen kann, und die dabei regelmäßig ein TTN-Datenpaket mit ihren GPS Koordinaten abschicken. Erreicht das Datenpaket ein Gateway, ist also eine Netzabdeckung vorhanden, dann wird die GPS Koordinate auch auf der Karte dargestellt.  


## Du bist ganz neu bei The Things Network und fragst dich, was dahinter steckt? 
In wenigen Worten zusammengefasst, ist das TTN eine offene Netzwerkinfrastruktur. Das besondere ist, dass das dafür verwendete LoRaWAN eine hohe Reichweite hat und das versenden der Datenpunkte wenig Energie benötigt. Damit können Sensoren, z.B. im Wald, ein bis zwei Jahre Daten senden, ohne das ein Batteriewechsel nötig ist. Die Gateways zum empfangen und weitergeben der Daten an den Besitzer der Daten, werden durch die Community bereitgestellt und stehen für alle frei zur Verfügung. 

Kommt gerne vorbei, wir werden versuchen, alle deine Fragen zum TTN zu beantworten. Anmeldung bitte auf [Meetup.com](https://www.meetup.com/code-for-bielefeld/events/291550864/?isFirstPublish=true)

