# Arvutiv-rkude-alused
Udacity networking for web developers
Lesson 1

Ping - saad vaadata kas ühendus sinu ja mõne muu hosti vahel on võimalik.
printf - saad sisestada teksti ja suudad eristada mõnda käsku näiteks \n et tekst hakkaks uuelt realt.
nc - andmete edastamine internetiühenduste vahel.
| (pipe) - outputi ülekandmine teise kohta.
-l - paneb nc kindlale portile kuuldele.
Control-D - disconnectib netcati portist.

    - Saab saata nc commandi vastuse file sisse.

Lesson 2

CTRL + C - lõpetab kindla protsessi näiteks ping käsu.
host - nagu DNS, veebilehe sisse kirjutamisel tõlgib selle IP-ks.
dig - nagu host, aga annab rohkem informatsiooni.

Lesson 3

käske eriti polnud, rääkis pigem sellest kuidas maailmas pole piisavalt IP aadresse kõigile ning sellele on juba lahendus. 
praegune lahendus on NAT süsteem, ruuteritel on private IP mis on maja peale jaotatud.

Lesson 4

tcpdump - Saab vaadata DNS trafficut.
rääkis miks on packetid vajalikud ja kuidas nad töötavad.
pika aja peale kui üks pool ei saa teiselt vastust siis ühendus katkeb.

Lesson 5

traceroute - näitab kõiki IP-si mida sa läbisid enne kui jõudsid soovitud aadressile.
käske oli vähe ja rääkis rohkem, et ruuter ei suuda lasta väga suurt arvu packeteid korraga läbi ning mida ta teeb selle jaoks.
rääkis ka, et seadmetel on firewall, mis filtreerib tegevust seadme ja võrgu vahel.

# Mida ma huvitavat teada sain
Portid 1023 ja vähem on reserveeritud.

IPv4 aadresseid on üle 4,3 miljardi

IP-d on jagatud octetidesse ja IP-l on eraldi veel host IP-d.

inimestel saavad olla samad IP-d kui nad on NAT-iga eraldatud.

ühendusvea asukohast saab teada errori käitumisest, näiteks TCP-ga "timeoutid".

sain teada kuidas timeout tekib.

interneti operaatorid nimetavad enda "node"-d läheduses olevate lennujaamadega, et neid oleks geograafiliselt kergem leida.

packetitel on Time to live, et ei tekiks infinite loopi.
