<h1 align="center">Hi, I'm Kesha 👋</h1>

<p align="center">
  I maintain the React Native libraries your app probably already depends on.
</p>

<p align="center">
  <a href="https://github.com/sponsors/kesha-antonov">
    <img src="https://img.shields.io/badge/💛_Sponsor_my_work-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white" alt="Sponsor kesha-antonov" />
  </a>
</p>

<p align="center">
  <strong>~680,000 npm downloads every month.</strong> <strong>11 million installs</strong> have gone
  through code I'm responsible for. Chat UI, pinch-to-zoom, background downloads, WebSocket transport,
  cloud sync. Free, MIT/Apache, and maintained by one person.
</p>

---

## 📦 What I maintain

| Library | What it does | Downloads |
|---|---|---|
| **[react-native-gifted-chat](https://github.com/FaridSafi/react-native-gifted-chat)** <br/> ⭐ 14.4k | The default chat UI of the React Native ecosystem. 76% of its source is mine, and every release since 2024 | ![](https://img.shields.io/npm/dm/react-native-gifted-chat?label=%20&color=blue) |
| **[react-native-zoom-reanimated](https://github.com/kesha-antonov/react-native-zoom-reanimated)** <br/> ⭐ 309 | Apple Photos-style pinch, pan and double-tap zoom at 120fps. 1.16M downloads all-time | ![](https://img.shields.io/npm/dm/react-native-zoom-reanimated?label=%20&color=blue) |
| **[react-native-background-downloader](https://github.com/kesha-antonov/react-native-background-downloader)** <br/> ⭐ 215 | Large file downloads and uploads that survive backgrounding and app termination. 1.07M all-time | ![](https://img.shields.io/npm/dm/@kesha-antonov/react-native-background-downloader?label=%20&color=blue) |
| **[react-native-action-cable](https://github.com/kesha-antonov/react-native-action-cable)** <br/> ⭐ 67 | Rails ActionCable channels over WebSocket, in React Native | ![](https://img.shields.io/npm/dm/@kesha-antonov/react-native-action-cable?label=%20&color=blue) |
| **[react-native-chat](https://github.com/kesha-antonov/react-native-chat)** <br/> ⭐ 45 | The modern successor to Gifted Chat: streaming AI messages, reactions, replies, Web support, drop-in migration | ![](https://img.shields.io/npm/dm/@kesha-antonov/react-native-chat?label=%20&color=blue) |
| **[react-native-cloud-sync](https://github.com/kesha-antonov/react-native-cloud-sync)** | iCloud KV, CloudKit, iCloud Drive and Google Drive behind one API. iOS, Android, Web | ![](https://img.shields.io/npm/dm/react-native-cloud-sync?label=%20&color=blue) |

---

## 🔧 Why this work needs funding

Most of these libraries were abandoned before I picked them up.

**Gifted Chat went 14 months without a single release** while still being installed 150,000 times
a month. I shipped the next one, and then 25 more. Today:

- **76%** of its source code is mine, 5,437 of 7,176 lines by `git blame`
- **85%** of every commit to the repo in the last two years is mine, 401 of 471
- **154 issues and 29 pull requests** were sitting open when I arrived. The repo now has **3 open issues**
- monthly downloads went from **168,000 to 444,000** after sitting flat for 30 months

The original `react-native-background-downloader` gets ~200 downloads a week. My fork gets
**~22,000**. That gap is what maintenance actually looks like from the outside: nothing
dramatic, just the library continuing to work.

Behind it, every release cycle means:

- **Keeping up with React Native itself** - New Architecture, Fabric, TurboModules, bridgeless mode. Every RN release can break native code, and someone has to port it before your build fails
- **Chasing Reanimated, Gesture Handler and Expo SDK bumps** so gestures and animations keep running at 120fps instead of dropping to the JS thread
- **Native platform churn** - iOS background session limits, Android foreground service and notification permission rules, Gradle and AGP upgrades, Kotlin versions
- **Triaging issues from apps I will never see** - reproducing a bug on a Samsung device in a market I don't live in, from a stack trace and a hunch
- **Reviewing and shepherding community PRs**, writing docs, migration codemods and Expo Snack playgrounds so upgrading is a one-command job

None of that ships a feature for me. All of it keeps thousands of production apps building on Monday morning.

---

## 💛 What your sponsorship pays for

Sponsorship converts directly into maintenance time. Concretely:

- **Faster issue turnaround** - sponsored issues get looked at first
- **Same-week support for new RN, Expo and Reanimated releases** instead of "when I get a weekend"
- **Real documentation sites**, migration guides and runnable examples, not just a README
- **New Architecture work** across every library I maintain
- **Keeping abandoned libraries alive** rather than letting them rot into another fork graveyard

If any of these packages are in your `package.json`, the maintenance is already
paying for itself in engineering hours you didn't spend. Sponsoring makes that sustainable.

<p align="center">
  <a href="https://github.com/sponsors/kesha-antonov">
    <img src="https://img.shields.io/badge/Become_a_sponsor-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white" alt="Become a sponsor" />
  </a>
</p>

---

## 🏢 For companies

If your product ships React Native, one of these libraries is very likely in your bundle right now.
A monthly sponsorship is cheaper than a single engineering day, and it buys you:

- **Prioritized issues and PR review** for the bugs that block your release
- **A heads-up on breaking changes** before they land
- **Your logo in the READMEs** of libraries seen by hundreds of thousands of developers a month
- **A direct line** for integration questions

Need something deeper - a custom feature, a migration, or a hard native bug in your own app?
I'm available for contract work. Open an issue or reach out and we'll talk.

---

## 📊 Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=kesha-antonov&show_icons=true&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kesha-antonov&layout=compact&hide_border=true&langs_count=6" alt="Top languages" height="165" />
</p>

---

<p align="center">
  <sub>Everything above is MIT or Apache 2.0 licensed and free to use, forever.<br/>
  Sponsoring isn't a license fee, it's what keeps the next release coming.</sub>
</p>
