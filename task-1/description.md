## Aufgabenstellung

Hilfe! Am Nordpol ist Weihnachtsstress ausgebrochen! Heute ist Weihnachten und der Weihnachtsmann katert seit Tagen seinen letzten Vollmilchrausch aus. Nun beschließen die Wichtel sich selbst zu kümmern. Dazu einigen sie sich auf den folgenden Plan: Am Anfang werden die beiden Schlitten schoneinmal angeschmissen, da diese vorwärmen müssen. Dann gehen alle 24 Wichtel zu ihrem Arbeitsplatz. Sie wissen, dass noch genau 10.023 Spielzeuge gebaut werden müssen. Wenn alle bereit sind, geht es los: Jeder Wichtel baut fleißig Spielzeuge. Aber da jeder Wichtel unterschiedlich schnell ist [1] und alle so schnell wie möglich fertig werden müssen beschließen sie, die Gesamtmenge an noch zu bauenden Spielzeugen nicht am Anfang aufzuteilen, sondern an eine große Wand zu projezieren. Um ein Spielzeug zu bauen geht ein Wichtel zur Wand und verringert die Zahl um eins. Damit `resertiert` er sozusagen das Spielzeug, das er gleich baut. Das gleicht nicht nur die Tagesform der Wichtel aus, sondern steigert auch noch die Moral! Wenn ein Wichtel ein neues Spielzeug reservieren will, es aber keine mehr zu bauen gibt, wartet er, bis alle Wichtel ihre Spielzeuge fertig gebaut haben.

Wenn alle Spielzeuge gebaut sind, treffen sich die Wichtel wieder und beladen die Schlitten. Diese ist in diesem Jahr besonders nice Modelle: Zwei Quadro Toupee Turbos mit tiefergelegtem Kutschbock. Die Geschenke werden gleichmäßig auf die Schlitten verteilt und die Arbeit der Wichtel ist getan. Nun können sie wieder Zuckerstangenzigaretten drehen und Scharade spielen. Die Schlitten müssen derweil die Geschenke ausfahren. In jedem Haushalt lädt ein Schlitten 1 bis 20 Geschenke aus. Dabei achten sie darauf, dass immer nur der Schlitten Geschenke ablädt, der noch mehr Geschenke hat. Wenn auch diese Arbeit getan ist drehen sie um und fliegen zurück zum Nordpol. Das letzte --- bevor sie nach dem langen Tag den V8 abstellen --- ist die gelangweilten Rentiere mit Lichthupen zu ärgern.

[1] je nach Tagesform braucht ein Wichtel zwischen 8 und 12 Millisekunden für ein Spielzeug, was zufällig ausgelost wird, wenn er seinen Arbeitsplatz erreicht.

## Anforderungen
- keine atomics
- kein `concurrent` modul
- keine pipelines
- kein fluchen wie doof alles ist

## Tips
<details>
  <summary>Tip 1</summary>
  Man braucht keinen Weihnachtsmann für diese Aufgabe
</details>
<details>
  <summary>Tip 2</summary>
  Schlitten und Wichtel sind unterschiedliche Klassen
</details>
<details>
  <summary>Tip 3</summary>
  Überlege für jeden Akteur (Wichtel, Schlitten, Weihnachtsmann) getrennt wie sein Lifecycle aussieht
</details>