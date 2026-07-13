# Deutsche Besucher am Flughafen Antalya: 2021 bis 2025

Wie viele Menschen aus Deutschland kommen jedes Jahr nach Antalya? Dieses Dataset beantwortet die Frage mit offiziellen Zahlen der Provinzdirektion für Kultur und Tourismus Antalya (Antalya İl Kültür ve Turizm Müdürlüğü) für die Jahre 2021 bis 2025.

*English: Annual arrivals of German nationals at Antalya airports (AYT and GZP), 2021 to 2025, based on official figures of the Antalya Provincial Directorate of Culture and Tourism. CC BY 4.0.*

## Die Zahlen im Überblick

| Jahr | Besucher aus Deutschland | Veränderung | Anteil an allen Besuchern | Rang |
|---|---|---|---|---|
| 2021 | 1.268.179 | | 13,9 % | 3 |
| 2022 | 2.826.000 | +122,8 % | 21,0 % | 2 |
| 2023 | 3.363.510 | +19,0 % | 21,4 % | 2 |
| 2024 | 3.517.589 | +4,6 % | 20,8 % | 2 |
| 2025 | 3.554.921 | +1,1 % | 20,8 % | 2 |

Kurz eingeordnet: 2021 lag Deutschland pandemiebedingt noch auf Platz 3, sogar knapp hinter der Ukraine. 2022 hat sich die Zahl mehr als verdoppelt. Seit 2023 kommen jedes Jahr über 3,3 Millionen deutsche Besucher, jeder fünfte Antalya-Gast reist damit aus Deutschland an. Nur Russland schickt mehr Besucher.

## Was genau gezählt wird

Gezählt werden Ankünfte deutscher Staatsbürger über die Flughäfen Antalya (AYT) und Gazipaşa Alanya (GZP) auf internationalen Flügen. Maßgeblich ist die Nationalität, nicht der Abflugort. Die Spalte `besucher_gesamt` umfasst alle Ankünfte (Ausländer plus im Ausland lebende türkische Staatsbürger) ohne Transferpassagiere. Die Spalten `veraenderung_vorjahr_prozent` und `anteil_deutschland_prozent` sind aus den Quellwerten berechnet.

## Dateien und Spalten

`antalya_deutsche_besucher_2021_2025.csv` und die JSON-Variante enthalten je Jahr: `airport_iata`, `airport_name_de`, `jahr`, `besucher_deutschland`, `veraenderung_vorjahr_prozent`, `anteil_deutschland_prozent`, `besucher_gesamt`, `rang_deutschland`, `quelle`, `quelle_url`, `hinweis`. Das Schema ist bewusst so angelegt, dass weitere Flughäfen als zusätzliche Zeilen ergänzt werden können.

## Quellen je Jahr

Alle Werte gehen auf die Daten der Antalya İl Kültür ve Turizm Müdürlüğü zurück, veröffentlicht über amtliche Erklärungen und Agenturmeldungen:

- 2021: Hürriyet, Jahresbilanz vom Januar 2022 (1.268.179 deutsche Besucher, 9.094.051 gesamt)
- 2022: Milliyet/DHA, Erklärung des Gouverneurs Ersin Yazıcı (2.826.000 deutsche Besucher, gerundete Angabe, 13.432.593 gesamt)
- 2023: Anadolu Ajansı (3.363.510 deutsche Besucher, 15.689.258 gesamt)
- 2024: Hürriyet/AA, Angaben von Tourismusminister Ersoy (3.517.589 deutsche Besucher, 16.925.349 gesamt ohne Transfer)
- 2025: Turizmdays und DHA, Jahresdaten der Provinzdirektion (3.554.921 deutsche Besucher, 17.122.548 gesamt)

Die vollständigen Quell-URLs stehen in jeder Datenzeile. Konsistenzprüfung: der in der Quelle genannte Zuwachs von rund 19 Prozent für 2023 deckt sich exakt mit dem Verhältnis der Werte 2022 und 2023.

## Lizenz

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.de). Nutzung frei, auch kommerziell, unter Namensnennung: „Daten: [flughafen-live.de](https://flughafen-live.de/flughafen-antalya/)". Aktuelle Ankünfte und Abflüge in Antalya in Echtzeit: [flughafen-live.de/flughafen-antalya](https://flughafen-live.de/flughafen-antalya/)
