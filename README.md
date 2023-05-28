# D.A.R.V.

**Anmerkung**: dies ist eine detusche Übersetzung mit Hilfe eines Online-Übersetzers und manuellen Korrekturen des englischen Originalartikels von Robert Vice von https://www.cloudynights.com/articles/cat/articles/darv-drift-alignment-by-robert-vice-r2760 . Es gab eine Änderung der Reihenfolge (Absatz "Vorbereitungen") und einige Ergänzungen (in eckiger Klammer), die jedoch keinerlei inhaltliche Änderungen mit sich bringt, lediglich strukturelle oder Ergänzungen darstellen. Alle Rechte (auch der Bilder) liegen bei Robert Vice. Eine Vervielfältigung dieser Übersetzung oder Auszüge daraus sind daher nicht gestattet. Haftungsausschluss: Ich übernehme keine Verantwortung für Fehler, die durch die Verwendung dieser Übersetzung entstehen. Diese Seite ist nur für den persönlichen Gebrauch. 

Ich entwickle parallel ein Skript für Kstars, um dies für EKOS / INDI zu automatisieren: https://github.com/apos/kstars_scripts/tree/master 

## (DSLR / CCD Drift Alignment von Robert Vice) - Deutsche Übersetzung

Viele Jahre lang habe ich Zeit damit verbracht, die Star-Drift-Methode für die Ausrichtung meines Teleskops zu erlernen.  Obwohl es mühsam ist, hat es sich als sehr nützlich erwiesen.  Nachdem ich jedoch Nacht für Nacht damit vergeudet habe, das Teleskop richtig auszurichten, habe ich einen einfacheren Weg der Ausrichtung gefunden.

Wenn man die fotografische Methode der Ausrichtung an die neuere Technologie wie CCD-Kameras und DSLR-Kameras anpasst, kann man eine genaue Ausrichtung in nur wenigen Minuten statt in Stunden oder Tagen erreichen.

So gehen Sie vor: 

## Vorbereitungen

1. Stellen Sie Ihr Teleskop auf und richten Sie es normal aus.

2. Setzen Sie Ihre CCD- oder DSLR-Kamera in den Okularhalter ein oder befestigen Sie sie über den T-Adapter.

3. Stellen Sie den Stern für die CCD- oder DSLR-Kamera scharf.

Anmerkung durch den Übersetzer: Grundsätzlich verwendet die Methode 


## Azimuth (horizontale Einstellung)

2. Stellen Sie Ihr Teleskop so ein, dass es **genau nach Süden und auf 0 Grad Deklination** zeigt.

3. Suchen Sie einen halbhellen Stern.  Ein Stern der 6. Größenklasse eignet sich hervorragend, aber auch ein hellerer Stern kann verwendet werden.

4. Sobald der Stern fokussiert ist, bewegen Sie ihn **auf die rechte Seite des Kamerasensors**.

5. Stellen Sie Ihr Teleskop auf die niedrigste Antriebsgeschwindigkeit ein.  In der Regel ein Leitgeschwindigkeitsmodus.

6. Stellen Sie Ihre Kamerasoftware so ein, dass eine **Belichtung von 125 Sekunden erfolgt**.  Die ersten 5 Sekunden werden verwendet, um einen Referenzpunkt auf dem Bild zu erstellen.

7. Sobald die ersten fünf Sekunden verstrichen sind, **drücken Sie die Taste W (Westen)** auf der Teleskoptastatur, damit sich der Stern auf die gegenüberliegende Seite des Sensors bewegt. Bewegen Sie das Teleskop in der ersten Minute weiter nach Westen.  

8. **Sobald die erste Minute verstrichen ist, kehren Sie die Richtung des Teleskops sofort um[, und behalten die Bewegung nach Osten (Taste E) bis zum Ende der Aufnahme für die zweite Minute bei]**

9. Wenn die zweite Minute abgelaufen ist, hören Sie auf, das Teleskop zu bewegen.

10. Nachdem das Bild heruntergeladen wurde, sollten Sie ein Bild erhalten, das dem untenstehenden ähnelt.

![image](https://github.com/apos/d_a_r_v/assets/456034/48e8a3ed-07aa-48c4-82b9-1adbc3d02c2e)

Dies ist ein erstes Bild, das aufgenommen wurde.  Was Sie sehen, ist der Winkel der Abweichung. Wir versuchen, aus < [dem spitzen Winkel] eine durchgezogene Linie zu machen.  Um dies zu korrigieren, müssen wir einige Anpassungen am Azimut der Teleskopmontierung vornehmen.  Beachten Sie, dass der anfängliche Sternpunkt tiefer liegt als der Punkt, an dem die Aufnahme beendet wurde.  Dies zeigt uns, dass das Teleskop zu weit nach Westen ausgerichtet ist.  Um dies zu beheben, nehmen Sie eine **Korrektur an der Azimutsteuerung vor, um das Teleskop nach Osten zu bewegen**.


11. **Führen Sie nun die gleichen Schritte erneut durch [bis die Linien exakt übereinstimmen]**.  Wenn das Bild heruntergeladen ist, sollte es zeigen, dass der Abweichungswinkel kleiner geworden ist.

- Hier haben wir das zweite Bild aufgenommen.  Obwohl beide Bilder identisch aussehen, hat sich der Abweichungswinkel leicht verringert.  Ich muss weitere Korrekturen am Azimut vornehmen.

![image](https://github.com/apos/d_a_r_v/assets/456034/19b85bb7-23dd-4d24-b58d-3dd13a7a88c5)

- Hier habe ich eine weitere Korrektur vorgenommen, und der Abweichungswinkel hat sich ein wenig verringert.  Muss aber noch einmal korrigiert werden.
 
![image](https://github.com/apos/d_a_r_v/assets/456034/cd5a7f20-51da-4e49-a64e-24757b35f393)


- Hier sehen Sie die leichte Abnahme der Abweichung gegenüber dem letzten Bild.  Es müssen noch weitere Korrekturen vorgenommen werden.
 
![image](https://github.com/apos/d_a_r_v/assets/456034/928e4bf2-6f4b-488d-bcf2-527579f1f4b4)


- Jetzt können Sie sehen, dass sich der Abweichungswinkel noch weiter verringert hat.  Wir werden weitere Korrekturen am Azimut vornehmen.

![image](https://github.com/apos/d_a_r_v/assets/456034/98b7636b-c3f9-4f0e-9386-e74cac3454bd)


- Da wir weiterhin Korrekturen vornehmen, hat sich der Winkel der Abweichung stark verringert.  Wir sind jedoch noch nicht fertig.  Nehmen Sie noch einige weitere Korrekturen am Azimut vor.

![image](https://github.com/apos/d_a_r_v/assets/456034/5f8995dc-30bc-43e7-85df-457b063fec6a)

- Here you can see we have almost eliminated the angle of deviation.  Make a few more corrections.

![image](https://github.com/apos/d_a_r_v/assets/456034/f66d3e1f-1a87-4c1c-a040-4ddc8008fb6a)


- Hier sind wir fast fertig, aber es ist immer noch etwas daneben.  Ich werde eine weitere Korrektur vornehmen.

![image](https://github.com/apos/d_a_r_v/assets/456034/e13be248-b579-4119-a999-24ba3e5d0473)

12. Das Endergebnis.
Hier ist eine letzte Korrektur.  Der Sternenschweif ist eine einzelne durchgezogene Linie.  Der Abweichungswinkel ist jetzt 0.

![image](https://github.com/apos/d_a_r_v/assets/456034/c9b0bb31-791b-4e2a-a8c8-d46173f728e2)


# Altitude (Einstellen der Höhe)
Sobald Sie den Azimut festgelegt haben, müssen Sie die Höhe festlegen.  

13. Dazu stellen Sie das Teleskop einfach auf **einen Stern am Ost- oder Westhorizont und auf 0 Grad Deklination (DEC)**. 

14. Der einzige Unterschied besteht darin, dass wir diesmal die Höhe und nicht das Azimut einstellen.  Die Bilder sind identisch, wenn Sie die Höhe einstellen.  Allerdings müssen Sie die Höhe entsprechend anpassen.  Hier müssen Sie die Höhe entweder erhöhen oder verringern, bis der Sternenschweif eine einzige durchgezogene Linie ist.  

# [Da Capo al fine]

15. Wenn Sie mit der Höheneinstellung fertig sind, gehen Sie zurück und überprüfen Sie die azimutale Ausrichtung.  Wenn alles in Ordnung ist, sind Sie fertig.

# Weitere Informationen

Wenn Sie das richtig machen, haben Sie ein sehr genau ausgerichtetes Teleskop. 

Die verwendeten Bilder sind eine zweiminütige Belichtung, die zu Demonstrationszwecken gemacht wurde.  Sie können die Belichtungszeit erhöhen, um die Genauigkeit zu verbessern.

Anhand der Größe des CMOS-Sensors und des Sichtfelds meines 8-Zoll-Objektivs mit f/6,3 können Sie sehen, dass ich einen großen Bereich zum Spielen habe.  Zwei-Minuten-Belichtungen nutzen nur einen kleinen Bereich meiner Kamera/Teleskop-Kombination.  Wenn nötig, könnte ich die Belichtungszeit verlängern und etwa 10 Minuten benötigen, um den gesamten Rahmen abzudecken.  Das würde eine viel genauere Ausrichtung ergeben als eine zweiminütige Belichtung.

Seien Sie also mutig und experimentieren Sie mit den Belichtungszeiten, um herauszufinden, wie lange Sie arbeiten können und wie genau Sie Ihr System einstellen können.

(Hinweis: Diese Methode wurde mit einem gabelmontierten Teleskop angewendet.  Diejenigen, die ein GEM verwenden, müssen andere Korrekturen vornehmen, aber diese Methode funktioniert auch mit ihnen und wird ihre Genauigkeit genauso erhöhen).

Urheberrecht © 2003 - 2011
Robert Vice

Klicken Sie [hier](http://rcfotos.selfip.net/darv/DARV.pdf), um eine Kopie im PDF-Format herunterzuladen.
