# DO 2026 Dealer Accounts — Version 1

Android Studio project for the dealer sales/accounting app.

## Version 1 modules
- Dashboard
- Feed Sales / DO Entry
- Dealer-wise accounts
- Separate Tilapia Fry ledger
- Feed Price List: Feed Name, Code, Dealer Rate, MRP
- Tilapia Fry: Type, Dealer, Delivery Date, Quantity, Rate, Total, Debit, Credit, Balance
- Dealer-wise combined Feed + Fry report
- Offline SQLite storage

## Rates included
The uploaded Fish Feed Rate PDF dated 15.09.2026 is represented in the price table; the document states dealer rates apply from 17.09.2026.
Tilapia fry: Dealer ৳1.85/piece; MRP ৳2.00/piece.

## Build
Open `DO2026App` in Android Studio, allow Gradle sync, then Build > Build APK(s).
The chat environment does not include a configured Android/Gradle build toolchain, so this package is the Android source project rather than a compiled APK.
