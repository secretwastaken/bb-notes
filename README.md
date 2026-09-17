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
  A tiny to-do list with a pink Y2K scrapbook look — cut-out letters, sticker cards,<br/>
  pixel stars, and a burst of daisies every time something gets checked off.
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
</table>

<p align="center"><img src="assets/divider.png" alt="" width="100%" /></p>

<p align="center"><img src="assets/heading-how-it-works.png" alt="how it works" height="60" /></p>

1. Hit **log in with discord**. Discord asks for the `identify` scope only — id, name, avatar. No email, no servers.
2. You're on your list. Only you can see it; every read and write is scoped to your account.
3. Add things, check them off, drag to reorder, clear the done ones. A daisy blooms on every check — and when the last one goes, the whole title blooms.
4. Come back next week, on your phone, after clearing your cache — it's all still there.

<p align="center"><img src="assets/login.png" alt="the login card" width="720" /></p>

<p align="center"><img src="assets/divider.png" alt="" width="100%" /></p>

<p align="center"><img src="assets/heading-the-look.png" alt="the look" height="60" /></p>

Sticker-bomb collage energy: ransom-note letters cut from different papers, chunky
white-outlined cards on grid paper, washi tape, pixel stars, and daisies that sway in
the corners. Every check pops eleven more daisies out of the box.

<p align="center"><img src="assets/list.png" alt="BBNotes on desktop" width="100%" /></p>

<p align="center"><img src="assets/divider.png" alt="" width="100%" /></p>

<p align="center"><img src="assets/heading-the-stack.png" alt="the stack" height="60" /></p>

| | |
| --- | --- |
| **Frontend** | React 19 + Vite — no UI framework, hand-rolled CSS |
| **Backend** | Express 5 on Node 22 |
| **Database** | SQLite via the built-in `node:sqlite` — one file, WAL mode |
| **Auth** | Discord OAuth2 (`identify` only), httpOnly session cookie |
| **Deploy** | One process serves both the site and the API |

<p align="center"><img src="assets/divider.png" alt="" width="100%" /></p>

<p align="center"><img src="assets/footer.png" alt="made with ♡ · saved forever · just for u" height="56" /></p>
