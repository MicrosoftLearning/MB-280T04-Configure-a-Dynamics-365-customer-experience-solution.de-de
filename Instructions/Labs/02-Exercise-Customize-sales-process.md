---
lab:
  title: 'Übung 1: Anpassen des Verkaufsprozesses'
---

# Übung 1: Anpassen des Verkaufsprozesses

## Szenario: Contoso Home Security 
Contoso Home Security ist ein Unternehmen, das sich direkt an den Verbraucher wendet und Geräte für die Haussicherheit und deren Überwachung anbietet. Die Produkte umfassen smarte Türklingeln und Thermostate, verschiedene Sicherheitssysteme, Feuchtigkeitssensoren und vieles mehr. Da es sich um Endverbraucher-Produkte handelt, werden diese online und in Contoso-Einzelhandelsgeschäften in 11 großen US-Städten verkauft. Online-Kunden wird eine Kundenbetreuung zugewiesen. Ihre Aufgabe ist es, mit der Kundschaft in Kontakt zu bleiben und zu versuchen, ihr weitere Produkte und Dienste bereitzustellen. 

### Der Contoso-Vertriebsprozess
Darüber hinaus wird die Kundenbetreuung für alle Firmenkundinnen und -kunden eingesetzt, die sich für Sicherheitslösungen interessieren. Der Vertrieb an Firmen dauert im Allgemeinen länger und umfasst mehrere unterschiedliche Phasen und Aufgaben.

Der Vertriebsprozess kann z. B. die folgenden Phasen umfassen:

-   **Qualifizieren:** Hier versucht die Kundenbetreuung zu ermitteln, ob wir gut zu einer Kundin bzw. einem Kunden passen würden.
-   **Entwickeln:** Hier arbeitet die Kundenbetreuung mit anderen Mitgliedern des Vertriebsteams zusammen, um eine Lösung zu erstellen, die am besten für die Kundschaft geeignet ist. In dieser Phase sollte die Kundenbetreuung relevante Produkte aus dem Contoso-Produktkatalog benennen.
-   **Angebot:** Hier erstellt die Kundenbetreuung ein Angebot und unterbreitet es der Kundschaft. Ein Angebot kann mehrere Iterationen durchlaufen, bevor es zu einem Abschluss kommt.
-   **Tech Check:** Diese Stufe gilt nur für Geschäftsabschlüsse, die mit mehr als 20.000,00 US-Dollar veranschlagt werden. Diese Lösungen müssen vor einem Abschluss von der technischen Fachberatung geprüft werden.
-   **Abschluss:** Hier erläutert die Kundenbetreuung noch einmal das gesamte Angebot und stellt sicher, dass die Kundschaft zur Unterzeichnung bereit ist.

### Leadpflege 
Contoso verfügt auch über ein Lead-Nurturing-Programm, das eingesetzt wird, um die Chancen auf einen Geschäftsabschluss zu maximieren. Das Lead-Nurturing-Programm umfasst Folgendes:

1.  **Einführender Telefonanruf:** Die Kundenbetreuung ruft bei der Kundschaft an, um Contoso und die Produkte vorzustellen, die wir verkaufen.
2.  **Informations-E-Mail:** Einen Tag nach dem ersten Telefonanruf sendet die Kundenbetreuung der Kundschaft eine E-Mail. Die E-Mail enthält Details zu Contoso Home Security und den angebotenen Produkten.
3.  **Folge-E-Mail:** Drei Tage nach der Informations-E-Mail wird eine weitere E-Mail an die Kundschaft gesendet, um zu schauen, ob es Fragen gibt, die wir beantworten können.
4.  **Telefonanruf zur Terminvereinbarung:** Zwei Tage nach der Folge-E-Mail sollte ein weiterer Telefonanruf erfolgen, bei dem die Kundenbetreuung sich um einen Termin mit der Kundschaft bemüht, um festzustellen, ob eine Eignung vorliegt oder nicht.

### Wichtige Details
-   Der Lead-Nurturing-Prozess sollte nur bei Kundinnen bzw. Kunden angewendet werden, die als Unternehmenskundschaft ausgewiesen sind.
-   Contoso Home Security nennt Verkaufschancen nicht Verkaufschancen, sondern **Abschlüsse**.
-   Wenn es um einen Betrag von über 20.000,00 \$ geht, sind technische Prüfungen erforderlich. Dieser Schritt ist unabdingbar. Es kann im Vertriebsprozess nicht weitergehen, wenn er nicht vollzogen wurde.
    -   Die technische Prüfung muss im Detail zusammen mit dem Angebot schriftlich nachgehalten und protokolliert werden. Folgendes ist festzuhalten: welches Teammitglied sie durchgeführt hat, das Datum, an dem sie abgeschlossen wurde, und alle anderen relevanten Details. Auch wenn alles in Ordnung ist, muss dies vermerkt werden.
-   Nicht alle Verkäufe von Contoso werden im CRM-System protokolliert.
    -   In Einzelhandelsgeschäften getätigte Transaktionen werden in einem separaten Point-of-Sale-System gespeichert.
    -   Onlinetransaktionen werden in einer separaten E-Commerce-Website gespeichert.
-   Contoso verfügt auch über ein Treueprogramm, bei dem sich Kundinnen und Kunden registrieren können. Auch diese Informationen werden in einer separaten Website gespeichert.

Da bei Contoso Kundeninformationen an mehreren Stellen vorliegen, ist es oft nicht einfach, sich ein vollständiges Bild von einer Kundin oder einem Kunden in der gesamten Organisation zu verschaffen. Eine Konsolidierung all dieser Daten in einer einzigen Ansicht wäre hilfreich.

Datenquellen finden sich unter den folgenden CSV-Datei-Pfaden:
- **Kundinnen und Kunden:**https://aka.ms/CI-ILT/Contacts
- **POS-Einzelhandelstransaktionen:**https://aka.ms/CI-ILT/POSPurchases
- **Online-Transaktionen:**https://aka.ms/CI-ILT/OnlinePurchases
- **Kundschaft im Treueprogramm:**https://aka.ms/CI-ILT/LoyaltySchemeCustomers

