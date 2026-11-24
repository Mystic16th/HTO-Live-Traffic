# HTO Live Traffic

**The Greek sky comes alive in Falcon BMS.**

HTO Live Traffic builds a live-traffic Tactical Engagement (`Base_Default.tac`) for the **HTO theater v1.0.4** in **Falcon BMS 4.38**. From 07:00Z and around the clock, the skies and seas of Greece fill with traffic, just like the real thing. You then build your own flights on top of it in TE.

Created by **Mystic_J** · 393 Squadron, 16th Ark Angels

## Download

Get the latest version from the **[Releases](../../releases/latest)** page:

- `HTO_Live_Traffic_v<version>.exe`: the program
- `HTO_Live_Traffic_Overview.pdf`: a short guide (optional)

There is no installer. Download the .exe, put it in any folder and run it.

> Windows SmartScreen may warn you because the program is not signed. Click **More info → Run anyway**.

## What you get

**Up to 358 flights a day**
- Airline A320s to and from Athens, Thessaloniki, Rhodes, Heraklion, Chania, Santorini and more, with extra island flights in summer.
- Hellenic Air Force fighters (F-16, Mirage 2000-5, Rafale, F-4) in pairs and four-ships, with real loadouts and squadron skins.
- C-27J and C-130 transports, helicopters, T-6 trainers and P-3 maritime patrols.
- Real-world callsigns for every airline and squadron.

**165 to 180 ships every day**
- Ferries on their real timetables (Piraeus – Heraklion, Chania, the Cyclades, Rhodes, the Ionian).
- Cargo ships and tankers on the real shipping lanes, based on **EMSA** traffic density data (via the EU's EMODnet).
- Ships at anchor outside Piraeus, Elefsina, Agioi Theodoroi and Thessaloniki, placed from real **MarineTraffic** AIS pictures.

**A different sky and sea every day**
- A new schedule every day. Everyone who runs it on the same day gets the same traffic, which suits multiplayer.
- Seasons: summer island flights, extra summer ferries, and cruise ships from April to October.
- Weekdays and weekends: the Air Force flies less on Saturday and Sunday, just like the real one.
- Greek summer and winter time are handled automatically.

## How to use it

1. Run `HTO_Live_Traffic_v<version>.exe`. A map of the HTO opens in your web browser. Leave the black window open while you use the map.
2. **Sterile areas (optional):** draw polygons or circles on the map. No traffic will fly through them. Use them for ROZ, MOA, exercises or training ranges.
3. **Take-off time:** type the time you want to take off, in Zulu (for example `15:00`). The TE clock starts 2 hours earlier, so the traffic is already flying when you take off.
4. Click **Create the mission file**. The program writes `Base_Default.tac` and `Base_Default.l16.txtpb` next to itself.
5. Open `Base_Default.tac` in TE and build your own flights on top of the live traffic.

> **Important:** do not change the start time inside TE. BMS does not fly the hours you skip, so flights are left stuck in place. Set the time **only** in HTO Live Traffic.

## Requirements

- Windows 10 or 11 (64-bit)
- Falcon BMS 4.38 with the HTO theater v1.0.4
- A web browser for the map. No Internet connection is needed.

## Data sources

- **EMSA, via EMODnet:** long-term ship route density, used to draw the cargo and tanker lanes.
- **MarineTraffic:** a single AIS snapshot (22 November 2026) for the anchorages, so the daily numbers are approximate.

## Part of the HTO ecosystem

- **HTO Live Traffic:** live air and sea traffic
- **[HTO Live Weather](https://github.com/Mystic16th/HTO-Live-Weather):** real weather and .fmap files for the HTO
