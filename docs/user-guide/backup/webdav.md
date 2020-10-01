# Verbindung über WebDAV herstellen #

WebDAV-Clients wie der Windows Explorer von Microsoft oder der Apple Finder können eine direkte Verbindung herstellen
zu PhotoPrism.
Dadurch wird der * Originalordner * als Netzwerklaufwerk bereitgestellt und Sie können ihn öffnen, bearbeiten und löschen
Dateien von Ihrem Computer oder Smartphone, als wären sie lokal.

Die URL des Originalordners für öffentliche Server lautet:

`` `
https: //admin@example.com/originals/
`` `

Bitte ersetzen Sie * example.com * durch Ihre tatsächliche Domain.
Der Schrägstrich am Ende ist wichtig und kann nicht weggelassen werden.

Wenn Sie eine Verbindung herstellen, müssen Sie sich mit Ihrem regulären Passwort authentifizieren.
Es ändert sich auch, wenn Sie es in * Einstellungen * aktualisieren. Der Benutzername lautet "admin".

!!! die Info
    Sie können auch eine Verbindung zum Importordner herstellen, indem Sie in der URL "Originale /" durch "Import /" ersetzen.

Für Benutzer, die PhotoPrism lokal auf dem Standardport * 2342 * ausführen, lautet die URL des Ordners * originals *:

`` `
http: // admin @ localhost: 2342 / originals /
`` `

!!! Beachtung
    Verwenden Sie WebDAV ** niemals ohne https ** außerhalb Ihres lokalen, privaten Netzwerks als Ihr
    Das Passwort würde im Klartext über das Internet übertragen.

## Verbindung zu einem WebDAV-Server unter macOS herstellen ##

1. Wählen Sie im ** Finder ** auf Ihrem Mac Go> Connect to Server
2. Geben Sie die URL wie oben gezeigt in das Feld ** Serveradresse ** ein
3. Klicken Sie auf ** Verbinden **

## Herstellen einer Verbindung zu einem WebDAV-Server unter Windows 10 ##

1. Öffnen Sie Windows ** File Explorer **
2. Klicken Sie mit der rechten Maustaste auf ** Dieser PC **
3. Wählen Sie in der Dropdown-Liste ** Netzwerklaufwerk zuordnen ... ** aus
4. Geben Sie den Laufwerksbuchstaben und den Ordner ein, denen Sie Ihre WebDAV-Verbindung zuordnen möchten
5. Aktivieren Sie die Kontrollkästchen ** Bei Anmeldung erneut verbinden ** und ** Mit unterschiedlichen Anmeldeinformationen verbinden **
6. Klicken Sie auf den Link ** Mit einer Website verbinden, auf der Sie Ihre Dokumente und Bilder speichern können **
7. Klicken Sie auf die Schaltfläche ** Weiter **
8. Klicken Sie auf ** Wählen Sie einen benutzerdefinierten Netzwerkspeicherort ** und klicken Sie dann auf die Schaltfläche ** Weiter **
9. Geben Sie im Feld ** Internet- oder Netzwerkadresse ** die oben gezeigte URL ein
10. Klicken Sie auf die Schaltfläche ** Weiter ** und dann auf ** Fertig stellen **

Der Originalordner wird im Windows Explorer als zugeordnetes Laufwerk angezeigt, und Sie können sofort Folgendes hinzufügen:
Bearbeiten oder Löschen von Dateien und Verzeichnissen mit dem Windows-Datei-Explorer.

Wenn Sie immer noch Probleme beim Herstellen einer Verbindung über WebDAV haben, müssen Sie dies möglicherweise tun
[Update] (https://help.dreamhost.com/hc/en-us/articles/216473357-Accessing-WebDAV-with-Windows) die
Grundlegende Authentifizierungsstufe in der Registrierung.