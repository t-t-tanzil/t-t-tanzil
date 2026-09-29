<div align="center">

# Taqi Tahmid Tanzil

### Senior Mobile Engineer · Android · Kotlin · Flutter · KMP

9 years, 20+ apps shipped. I build mobile applications and spend a lot of time thinking about what happens behind the screen: architecture, data, reliability, and the parts that become difficult as a product grows.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/t-t-tanzil/)
[![Portfolio](https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.taqitahmid.dev/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:t.tanzil92@gmail.com)

</div>

---

## About

I've been building mobile applications since 2017.

I started with Android in Java, moved to Kotlin, and later added Flutter for products where cross-platform development made sense.

Over the years I've worked on travel, healthcare, fintech, telecom, social and enterprise products, and I've shipped 20+ apps. Some of them are in the stores (below). Most of my professional work isn't public, so this profile is also where I keep what I build to explore ideas, test architecture decisions and learn something new.

At work I moved from feature development into architecture and technical ownership. I led mobile at Truely, where I managed one mobile engineer, owned hiring decisions and ran both store releases. At Dhrubok I managed two to three mobile engineers and led delivery across teams of four or five, including backend and design. I'm a Certified Scrum Master.

Since April I've been building my own apps under Taqsoft.

### What I work with

**Android**

Kotlin · Jetpack Compose · Coroutines · Flow · Room · WorkManager · Retrofit · Hilt · Google Maps · Firebase · Google Health · In-body Devices · RevenueCat SDK · PLay store payment · Stripe

**Flutter**

Dart · BLoC · GetX · Clean Architecture · REST APIs · Firebase · Firebase Analytics · FCM · Stripe · LingoDev

**Kotlin Multiplatform**

SQLDelight · Koin · StateFlow · Google Subscription

**Architecture**

MVVM · Clean Architecture · Modularization · Offline-first applications · Local persistence · Synchronization

**Devices and payments**

BLE · Google Fit · eSIM · Stripe · Google Play Billing

**Delivery**

Testing · CI/CD · Fastlane · Codemagic · GitHub Actions · Git

---

## Apps in the stores

Six of the 20+ apps I've shipped:

- [Truely](https://apps.apple.com/us/app/truely-travel-esim-data-plan/id6480101996): travel eSIM app, where I was Mobile Team Lead
- [Tomo](https://apps.apple.com/us/app/tomo-%E5%8F%8B/id6737231798): community social app
- [NYPD Columbia Association](https://apps.apple.com/us/app/nypd-columbia-association/id1588621313): civic
- [rePrecinct](https://apps.apple.com/us/app/reprecinct/id6444239603): real estate
- [Poshora](https://apps.apple.com/us/app/poshora-app/id6642673369): commerce
- [Payway Salary](https://apps.apple.com/us/app/payway-salary/id6642660765): earned-wage-access app for salaried workers in Panama, built on contract

## Independent products

- [Vexylt](https://vexylt.com): a link-in-bio app built from blocks (links, projects, experience, services) with QR sharing, analytics and a Pro tier. The Android app is built with Kotlin Multiplatform, with a companion web app.
- **Ignyr**: a Flutter habit tracker built around the streak, with Firebase sync, reminders and a leaderboard.
- [SmartJSONViewer](https://smartjsonviewer.com/): a small developer tool for viewing and exploring JSON data.

---

## Reference projects: offline-first, three ways

### Kotlin Multiplatform: Offline-First User List

[View Repository →](https://github.com/t-t-tanzil/KmpUserList)

I wanted to understand the offline-sync problem from a shared-code perspective, so I built a small application with Kotlin Multiplatform.

The application is intentionally simple: users can add a name and age, even without an internet connection. Local changes are kept on the device and synchronized with the server when connectivity comes back.

The interesting part isn't the form itself. It's what happens when the network disappears.

**Things explored:**

- Kotlin Multiplatform
- Shared business and data logic
- SQLDelight
- Ktor Client
- Koin
- StateFlow
- Offline persistence
- Connectivity monitoring
- Synchronization
- Retry handling

### Android: Offline-First User List

[View Repository →](https://github.com/t-t-tanzil/Android_MVVM_BoilerPlate-1.0)

The Android version of the same problem.

The app can be used without a network connection, stores changes locally, and synchronizes them with the backend once connectivity is restored.

I built this mainly to work through the architecture rather than the UI.

**Tech stack:**

- Kotlin
- Jetpack Compose
- MVVM
- Clean Architecture
- Hilt
- Room
- Retrofit / OkHttp
- WorkManager
- Coroutines
- Flow

### Flutter: Offline-First User List

[View Repository →](https://github.com/t-t-tanzil/flutter_clean_arch_boilerplate_1.0)

The Flutter implementation of the same offline-first problem.

Building the same idea across Android, Flutter and KMP has been useful for comparing where the architecture can be shared and where each platform needs a different approach.

**Focus areas:**

- Flutter
- Dart
- Clean Architecture
- State management
- REST APIs
- Offline persistence
- Synchronization

---

## Why these projects?

Most of my professional experience comes from production applications, where the constraints are usually already there.

These projects give me a place to experiment with things I don't always get to try at work: offline-first architecture, synchronization, shared business logic and mobile system design.

## Going deeper on

- Kotlin Multiplatform (I'm shipping it in Vexylt)
- Mobile system design
- Backend development and distributed systems

## A few things I'm interested in

- Mobile architecture
- Offline-first applications
- Kotlin Multiplatform
- Android and Kotlin
- Flutter
- CI/CD and release engineering
- Developer experience
- Building software that remains understandable as it grows

---

## Connect

I'm open to remote senior and lead mobile roles. I'm based in Dhaka (UTC+6), with full overlap with European working hours:

- Senior Mobile Engineer
- Senior Android Engineer
- Senior Flutter Engineer
- Lead Mobile Engineer

I also take short contract work: [taqitahmid.dev/consulting](https://www.taqitahmid.dev/consulting)

If you're working on an interesting mobile problem, feel free to reach out.
