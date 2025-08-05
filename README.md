# FlutterProject
Fundraising Portal is a application built using Flutter that simulates an intern dashboard. It includes a dummy login/signup screen and a dashboard displaying static data such as the intern’s name, referral code, total donations raised, and a rewards/unlockables section.

## 🚀 Features

- ✅ Dummy Login/Signup Page (no actual authentication)
- ✅ Dashboard displaying:
  - Intern Name
  - Dummy Referral Code
  - Total Donations Raised (a static number)
  - Static Rewards Section
  - Leader Board
  - Bonus Page

---

## 🛠️ Tech Used

- **Framework:** IdxProject, FlutterFlow

---

## 📁 Project Structure
---

## 📱 App Structure & UI Flow

The Intern Portal Flutter app consists of **four main pages** and follows a simple, intuitive user navigation flow:

---

### 🔹 1. **Login Page (`loginPage`)**

* Entry point of the app.
* Contains:

  * Email and password fields
  * “Sign In” button
  * Navigation to Sign Up page
  * Forgot password/help text (non-functional/dummy)

✅ **Navigation:**

* On successful dummy login → navigates to **Intern Dashboard**
* Link to create an account → navigates to **SignUp Page**

---

### 🔹 2. **Sign Up Page (`signUpPage`)**

* Allows new users to create a dummy account (no authentication).
* Contains:

  * Name, email, and password fields
  * “Create Account” button

✅ **Navigation:**

* On clicking “Create Account” → navigates to **Intern Dashboard**
* Back link → returns to **Login Page**

---

### 🔹 3. **Dashboard Page (`dashBoard`)**

* Displays all key intern details and fundraising progress.

✅ Sections Included:

* Intern name
* Referral code
* Total donations raised
* Static tiles (e.g., Rewards, Team Progress)
* Leaderboard with dummy ranking and amounts

✅ **Navigation:**

* Button/tile click → opens **Success Celebration Page**

---

### 🔹 4. Bonus Page (bonusPage)

* A celebratory screen triggered after fundraising milestone.
* Displays:

  * “Congratulations” message
  * Fundraising success visuals (static)
  * Amount raised
  * Unlocked badges/rewards
  * Navigation back to Dashboard

---

