## Beschreibung Zielbild

Ein Anbieter möchte den Schüler oder Lehrendenstatus imm Rahmen der Bestellung einer für SuS subventionierten Leistung prüfen. Hierfür wird in dem Formular (oder einem dedizierten Schritt ein IFrame vom Vidis Portal (oder einer deidzierten Vidis-App) geladen).
Existiert eine Vidis Session so zeigt diese den Status und die von Vidis erhaltenen Daten an und erlaubt per OptIn durch den User die Erzeiugung eines signierten JWT an die aufrufenden Seite.
 In dem JWT sind die zur Validierung durch den Betreiber benötigen Informationen enthalten. Diese kann das JWT mithilfe eines Public Keys validieren.


Ist der Nutzer nicht eiongeloggt (keine Vidis Session) So kann er dass  in einem neuen Tab (oder im IFrame machen). Per Broadcast Channel wird dann aktualsiert.