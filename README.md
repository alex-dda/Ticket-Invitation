GTE PARTY - Ticket-Generierungs-App

Dieses Projekt ist eine vollständige Web-Anwendung zur Registrierung für ein Event, zur dynamischen Preisberechnung und zur automatischen Erstellung von PDF-Tickets mit einem einzigartigen QR-Code.

Funktionen
- Dynamisches Formular:** Vollständig auf Deutsch mit Echtzeit-Validierung.
- Ländervorwahl: Automatische Anpassung der Telefonvorwahl (+49 / +237) basierend auf der Länderauswahl (DE / Cmr).
- Preiskalkulation: Automatische Berechnung des Ticketpreises in Echtzeit basierend auf dem Status des Teilnehmers (Intern: 15 € / Extern: 20 €).
- Echtzeit-Datenbank: Speicherung der Daten und Duplikatsprüfung über Firebase Firestore.
- PDF-Generierung: Automatischer Download eines strukturierten PDF-Tickets inklusive dynamischem QR-Code (via jsPDF & QRious).
- Ticket-Scanner (`scan.html`): QR-Code-Validierung am Einlass mit automatischer Statusaktualisierung in der Datenbank.

Technologien
- HTML5 / CSS3 (Responsives Design nach präziser Layout-Vorlage)
- JavaScript (ES6+)
- Firebase Firestore (Web SDK)
- Externe Bibliotheken: jsPDF, QRious, html5-qrcode
