
---

# Account and Data Deletion Policy

**App Name:** *Focus Arena*
**Last Updated:** *10/2/2026*

This page explains how users of *Focus Arena* can delete their account and associated data, what data is deleted, and what limited data may be retained in an anonymised form.

---

## How to Request Account Deletion

Users can delete their account **directly from within the app**:

1. Open the app and navigate to **Settings**.
2. Select **Delete Account**.
3. Confirm the deletion after the mandatory **5-second safety countdown**.

Once confirmed, the deletion process starts immediately and cannot be undone.

---

## Retention Period

**There is no retention period.**

* Account deletion is **immediate and permanent**.
* Data is erased from the database as soon as deletion is confirmed.
* There is no “soft delete”, recovery window, or temporary storage.
* Deleted accounts **cannot be restored**.

---

## Data That Is Permanently Deleted

The app performs a **deep delete** that removes all personal data from all primary systems and collections, including but not limited to:

* **User Profile**

  * Name, email address, preferences, and settings stored in the `users` collection.
* **Tasks**

  * All user-created tasks.
* **Focus Sessions**

  * Complete focus and productivity session history.
* **Time Blocks**

  * All custom-defined time blocks.
* **Inbox / Notifications**

  * All notifications and in-app messages.
* **Authentication Data**

  * Login credentials (email/password or social login identifiers) are permanently removed from the authentication system.

Once deleted, this data is **irreversibly erased** and cannot be accessed by the user or the developer.

---

## Data That May Be Retained (Anonymised)

Some historical records that involve **other users** are retained for data integrity but are **fully anonymised**:

### Challenge History

* Past challenge results (wins/losses) stored in `challenge_results` are not deleted.
* **Reason:** To preserve the history and statistics of other participants.
* **Privacy Impact:**

  * Your user profile is deleted.
  * The stored User ID no longer resolves to any personal data (no name, email, or profile).
  * The data cannot be used to identify you.

### Active Challenges

* You are immediately removed from the `participantIds` list of any active challenges.
* From the perspective of other users, you simply disappear from the challenge.

---

## Data Security

All data deletion requests and operations are processed securely. User data is transmitted using encrypted connections (HTTPS/TLS).

---

## Contact

If you experience issues deleting your account or have questions regarding data privacy, you may contact the app developer at:

**Email:** *[cordovagroup2@gmail.com]*

---

