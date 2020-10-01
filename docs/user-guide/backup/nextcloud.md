# Sichern und mit Nextcloud synchronisieren #

## Mit Nextcloud verbinden ##
Mit PhotoPrism können Sie eine Verbindung zu einem Nextcloud-Server herstellen, sodass Sie dies automatisch tun können
Erstellen Sie Backups oder rufen Sie Ihre neuesten Bilder ab.

**Verbinden:**

1. Gehen Sie zu * Einstellungen *
2. Öffnen Sie die Registerkarte * Backup *
3. Klicken Sie auf * Server hinzufügen *
    ! [Screenshot] (img / nextcloud-connect.png)
4. Geben Sie Ihre Nextcloud-Server-URL, Ihren Benutzernamen und Ihr Passwort ein
5. Klicken Sie auf * verbinden *
    ! [Screenshot] (img / nextcloud-connect-2.png)
6. Jetzt ist Ihre Nextcloud mit PhotoPrism verbunden

## Manuelles Hochladen von Dateien in Nextcloud ##
** So konfigurieren Sie den manuellen Upload: **

1. Gehen Sie zu * Einstellungen *
2. Öffnen Sie die Registerkarte * Backup *
3. Klicken Sie in die Upload-Zelle Ihres Nextcloud-Servers

! [Bildschirmfoto] (img / upload-1.png)
4. Wählen Sie den Ordner aus, in den Fotos hochgeladen werden sollen, und klicken Sie auf * Speichern *.

! [Bildschirmfoto] (img / upload-2.png)

** So laden Sie Dateien von PhotoPrism in Nextcloud hoch: **

1. Gehen Sie zu * Fotos *
2. Wählen Sie die Fotos aus, die Sie hochladen möchten
3. Öffnen Sie das Kontextmenü
4. Klicken Sie auf: Materialwolke:
5. Wählen Sie Ihr nextcloud-Konto aus und klicken Sie auf * upload *

! [Bildschirmfoto] (img / upload-3.png)

!!! die Info
    Beim manuellen Hochladen werden nur JPEGs kopiert.
    Unterstützung für RAW- und Videodateien wird in einer zukünftigen Version hinzugefügt.

!!! Beachtung
    Aufgrund von Problemen mit einigen Nextcloud-Einstellungen kann das Hochladen in Nextcloud zu 0-Byte-Dateien führen. Informationen zur Lösung finden Sie [hier] (https://github.com/photoprism/photoprism/issues/443).

## Dateien mit Nextcloud sichern / synchronisieren ##
1. Gehen Sie zu * Einstellungen *
2. Öffnen Sie die Registerkarte * Backup *
3. Klicken Sie in die Synchronisierungszelle Ihres nextcloud-Servers
! [Screenshot] (img / sync-1.png)
4. Aktivieren Sie die Synchronisation in der oberen rechten Ecke
5. Wählen Sie den Ordner, in dem sich alle Ihre Fotos in Nextcloud befinden
6. Wählen Sie aus, wie oft Ihre Dateien synchronisiert werden sollen
7. Wählen Sie die für Sie geeigneten Optionen aus und klicken Sie auf * Speichern *.

! [Bildschirmfoto] (img / sync-2.png)

!!! Beachtung
    Videos werden noch nicht synchronisiert. Wir arbeiten daran.

### Remote Sync-Optionen ###
* * Remote-Dateien herunterladen * lädt alle Dateien aus Ihrer nächsten Cloud herunter, die in PhotoPrism noch nicht vorhanden sind
* * Lokale Dateien hochladen * lädt alle Dateien von PhotoPrism in Ihren nextcloud-Ordner hoch, die dort noch nicht vorhanden sind
* * Dateinamen beibehalten * behält Dateinamen von Nextcloud bei, ohne sie umzubenennen
* * Rohbilder synchronisieren * lädt Rohdateien zusammen mit JPEGs hoch / herunter