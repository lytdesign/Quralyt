<div align="center">

<img src="assets/banner.svg" alt="QuraLYT. Read with clarity. Reflect with ease. A privacy first Qur'an app with a free core experience for every Muslim." width="100%" />

<br />

![Status](https://img.shields.io/badge/Status-Prelaunch%20Development-E8B84B?style=for-the-badge&labelColor=26114D)
![Price](https://img.shields.io/badge/Core-Free%20Forever-26114D?style=for-the-badge&labelColor=191850)
![Android](https://img.shields.io/badge/Android-In%20Testing-26114D?style=for-the-badge&logo=android&logoColor=white&labelColor=191850)
![iOS](https://img.shields.io/badge/iOS-Planned-26114D?style=for-the-badge&logo=apple&logoColor=white&labelColor=191850)
![Built with FlutterFlow](https://img.shields.io/badge/Built%20with-Flutter%20%2B%20FlutterFlow-26114D?style=for-the-badge&labelColor=191850)
![Mission](https://img.shields.io/badge/Mission-Sadaqah%20Jariyah-E8B84B?style=for-the-badge&labelColor=26114D)

[**About**](#about) &nbsp;·&nbsp; [**Design**](#design-system) &nbsp;·&nbsp; [**Features**](#reading-experience) &nbsp;·&nbsp; [**Roadmap**](#roadmap) &nbsp;·&nbsp; [**Screenshots**](#screenshots) &nbsp;·&nbsp; [**Support**](#support-quralyt) &nbsp;·&nbsp; [**Credits**](#credits)

</div>

<br />

**QuraLYT** is an ad free, privacy first Qur'an app. Its core reading and listening experience is free for every Muslim, forever. Optional Pro and Elite experiences are planned for the future.

*This public repository documents QuraLYT, its design, accessibility principles, features, and roadmap. It is not a public release of the proprietary application source code.*

> [!NOTE]
> **Current status.** QuraLYT is an independently developed Android app in prelaunch testing. Its core reader, translations, Tafsir, LYTSnap sharing, bookmarks, and audio playback have been implemented. Current work includes final fixes, device testing, accessibility improvements, content verification, and optional TTS voice delivery. Not every feature is release ready yet.
>
> QuraLYT is not yet available on Google Play or the App Store. Android comes first; iOS is planned for later. In sha Allah.

<br />

## About

QuraLYT is a Qur'an platform created to help Muslims build a deeper connection with the words of Allah through a calm, respectful, distraction free experience. Every screen, interaction, and feature is designed to reduce digital noise and make reading, listening, learning, and reflecting feel natural and peaceful.

QuraLYT was never created to compete. It was created to serve.

> *To create a calm, respectful, and accessible Qur'an platform that helps people read, learn, and reflect with clarity.*

### Why QuraLYT exists

Many Qur'an apps are cluttered with ads, subscriptions, and data collection. I asked a different question: instead of what feature should be built next, how can reading the Noble Qur'an become calmer, clearer, more accessible, and more dignified for every Muslim.

| Every decision begins with that question | |
| :--- | :--- |
| Accessibility at the core, not added afterward | No advertising, ever |
| Privacy by design, before profiling | No tracking, ever |
| Clarity before complexity | Built for everyone, not just the technically confident |
| Community focused development, shaped by feedback rather than analytics | |

### Who QuraLYT is for

QuraLYT is designed to be welcoming to the entire Ummah, across different ages, abilities, levels of experience, and backgrounds.

| | |
| :--- | :--- |
| **Lifelong Muslims**<br />Whether reading for the first time or the thousandth. | **New Muslims and those returning to Islam**<br />No assumptions, no confusion, and clear guidance from the very first screen. |
| **Children learning with family**<br />In homes, mosques, and schools. | **Anyone overwhelmed by existing Qur'an apps**<br />Cluttered menus, ads, and unclear navigation were never meant to stand between a reader and the Qur'an. |

<br />

## A Personal Note

> QuraLYT has been crafted by one person, one step at a time, over many years. Every screen, every feature, every decision, and every challenge has been part of a journey driven by a simple intention: to create a Qur'an platform that serves the Ummah with sincerity, respect, and excellence.
>
> It has not always been easy. Like many long term projects built independently, there have been setbacks, difficult choices, and moments where progress felt almost impossible. Yet, by the mercy of Allah, QuraLYT continued to grow.
>
> Today, the foundation is in place.
>
> The work has continued through independent development, careful testing, and access to valuable Qur'an resources provided by others. I am sincerely grateful to the people and organisations who have helped make this possible. Their contributions are recognised in the Credits section.
>
> I pray that this project becomes a lasting source of benefit, a means of bringing people closer to the Qur'an, and a form of sadaqah jariyah for everyone who helps it grow.
>
> QuraLYT is a project of LYTDesign™ in Norway, independently built and maintained by one person.

<br />

## Design System

QuraLYT's interface is built on a **box based cognitive UI system**, the same underlying design language LYTDesign applies across its ecosystem. Within QuraLYT specifically, this system is branded **LYTGrid™**.

Many apps bury features behind menus and nested navigation, forcing readers to remember where each action lives. LYTGrid takes a different approach: important features have clear, predictable spaces on screen, with navigation kept as straightforward as possible so readers can focus on the Qur'an.

| Reduced cognitive load | Consistency for elderly and neurodivergent readers | Clarity over depth |
| :--- | :--- | :--- |
| Predictable, single-purpose boxes mean less mental effort spent figuring out the interface itself. | The same interaction pattern repeats everywhere, so once it is learned once, it is learned everywhere. | Where possible, important actions remain visible rather than being buried in deep navigation. |

LYTGrid began as QuraLYT's interface system. The long term intent is for it to grow into a reusable design system across LYTDesign's wider product line, not remain specific to one app.

Within that system, QuraLYT's visual language is built to feel close to the traditional **Mushaf** while remaining fully modern in interaction and structure:

- **Mushaf inspired reading experience:** ribbon style bookmarks, respectful page rhythm, and typography chosen to feel familiar and dignified, not like a generic app rebuilt around the Qur'an
- **Calm reading:** nothing on screen fights for attention that shouldn't
- **Respectful motion:** transitions and interactions are quiet and purposeful, never playful or attention seeking
- **Typography:** Arabic script with full diacritics, sized and spaced for genuinely long reading sessions
- **Surah artwork:** every Surah is paired with original illustration, created to encourage reflection while remaining respectful of the Qur'an, modern in style without ever distracting from the text itself

<br />

## Reading Experience

*What QuraLYT is built to offer:*

<img src="assets/features.svg" alt="What QuraLYT is built to offer: the complete Qur'an with no account required, immersive audio, LYTFocus full screen mode, LYTSnap sharing, ribbon bookmarks, and calm themes." width="100%" />

<br />

- Complete Qur'an, all 114 Surahs, every Ayah
- **LYTFocus™:** Full Screen Mode, one tap to remove every distraction
- Ribbon style bookmarks, inspired by the traditional Mushaf, with reading progress saved
- 114 Surah artworks throughout the app
- Immersive Classic Audio Player, paired with Surah artwork, reciter selection, and playback controls
- Streaming recitation, with optional downloads for offline listening
- Continue Reading, with saved Surah, ayah, and reading progress
- Multiple translation resources and Tafsir displayed with their source information
- No account required to read the Qur'an

### Learning & Reflection

- **LYTTouch™:** touch and hold contextual help, right on screen, so features are discovered naturally instead of through manuals or help pages
- **LYTSnap™:** select and share Qur'an ayahs as formatted image cards or text
- **Share Audio:** share Surah artwork and listening information through supported phone sharing options
- **Tafsir:** read Ibn Kathir explanations alongside the relevant ayah or passage, with the applicable verse range shown
- **Planned:** expanded visual and AI assisted reflection tools, described separately under QuraVision

<br />

## Accessibility

Accessibility has guided QuraLYT from the beginning, not as a feature added later. Every screen is designed to be clear, calm, readable, and easy to navigate for as many people as possible. I continue to improve accessibility throughout development, with the goal of aligning with **WCAG 2.2 AA**.

This is also part of why the interface is built on LYTGrid: predictable, single-purpose boxes reduce the mental effort needed just to operate the app, which matters as much for accessibility as it does for calm reading.

Optional offline text to speech for translations is being developed as an accessibility aid. Its voice download system is still under testing and is not yet a released feature. For Qur'an recitation, the dedicated audio player remains the appropriate choice.

*Formal compliance badges will only be published once independently audited. I do not want to overclaim accessibility before it is verified.*

<br />

## Platform Vision

QuraLYT is designed to work offline wherever possible. This is a **local first** philosophy: your reading activity doesn't need to touch a server to happen, the Qur'an should be readable without depending on an internet connection, and not every reader has consistent connectivity.

Beyond phone support today, the platform vision includes:

| | |
| :--- | :--- |
| **Tablet support**<br />A true tablet layout built for larger screens. | **Android TV support**<br />Bringing the Qur'an to a shared screen for families and gatherings. |
| **Car support, through LYTDash™ Mode**<br />A landscape, glance friendly dashboard designed for car displays and hands free listening. | **Multi user profiles**<br />One Elite subscription for the whole family, with separate bookmarks, progress, and preferences. |
| **Cloud backup**<br />Securely syncing bookmarks, notes, and reading progress across personal devices. | |

<br />

## Future Ecosystem

**QuraVision™** is QuraLYT's long term vision beyond reading and listening: a guided understanding ecosystem meant to help readers go deeper with the Qur'an through reflection, learning, and intelligent guidance, without ever replacing the text itself or a qualified scholar. It is not built yet. These are long term commitments guiding where QuraLYT is heading, shared openly so nothing here is mistaken for something available today:

- **QLES™** (reflective AI support): intended to help a reader sit with a verse a little longer, offering gentle, context aware prompts for reflection rather than answers or interpretation
- **QLIS™** (Islamic guidance AI): intended to help a reader find relevant Islamic learning material, such as related guides or topics, without replacing scholarly advice
- Illustrated Hadith collection, with clear explanations and optional audio
- Illustrated Islamic guides covering prayer, Hajj, Umrah, Ramadan, and everyday learning
- Prayer times by LYTDesign

<br />

## Trust & Authenticity

Qur'an text, translations, audio recitations, and Tafsir are selected with authenticity, licensing, and attribution in mind. Translations displayed in QuraLYT are translations of the meaning, not the divine word itself. Rowwad translations made available through QuranEnc are used under the conditions confirmed for QuraLYT. Tafsir is presented by the passage to which an explanation applies, rather than misleadingly treating every explanation as a separate commentary on a single ayah. The Arabic Qur'an remains the primary source at all times.

Resource credits and permissions apply to specific works; they do not imply that any provider has endorsed QuraLYT.

<br />

## Free, Pro & Elite

QuraLYT is built on a simple promise: the core Qur'an experience will always remain free. Every Muslim should be able to read, listen to, and reflect on the Qur'an without advertising, mandatory subscriptions, or locked essential features.

For readers who want to go beyond a conventional Qur'an app, QuraLYT plans optional Pro and Elite experiences. These are not about restricting access to the Qur'an. They are about expanding how people can engage with it, through additional personalization, enhanced reading environments, cross device experiences, and future features that help different readers connect with the Qur'an in ways that suit them.

Elite is planned as QuraLYT's long term premium experience: the full set of premium themes, cloud backup across devices, multi user family profiles, and the platform capabilities planned for tablet, TV, and car use. It is intended for readers and families who want the most complete version of QuraLYT, while the core reading experience remains exactly as free as it is for everyone else.

When available, optional Pro and Elite purchases are intended to help support continued development of the free core experience, accessibility improvements, and long term maintenance for the benefit of the Ummah.

<br />

## Themes

QuraLYT's themes were never created to show off colours or make the app look modern. They were designed as part of the reading experience itself.

The environment around us influences how comfortable it feels to spend time reading. A quiet evening, an early morning, or a bright afternoon each create a different atmosphere. QuraLYT's themes are carefully crafted to complement those moments, helping create a calm and comfortable space for reading, reflection, and listening.

*Modern design should never compete with the Qur'an. It should quietly support it.*

| Tier | Themes |
| :--- | :--- |
| **Core (Free)** | Purple Bloom (default), Blue Dusk, Teal Garden |
| **Elite** | Verdant Serenity, Velvet Night, Crimson Tide, Amber Night, Obsidian Flame, Royal Veil |

Special reading modes include Full Screen Mode, Quiet Mode, Child Mode, Elderly Mode, and Dash Mode, each designed for a different reading situation.

<br />

## Languages

**V1 interface languages:** English, Norwegian, Japanese, Bengali, Turkish, Indonesian, and Traditional Chinese.

The Qur'an is read in Arabic. Translation availability is separate from interface language availability and depends on the source and language; not every translation is available in every language.

**Long term vision, underserved languages, future phases:** Fulfulde, Bambara, Wolof, Mooré, Igbo, Mandinka, Lingala, Dinka, Tigrinya, and more planned.

Many of these languages have little or no Qur'an resources available today. This is a long term project depending on scholars, translators, voice artists, and the support of the Ummah, and it will take years to unfold gradually, language by language. Every translation is labeled as a translation of the meaning, with the translator credited.

<br />

## Roadmap

| Stage | Status |
| :--- | :--- |
| Core UI design system | ✅ Done |
| Android phone interface and core reading experience | ✅ Implemented |
| Translation, Tafsir, LYTSnap, and audio features | ✅ Implemented; final verification ongoing |
| Recitation downloads, scheduling, and media controls | 🔄 Device testing |
| Optional offline TTS and voice downloads | 🔄 Under testing |
| Content, licensing, accessibility, and release checks | 🔄 In progress |
| Public Android beta | ⏳ Planned |
| Android V1 release | ⏳ Planned |
| iOS, tablet, TV, car, and expanded learning features | ⏳ Future phases |

*Further public documentation may include release notes, accessibility findings, and source acknowledgements. This documentation repository is not an invitation to modify QuraLYT's proprietary app code.*

<br />

## Screenshots

<table>
<tr>
<td width="25%" align="center"><img src="assets/screenshots/home.svg" alt="QuraLYT home screen" width="100%" /></td>
<td width="25%" align="center"><img src="assets/screenshots/reading.png" alt="QuraLYT reading view" width="100%" /></td>
<td width="25%" align="center"><img src="assets/screenshots/themes.png" alt="QuraLYT themes" width="100%" /></td>
<td width="25%" align="center"><img src="assets/screenshots/media player.png" alt="QuraLYT Media Player" width="100%" /></td>
</tr>
<tr>
<td align="center"><sub><b>Home</b><br />The entry point into QuraLYT</sub></td>
<td align="center"><sub><b>Reading</b><br />Calm, distraction free reading</sub></td>
<td align="center"><sub><b>Themes</b><br />Calm palettes</sub></td>
<td align="center"><sub><b>Media Player</b><br />Peaceful listening to the Qur'an</sub></td>
</tr>
</table>

<div align="center">

*For official QuraLYT information and updates, visit [quralyt.com](https://quralyt.com).*

</div>

<br />

## My Promise

| | |
| :--- | :--- |
| Free core Qur'an reading, forever. | No advertising. |
| No tracking. | Respect for the Noble Qur'an. |
| Accessibility from the beginning, not as an afterthought. | Authentic resources with proper licensing and attribution. |

<br />

## Support QuraLYT

QuraLYT is built as a long term project to serve the Muslim Ummah through a free, ad free, and privacy first Qur'an experience.

There are no investors, no advertising, and no user profiling. If you would like to help support continued development, accessibility improvements, translations, and maintenance, your support is greatly appreciated and always voluntary. The core Qur'an reading experience will remain free for everyone, In sha Allah.

<div align="center">

[**Support →**](https://quralyt.com/support.html) &nbsp;·&nbsp; [**Ko-fi →**](https://ko-fi.com/quralyt) &nbsp;·&nbsp; [**Instagram →**](https://www.instagram.com/quralyt/) &nbsp;·&nbsp; [**quralyt.com →**](https://quralyt.com)

</div>

<br />

## License

QuraLYT™ — Proprietary Software

© 2026 LYTDesign™. All rights reserved.

QuraLYT is proprietary, closed-source software developed by LYTDesign™.

This public repository is provided for project information and documentation. No permission is granted to copy, modify, distribute or commercially exploit QuraLYT's proprietary application code or original designs without written authorization.

Qur'an text, translations, audio recordings, fonts, software libraries and other third-party resources remain subject to their respective licences and attribution requirements.

## Credits

Built with the intention of sadaqah jariyah, for the Ummah, In sha Allah.

**With sincere gratitude to:**

- **Rowwad Translation Center:** for the translations of Qur'anic meaning used in QuraLYT.
- **QuranEnc:** for making Rowwad translations available and confirming permission to republish them in QuraLYT under the stated conditions.
- **MP3Quran:** for granting permission to use the recitations of Sheikh Abdulrasheed Ali Sufi in QuraLYT. This acknowledgement concerns those recordings, not the entire MP3Quran catalogue.

May Allah reward everyone who has helped make these resources available and accept their efforts. Ameen.

*These are acknowledgements of specific resources and permissions, not claims of partnership or endorsement. Other third party resources remain credited under their applicable licences inside the app.*

<br />

<div align="center">

**QuraLYT™** · Read with Clarity. Reflect with Ease.<br />
<sub>A project of <a href="https://www.lytdesign.com">LYTDesign™</a>, Norway. Built with sincerity for the Ummah, In sha Allah.</sub>

</div>
