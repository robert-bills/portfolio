# 📄 Case Study: Real-World Phishing Response and Tool Enhancement

**Incident Date:** 25 July 2025  
**Author:** Rob Bills — Developer · Educator · Concerned Citizen  
**Tool:** [Phish Finder – SeaBeasties Tools](https://seabeasties.tools/phish-finder)

---

## 🧠 The Threat

While searching for new opportunities through a state-run job board (Connecting Colorado), I received an unsolicited message claiming to be from a company recruiter. The email contained:

- A suspiciously generic greeting (`"Dear Applicant"`)
- Unrealistic salary offers ($40–$60/hr) for a wide range of roles
- A link to a public Microsoft Teams meeting using `teams.live.com`
- Instructions to contact a ProtonMail address pretending to be HR
- An urgent request for immediate interview via chat

---

## 🔍 Actions Taken

I immediately recognized signs of a phishing attempt and followed up with coordinated reporting and mitigation:

- Reported the ProtonMail address to Proton’s abuse team
- Submitted the message to Gmail as phishing
- Alerted Connecting Colorado to the misuse of their job platform
- Received **confirmation from ProtonMail** that the scam account was disabled under their Terms of Service

---

## 🛠️ Tool Enhancement

Using this phishing message as a real-world test case, I updated **Phish Finder**, a browser-based message analyzer I built for non-technical users.

### Key updates included:

- Detection for **free email providers** (e.g., Gmail, ProtonMail, Yahoo)
- Flagging of **public meeting tools** like Zoom, Google Meet, Teams Live
- Risk-tiered scoring logic that now correctly triggers a **High Risk** alert
- Improved UI feedback and plain-language flag descriptions

After testing against the scam message, **Phish Finder correctly flagged the message as High Risk**, surfacing both the impersonation and meeting invite.

---

## 🌍 Community Contribution

The updated tool was:

- Shared with a small, trusted tester group for early validation
- Indexed and findable via Google (search: **SeaBeasties Tools Phish Finder**)
- Offered to local workforce media contacts as a **free public resource** for job seekers

> **No sign-up. No data collection. Just plain-language analysis to help regular people stay safe.**

---

## 🧭 Outcome

- ✅ Threat actor’s ProtonMail account deactivated  
- ✅ Scam reported to all relevant platforms  
- ✅ Public phishing detection tool updated and redeployed  
- ✅ Offered the Colorado workfoce a free tool to detect this exact scam vector

---

## 💬 Quote

> *"I didn’t want to just report the problem. I wanted to DO something to protect people."*

---

## 📎 Tool Link

[https://seabeasties.tools/phish-finder](https://seabeasties.tools/phish-finder)
