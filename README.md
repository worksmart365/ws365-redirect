# ws365.ch → worksmart365.ch

Statisches GitHub-Pages-Repo, das die Kurz-Domain **ws365.ch** dauerhaft auf
[worksmart365.ch](https://worksmart365.ch) weiterleitet.

- `index.html` → Meta-Refresh + JS-Redirect auf `https://worksmart365.ch/`
- `404.html` → identischer Redirect (für alle Unterpfade)
- `CNAME` → `ws365.ch` (GitHub-Pages-Custom-Domain-Binding)

Alle Pfade landen auf der Startseite von worksmart365.ch. Keine Pfad-Übernahme.

## E-Mail

MX- und zugehörige Records auf `ws365.ch` bleiben unverändert – Microsoft-365-E-Mail
läuft weiterhin. Nur Web-Traffic wird umgeleitet.
