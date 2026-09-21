<p align="center">
  <img src="assets/banner.png" alt="BBNotes — a cute little to-do list for everyone" width="100%" />
</p>

<p align="center">
  <img src="assets/badge-made.png" alt="made with ♡" height="30" />
  <img src="assets/badge-discord.png" alt="discord login" height="30" />
  <img src="assets/badge-saved.png" alt="saved forever" height="30" />
  <img src="assets/badge-react.png" alt="react 19" height="30" />
  <img src="assets/badge-node.png" alt="node 22" height="30" />
  <img src="assets/badge-sqlite.png" alt="sqlite" height="30" />
</p>

<p align="center">
  A tiny notebook with a pink Y2K scrapbook look — cut-out letters, sticker cards,<br/>
  pixel stars, and a burst of daisies every time something gets checked off.<br/>
  Three pages behind a book's spine: <b>to-dos</b>, <b>notes</b> and <b>reminders</b>.
</p>

<p align="center">
  <sub>BB is for <a href="https://khihani.com/b/beck-and-baddie">Beck &amp; Baddie</a> — two VRChat avatars made by my friend <a href="https://dyzzy.store/b/beck-by-dyzzy">Dyzzy</a> and <a href="https://khihani.com/b/baddie-by-khihani">Khihani</a>, whose showcase this whole look is based on.<br/>
  Beck was modelled after his childhood with his Mom: the music she introduced him to, the cartoons they watched,<br/>
  the colours of his childhood bedroom walls, and — most importantly — her favourite thing: flowers.<br/>
  That's why there's a daisy on every check. Much of the proceeds from Beck go to her care. ♡ <br/>
    <a href="https://www.youtube.com/watch?v=mwiBkRRgyfs"> You can check the showcase here.</a>
  </sub>
</p>

<p align="center"><img src="assets/divider.png" alt="" width="100%" /></p>

<p align="center"><img src="assets/heading-features.png" alt="features" height="60" /></p>

<table align="center">
  <tr>
    <td><img src="assets/feature-discord.png" alt="ur list, ur login — sign in with Discord" width="100%" /></td>
    <td><img src="assets/feature-daisy.png" alt="a daisy on every check" width="100%" /></td>
  </tr>
  <tr>
    <td><img src="assets/feature-saved.png" alt="saved forever — a real SQLite file on the server" width="100%" /></td>
    <td><img src="assets/feature-phone.png" alt="cute on ur phone too" width="100%" /></td>
  </tr>
  <tr>
    <td><img src="assets/feature-spine.png" alt="three pages, one spine — to-dos, notes and reminders behind a book's index tabs" width="100%" /></td>
    <td><img src="assets/feature-notes.png" alt="notes on index cards — a title, as much writing as you like, pinned and searchable" width="100%" /></td>
  </tr>
  <tr>
    <td colspan="2"><img src="assets/feature-reminders.png" alt="reminders that ring — once, daily or weekly, with snooze and a browser notification" width="50%" /></td>
  </tr>
</table>

<p align="center"><img src="assets/divider.png" alt="" width="100%" /></p>

<p align="center"><img src="assets/heading-how-it-works.png" alt="how it works" height="60" /></p>

1. Hit **log in with discord**. Discord asks for the `identify` scope only — id, name, avatar. No email, no servers.
2. You're in your notebook. Only you can see it; every read and write is scoped to your account.
3. **to-dos** — add things, check them off, drag to reorder, clear the done ones. A daisy blooms on every check — and when the last one goes, the whole title blooms.
4. **notes** — index cards with a title and as much writing as you like. Open one and it saves itself as you type; pin the important ones to the top; find them with the search box.
5. **reminders** — a thing to do at a time, picked on a calendar sheet: once, daily or weekly. Overdue ones get flagged; snooze by an hour or a day, or tick them off. While a BBNotes tab is open it pings you with a browser notification when one comes due.
6. Come back next week, on your phone, after clearing your cache — it's all still there.

<p align="center"><img src="assets/login.png" alt="the login card" width="720" /></p>

<p align="center"><img src="assets/divider.png" alt="" width="100%" /></p>

<p align="center"><img src="assets/heading-the-look.png" alt="the look" height="60" /></p>

Sticker-bomb collage energy: ransom-note letters cut from different papers, chunky
white-outlined cards on grid paper, washi tape, pixel stars, and daisies that sway in
the corners. Every check pops eleven more daisies out of the box. The three pages hang
off a book's spine along the top edge — index tabs on every screen, a sheet that slides
up for the calendar on phones.

<p align="center"><img src="assets/list.png" alt="BBNotes on desktop" width="100%" /></p>

<p align="center"><img src="assets/divider.png" alt="" width="100%" /></p>

<p align="center"><img src="assets/heading-the-stack.png" alt="the stack" height="60" /></p>

| | |
| --- | --- |
| **Frontend** | React 19 + Vite — no UI framework, hand-rolled CSS |
| **Backend** | Express 5 on Node 22 |
| **Database** | SQLite via the built-in `node:sqlite` — one file, WAL mode; to-dos, notes and reminders side by side |
| **Auth** | Discord OAuth2 (`identify` only), httpOnly session cookie |
| **Reminders** | No server push: an open tab checks the clock and rings a browser notification when one comes due |
| **Deploy** | One process serves both the site and the API, under a path if you like (`PUBLIC_URL`), with a coming-soon page when it isn't open yet (`COMING_SOON=1`) |

<p align="center"><img src="assets/divider.png" alt="" width="100%" /></p>

<p align="center"><img src="assets/footer.png" alt="made with ♡ · saved forever · just for u" height="56" /></p>
