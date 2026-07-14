# CT Dent Assistant

**A Windows desktop companion for the [CT Dent](https://doctors.ct-dent.co.uk) reporting portal.**

CT Dent Assistant turns your case list into a live, one-click worklist. For any
case it signs you in, downloads the scan in your preferred format, and launches
the correct viewer automatically — while logging every case opened for easy
monthly reporting.

## ⬇️ Download

**[Download the latest installer](../../releases/latest)** → run `CT_Dent_Setup.exe`.

- Windows 10 / 11 (64-bit)
- Installs per-user — **no admin prompt**
- Works with Microsoft Edge, Google Chrome, or Brave (uses your own browser)
- No separate browser download needed

## Features

- **Live worklist** with colour-coded case statuses
- **One-click open** — downloads the scan and launches the DICOM viewer *you* chose
  (any one you have installed); Volume Viewer downloads bring their own
- **Clinical history** on any row, before you open the case
- **Multi-study aware** — open and bill each study of a patient separately
- **Monthly billing export** and a **PDF invoice** in one click
- **Side-strip / pin / transparency** modes to sit neatly beside the portal

## 🛡 How your patient data is protected

**Nothing is ever uploaded.** There is no server, no cloud, no account and no
tracking. The app only drives *your own browser* to the CT Dent portal you
already use. Your patient data never leaves your computer.

**You choose where it is kept — and it must be an encrypted drive.** On first
run the app makes you pick a **Storage Target** folder, ideally on a
BitLocker-encrypted drive. There is **no default location**: nothing is saved
anywhere until you choose it. The app asks Windows whether that drive really is
encrypted and warns you loudly if it is not.

**Everything the app keeps lives in that one place:** the scans, the case log
(patient names and fees), the cached clinical histories, the browser profile
(browsers quietly cache the portal pages they show, and those carry patient
names), and the month-end report in `ctdent-case-logs`.

> **Older versions got this wrong.** Version 2.1.3 and earlier left some of the
> above on your `C:` drive, which may not be encrypted. **Version 2.2.0 moves it
> all onto your encrypted drive and deletes the old copies from `C:`.**

**Your sign-in is protected.** The portal session token is scrambled with
Windows' own built-in protection and locked to your Windows account, so a copy
taken to another computer is useless there. It does *not* protect against
malware already running on your own computer as you.

**Your CT Dent password is never asked for, typed or stored.** You sign in
yourself, in your own browser.

**Uninstalling never silently deletes patient records.** It asks separately
about your scans, your invoices and your exported reports — and every question
defaults to *keeping* them.

### What is still down to you

- Use an encrypted drive (**BitLocker**, or **BitLocker To Go** for external disks).
- Lock your computer when you step away (**Win + L**).
- Don't email scans around, or copy them to unencrypted memory sticks.
- Delete cases you no longer need.
- As the reporting clinician **you are the data controller** under UK GDPR.

## More from the same developer

| | | |
|---|---|---|
| 🧬 **[Leela-SR](https://leela-sr.vercel.app/)** | Evidence Synthesis Platform | [Open Leela-SR](https://leela-sr.vercel.app/) |
| 🚀 **[Moonshot](https://moonshot-app.vercel.app/)** | AI Presentations & Papers | [Launch Moonshot](https://moonshot-app.vercel.app/) |
| 🌀 **[RadInsights](https://www.radinsights.xyz)** | Your Radiology Companion | [Enter RadInsights](https://www.radinsights.xyz) |

## Support

Developed by **Dr. Gaurav S Gupta** • **Eralight Limited** •
[contact@radinsights.xyz](mailto:contact@radinsights.xyz) •
© Eralight Limited. All rights reserved.

---

_This repository hosts the public installer download only. The application source
is proprietary. © Eralight Limited. All rights reserved._
