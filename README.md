<p align="center">
  <img src="public/sharelah.png" alt="Sharelah logo" width="120" height="120">
</p>

<h1 align="center">Sharelah</h1>

<p align="center">
  <strong>Login-free file and text sharing between devices.</strong><br>
  Join with a code or QR. Delete the session when you're done.
</p>

<p align="center">
  <a href="https://sharelah.onrender.com/"><strong>TRY ME!</strong></a>
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#how-it-works">How it works</a> •
  <a href="#tech-stack">Tech stack</a> •
  <a href="#getting-started">Getting started</a> •
  <a href="#privacy">Privacy</a>
</p>

---

## Overview

**Sharelah** moves files and text from one device to another without accounts, sign-ups or installs. Open it in a browser, start a session, and anyone with the code or QR can join.

## Features

* **No login.** Nothing to sign up for.
* **Quick pairing.** Join a session with a code or by scanning a QR.
* **Files and text.** Send either, to any device with a browser.
* **Live updates.** Shared items show up on connected devices in real time.
* **Disposable.** Delete the session and everything in it is gone.

## How it works

1. **Start a session.** The server creates it and gives you a join code and QR.
2. **Join.** Other devices enter the code or scan the QR.
3. **Share.** Text and files are added to the session and appear on every connected device.
4. **Clean up.** Delete the session, or let it expire after 2 hours of inactivity.

## Tech stack

* **Server:** Node.js, Express
* **Real-time:** Socket.IO
* **Uploads:** Multer
* **QR codes:** qrcode
* **Hosting:** Render

## Getting started

Try the hosted version at **[sharelah.onrender.com](https://sharelah.onrender.com/)**, or run it locally.

**Prerequisites:** Node.js 18 or newer.

## Privacy

Sessions and files live in memory and on local disk only. They are wiped when:

* the session is deleted,
* 2 hours pass with no activity, or
* the server restarts.