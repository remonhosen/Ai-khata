# হিসাবের খাতা AI Pro 📒

**By REMON**

বাংলা-first Android personal/shop accounting app with Salary, Income, Expense, Customer Due and Voice Command.

## Features

- Salary / Income entry
- Expense entry
- দোকানের বাকি / customer receivable
- Customer payment entry
- Current balance dashboard
- Transaction history
- বাংলা Voice Command
- Offline SQLite storage
- No API key required for the current voice parser
- GitHub Actions workflow that builds a debug APK automatically

## Example voice commands

- `আজ ৫০,০০০ টাকা salary পেয়েছি`
- `আজ ৮০০ টাকা বাজার খরচ`
- `রহিম ৫০০ টাকা বাকি নিয়েছে`
- `রহিম ২০০ টাকা পরিশোধ করেছে`

## GitHub থেকে APK build

1. এই project GitHub repository-তে upload করুন।
2. GitHub-এ **Actions** tab খুলুন।
3. **Android Build** workflow run হবে push-এর পর।
4. Workflow শেষ হলে **Artifacts** থেকে `HisaberKhataAIPro-debug` download করা যাবে।

## Local Android Studio

Project folder Android Studio-তে খুলে Gradle sync করে Run করুন।

## Next roadmap

- Real AI chat integration
- Customer-wise ledger
- Daily/monthly/yearly reports
- PDF/Excel export
- Backup/restore
- PIN + biometric lock
- Cloud sync
- Better AI intent detection
