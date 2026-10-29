

## Serverabgleich vom 30. Oktober 2026

Der vorhandene Patch in `client.lua` prüft die Entitäts-Handles und ruft `SetEntityVelocity` mit getrennten x-, y- und z-Werten auf. Er bleibt gegenüber dem unveränderten Upstream erhalten.

Prüfung: Git-Baumvergleich und Syntaxprüfung der lesbaren Lua-Dateien. Native-Funktionen, Standorte und NUI-Verhalten müssen nach geplanter Aktivierung im Spiel geprüft werden.
