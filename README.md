# Simple PDF Sign // 100% Private Client-Side PDF Signing & Stamping

<p align="center">
  <img src="assets/social-preview.jpg" alt="Simple PDF Sign Cover Artwork" width="100%">
</p>

> **"Sign, stamp, and export PDF documents in seconds directly in your browser."**  
> Zero accounts. Zero cloud uploads. Zero subscriptions. 100% client-side privacy.  
> A lightweight, zero-backend web utility engineered for professionals who need to apply signatures, company stamps, and dates to contracts, NDAs, and agreements without exfiltrating sensitive corporate files to third-party clouds.

[![Live Web Tool](https://img.shields.io/badge/Live_Tool-emaf205.com%2Fideas%2Fsimple--pdf--sign-dfff00?style=for-the-badge&logo=googlechrome&logoColor=000000)](https://emaf205.com/ideas/simple-pdf-sign/)
[![YouTube Demo](https://img.shields.io/badge/YouTube-Video_Walkthrough-red?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/_kEl7B9Udy4)
[![GitHub Repo](https://img.shields.io/badge/GitHub-emanuelebdc%2FSimple--PDF--Sign-black?style=for-the-badge&logo=github&logoColor=white)](https://github.com/emanuelebdc/Simple-PDF-Sign)
[![Privacy](https://img.shields.io/badge/Privacy-100%25_Client--Side-10b981?style=for-the-badge)](https://github.com/emanuelebdc/Simple-PDF-Sign)
[![License: MIT](https://img.shields.io/badge/License-MIT-black?style=for-the-badge)](LICENSE)

---

## ✦ The Genesis & Why This Exists

Every independent professional, corporate consultant, and studio director encounters this routine irritation:
You receive an agreement, lease contract, NDA, or invoice in PDF format. You merely need to stamp your signature PNG onto page 4, add the date, and email it back.

What are the conventional options available today?
1. **Commercial Cloud PDF SaaS**: Services like Smallpdf, Adobe Acrobat Online, or DocuSign force you to register an account, impose strict daily usage caps, bombard you with aggressive paywalls, and most alarmingly: **require uploading confidential financial and legal contracts to remote multi-tenant cloud servers**.
2. **Bloated Desktop Software Suites**: Installing 1GB+ desktop software packages that constantly prompt for cloud logins, demand subscription licenses, and consume heavy background RAM.

I built **Simple PDF Sign** in Milan out of pure necessity: **an instantaneous, razor-sharp web utility that lets you drop a PDF, paste your signature or official seal, position and scale it in real-time, and download the finished document in under 15 seconds.**

**Your documents never leave your machine.** Every byte of PDF parsing, canvas rendering, vector scaling, and document flattening executes strictly inside your browser's local sandbox RAM.

---

## ✦ Video Walkthrough in Action

Watch the complete 15-second signing workflow demonstrated live:

<p align="center">
  <a href="https://youtu.be/_kEl7B9Udy4">
    <img src="https://img.youtube.com/vi/_kEl7B9Udy4/maxresdefault.jpg" alt="Simple PDF Sign Walkthrough Video" width="85%">
  </a>
</p>

---

## ✦ How It Works in 4 Steps

1. **Drop your PDF**: Drag any single-page or multi-page PDF agreement directly into the browser viewport.
2. **Add Signature or Stamp**: Upload a transparent PNG/JPEG signature, digital corporate seal, or custom graphic badge.
3. **Position & Scale Interactively**: Drag the stamp freely across any page, adjust opacity, rotate, or scale to match signature lines with sub-millimeter precision.
4. **Instant Client-Side Export**: Download the newly flattened, production-ready PDF file immediately.

---

## ✦ Scheda Tecnica // Technical Specifications

| Parametro | Specifica Tecnica |
|:---|:---|
| **Piattaforma di Esecuzione** | 100% Client-Side Web Application (Standalone & Hosted) |
| **Tecnologie Core** | HTML5 Canvas 2D, Modern CSS3 Flex/Grid, ES6+ JavaScript |
| **Elaborazione PDF** | Rendering e flattening vettoriale completamente in-memory |
| **Privacy e Sicurezza Dati** | **0 Byte Exfiltration**: zero upload su server remoti, zero cookie, zero telemetria |
| **Supporto Documentale** | Contratti multi-pagina con cassetto di navigazione pagine fluido |
| **Formati Firma Supportati** | PNG con canale alpha trasparente, JPEG, WebP |
| **Funzionalità Manipolazione** | Spostamento libero, ridimensionamento proporzionale, rotazione, opacità variabile |
| **Compatibilità Browser** | Chrome, Safari, Edge, Firefox, Arc, Brave (Desktop e Tablet) |
| **Impronta Software** | Pacchetto compresso ultraleggero (~30 KB), zero dipendenze npm |

---

## ✦ Struttura del Progetto

```text
Simple-PDF-Sign/
├── index.html               # Interfaccia grafica, viewport PDF e controlli di timbratura
├── styles.css               # Design system Swiss, contrasto elevato e drawer laterale
├── app.js                   # Motore di rendering PDF, gestione eventi touch/mouse e export
├── assets/                  # Grafica editoriale e social cover
│   └── social-preview.jpg   # Banner 16:9 hero ufficiale
├── simple-pdf-sign-v1.zip   # Archivio standalone pronto all'uso offline
├── LICENSE                  # Licenza open-source MIT
└── README.md                # Documentazione ufficiale e manifesto
```

---

## ✦ Quickstart & Offline Execution

### Opzione 1: Utilizzo Standalone Locale (Offline)
1. Clona la repository o scarica l'archivio ZIP:
   ```bash
   git clone https://github.com/emanuelebdc/Simple-PDF-Sign.git
   cd Simple-PDF-Sign
   ```
2. Estrai l'archivio `simple-pdf-sign-v1.zip`:
   ```bash
   unzip simple-pdf-sign-v1.zip -d app
   ```
3. Apri `app/index.html` con un doppio clic in qualsiasi browser. Non è necessario alcun server web.

### Opzione 2: Web App Ufficiale Online
Accedi in qualsiasi momento alla versione live hosted:  
👉 **[https://emaf205.com/ideas/simple-pdf-sign/](https://emaf205.com/ideas/simple-pdf-sign/)**

---

## ✦ Autore & Filosofia del Progetto

Ideato, progettato e sviluppato da **[Emanuele BDC](https://emaf205.com)** a Milano.  
Pubblicato all'interno del laboratorio di strumenti indipendenti **[EmaF205 Ideas Hub](https://emanuelebdc.com/ideas/)**.

Costruito per professionisti, consulenti e studi che esigono sovranità digitale, rispetto maniacale della privacy e velocità d'esecuzione senza compromessi.

Rilasciato sotto licenza open-source **[MIT License](LICENSE)**. Libero per utilizzi personali e commerciali.
