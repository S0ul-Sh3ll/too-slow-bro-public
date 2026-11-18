# Privacy Policy — Too Slow Bro

_Effective date: 18 November 2026_

Too Slow Bro ("the app") is a multiplayer reaction game for Android, played with people nearby (Wi-Fi, hotspot or Bluetooth) or online, published by **S0ulSh3ll** ("we"). This policy explains what information the app uses, where it goes, and the choices you have.

**In short:** there is no account and no sign-up. Your game data stays on your phone and on the phones of the people you play with. Data only leaves your phone for the internet when you **Play online** (our game server, which keeps it in memory only) and for Google's advertising service (AdMob), which shows the banner ad.

## 1. Information you enter
- **Nickname, avatar and colour.** You choose these on the profile screen. They are stored on your phone. When you join or host a game, they are sent to the other phones in that game room (and, online, through our game server) so everyone can see who is playing.
- We do not ask for your real name, email, phone number, age or photos.

## 2. Game data
- **Match results and reaction times** (for the Stats screen) are stored only on your phone, in the app's private storage.
- **During a game**, each phone sends the other phones in the room its round results (for example: which step you tapped and your reaction time in milliseconds). This is how the phones agree on the winner.
- In **local games**, game traffic travels directly between phones over your local Wi-Fi network, a phone hotspot, or Bluetooth. It does not go through any server, and we never receive it.
- In **online games**, it goes through our game server; see [Playing online](#3-playing-online).

## 3. Playing online
**Play online** lets you play people who are not near you: a quick match for 2 or 4 players, or a private room shared with a 5-digit code. Online games run on a game server operated by us, hosted by **DigitalOcean** in a data centre in **Singapore**. The connection between your phone and the server is encrypted (TLS). Traffic to the server passes through **Cloudflare**, which protects it against attacks and overload; Cloudflare handles the encrypted connection on our behalf and sees your IP address and the game traffic as it passes through, under its own privacy policy (https://www.cloudflare.com/privacypolicy/).

When you play online, the server receives:

| Data | Why |
|---|---|
| Your IP address | Needed for any internet connection, so the server can send the game back to your phone. The game server does not store or log it |
| Your nickname, avatar and colour | Shown to the other players in your game |
| A random player ID made on your phone (not linked to your identity) | Lets you get your seat back after a dropped connection or if the app closes. It is never shown or sent to other players |
| Your taps and round results (reaction times) | To play the game. The server runs the match, judges every round and checks that results are believable |
| The emoji reactions you send | Shown to the other players in your game |
| The 5-digit code of a private room you join | To put you in your friend's room |
| The app's network version number | To tell you when the app needs an update to play online |

**No chat with strangers:** online games have no typed chat. You can only send a fixed set of emoji, so nobody can send you written messages.

**How long it is kept:** only in the server's memory while you are connected or your game is still running, and for up to 5 minutes after you drop out of a running game (so you can rejoin). Nothing is written to disk, and the game server keeps no records of who played. We do not use this data for advertising or analytics, and we do not share it with anyone except the other players in your game. DigitalOcean provides the server hardware and network under its own privacy policy (https://www.digitalocean.com/legal/privacy-policy) and does not receive game data from us. Cloudflare only passes the traffic through and keeps standard network logs, such as IP addresses, for a limited time for security.

## 4. Permissions the app uses
| Permission | Why |
|---|---|
| Internet, network state, Wi-Fi state, Wi-Fi multicast | To find and join game rooms on the local network, to play online, and to load ads. |
| Bluetooth (scan, connect, advertise) | For 2-player games over Bluetooth. The app declares that Bluetooth scanning is **not** used to derive your location. |
| Location (Android 10 and 11 only) | Android requires this permission for Bluetooth scanning on those versions. The app never reads, stores or sends your location. |
| Vibration | Haptic feedback on taps and results. |
| Motion sensor (no permission needed) | Tilt Maze reads the phone's tilt on the device only. |

The app does **not** use the microphone, camera, contacts, photos or files.

## 5. Advertising (Google AdMob)
The app shows a banner ad provided by Google AdMob. To show and measure ads and to prevent fraud, Google's SDK may collect and process:
- your device's **advertising ID**,
- your **IP address** (which can indicate an approximate location),
- device information (model, OS version, language),
- ad interaction data (for example, ads shown and tapped), and diagnostic data.

This information is collected and processed by Google, not by us; we do not receive it in a form that identifies you. Google's use of this data is described in **Google's Privacy Policy** (https://policies.google.com/privacy) and **How Google uses information from sites or apps that use its services** (https://policies.google.com/technologies/partner-sites).

**Your choices:**
- In the EEA, the UK and Switzerland, the app asks for your consent before personalised ads are shown (Google's User Messaging Platform). You can change your choice at any time in the app: **Settings → Ad privacy choices** (shown where this applies).
- You can reset your advertising ID or opt out of personalised ads in your phone's settings: **Settings → Google → Ads** (or **Settings → Privacy → Ads** on some phones).

## 6. Data sharing
We do not sell, rent or share your information. The only data shared is:
- your nickname, avatar, colour and round results, with the other players in the same game room (on their phones; online games pass through our game server, see Playing online), and
- the advertising data collected directly by Google AdMob, as described above.

## 7. Data retention and deletion
- Everything the app stores lives on your phone. You can delete it at any time by uninstalling the app, or in **Settings → Apps → Too Slow Bro → Storage → Clear storage**.
- Other players' phones keep your nickname and match results in their own local stats until they clear or uninstall the app.
- Online games: kept only in the game server's memory while you are connected or your game is running, then erased. Nothing is saved to disk.
- Data collected by Google AdMob is retained according to Google's policies.

## 8. Children
The app is not directed at children under 13, and we do not knowingly collect personal information from children. The app itself collects no personal information beyond the nickname you type. Online games have no typed chat, only a fixed set of emoji, so children cannot receive written messages from strangers. If you believe a child has provided personal information, contact us and we will help remove it.

## 9. Security
In local games, game data is exchanged only between phones on the same local network or Bluetooth connection that you choose to join. Online games use an encrypted connection (TLS) to our server, which holds game data only in memory. Ad traffic to Google is encrypted (HTTPS).

## 10. Changes to this policy
If this policy changes, we will update the effective date above and publish the new version at the same address.

## 11. Contact
Questions about this policy or your data: **rishabhdahiya.work@gmail.com** or open an issue on this GitHub repository.
