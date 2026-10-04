# TOR POS

[← Back to profile](README.md) · [Deutsch](README.de.md)

## Project Owner & Lead Developer

**TOR POS** is the project owner and lead developer of **TOR POS**. TOR POS is an independently developed proprietary software project led by Serwan Duman.

## Modern point-of-sale software for real-world operations

**TOR POS** is a modular point-of-sale platform for **retail, gastronomy and restaurants**. It is being developed for the German market and brings together checkout operations, inventory, restaurant workflows, device integration and fiscal processes in one platform.

The project focuses on **reliability, traceable workflows, offline operation and practical usability**. The goal is not only to provide a rich feature set, but to build a system whose technical and operational behavior can be tested, documented and released in a controlled way.

## Product lines

### TOR Retail
Designed for everyday retail checkout operations, including product and category management, barcode and scanner workflows, inventory, stocktaking, returns, cancellations, reporting and daily closing procedures.

### TOR Gastro
Designed for snack bars, cafés, take-away businesses and fast-service gastronomy. It includes menu and order workflows, dine-in/take-away scenarios, kitchen routing, pickup numbers and other typical gastro processes.

### TOR Restaurant
Designed for table-service restaurants and more complex service workflows, including table management, split payments, reservations, handheld support, Kitchen Display System (KDS), QR self-ordering, kitchen stations and additional service-oriented features.

## Fiscal and compliance-oriented development

TOR POS is designed with the German fiscal environment in mind and includes functionality around **TSE**, **KassenSichV**, **DSFinV-K 2.4**, fiscal exports, cash-register notification support, logging and audit-oriented workflows.

Important: TOR POS is not presented as “BMF certified”, “approved by the tax office” or officially certified as a cash-register product. The software is designed to work with certified TSE technology; real hardware acceptance, external data validation and other release steps are documented and verified separately.

## Devices and payments

The project is designed to work with common POS hardware and peripherals, including:

- receipt printers
- cash drawers
- barcode scanners
- scales and other peripherals
- ZVT-compatible payment terminals
- KDS and handheld devices
- optional cloud and digital-receipt services

## Architecture and technology

TOR POS is based on a modern Windows/.NET architecture.

**Technology stack:** C# · .NET · Avalonia UI · SQLite · REST APIs · GitHub Actions

The platform follows an **offline-first approach**: core checkout operations are intended to remain reliable locally, while cloud services are added where they provide clear operational value.

## Quality and release safety

A major focus of the project is controlled release qualification rather than unverified deployment. This includes automated testing, database migration testing, backup/restore verification, hardware acceptance, external DSFinV-K validation, fiscal review, audit trails and traceable release gates.

Critical software defects are deliberately separated from external release dependencies: a missing hardware acceptance test is not a software defect, but it may still block a production release.

## Current status

TOR POS is in an advanced development and qualification phase. The focus is increasingly shifting from adding features to **acceptance testing, external validation, real-device testing, release safety and practical field verification**.

## Goal

TOR POS aims to be a modern, understandable and robust POS platform that works in everyday business and keeps its technical and fiscal processes transparent and traceable.

---

**TOR POS — Software for real business operations.**  
**Project Owner & Lead Developer: Serwan Duman**
