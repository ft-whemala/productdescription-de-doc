# Troubleshooting TSE-as-a-Service

## Hardware TSE-as-a-Service

### Subscription

Bei einer Verlängerung der Subscription, oder falls die zur Verfügung stehenden Signaturen der Hardware-TSE aufgebraucht wurden, erfolgt derzeit keine automatische Lieferung einer neuen Hardware TSE durch fiskaltrust. Der Tausch muss wie unten beschrieben über den fiskaltrust Händlersupport beantragt werden.

Die zur Verfügung gestellte Hardware TSE bleibt im Eigentum der fiskaltrust Germany GmbH und ist bei Tausch bzw. bei Ersatz sowie bei Vertragsende an fiskaltrust zurück zu senden.

### Störungsmeldungen

fiskaltrust leitet jene Störungsmeldungen von Kassenbetreiber an den verbunden Kassenhändler weiter, bei welchen der Kassenhändler die Möglichkeit hat bzw. es ihm zumutbar ist diese zu beheben. 

### Hardwareaustausch 

Für den Austausch einer Hardware-TSE im Rahmen von Garantie oder Gewährleistung oder für einen außerordentlichen Austausch im Rahmen der [Fair-Use-Bedingungen](../../for-posoperators/market-de-fair-use-policy.md) muss als erster Schritt eine Ticket-Nummer per E-Mail unter [support@fiskaltrust.de](mailto:support@fiskaltrust.de") angefragt werden. Rücksendungen müssen in den Empfängerdaten diese Ticket-Nummer enthalten. Bei Fällen, in denen die Rücksendung nach hin Sendung einer Vorabaustausch-Hardware-TSE erfolgt, muss die Rücksendung innerhalb von 14 Tagen bei fiskaltrust einlangen, ansonsten wird für das Vorab-Austauchgerät der reguläre Shop-Preis berechnet. 

Die Rücksende-Adresse ist: 

fiskaltrust gmbh

[Ticket Nummer]

Toulouser Allee 19a, 40211 Düsseldorf. 

Ein ordentlicher Austausch im Rahmen von den [Fair-Use-Bedingungen](../../for-posoperators/market-de-fair-use-policy.md) muss über die Plattform eingemeldet werden. Die Rücksendung der nicht mehr genutzten TSE muss entsprechend der Anweisungen der Plattform gehandhabt werden. Langt die Rücksendung der nicht mehr genutzten TSE nicht innerhalb von 14 Tagen beim fiskaltrust ein, wird für die zur Verfügung gestellte Hardware-TSE der reguläre Shop-Preis berechnet. 

## Cloud TSE-as-a-Service

### Verfügbarkeit 

Die Verfügbarkeit der Cloud-TSE ist entsprechend der Herstellerangaben:

| Qualitätskriterium          | Regelung                                                     |
| --------------------------- | ------------------------------------------------------------ |
| Ausfall:                    | FISKALY SIGN gilt für eine Minute als ausgefallen, wenn für mehr als 10% der in dieser Minute an der API eintreffenden Anfragen aller Nutzer von FISKALY SIGN ein Fehlercode (result code 5xx) resultiert, ausgenommen |
| Ausfallzeit:                | ist die Anzahl aller Minuten des Durchrechnungszeitraums, in denen eine Ausfall von FISKALY SIGN vorgelegen hat |
| Wartungszeit                | ist die Anzahl aller Minuten des Durchrechnungszeitraums, während derer eine angekündigte Wartung durchgeführt wird |
| Gesamtzeit                  | ist Anzahl aller Minuten des Durchrechnungszeitraums abzüglich der Wartungszeit |
| Verfügbarkeit:              | ist berechnet nach der Formel <br />Verfügbarkeit = (Gesamtzeit – Ausfallzeit) / Gesamtzeit |
| Vorwarnzeit für Wartungen:  | 3 Arbeitstage                                                |
| Zugesicherte Verfügbarkeit: | bis zu dem in der NICHTBEANSTANDUNGSREGELUNG genannten Datum 99,6% pro Monat, danach 99,95% pro Jahr |

Wenn Betriebseigenschaften und Laufzeitumgebungseigenschaften entsprechend den Zertifizierungsangaben erfüllt sind, wird fiskaltrust die Entstörung der Cloud-TSE mit dem Hersteller koordinieren. 

### Störungsmeldungen

fiskaltrust leitet jene Störungsmeldungen von Kassenbetreiber an den verbunden Kassenhändler weiter, bei welchen der Kassenhändler die Möglichkeit hat bzw. es ihm zumutbar ist diese zu beheben. 

Details bezüglich der Störungsbehebung der Cloud TSE sind im SLA für Kassenhändler enthalten.

## Weiterführende Informationen

[Fair Use Policy](../../for-posoperators/market-de-fair-use-policy.md)

[Feature Dokumentation](../../product-service-description/compliance-as-a-service/features/TSE-as-a-service.md)
