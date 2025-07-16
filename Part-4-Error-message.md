
![Technical Writing](/images/technical-writing-1024x574.png "Technical Writing")


## 📋 Table of Contents

1. [Identify the Cause](#1️⃣-identify-the-cause)
2. [Specify Invalid Values](#2️⃣-specify-invalid-values)
3. [Specify Requirements and Constraints](#3️⃣-specify-requirements-and-constraints)
4. [Explain How to Fix It](#4️⃣-explain-how-to-fix-it)
5. [Provide Examples if Helpful](#5️⃣-provide-examples-if-helpful)
6. [Write Clearly](#6️⃣-write-clearly)
7. [Be Concise — Not Cryptic](#7️⃣-be-concise--not-cryptic)
8. [Avoid Double Negatives & Exceptions](#8️⃣-avoid-double-negatives--exceptions)
9. [Match the Audience](#9️⃣-match-the-audience)
10. [Use Terminology Consistently](#🔟-use-terminology-consistently)
11. [Format Long Messages Carefully](#1️⃣1️⃣-format-long-messages-carefully)
12. [Keep a Positive, Helpful Tone](#1️⃣2️⃣-keep-a-positive-helpful-tone)
13. [How You Can Help as Delivery Lead](#⚙️-how-you-can-help-as-delivery-lead)


# 🚫✅ Writing Better Error Messages — Practical Guide

Good error messages save users time and frustration. This guide explains **best practices** and how your team can put them into action.

---

## 📌 Best Practices for Writing Error Messages

---

### 1️⃣ Identify the Cause

✅ Be clear about *why* the error happened.  
🔍 Example: *“File upload failed because the file size exceeds 5 MB.”*

---

### 2️⃣ Specify Invalid Values

✅ If the user entered something wrong, show exactly what it was.  
🔍 Example: *“Username 'abc!' is invalid. Usernames must use only letters and numbers.”*

---

### 3️⃣ Specify Requirements and Constraints

✅ Tell users what rules apply — permissions, limits, or prerequisites.  
🔍 Example: *“This feature requires admin permissions.”*

---

### 4️⃣ Explain How to Fix It

✅ Always help the user move forward — don’t just say “Error.”  
🔍 Example: *“Please enter a password with at least 8 characters.”*

---

### 5️⃣ Provide Examples if Helpful

✅ Sometimes, an example clarifies the fix faster than words alone.  
🔍 Example: *“Example valid username: johndoe123”*

---

### 6️⃣ Write Clearly

✅ Use plain, direct language. Avoid jargon if the audience is non-technical.  
🚫 No confusing terms or technical slang for general users.

---

### 7️⃣ Be Concise — Not Cryptic

✅ Keep it short but clear.  
🚫 *Too short:* “Invalid input.”  
✅ Better: *“Invalid date format. Use MM/DD/YYYY.”*

---

### 8️⃣ Avoid Double Negatives & Exceptions to Exceptions

✅ Write straightforward rules.  
🚫 Bad: *“Action cannot not be undone.”*  
✅ Better: *“Action is permanent.”*

---

### 9️⃣ Match the Audience

✅ Use the right level of detail and words for your users.  
🔍 Example: For devs — “Null pointer exception in line 45.”  
For end-users — *“The app couldn’t connect. Try restarting.”*

---

### 🔟 Use Terminology Consistently

✅ Pick one term and stick to it.  
🚫 Don’t mix *folder* and *directory*. Choose one.

---

### 1️⃣1️⃣ Format Long Messages Carefully

✅ For longer errors, break up info clearly — use links for details.  
✅ Example: “Learn how to fix this [here](#).”

---

### 1️⃣2️⃣ Keep a Positive, Helpful Tone

✅ Be supportive, not cold or robotic.  
🚫 No need to over-apologize — stay neutral and clear.  
🔍 Example: *“Couldn’t save your changes. Please check your connection and try again.”*

---

## ⚙️ How You Can Help as a Delivery Lead

---

✅ **Set Standards:**  
Keep these tips as a checklist for reviews.

✅ **Do Peer Reviews:**  
Encourage devs and tech writers to review error messages together.

✅ **Clarify Audience:**  
Ask: *Who sees this message? Does it match their skill level?*

✅ **Check Consistency:**  
Push for consistent words — the same term every time.

✅ **Make It Habit:**  
Add *error message clarity* to your Definition of Done or PR checklist.

✅ **Share Good Examples:**  
Highlight real examples — what’s clear, what’s confusing — in team stand-ups.

✅ **Keep Improving:**  
Revisit error messages during maintenance — improve them as your app changes.

---

## 🏆 Bottom Line

Clear, helpful error messages guide users.  
They reduce support calls, fix frustration, and make your product feel polished.

**One small habit. Big trust builder.**

---