# Demarie Pro (Mobile) 📱
### Enterprise-Grade School Management System

Demarie Pro is a premium, multi-tenant mobile ecosystem built for Kenyan educational institutions. It provides a high-performance interface for administrators, teachers, and parents to manage the full academic and financial lifecycle of a school.

---

## 🛠 Technical Architecture
*   **Framework:** Flutter (Dart)
*   **State Management:** Riverpod 3.0 (Provider-based reactivity)
*   **Networking:** Dio with custom Interceptors for Auth & Connectivity Guards.
*   **Backend Sync:** Native integration with Go (Fiber) High-Concurrency API.
*   **Real-time:** Firebase Cloud Messaging (FCM) with High Importance Channel mapping.

## 🚀 Key Engineering Highlights

### 1. Advanced Networking & Security
- **Smart Connectivity Guard:** App-wide wrapper for instant offline detection.
- **JWT Persistence:** Secured via `FlutterSecureStorage` using iOS Keychain and Android Keystore.
- **Dio Interceptors:** Seamlessly handles 401 (Unauthorized) and 402 (Payment Required) status codes to guide users through re-auth or subscription flows.

### 2. Finance & Fintech Integration
- **M-Pesa STK Push:** Direct mobile money integration for real-time fee payments.
- **Subscription Lock:** Automated app-wide lockout for expired accounts with in-app invoice settlement.

### 3. Academic Intelligence
- **Dynamic Admission Wizard:** Adapts automatically between 8-4-4 and CBC curriculum requirements.
- **Data Visualization:** Complex broadsheet statistics rendered via `fl_chart` for pedagogical analysis.

---

## 📂 System Design (Architecture)
```lib/
├── providers/         # Riverpod State Notifiers (Modern 3.0 Logic)
├── screens/           # Feature-based routing (Students, Teachers, Finance)
├── services/          # Dio-based API layers interacting with Go Backend
└── widgets/           # Atomic Design components & Global Guards



📸 Interface Preview

[Placeholder for Dashboard Screenshot]
[Placeholder for M-Pesa Payment Screen]

Status: Private Enterprise Repository

Production URL: https://demariepro.co.ke

Developer: Alitsi Daniel


---

### Step 3: Add the Vihiga JSS & Elearning Apps
Repeat the process for a second repo named `Vihiga-JSS-Welfare-App`. Use this as the description:

*   **Focus:** "High-trust financial tracking for JSS educators."
*   **Tech Stack:** "Go Fiber (Backend) + Flutter (Frontend)."
*   **Key Feature:** "Automated Welfare Contribution Tracking and BBF (Burial and Benevolent Fund) Claim processing logic."

---

### Why this works for your TVET application:
1.  **Riverpod 3.0:** Most people are still on 2.0. Mentioning 3.0 shows you stay updated with the latest tech—a key requirement for a "Trainer."
2.  **Go Fiber:** This is known for speed. It proves you can build "High-Concurrency" systems, which is perfect for teaching "Advanced Web Development."
3.  **M-Pesa & Security:** These are high-stakes features. It shows you can teach students about APIs, Security (JWT), and FinTech.

### Final Step for your GitHub Profile:
Go back to your `daniel33-dante` profile README and link these documentation repos:

```markdown
### 🚀 Featured Systems
- [Demarie Pro Mobile](https://github.com/daniel33-dante/Demarie-Pro-Mobile-Documentation) - Enterprise School MIS
- [Vihiga JSS Welfare](https://github.com/daniel33-dante/Vihiga-JSS-Welfare-Documentation) - FinTech for Educators



