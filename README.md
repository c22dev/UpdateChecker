<img src='https://i.ibb.co/Ksc0RFR/Pag-NX-modified.png' width=100>

# UpdateChecker
A Github update checker written in SwiftUI that you can implement in your app
## What is Update Checker ?
Update Checker is a simple Github update checker that can be implemented in any Swift made app.

You can use it and edit it without credits (except if you create a new github repo, keep in mind to fork it)
### What to keep and what can you remove ?
Everything is in `UpdateCheckerApp.swift`. The script is divided into several parts :
- Basic sturcture (call ContentView() for example)
  - Check if info.plist bundle version is up to date compared to Github (keep)
  - Update alert pop-up (you can replace with anything)
- End of basic structure
- Alert pop-up code (you can delete that if you haven't used it
