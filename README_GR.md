# MyoIntelligence — GitHub Pages (Ελληνικές οδηγίες)

## Σημαντικό: συμπλήρωσε τα στοιχεία ΠΡΙΝ δημοσιεύσεις

Στα αρχεία `index.html`, `el.html`, `support.html`, `support-el.html` υπάρχουν εμφανείς σημάνσεις με αγκύλες. Αντικατάστησε:

- `[DEVELOPER_NAME_OR_COMPANY]` → το όνομα ή την επωνυμία του υπεύθυνου της εφαρμογής.
- `[ΟΝΟΜΑ_Ή_ΕΠΩΝΥΜΙΑ_ΔΗΜΙΟΥΡΓΟΥ]` → το αντίστοιχο όνομα στα ελληνικά.
- `[SUPPORT_EMAIL]` και `[EMAIL_ΥΠΟΣΤΗΡΙΞΗΣ]` → **το πραγματικό email επικοινωνίας σου**.

Η μη δημοσίευση πραγματικών στοιχείων επικοινωνίας αφήνει την πολιτική ημιτελή. Η δημόσια σελίδα περιλαμβάνει πληροφορίες υπευθύνου που εσύ θα επιλέξεις να διαθέσεις· μην τοποθετείς προσωπικά στοιχεία χωρίς να το έχεις αποφασίσει.

## Δημοσίευση μέσω GitHub Pages

1. Μπες στο https://github.com και κάνε Sign in.
2. Επίλεξε **New repository**.
3. Όνομα repository: `myointelligence-privacy` (μπορείς να διαλέξεις άλλο).
4. Επίλεξε **Public** αν χρησιμοποιείς GitHub Free και κάνε **Create repository**.
5. Ανέβασε **τα αρχεία μέσα στον φάκελο** `MyoIntelligence_GitHub_Pages` στη ρίζα του repository — **όχι τον φάκελο ως υποφάκελο**. Χρειάζεται το `index.html` να βρίσκεται στη ρίζα.
6. Στο repository πήγαινε **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
7. Επίλεξε **Branch: main** και **Folder: /(root)** → **Save**.
8. Μόλις ολοκληρωθεί η δημοσίευση, άνοιξε το URL που θα εμφανίσει το GitHub.

Συνήθως το δημόσιο URL έχει τη μορφή:

`https://TO-GITHUB-USERNAME-SOU.github.io/myointelligence-privacy/`

Αυτή είναι η αγγλική πολιτική (`index.html`). Η ελληνική είναι:

`https://TO-GITHUB-USERNAME-SOU.github.io/myointelligence-privacy/el.html`

Η σελίδα υποστήριξης είναι:

`https://TO-GITHUB-USERNAME-SOU.github.io/myointelligence-privacy/support.html`

## Πού μπαίνουν στο App Store Connect

- **MyoIntelligence → App Privacy → Privacy Policy URL**: βάλε το παραπάνω URL της αγγλικής πολιτικής με τελική `/`.
- **Έκδοση εφαρμογής → Support URL**: βάλε το `/support.html`.
- Προαιρετικά δήλωσε και το ελληνικό URL ως τοπικοποιημένη πολιτική αν προσθέσεις ελληνική τοπικοποίηση στο App Store Connect.

## Πριν κάνεις Submit for Review

Η παρούσα πολιτική βασίζεται στον διαθέσιμο κώδικα του **AnatomyAtlas 19 / MyoIntelligence** που εξετάστηκε στις 15 Οκτωβρίου 2026. Δεν αποτελεί έλεγχο της νεότερης έκδοσης που βρίσκεται ήδη στο TestFlight. Έλεγξε ότι εκείνη **δεν** έχει προσθέσει άλλες υπηρεσίες δεδομένων, analytics, λογαριασμούς, online συγχρονισμό ή διαφημίσεις.

Επειδή φορτώνονται εικόνες από Wikimedia Commons, στο **App Privacy** πρέπει να δηλωθούν με ακρίβεια οι πρακτικές δεδομένων της εφαρμογής και των τρίτων υπηρεσιών. Η ύπαρξη αυτού του URL δεν συμπληρώνει αυτόματα το App Privacy ερωτηματολόγιο. Το τι πρέπει να δηλωθεί εξαρτάται από τις πραγματικές πρακτικές συλλογής των τρίτων και τους ορισμούς της Apple.

Αυτό είναι προσχέδιο δημόσιας πολιτικής για την εφαρμογή, όχι νομική γνωμοδότηση. Για επίσημη νομική συμμόρφωση με GDPR και εμπορική διάθεση, χρειάζεται κατάλληλος έλεγχος.

## Αρχεία

- `index.html` — Privacy Policy (English), προτεινόμενο βασικό URL.
- `el.html` — Πολιτική απορρήτου (Ελληνικά).
- `support.html` — Support (English) + εκπαιδευτική αποποίηση ευθύνης.
- `support-el.html` — Υποστήριξη (Ελληνικά) + εκπαιδευτική αποποίηση ευθύνης.
- `styles.css` — Responsive εμφάνιση με Light/Dark Mode.
- `.nojekyll` — Απενεργοποίηση Jekyll processing.

Δεν υπάρχουν διαφημίσεις, εξωτερικά fonts ή tracking scripts στα παραπάνω αρχεία.
