<p align="center"><img src="icon.png" width="140" alt="Transfer Portal"></p>

<h1 align="center">Transfer Portal</h1>
<p align="center">Send files, folders and messages straight from one PC to another — encrypted, with nothing stored in between.</p>

<p align="center"><a href="https://github.com/Alchemy-Labs-Creations/Transfer-Portal-Hub/releases/latest/download/Transfer-Portal-Setup.exe"><b>⬇ Download for Windows</b></a></p>

---

## Getting started

Someone sends you an **invite**: a short message with a link and an invite code.

1. Download and run **Transfer-Portal-Setup.exe** from the link above.
   Windows may say it's from an unknown publisher. Click **More info**, then **Run anyway**.
2. Open Transfer Portal. On the Welcome screen, type your name.
3. Paste the whole invite message into **Your invite** and press **Join**.

After a few seconds you'll see each other as online, and you can send files right away.

## What it does

- **Files and whole folders**, any size, sent PC to PC. Pause, resume or cancel from either side.
- **Messages** with each PC you're paired with. Write any time: if the other PC is off, your message waits for it and arrives when it's back.
- **Notices when you're away** (optional): a phone ping through the free ntfy app, or a short email, when a message or files are waiting. Turn them on in **Settings → Notifications when you're away**.
- **Always ready**: closing the window keeps it in the system tray so you can be reached. It can also start with Windows.
- **Quarantine**: everything you receive waits in Quarantine while Windows Defender scans it. Release it to your save folder when you want it.
- **History** of what you sent and received, sorted by PC and by kind of file.

## Private by design

Your files and messages go **directly between the two PCs**, encrypted. The only server involved introduces the two PCs to each other when they connect.

When a message has to wait for a PC that's off, the server holds it **locked** with a key only the two PCs have, so it can't read it. It's deleted as soon as it's collected, or after 30 days. Files never wait on the server: they only travel when both PCs are online.

Email notices only say who wrote and that something is waiting, never what was said.

Each pair code belongs to just the two of you. Keep it private: anyone with it could pair in your place. If a code gets out, press **New code** in Settings.

## Removing it

Go to **Windows Settings → Apps → Installed apps → Transfer Portal → Uninstall**. Your received files stay where you saved them.

---

<sub>Made by Alchemy Labs Creations. The connection helper (signaling server) lives in <a href="https://github.com/Alchemy-Labs-Creations/Transfer-Portal-Server">Transfer-Portal-Server</a>.</sub>
