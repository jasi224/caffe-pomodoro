# Caffè Pomodoro – iPhone PWA v2

- iPhone-first interface
- Desktop installation UI and keyboard shortcuts removed
- Timer uses absolute timestamps so it can be reconciled after iOS suspends the app
- PWA manifest + service worker + iPhone icons included

Important iOS limitation:
A Home Screen web app cannot reliably keep arbitrary JavaScript running while suspended, and a web PWA cannot provide a native-style live countdown/Live Activity on the iPhone Lock Screen. Web Push can provide an end-of-phase notification, but that requires a push service/server.

iPhone-Hinweis
--------------
Diese Version bleibt vollständig im bestehenden GitHub-Pages-Setup.
Der Timer kann beim Wiederöffnen anhand der echten Endzeit korrigiert werden.
Eine Benachrichtigung kann angezeigt werden, solange iOS der Web-App noch
Ausführungszeit gibt bzw. beim Wiederöffnen. Eine garantiert zeitgenaue
Benachrichtigung bei vollständig suspendierter/geschlossener PWA ist ohne
externen Push-Server technisch nicht möglich.
