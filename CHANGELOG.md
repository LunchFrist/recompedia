# Recompedia change log

This file tracks public content and feature updates to [recompedia.com](https://recompedia.com). Project statuses in the live index may change more frequently; see the [Recent changes feed](https://recompedia.com/changes.xml).

## 2026-10-20 — 23 games added

Added 23 games from 20 public project repositories. Entries are based on each project's README, release information and current development milestone; an in-progress build is not described as finished.

### Nintendo 64 (15 games)

- [Wayne Gretzky's 3D Hockey](https://github.com/geno55/wg3d-recomp): boot, rendering, audio, input and Controller Pak saves confirmed; correctness work continues.
- [Dark Rift](https://github.com/kilnan/DarkRiftRecomp): boots and is playable with glitches; Apple Silicon macOS.
- [Knife Edge: Nose Gunner](https://github.com/navjack/KnifeEdgeRecomp): playable through the first-stage boss; Apple Silicon macOS.
- [BattleTanx: Global Assault](https://github.com/TheGh0stShip/BattleTanx-Global-Assault-PC-Port): menus and campaign gameplay reached; multiplayer experimental.
- [Diddy Kong Racing](https://github.com/sp00nznet/diddykongracing): Adventure-mode overworld and menus reached.
- [Rampage: World Tour](https://github.com/sp00nznet/Rampage): marked playable at 60 fps.
- [Rampage 2: Universal Tour](https://github.com/sp00nznet/Rampage): render loop active, but README reports a black screen.
- [Neon Genesis Evangelion](https://github.com/evaa-01/adam): intro, menus and first mission reached at 30 fps.
- [Snowboard Kids](https://github.com/HikariLucy/SnowboardKids-Recomp): public beta; gameplay validation continues.
- [Cruis'n USA](https://github.com/navjack/cruisn-recomp): README describes the port as completable.
- [Cruis'n World](https://github.com/navjack/cruisn-recomp): boots, loads gameplay code and plays audio.
- [Cruis'n Exotica](https://github.com/navjack/cruisn-recomp): boots, loads gameplay code and plays audio.
- [Army Men: Sarge's Heroes](https://github.com/RangerXT/Army-Men-Sarges-Heroes-64-Recompiled): alpha 2 verifies the title and first mission.
- [NBA Hangtime](https://github.com/8bitninja64/HangtimeRecomp): README reports playability from title to final results.
- [Turok 2: Seeds of Evil](https://github.com/SirBraga/turok2-recomp): early public test; boots and plays, with known issues.

### Xbox 360 (3 games)

- [Dead Rising 2: Case Zero](https://github.com/wivi514/Dead_Rising_2_Case_Zero_Xenon_Recomp): v1.1.3, reported playable start to finish, including solo and online co-op.
- [Dead Rising 2: Case West](https://github.com/wivi514/Dead_Rising_2_Case_West_Xenon_Recomp): v1.1.2 final build; single-player reported playable start to finish.
- [Rayman Origins](https://github.com/XDanfr/RaymanOriginsRecomp): graphics, audio, movies and controls documented as working; project remains in progress.

### PlayStation 2 (3 games)

- [Dynasty Warriors 2](https://github.com/vs-sr-dev/pc-dynastywarriors2): PAL SLES-50057 build boots and reaches the menu.
- [Metropolismania](https://github.com/koaque/Metropolismania-PC): boots into a city; not yet ready for a full playthrough. Synced metadata identifies USA SLUS-20377.
- [WWE Crush Hour](https://github.com/KaikoClanworth1/wwe-crush-hour-pc): v0.0.1-alpha; stable menus and matches, including split-screen verification.

### GameCube (2 games)

- [Chibi-Robo!](https://github.com/Armandpro12/chibi-robo-pc): v0.1.0 reaches title, new game and the first module load; US and PAL versions validated.
- [Mega Man X: Command Mission](https://github.com/vs-sr-dev/pc-megamanxcm): boot, opening movie, menu, new game and opening scenes with sound confirmed.

The index now covers **71 games and 83 project entries**. Game-specific target versions and requirements are shown on the corresponding pages. Recompedia distributes no game files.

## 2026-10-22 — Daily data refresh

The public index was refreshed from project repositories and GameDB. Items below reflect data that the source repositories returned on this run; when a repository request failed, the existing entry was retained rather than guessed.

- [ICO](https://github.com/nathanialf/ico-pc) advanced to **v0.8.1**. Its README lists the European disc (SCES-50760), Japanese disc (SCPS-11003), and Korean disc (SCPS-56001) as supported; the American release is not supported. The page also lists Windows, Linux, Steam Deck, ARM Linux, Android, iOS via LiveContainer, and Apple-silicon macOS, with platform-specific testing caveats.
- [Gran Turismo 4 decompilation](https://github.com/gustavocanepa/gt4-decomp) is reported at **83.6% matched code** in its objdiff report. This is a matching-decompilation measure, not a claim that the PC/browser port is complete.
- Repository activity dates were refreshed where available, including [Super Mario Sunshine](https://github.com/doldecomp/sms), [Ratchet & Clank](https://github.com/OpenRAC/rac1-decomp), [Digital Devil Saga 1 and 2](https://github.com/Megami-Decomps/dds-decomp), and [Star Ocean: Till the End of Time](https://github.com/celophi/so3-decomp).
- Some upstream requests failed during this run, so those project values were kept unchanged until their sources can be reached.

The site also published [“ICO PC Port v0.8.1: Disc Versions & Devices”](https://recompedia.com/blog/ico-pc-port-versions-v0-8-1), covering the confirmed disc releases and platform-specific installation notes.
