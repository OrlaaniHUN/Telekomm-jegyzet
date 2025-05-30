
I. Általános fogalmak és modellek
1. Hálózati elemek: hosztok, útválasztók (routerek), kapcsolók (switch-ek), hubok, hidak (bridge-ek), átjárók (gateway-ek)
2. Szolgáltatási modellek: foglalás-alapú (circuit-switching) vs. igény-szerinti (packet-switching) erőforrás-megosztás
3. Hozzáférési technológiák: DSL-variánsok (ADSL, VDSL), CATV/HFC, optikai FTTH, PON
4. Referenciamodellek: ISO-OSI modell (7 réteg, szolgáltatások, interfészek, rétegek kapcsolatainak áttekintése), TCP/IP modell (4 réteg) és hibrid adaptációk
5. PDU és enkapszuláció: fejléc/trailer a rétegekben, MTU-szempontok
6. Késleltetési összetevők: feldolgozási, sorbanállási, továbbítási, terjedési késleltetés; végpont–végpont késleltetés

II. Fizikai réteg
7. Jelek és átvitel alaptípusai, hatások: analóg vs. digitális; baseband vs. broadband, csillapítás, zaj, fáziseltolódás, frekvencia-szelektív fading, inter-szimbólum interferencia
8. Moduláció és multiplexelés: AM, FM, PSK (QPSK, QAM-16)
9. Statikus multiplexálás: TDMA, FDMA, CDMA
10. Szimbólum- és bitkódolás: NRZ, NRZI, Manchester, 4B/5B

III. Adatkapcsolati réteg
11. Keretezés és elválasztás: karakter-számlálás, bájt-stuffing, bit-stuffing, órajel-alapú keretezés
12. Hibakezelés - Redundancia, Hamming-távolság, kódteljesítmény
13. Paritás technika, Hamming kód
14. Ellenőrzőösszeg, CRC
15. Megbízható adatátvitel: Stop-and-wait (egysávú), alternáló-bit, csúszóablak (Go-Back-N, Selective Repeat), Átbocsátóképesség és kihasználtság elemzése késleltetés és hibák mellett
16. MAC alréteg: Pure ALOHA vs. Slotted ALOHA (hatékonysági képletekkel)
17. MAC alréteg: CSMA-változatok (1-persistence, p-persistence, non-persistence) vs. CSMA/CD
18. MAC alréteg: Alapvető bittérkép protokoll, Binary countdown protokoll, Adaptív fabejárás protokollja
19. MAC alréteg: Ehernet, LAN-kapcsolás és bridging: MAC-tanulás, továbbítási táblák, Spanning Tree Protocol

IV. Hálózati réteg
20. IP-címzés: IPv4: osztályok, alhálózatok, CIDR, IPv6: címtípusok, fejléc, automatikus konfiguráció, Routerek: leghosszabb prefix illeszkedés (LPM)
21. IPv4 Fragmentálás és újraegyesítés: IPv4 fragment-mezők, MTU-feltérképezés; IPv6 fragmentálás tilalma
22. Útválasztó algoritmusok: Távolságvektor (RIP, “count-to-infinity”)
23. Útválasztó algoritmusok: Link-state (OSPF, Dijkstra)
24. Útválasztó algoritmusok: Útvonalvektor (BGP: AS-útvonal, attribútumok, export/import szabályok)
25. ICMP-üzenetek: Echo, TTL túllépés, célállomás elérhetetlen
26. Címfeloldás: ARP, ARP szerepe

V. Szállítási réteg
27. UDP: fejlécmezők, ellenőrzőösszeg, tipikus alkalmazások
28. TCP alapok: fejléc, sorszámok és nyugta számok, kapcsolathoz tartozó állapotok, kapcsolat felépítése (három utas kézfogás)
29. Megbízható átvitel: nyugtázási stratégiák, újraküldési időzítők, fast retransmit/recovery (RENO)
30. Folyamszabályozás: csúszóablak, hirdetett ablak, hatás az átbocsátóképességre, Nagle algoritmusa
31. Torlódásvezérlés: Slow start, Additive Increase 
32. Torlódásvezérlés: Reno, NewReno, Cubic, Compound TCP, DCTCP
33. Aktív sor-kezelés (AQM): RED, ECN jelzés

VI. Alkalmazási réteg
34. DNS: hierarchia, zónafájlok, rekordtípusok (A, AAAA, CNAME, MX), rekurzív vs. iteratív lekérdezés
35. HTTP/HTTPS: metódusok, státuszkódok, header-ek, tartós vs. nem tartós kapcsolatok, TLS-kézfogás áttekintése
36. NAT, VPN