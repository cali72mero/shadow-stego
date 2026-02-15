# 🕵️‍♂️ Shadow Stego

> **Verstecke verschlüsselte Nachrichten in harmlosen Bildern.**

[![GitHub Pages](https://img.shields.io/badge/Status-Online-success?style=for-the-badge&logo=github)](https://cali72mero.github.io/shadow-stego/)
[![Security](https://img.shields.io/badge/AES--256-GCM-00f2ff?style=for-the-badge&logo=shield)](https://cali72mero.github.io/shadow-stego/)

---

## 👁️ Was ist das?

**Shadow Stego** ist ein Steganographie-Tool im Cyberpunk-Stil. Es erlaubt dir, geheime Textnachrichten **in den Pixeln eines Bildes** zu verstecken.

Das Besondere: **Das Bild sieht für jeden Betrachter völlig normal aus.** Niemand weiß, dass eine Nachricht darin verborgen ist.

## 🔐 Doppelte Sicherheit

Wir nutzen ein **2-Schichten-Sicherheitsmodell**:

1.  **AES-256-GCM Verschlüsselung:** Deine Nachricht wird zuerst mit einem Passwort militärisch verschlüsselt.
2.  **LSB-Steganographie:** Die verschlüsselten Daten werden in den unbedeutendsten Bits (Least Significant Bits) der Bildpixel versteckt.

Selbst wenn jemand weiß, dass eine Nachricht im Bild ist, kann er sie ohne Passwort nicht lesen (AES-256).

---

## 🚀 Anleitung

### 🔒 ENCODE (Verstecken)

1.  Wähle ein **Träger-Bild** (ein normales Foto, z.B. Landschaft oder Katze).
2.  Gib deine **geheime Nachricht** ein.
3.  Setze ein **starkes Passwort**.
4.  Klicke auf **NACHRICHT VERSTECKEN**.
5.  **Speichere das Bild**. (Wichtig: Das Bild wird als `.png` gespeichert).

### 🔓 DECODE (Lesen)

1.  Lade das **bearbeitete Bild** (`shadow_secret.png`) hoch.
2.  Gib das **Passwort** ein.
3.  Klicke auf **NACHRICHT AUSLESEN**.
4.  Der geheime Text erscheint.

---

## ⚠️ WICHTIG: PNG vs. JPG

Das resultierende Bild **MUSS** im **PNG-Format** bleiben.

-   ❌ **Nicht per WhatsApp senden** (WhatsApp komprimiert Bilder und zerstört die versteckten Daten).
-   ❌ **Nicht per Facebook/Insta posten**.
-   ✅ **Sende es per E-Mail** (als Anhang).
-   ✅ **Sende es per "Sicherer File Transfer"** (dein eigenes Tool!).
-   ✅ **Sende es als ZIP-Datei**.

---

## 🛠️ Tech Stack

-   **HTML5 Canvas API** (für Pixel-Manipulation)
-   **Web Crypto API** (für AES-256 Verschlüsselung)
-   **Matrix Rain Effect** (für den Cyberpunk-Vibe)

---

## 👨‍💻 Entwickler

Entwickelt von **cali72mero** als Teil des Privacy-Ökosystems.
100% Client-Side. Keine Server. Keine Logs.

[Zurück zum Privacy Hub](https://cali72mero.github.io/privacy-hub/)