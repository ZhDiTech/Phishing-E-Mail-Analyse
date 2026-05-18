# Phishing-E-Mail Analyse

## Übersicht
Dieses Projekt dokumentiert die Analyse einer verdächtigen Phishing-E-Mail, die sich als Google Black Friday Angebot ausgibt.

Ziel der Analyse war es:
- die Herkunft der E-Mail zu untersuchen
- verdächtige URLs und Anhänge zu analysieren
- Indicators of Compromise (IOCs) zu identifizieren
- die Bedrohung zu bewerten

## Analysierte Bereiche
- Header Analyse
- SPF / DKIM / DMARC Prüfung
- URL Analyse
- VirusTotal Analyse
- Analyse des Dateianhangs
- IOC Extraktion
- Social Engineering Merkmale

## Verwendete Tools
- VirusTotal
- MXToolBox
- E-Mail Header Analyse
- Manuelle Sicherheitsanalyse

## Wichtige Erkenntnisse
- Verdächtige Absenderadresse
- Gefälschte Google-Imitation
- Manipulierte URL
- Verdächtiger DOCX-Anhang
- Social-Engineering-Techniken
- Fehlgeschlagene Authentifizierungsprüfungen

## Indicators of Compromise (IOCs)
- Absender: `g.corp.sender@gmail.com`
- Betreff: `Black Friday early access`
- Verdächtige URL: `http://006.zzz[.]com[.]ua/`
- Mailserver: `mail11.tpgi.com.au`
- Anhang: `Black Friday early access.docx`

## Fazit
Die analysierte Nachricht wurde als wahrscheinliche Phishing-E-Mail eingestuft. Mehrere technische und inhaltliche Merkmale deuten auf eine betrügerische Absicht hin.

## Dokumentation
Die vollständige Analyse befindet sich im Ordner `/docs`.
