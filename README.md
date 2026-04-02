# VLL-Pro-The-Freelance-Accounting-Suite-
"A professional, offline-first accounting ecosystem for footwear wholesalers. Built with Vanilla JS, IndexedDB, and SHA-256 hashing for immutable financial audit trails

Key Modules
Office Cashbook: A digital daily ledger featuring dual-entry logic (Credit/Debit) and real-time mode reconciliation (Cash/Bank/Credit).

Party Ledger (Khata): An alphabetized customer management system with Universal Sync capabilities and area-wise transaction tracking.

Tally Bridge (1.js): An atomic data injection engine that uses fuzzy column mapping to import Tally Prime and Excel spreadsheets directly into the browser database.

 Technical Excellence
Data Integrity (SHA-256): Implements a custom "Atomic Hashing" protocol where every imported row is hashed to ensure an immutable financial audit trail.

Offline-First Architecture: Utilizes LocalStorage and IndexedDB for data persistence, ensuring the app remains functional in warehouses with poor connectivity.

Atomic Transactions: Leveraging the db.transaction API in JavaScript to prevent data corruption during large-scale Tally imports.

Binary Processing: Powered by SheetJS (XLSX) for high-speed client-side parsing of complex wholesale spreadsheets.

 Project Structure
index.html: The central dashboard and launcher for the suite.

Cashbook.html: The interface for daily financial entry.

Legder.html: The customer profile and credit management portal.

Bridge.html: The dedicated UI for Tally/Excel imports.

js/1.js: The core logic engine for data parsing and stock reconciliation.

 Usage
Open index.html in a modern browser (Chrome or Edge recommended).

Developer
Kartik Bhatia Full-Stack Developer | B.Sc. IT Student @ SRKI LinkedIn | GitHub

Navigate to the Tally Bridge to import existing records.

Manage daily transactions via the Cashbook; balances will automatically reflect in the Party Ledger.
