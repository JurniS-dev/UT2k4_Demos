# UT2k4_Demos

Server-recorded match demos from the **JurniS** UT2004 duel/TDM servers (Chicago, Los Angeles, Miami, New York). Updated automatically, every hour.

## Where to find demos

- **[Recent Demos](../../releases/tag/recent-demos)** — every match from the last 7 days. Files move out of this release after one week, so grab them while they're fresh — links into Recent expire when the demo is archived.
- **Demo Archive 001, 002, …** — the permanent archive. Every demo eventually lands here and stays forever. Cite these links if you want something permanent.

You can browse all releases [here](../../releases).

## Filenames

Duel demos:

```
Player1-vs-Player2-Map-M-D-YYYY-(HH-MM).demo4
```

Example: `Abnormal-vs-sL-vEr-DM-Rankin-DML-11-5-2026-(22-45).demo4` — a duel between Abnormal and sL-vEr on DM-Rankin-DML, Nov 5 2026, 22:45.

Team demos (TDM) list every player, with `-vs-` separating the two teams.

## How to play a demo

1. Download the `.demo4` file.
2. Put it in your Unreal Tournament 2004 `Demos` folder.
3. Open the console in-game and run:

   ```
   demoplay <filename-without-extension>
   ```

   Example: `demoplay Abnormal-vs-sL-vEr-DM-Rankin-DML-11-5-2026-(22-45)`

## Playback requirements — read this first

These are **server-side demos**: your client must have the exact map and the server's mutator packages (UTComp v20) installed, or playback will fail with missing-file errors. Non-stock maps must be installed before playing their demos.

Demos are only recorded when two players are in a match — warmup and empty-server sessions are not uploaded.
