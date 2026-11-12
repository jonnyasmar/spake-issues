# Spake issues

This is where bugs and feature requests for [Spake](https://spake.app) are tracked in
public. Spake is a Mac app for voice notes that keep the screen recording, saved as
plain files. Its source code is private; this repository holds issues only.

One person reads everything here, the same one who wrote the app.

## Before you open an issue

- **Read the [known limitations](https://github.com/Hearthworks-Apps/spake-issues/issues/1)**
  pinned at the top of the issue list. Your problem may already be written down, with a
  workaround.
- **Search the open issues.** A thumbs-up on an existing issue counts; a duplicate
  splits the conversation.
- **Do not post a real note.** No recordings, transcripts, screen text or screenshots
  of your notes: this repository is public. If one note is involved, describe it
  (length, language, whether it was an area recording), or make a throwaway note that
  shows the same problem.

## Reporting a bug

Use the **Bug report** form. The things that make a report solvable in one round trip:

1. **Help ▸ Report a Problem…** in Spake. It builds a zip of Spake's logs and
   diagnostics on your Mac and sends nothing by itself. Save it, open it, check it, and
   drag it into the report, or use **Email Report** to send it to support@spake.app if
   you'd rather it weren't public.
2. **The Spake version** (Spake ▸ About Spake), your **macOS version**, and your
   **Mac model** (Apple menu ▸ About This Mac).
3. **What you did, step by step**, what you expected, and what happened instead.
4. **What stayed on disk.** Did the note's folder appear in your notes folder? Is
   there an `audio.wav` and a `recording.mp4` in it? Recordings that haven't reached
   your notes folder yet wait in `~/Library/Application Support/Spake/Recovery`.
5. **If Spake crashed:** macOS writes a crash report to
   `~/Library/Logs/DiagnosticReports`. Attach the most recent file named
   `SpakeApp-<date>.ips` (and any `spake-*.ips` from the same minute). GitHub doesn't
   accept the `.ips` extension; rename it to `.txt` first.

Crash reports contain the app's call stack and your macOS version, not your notes.
Read one before attaching it if you want to be sure.

## Requesting a feature

Use the **Feature request** form. The most useful part is what you were trying to do
when you noticed it was missing. Requests with a concrete use are the ones that move;
none of them come with a date.

## Security

**Do not report security problems here.** Email **security@spake.app** with a
description and steps to reproduce, and give me a chance to ship a fix before
disclosing. Don't attach a recording, a transcript, or credentials.

## Everything else

- License keys, activations, refunds, anything about a purchase:
  **support@spake.app**, from the address you bought with. Please don't post a license
  key here.
- What Spake sends over the network, and what it stores: [spake.app/privacy](https://spake.app/privacy)
- The note format, if you want to build against it: [spake.app/format](https://spake.app/format)
- Release notes: in the app's update window, and at [spake.app/changelog](https://spake.app/changelog).
