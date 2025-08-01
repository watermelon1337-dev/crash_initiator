# Crash Initiator (⚠️ BSOD Script)

> ⚠️ **WARNING:** This script is designed for educational or experimental use **in virtual machines only**.  
> It intentionally crashes Windows by terminating a critical system process (`csrss.exe`).

## ⚠️ DISCLAIMER

- **DO NOT** run this on your main system.
- I take **NO responsibility** for any data loss, damage, or consequences.
- Run only in a **safe, isolated environment (VM)**.
- This project is for **educational/demonstration purposes only**.

## What it does

- Asks for confirmation before proceeding.
- Plays two videos (`cmertvnishite.mp4`, `pokoivbogastve.mp4`).
- Shows a visual “goodbye” screen with ASCII skulls.
- Then forcefully kills `csrss.exe`, which causes a BSOD.

## How to run

1. Place your `.mp4` videos in the same folder.
2. Run `bsod_launcher.bat`.
3. Read the warning, type `Y` to confirm.
4. The system will crash after both videos finish playing.

## Important

- This uses the command:  taskkill /f /im csrss.exe
