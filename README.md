# 🌿 Massage Appointment - Progressive Web App (PWA)

[![Live Demo](https://img.shields.io/badge/demo-online-brightgreen)](https://massage-appointment.vercel.app/)
[![Platform](https://img.shields.io/badge/platform-Vercel-black)](https://vercel.com/)
[![Framework](https://img.shields.io/badge/framework-React-blue)](https://reactjs.org/)

Μια ολοκληρωμένη λύση διαχείρισης ραντεβού για το **Κέντρο Μασάζ του Γιώργου Βογιατζή** στη Νέα Τρίγλια. Η εφαρμογή έχει σχεδιαστεί για να προσφέρει μια απλή, γρήγορη και φιλική προς το χρήστη εμπειρία κράτησης, λειτουργώντας ως "native" εφαρμογή σε κινητά τηλέφωνα.

## ✨ Χαρακτηριστικά

- **📱 PWA Ready:** Εγκατάσταση στην αρχική οθόνη του κινητού χωρίς ανάγκη για App Store/Play Store.
- **📅 Dynamic Booking:** Σύστημα κρατήσεων σε πραγματικό χρόνο με χρήση **React hooks** για επικύρωση δεδομένων.
- **📧 Άμεση Ενημέρωση:** Ενσωμάτωση με το **EmailJS API** για αυτόματη αποστολή των στοιχείων του ραντεβού στον διαχειριστή.
- **📶 Offline Support:** Λειτουργία Service Worker για πρόσβαση στις πληροφορίες επικοινωνίας ακόμα και χωρίς σύνδεση στο internet.
- **⚡ High Performance:** Φιλοξενία στο **Vercel** για μέγιστη ταχύτητα απόκρισης.

## 🛠️ Τεχνολογικό Stack

* **Frontend:** HTML5, CSS3, JavaScript (ES6+)
* **UI Framework:** [Bootstrap 4](https://getbootstrap.com/) για πλήρως responsive σχεδιασμό.
* **Logic:** [React.js](https://reactjs.org/) (Standalone Babel version).
* **Automation:** [EmailJS](https://www.emailjs.com/) για το backend-less σύστημα αποστολής email.
* **PWA:** Service Workers και Web Manifest API.

## 📂 Δομή του Project

```text
├── index.html          # Η κύρια σελίδα και το React Component
├── styles.css          # Προσαρμοσμένο CSS για το branding της επιχείρησης
├── manifest.json       # Ρυθμίσεις εμφάνισης PWA (εικονίδια, θέμα)
├── service-worker.js   # Λογική caching και offline λειτουργίας
└── icons/              # Φάκελος με λογότυπα και εικόνες υπηρεσιών
