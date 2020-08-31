# Ordner mit Passwort schützen [de-de]

Mit diesem Quellcode einer Batch-Datei kannst du einen Ordner in Windows mit einem Passwort schützen, sodass niemand ohne das Passwort auf diesen Ordner zugreifen kann.

**Bitte beachte, dass diese Art der "verschlüsselung" nicht wirklich sicher ist und von jemandem mit ein wenig Ahnung einfach umgangen werden kann. Nutze diese Methode nicht um wirklich wichtige Dateien zu schützen.**

## Wie kann ich das nutzen?

1. Kopiere den **gesamten** Text aus der Textdatei [folder_with_password.txt](../folder_with_password.txt) und erstelle eine neue Datei auf deinem Computer mit diesem Text.
2. Ändere den Text *INSERT_PASSWORD_HERE* durch das Passwort welches du zum Entsperren eingeben möchtest.
3. Speichere diese Datei als **.bat Datei** ab und führe sie danach aus.
4. Nun kannst du deine privaten Dateien in diesen ordner ziehen und die .bat-datei erneut ausführen um den Ordner zu schützen. Wenn du den Ordner wieder sichtbar machen möchtest musst du das Programm erneut starten und das richtige Passwort eingeben.