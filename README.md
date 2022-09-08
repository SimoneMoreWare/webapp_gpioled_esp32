# webapp_gpioled_esp32

Nell’articolo di oggi vedremo come utilizzare realizzare una web app (o server web totalmente autonomo) con ESP32. Il progetto in questione controllerà due pin GPIO ai quali sono collegati a due LED. Utilizzeremo Arduino IDE. Potremmo accedere con qualsiasi device su rete locale.

Lista componenti

ESP32-WROVER
Breadboard
2x led
3x jumper
GPIO extension board (falcolatitivo)

![alt text](https://i0.wp.com/www.moreware.org/wp/wp-content/uploads/2022/09/esp32-web-server-arduino-ide-parts-required.png?w=750&ssl=1)

Fasi salienti del progetto

Il server gestirà due pin GPIO.

Sarà possibile accedere al server WEB digitando l’indirizzo IP dell’ESP32 su broswer (rete locale).

Cliccando i bottoni che compariranno sul web server si può cambiare lo stato del LED da accesso a spento e viceversa.

Collegamenti

In seguito schema e diagramma di collegamento. Per costruire un circuito ricordati di tenere la scheda spenta.

![alt text](https://i0.wp.com/www.moreware.org/wp/wp-content/uploads/2022/09/esp32_web_server_schematic.png?w=984&ssl=1)

Codice

Se questo è il tuo primo articolo ti invito di leggere prima questo per l’installazione dei driver della scheda. Ecco qui un piccolo riepilogo prima di compilare e caricare il codice.

![alt text](https://i0.wp.com/www.moreware.org/wp/wp-content/uploads/2022/08/ltc-2.png?w=599&ssl=1)
![alt text](https://i0.wp.com/www.moreware.org/wp/wp-content/uploads/2022/08/ltc-3.png?w=557&ssl=1)

Compila il codice presente nella repo github

una volta fatto potremo visualizzare l’indirizzo IP che utilizzeremo per accedere via broswer dal monitor seriale.

![alt text](https://i0.wp.com/www.moreware.org/wp/wp-content/uploads/2022/09/ESP-IP-address-1.png?w=739&ssl=1)

# Accesso server web
Per accedere al server web, apri il browser, incolla l’indirizzo IP di ESP32 e vedrai la pagina seguente. 

![alt text](https://i0.wp.com/www.moreware.org/wp/wp-content/uploads/2022/09/asdawq.png?w=952&ssl=1)


