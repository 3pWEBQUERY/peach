# Peach Dating App - Product Requirements Document

## Übersicht
Peach ist eine moderne Dating-Plattform, die sich an der Funktionalität von bemygirl.ch und and6.com orientiert. Die Plattform zielt darauf ab, Menschen auf authentische und sichere Weise zusammenzubringen.

## Zielgruppe
- Primär: Singles im Alter von 18-45 Jahren
- Sekundär: Menschen aller Altersgruppen, die nach bedeutungsvollen Beziehungen suchen
- Region: Deutschsprachiger Raum (DACH)

## Hauptfunktionen

### 1. Benutzerregistrierung und Profil
- Email-basierte Registrierung
- Social Media Login (Google, Facebook)
- Profilbilder-Upload (max. 6 Bilder)
- Detaillierte Profilinformationen:
  - Persönliche Daten (Alter, Standort, etc.)
  - Interessen und Hobbys
  - Beziehungsziele
  - Beschreibungstext

### 2. Matching-System
- Swipe-Funktionalität (Links/Rechts)
- Fortgeschrittene Filteroptionen:
  - Alter
  - Entfernung
  - Interessen
  - Beziehungsziele
- Match-Benachrichtigungen

### 3. Kommunikation
- Chat-System für gematchte Nutzer
- Emoji-Unterstützung
- Bild-Sharing-Möglichkeit
- Online-Status-Anzeige

### 4. Premium-Funktionen
- Erweiterte Suchfilter
- Profilbesucher sehen
- Unbegrenzte Likes
- Boost-Funktion
- Wer hat mich geliked?

## Technische Spezifikationen

### Frontend
- Next.js mit TypeScript
- Tailwind CSS für Styling
- Redux für State Management
- Progressive Web App (PWA)

### Backend
- Node.js/Express.js
- PostgreSQL Datenbank
- Redis für Caching
- WebSocket für Real-time Chat

### Sicherheit
- JWT Authentication
- HTTPS/SSL
- Datenverschlüsselung
- GDPR-Konformität



## MVP Timeline
1. Phase (Monat 1-2):
   - Basis-Authentifizierung
   - Profilerstellung
   - Grundlegendes Matching

2. Phase (Monat 3-4):
   - Chat-System
   - Erweiterte Profile
   - Basic Premium-Features

3. Phase (Monat 5-6):
   - Fortgeschrittene Matching-Algorithmen
   - Vollständige Premium-Features
   - Performance-Optimierung

## Erfolgskriterien
- Benutzerregistrierungen: 10.000 im ersten Monat
- Aktive Nutzer: 5.000 täglich nach 6 Monaten
- Match-Rate: 30% der aktiven Nutzer
- Konversionsrate zu Premium: 5% der aktiven Nutzer
