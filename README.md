# excel-configurator
Excel-basierter Produktkonfigurator – strukturierte Weiterentwicklung, Versionierung und Downloads.

Diese Vorlage entstand aus meiner Arbeit an variantenreichen Produkten und der Frage, wie man Angebotslogiken schnell verständlich abbilden kann – ohne sofort ein großes CPQ-System aufzusetzen.
Excel ist dafür überraschend gut geeignet, wenn die Struktur stimmt.

Der Konfigurator dient als pragmatischer Einstieg: eine Möglichkeit, Varianten sichtbar zu machen, Preislogiken zu testen und interne Diskussionen auf eine gemeinsame Basis zu bringen. Nicht mehr – aber auch nicht weniger.

⸻

Zielsetzung

Die Datei hilft, komplexe Produkte in klare Ebenen zu zerlegen und eine vollständige Angebotskonfiguration zu erzeugen. Sie unterstützt bei:
	•	strukturiertem Variantenaufbau
	•	nachvollziehbarer Preislogik
	•	Vorbereitung auf spätere Digitalisierungsschritte im Vertrieb

Sie soll Denkmodelle klären, nicht Prozesse digitalisieren. Dafür gibt es später bessere Werkzeuge.

⸻

Aufbau der Datei

Der Konfigurator ist modular aufgebaut und orientiert sich an vier Ebenen:

Produkt
Grunddaten inkl. Artikelnummer und Basispreis. Bis zu 50 Produkte möglich.

Sektion
Bauteile oder logische Bereiche des Produkts – maximal 10 je Produkt.

Element
Ausprägungen innerhalb einer Sektion, mit eigener Preislogik und beliebig vielen Varianten.

Konfiguration
Im Haupt-Reiter werden diese Bausteine per Dropdown kombiniert. Rechts entsteht automatisch eine vollständige Konfiguration mit Summenpreis.

⸻

Nutzung

1. Produktpflege – „Produktanlage“
	•	Produkte mit Name, Artikelnummer und Preis anlegen
	•	Sektionen definieren
	•	Elemente pflegen und sauber zuordnen (Produkt → Sektion → Element)

Ohne korrekte Zuordnungen greifen die Filterlogiken nicht.

2. Konfiguration – „Konfigurator“
	•	gewünschtes Produkt auswählen
	•	passende Sektionen und Elemente auswählen
	•	rechts erscheint die fertige Konfiguration
	•	Elemente können mehrfach gewählt werden

3. Ausdruck – „Ausdruck Konfiguration“
	•	Layout für PDF / A4 vorbereitet
	•	geeignet für interne Abstimmungen oder erste Kundenangebote

4. Berechnungstabellen (nicht anpassen)
	•	„Sektionsfilter“
	•	„Elementfilter“
	•	„Dropdown“

Diese Bereiche enthalten Hilfslogik für Filter und Preisberechnung.

⸻

Einordnung

Der Konfigurator ersetzt kein professionelles System.
Er ist bewusst einfach gehalten und erfüllt drei Aufgaben:
	•	Varianten sichtbar machen
	•	Logiken prüfen
	•	Anforderungen an spätere Systeme klären

Ich nutze diese Art von Templates regelmäßig in frühen Projektphasen – sie beschleunigen die Abstimmung erheblich, bevor es in echte Software geht.

⸻

Weiterentwicklung

Die Datei kann frei genutzt, erweitert oder verändert werden.
Wer etwas verbessert, kann die Änderung gerne als Pull Request einreichen oder als eigene Version veröffentlichen.

Dieses Projekt wird im Laufe der Zeit wachsen – abhängig davon, welche Logiken in realen Projekten sinnvoll sind und welche nicht.


⸻

Vorstellung

https://andreasrenk.de/impulse/excel-konfigurator-für-die-angebotskalkulation-ein-pragmatischer-ansatz
