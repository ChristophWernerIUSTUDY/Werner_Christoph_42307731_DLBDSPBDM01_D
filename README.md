Buchtausch-App-Datenbank
Dieses Repository enthält den SQL-Code und die Dokumentation zur Implementierung einer Datenbank für eine Buchtausch-App. Die App ermöglicht den Austausch von Büchern zwischen Benutzern, indem sie eine Plattform bereitstellt, auf der Bücher ausgeliehen und zurückgegeben werden können.

Inhalt des Repositories
-Werner-Christoph_42307731_DLBDSPBDM01_D_CREATE_SQL.sql: Enthält die SQL-Statements zur Erstellung der Tabellen und Beziehungen.
-Werner-Christoph_42307731_DLBDSPBDM01_D_INSERT_SQL.sql: Enthält die SQL-Statements zum Einfügen von Testdaten in die Tabellen.
-Werner-Christoph_42307731_DLBDSPBDM01_D_BENUTZERFREUNDLICHE_ABFRAGEN_SQL.sql: Enthält die SQL-Statements für benutzerfreundliche Abfragen.
-Werner-Christoph_42307731_DLBDSPBDM01_D_STORED_PROCEDURE_SQL.sql: Enthält die SQL-Statements zum Einfügen eine STORED PROCEDURE.
-Werner-Christoph_42307731_DLBDSPBDM01_D_Konzeptionsphase_AB.pdf: Enthält die Anforderungsspezifikation und das Entity-Relationship-Modell 
-Werner-Christoph_42307731_DLBDSPBDM01_D_Erarbeitungs-Reflexionsphase_KZ.pdf: Enthält eine Kurzzusammenfassung der Erarbeitungsphase.
-Werner-Christoph_42307731_DLBDSPBDM01_D_Erarbeitungs-Reflexionsphase_PR.pdf: Enthält eine Präsentation des Implementierungsverfahrens. 
-Werner-Christoph_42307731_DLBDSPBDM01_D_Abschlussphase_GH.pdf:Enthält den Link zum Github Repository.
-Werner-Christoph_42307731_DLBDSPBDM01_D_Abschlussphase_BE.pdf: Beschreibt die Funktionalität der Datenbank, die Anzahl der Tabellen und Einträge sowie die Größe der Datenbank.
-Werner-Christoph_42307731_DLBDSPBDM01_D_Installationsanleitung.pdf: Eine detaillierte Anleitung zur Installation und Einrichtung der Datenbank.



Funktionalität
Die Buchtausch-App-Datenbank bietet folgende Hauptfunktionen:

Benutzerverwaltung: Registrierung, Anmeldung und Verwaltung von Benutzerinformationen.
Buchverwaltung: Hinzufügen, Bearbeiten und Löschen von Büchern mit Details wie Titel, Autor, Verlag, ISBN, Kategorie, Jahr der Veröffentlichung, Sprache und Zustand.
Ausleihvorgänge: Verwaltung von Ausleihanfragen, Ausleihen und Rückgaben von Büchern.
Benachrichtigungen: Versenden von Benachrichtigungen über Ausleihen, Rückgaben und Reservierungen.
Bewertungssystem: Abgabe und Verwaltung von Bewertungen und Kommentaren zu Büchern.
Reservierungssystem: Möglichkeit, Bücher für einen bestimmten Zeitraum zu reservieren.
Räumliche Suche: Anzeige der verfügbaren Bücher auf einer Karte basierend auf Standortinformationen.
Installationsanleitung für die Buchtausch-App-Datenbank
Voraussetzungen
1.	Microsoft SQL Server: Stellen Sie sicher, dass Microsoft SQL Server auf Ihrem System installiert ist.
2.	SQL Server Management Studio (SSMS): Dieses Tool wird für die Verwaltung und Visualisierung der Datenbank verwendet.
Schritte zur Installation:
1.	Microsoft SQL Server installieren:
	o	Laden Sie den Microsoft SQL Server von der offiziellen Microsoft-Website herunter.
	o	Folgen Sie den Anweisungen des Installationsassistenten, um den SQL Server auf Ihrem System zu installieren.
2.	SQL Server Management Studio (SSMS) installieren:
	o	Laden Sie SQL Server Management Studio von der offiziellen Microsoft-Website herunter.
	o	Installieren Sie SSMS, indem Sie den Anweisungen des Installationsassistenten folgen.
3.	SQL-Dateien importieren:
	o	Öffnen Sie SQL Server Management Studio.
	o	Verbinden Sie sich mit Ihrer SQL Server-Instanz.
	o	Erstellen Sie eine neue Datenbank:
		Klicken Sie mit der rechten Maustaste auf Datenbanken und wählen Sie Neue Datenbank....
		Geben Sie der neuen Datenbank einen Namen, z.B. BuchtauschDB, und klicken Sie auf OK.
	o	Öffnen Sie die Datei Werner-Christoph_42307731_DLBDSPBDM01_D_CREATE_SQL.sql:
		Klicken Sie auf Datei > Öffnen > Datei und wählen Sie die Datei Werner-Christoph_42307731_DLBDSPBDM01_D_CREATE_SQL.sql aus.
		Führen Sie das Skript aus, indem Sie auf die Schaltfläche Ausführen klicken. Dadurch werden alle benötigten Tabellen und Beziehungen erstellt.
	o	Öffnen Sie die Datei Werner-Christoph_42307731_DLBDSPBDM01_D_INSERT_SQL.sql:
		Klicken Sie auf Datei > Öffnen > Datei und wählen Sie die Datei Werner-Christoph_42307731_DLBDSPBDM01_D_INSERT_SQL.sql aus.
		Führen Sie das Skript aus, um die Testdaten in die Tabellen einzufügen.
	o	Öffnen Sie die Datei Werner-Christoph_42307731_DLBDSPBDM01_D_STORED_PROCEDURE_SQL.sql:
		Klicken Sie auf Datei > Öffnen > Datei und wählen Sie die Datei Werner-Christoph_42307731_DLBDSPBDM01_D_STORED_PROCEDURE_SQL.sql aus.
		Führen Sie das Skript aus, um die Testdaten in die Tabellen einzufügen.
4.		Überprüfen der Installation:
	o	Stellen Sie sicher, dass alle Tabellen korrekt erstellt wurden und die Testdaten eingefügt sind.
	o	Führen Sie einige Abfragen aus, um sicherzustellen, dass die Datenbank ordnungsgemäß funktioniert. Zum Beispiel:

Code kopieren:
SELECT * FROM Bücher;
SELECT * FROM Benutzende;
SELECT * FROM Ausleihen;
	o	Überprüfen Sie die Ergebnisse, um sicherzustellen, dass die Daten korrekt angezeigt werden.

Abschluss
Nach Abschluss dieser Schritte sollte die Buchtausch-App-Datenbank vollständig eingerichtet und betriebsbereit sein. Sie können nun mit der Nutzung der Datenbank beginnen und die Buchtausch-App-Funktionalitäten testen.


Kontakt
Bei Fragen oder Anmerkungen wenden Sie sich bitte an [christoph.werner@iu-study.org].
