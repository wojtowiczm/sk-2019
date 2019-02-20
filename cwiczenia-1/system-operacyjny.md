System operacyjny w środowisku sieciowym
=========================================

Charakterystyka systemu operacyjnego
------------------------------------

| Charakterystyka | wartość           | komentarz |
| ------------- |:-------------:| -----:|
| nazwa      | linux | lubuntu 18.10 |


Konfiguracja połączenia sieciowego
----------------------------------

| Parametr | wartość           | komentarz |
| ------------- |:-------------:| -----:|
| Adres IP      | 10.0.2.15 | przydzielony przez DHCP |
| Maska podsieci      | 255.255.255.0 | ifconfig |
| Brama      | 10.0.2.2 | ip r |
| DNS 1      | 127.0.0.53 | $ cat /etc/resolv.conf |
| DNS 2      |  | brak |

Schemat sieci
-------------

![alt schemat](https://github.com/wolak041/sk-2019/blob/master/cwiczenia-1/schema.PNG)
