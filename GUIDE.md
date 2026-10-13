# Lectern user guide

Everything Lectern does, and how to use it. For the download, see the [latest release](https://github.com/Lord-Raven1/Lectern-Release/releases/latest).

**Contents:** [Getting it running](#getting-it-running) · [Connecting the projector](#connecting-the-projector) · [Starting](#starting) · [The toolbar](#the-toolbar) · [Zoom](#zoom) · [The cursor ring](#the-cursor-ring) · [Highlight](#highlight) · [Spotlight](#spotlight) · [Notes](#notes) · [Undo and clear](#undo-and-clear) · [Freeze and Back in a moment](#freeze-and-back-in-a-moment) · [Using other apps while showing](#using-other-apps-while-showing) · [Online lectures (Teams, Zoom)](#online-lectures-teams-zoom) · [Stopping](#stopping) · [Shortcuts](#shortcuts) · [Options](#options) · [Troubleshooting](#troubleshooting) · [The log](#the-log) · [Feedback](#feedback)

---

## Getting it running

There are three downloads. They're all the same app, and none of them needs admin rights.

| File | What it is | Best for |
|---|---|---|
| **Lectern-Portable-&lt;version&gt;.exe** | One file. Double-click it to run; nothing is installed. | University and work laptops. Keep it in Documents or on a USB stick. |
| **Lectern-&lt;version&gt;-win.zip** | The app as a folder. Unzip it anywhere and run `Lectern.exe`. | If the portable one won't open (some IT setups block programs that run from temporary folders, which the portable one does behind the scenes). |
| **Lectern-Setup-&lt;version&gt;.exe** | Installs Lectern for you only, with a Start menu and desktop shortcut. | Your own laptop. |

**"Windows protected your PC":** Lectern isn't code-signed yet, so Windows may warn you the first time. Click **More info**, then **Run anyway**. If there's no Run anyway button, your organisation has turned it off; try the zip, or ask IT to allow Lectern.

**Zip blocked after unzipping?** Right-click the downloaded zip, choose **Properties**, tick **Unblock**, click OK, then unzip it again.

---

## Connecting the projector

Lectern needs Windows to treat the projector as a **second screen in extend mode**:

- **Epson iProjection:** connect in its **extended display** mode.
- **HDMI or VGA cable:** press **Windows + P** and choose **Extend**.
- **Wireless (Miracast):** press **Windows + K**, connect, then choose **Extend**.

**Don't use Duplicate (mirror) mode.** In mirror mode the room sees your whole laptop screen, and Lectern has no screen of its own to show your window on.

**Keep your app on your own screen.** You extend so Lectern has a screen to draw on, but you never drag anything onto it yourself. Lectern copies your one window onto the projector, like PowerPoint's presenter view. If your window ends up on the projector screen, Lectern moves it back to the screen it came from.

---

## Starting

Open Lectern. Its window has two steps:

**1. What to show.** Click the window you want the room to see: VS Code, a browser, PowerPoint, a PDF, anything. Minimised windows are listed too (marked "Minimised: opens when you start") and come back up when you start. **Refresh** looks for windows again if you've just opened one. You can also pick a **whole screen**, though one window is more private.

**2. Projector.** Check the right screen is selected.

- With **two screens** (laptop + projector), Lectern picks the projector for you.
- With **three or more** (for example laptop + monitor + projector), Lectern asks which one is the projector. Click **Identify screens** to show a big number on each screen for a few seconds, then pick the matching one. Lectern remembers your choice.
- With **no projector** connected, Lectern shows its picture in an ordinary window instead. This is handy for trying it out, or for sharing that window in Teams or Zoom.

Click **Start showing**. Your window comes to the front, the projector shows it, and the toolbar appears on it.

---

## The toolbar

A small dark bar sits near the bottom of your shared window. It's on **your screen only**; the room never sees it. Hover over any button for a reminder of what it does.

From left to right:

| Button | What it does |
|---|---|
| ⋮⋮ (grip) | Drag it to move the toolbar out of the way. It stays in that spot relative to your window. |
| 🔍 Zoom | Turns on the zoom tool. See [Zoom](#zoom). |
| − / % / + | Zoom out, the current zoom level, zoom in. |
| Inward corners (Show it all) | Zooms back out to the whole window. Also ends the zoom tool. |
| Arrow | Follow the mouse while zoomed in, on or off. |
| Highlighter | Highlight lines. See [Highlight](#highlight). |
| Sun | Spotlight. See [Spotlight](#spotlight). |
| Speech bubble | Notes. See [Notes](#notes). |
| ↶ | Undo the last highlight, spotlight or note. |
| Bin | Clear all highlights, spotlights and notes. |
| ⏸ | Freeze the picture. |
| Cup | Show "Back in a moment". |
| Red square | Stop showing. |

After you click a toolbar button, the keyboard goes straight back to your window, so you can carry on typing.

The **Lectern window** has the same controls as large buttons, if you prefer them. The toolbar only shows while your shared window is in front; it hides while you're in another app.

**When a tool is on**, your window gets a faint tint and a yellow frame, with a hint at the top saying what to do. That means your next click goes to Lectern, not to your app. Press **Esc**, or click the tool's button again, to finish.

---

## Zoom

Turn on the zoom tool (toolbar 🔍, or **Ctrl + Alt + A**), then:

- **Click** a spot to zoom in there. Click again to zoom in further.
- **Drag a box** around an area to fill the projector with it.
- **Scroll the wheel** to zoom in and out around the mouse.

The zoom tool stays on so you can keep adjusting. Press **Esc** or click **Show it all** when you're done.

**Zoom in / zoom out** (the + and − buttons) work at any time without the zoom tool, around your mouse.

**Following the mouse:** when zoomed in, the view gently follows your mouse. It only moves when your mouse nears the edge of what the room can see, so it doesn't jitter. Turn it on or off with the arrow button or **Ctrl + Alt + F**.

**A zoom box locks the view.** When you zoom with a box, following turns off, so you can go to the toolbar for a highlight or note without the view drifting away. Turn following back on with the arrow button, **Ctrl + Alt + F**, or **Show it all**.

**What the room sees:** when you're zoomed in, a dashed yellow outline labelled **ROOM SEES** on your screen shows exactly which part is on the projector.

**Tip:** zoomed-in text survives wireless projection much better than a full screen, so zooming also helps when the picture is blurry.

---

## The cursor ring

Your normal mouse pointer is tiny on a projector, so Lectern draws a **big ring** around it on the projector, with a **ripple when you click**. The ring hides while your mouse is over another app. Both can be turned off under [Options](#options).

---

## Highlight

Turn on the highlight tool (toolbar highlighter, or **Ctrl + Alt + H**). A yellow **band follows your mouse**, so you can see which line you'll highlight before you click.

- **Click** a line to highlight it. The tool stays on, so click as many lines as you like.
- **Drag** over several lines to highlight them as one block.
- **Scroll the wheel** to make the band taller or shorter, to match your editor's line height. Lectern remembers it.
- **Drag an existing highlight** up or down to stretch it a line at a time.
- **Click an existing highlight** to remove it.
- Highlights that overlap or touch **merge** into one block.

Press **Esc** when you're done.

---

## Spotlight

Turn on the spotlight (toolbar sun), then **drag a box** around what matters. Everything else on the projector dims. Drawing a new spotlight replaces the old one. Remove it with undo or clear.

---

## Notes

Turn on notes (toolbar speech bubble), **click where the note should point**, type a short note, and press **Enter**. Press **Esc** to cancel.

To **move a note**, turn notes on, then drag the note to its new spot.

---

## Undo and clear

- **Undo** removes the last highlight, spotlight or note.
- **Clear** removes all of them.

**They also clear themselves:** highlights, spotlights and notes point at particular lines, so when you **scroll** or **switch files** and those lines move away, Lectern removes them within about a second, so they never point at the wrong thing. You can turn this off under [Options](#options).

Highlights and notes are drawn on the projector (and shown on your screen for reference) only. **Your files are never changed.**

---

## Freeze and Back in a moment

- **Freeze** (⏸) holds the current picture on the projector while you do something else in the window, such as looking something up. Click it again to go live.
- **Back in a moment** (cup) covers the projector with a "Back in a moment" card. Click it again to return.

---

## Using other apps while showing

Your laptop screen stays yours. While you're showing:

- You can use any other app: email, Teams, a browser. The room only ever sees the window you picked.
- When you switch to another app, the projector **holds the last picture** of your window, so the room doesn't watch your mouse wander. It goes live again when you come back. You can turn this off under [Options](#options).
- If you **minimise** the shared window, the projector holds the last picture until you bring it back.
- If you **close** it, the projector holds the last picture, and the Lectern window tells you. Pick another window to carry on.

---

## Online lectures (Teams, Zoom)

Lectern works for online lectures too, even with just your laptop screen:

1. With no projector connected, start showing as usual. Lectern opens its picture in a normal window called **Lectern stage**.
2. In Teams or Zoom, share **that window** (not your editor or your whole screen).
3. Work in your own window as normal. The call sees everything Lectern shows: zoom, highlights, notes and the cursor ring.

The Lectern stage window can sit behind your other windows, and the call still sees it live. Two things to know:

- **Don't minimise** the Lectern stage window. Windows can't share a minimised window, so the call would freeze.
- While you're clicking around in Teams or Zoom itself, the picture holds still (that's [automatic freeze](#using-other-apps-while-showing)) and goes live again when you're back in your window. If that gets in the way, turn it off under [Options](#options).

With a projector connected, you can also share the projector's screen in the call instead.

---

## Stopping

Click the **red square** on the toolbar, or **Stop showing** in the Lectern window. The projector screen goes back to normal Windows use.

---

## Shortcuts

Everything is on the toolbar. Three shortcuts cover what you reach for most, and they work while you type in any app:

| Keys | Does |
|---|---|
| **Ctrl + Alt + A** | Zoom tool on/off |
| **Ctrl + Alt + H** | Highlight tool on/off |
| **Ctrl + Alt + F** | Follow the mouse on/off |
| **Esc** | Finish or cancel the current tool |

If another app already uses one of these, the Lectern window says so. The toolbar works either way.

---

## Options

In the Lectern window while showing, open **Options**:

- **Big cursor ring on the projector**: the ring around your mouse.
- **Show clicks**: the ripple when you click.
- **Freeze the picture while you're in another app.**
- **Clear highlights and notes when the window scrolls or changes.**
- **Open log folder**: see [The log](#the-log).

---

## Troubleshooting

**The projector isn't listed.** Make sure it's in **extend** mode, not duplicate, then click **Refresh** in Lectern.

**The wrong screen shows Lectern's picture.** Pick the right one under "Projector" (use **Identify screens** if you have three or more).

**The toolbar isn't showing.** Click on your shared window: the toolbar only shows while that window is in front. If it keeps disappearing, attach [the log](#the-log) to your [feedback](#feedback): it records each time the toolbar hid and why.

**A shortcut does nothing.** Another app may already use it; the Lectern window lists any it couldn't use. Use the toolbar instead.

**My window keeps jumping back.** Lectern moves your window off the projector screen, because it should stay on your own screen. If something keeps putting it back there, Lectern stops trying and says so.

**The projector shows a still picture.** Freeze may be on, you may be in another app, or the window may be minimised or closed. The Lectern window says which.

**Something went wrong mid-lecture.** Click **Stop showing** and carry on as normal, then send [feedback](#feedback) about what happened.

---

## The log

Lectern keeps a log of what happens, to help track down problems: which buttons and shortcuts you used, your screens, when the toolbar hid and why, and any errors.

- **Find it:** in the Lectern window, open **Options** and click **Open log folder**. The file is **lectern-log.txt** (older entries move to **lectern-log.old.txt**).
- **Size:** it never takes more than about 2 MB.
- **Privacy:** it stays on your computer and is never sent anywhere unless you attach it yourself. It records the name of the window you share, but never other apps' window titles or the text of your notes.

---

## Feedback

Click **Feedback** at the bottom of the Lectern window, or [open an issue](https://github.com/Lord-Raven1/Lectern-Release/issues/new) directly. The Feedback link opens a short form on GitHub with your Lectern version and Windows details filled in. It needs a free GitHub account, and posts are public, so leave out anything private.

Please include what happened, what you were doing just before, your setup (iProjection or cable, any extra monitor), a screenshot if you can (**Windows + Shift + S**), and [the log](#the-log). The log is the most useful part: it shows exactly what Lectern did.

---

Lectern collects nothing and sends nothing anywhere. See [terms of use and privacy](TERMS.md) and the [licence](LICENSE). © 2026 **Lord-Raven1**. All rights reserved.
