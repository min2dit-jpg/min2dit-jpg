# TOR POS

[← Zur Profilübersicht](README.md) · [English](README.en.md)

## Projektinhaber & Lead Developer

**TOR POS** ist Projektinhaber und Lead Developer von **TOR POS**. TOR POS wird als eigenständig entwickeltes proprietäres Softwareprojekt unter seiner Leitung entwickelt.

## Moderne Kassensoftware für den realen Betrieb

**TOR POS** ist ein modular aufgebautes Point-of-Sale-System für **Einzelhandel, Gastronomie und Restaurants**. Das Projekt wird für den Einsatz im deutschen Markt entwickelt und verbindet Kassenbetrieb, Warenwirtschaft, Restaurantabläufe, Geräteintegration und fiskalische Prozesse in einer gemeinsamen Plattform.

Im Mittelpunkt stehen **Zuverlässigkeit, nachvollziehbare Abläufe, Offline-Fähigkeit und eine praxisnahe Bedienung**. Ziel ist nicht nur eine funktionsreiche Oberfläche, sondern ein System, dessen technische und betriebliche Prozesse reproduzierbar getestet, dokumentiert und kontrolliert freigegeben werden können.

## Produktlinien

### TOR Einzelhandel
Für klassische Verkaufsstellen und den täglichen Kassenbetrieb, unter anderem mit Artikel- und Warengruppenverwaltung, Barcode- und Scanner-Workflows, Lagerbestand, Inventur, Retouren, Storno, Berichten und Tagesabschlüssen.

### TOR Gastro
Für Imbiss, Café, Take-away und schnelle Gastronomiebetriebe. Dazu gehören unter anderem Menü- und Bestellabläufe, Inhouse-/Außer-Haus-Szenarien, Küchenrouting, Abholnummern und typische Gastro-Workflows.

### TOR Restaurant
Für Tischservice und komplexere Restaurantabläufe mit Tischplan, Split Payment, Reservierungen, Handheld-Anbindung, Kitchen Display System (KDS), QR-Self-Ordering, Küchenstationen und weiteren serviceorientierten Funktionen.

## Fiskal- und Compliance-orientierte Entwicklung

TOR POS berücksichtigt die Anforderungen des deutschen Kassenumfelds und enthält Funktionen rund um **TSE**, **KassenSichV**, **DSFinV-K 2.4**, fiskalische Exporte, Kassenmeldung-Unterstützung, Protokollierung und prüfungsorientierte Abläufe.

Wichtig: TOR POS wird nicht als „BMF-zertifiziert“, „Finanzamt-geprüft“ oder behördlich zugelassen dargestellt. Die Software wird mit zertifizierter TSE-Technik kombiniert; reale Hardwaretests, externe Datenvalidierung und weitere Freigabeschritte werden getrennt dokumentiert und nachgewiesen.

## Geräte und Zahlungsumfeld

Das Projekt ist auf typische POS-Hardware und Peripherie ausgelegt, darunter:

- Bondrucker
- Kassenschubladen
- Barcode-Scanner
- Waagen und weitere Peripherie
- ZVT-kompatible Kartenterminals
- KDS- und Handheld-Geräte
- optionale Cloud- und Digitalbon-Dienste

## Architektur und Technologie

TOR POS basiert auf einer modernen Windows/.NET-Architektur.

**Technologien:** C# · .NET · Avalonia UI · SQLite · REST APIs · GitHub Actions

Das System verfolgt einen **Offline-first-Ansatz**: Der operative Kassenbetrieb soll lokal zuverlässig funktionieren; Cloud-Dienste werden dort ergänzt, wo sie einen klaren betrieblichen Nutzen bieten.

## Qualität und Release-Sicherheit

Ein Schwerpunkt des Projekts liegt auf kontrollierter Freigabe statt auf ungeprüften Releases. Dazu gehören automatisierte Tests, Datenbank-Migrationstests, Backup-/Restore-Prüfungen, Hardware-Abnahme, externe DSFinV-K-Prüfung, fiskalische Validierung, Audit-Trails und nachvollziehbare Release-Gates.

Kritische Softwarefehler und noch offene externe Freigaben werden bewusst getrennt behandelt: Ein fehlender Hardware-Abnahmetest ist kein Softwarefehler, kann aber trotzdem eine produktive Freigabe blockieren.

## Aktueller Stand

TOR POS befindet sich in einer fortgeschrittenen Entwicklungs- und Qualifizierungsphase. Der Schwerpunkt verlagert sich zunehmend von neuen Funktionen auf **Abnahme, externe Validierung, reale Gerätetests, Release-Sicherheit und Praxiserprobung**.

## Ziel

TOR POS soll eine moderne, verständliche und robuste Kassensoftware sein, die im Alltag funktioniert und deren technische sowie fiskalische Prozesse transparent nachvollzogen werden können.

---

**TOR POS — Software für echte Geschäftsabläufe.**  
**Projektinhaber & Lead Developer: Serwan Duman**
