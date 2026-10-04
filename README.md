# Magical Athlete Companion

An unofficial companion for playing **Magical Athlete** and **Second Wind** at the table. Record races and points, manage decks and drafts, organise leagues and tournaments, and browse cards and statistics.

**[Open the app](https://malbonius.github.io/magical-athlete-companion/)** · Current build: **v0.54.0**

The app supports physical play: you resolve movement and powers at the table, then record what happened. It works on desktop and mobile, supports light and dark themes, and can be installed for offline use.

## Latest update — v0.54.0 · Flexible Race Endings

- Award-point fields can be cleared while typing in games, leagues and tournaments.
- Choose **Unusual ending** for custom race finishes: ties, unknown positions and end statuses can follow your rules, with no first- or second-place finisher required. Review the finishing awards and save the leg; this ending allows the game to be completed.

- Set details include collapsible **Racers** and **Tracks** lists. Tap a name to open full details, then use **Back to set** to return. Associated custom and hidden entries are included and labelled.

- Set details show an automatic racer count, including a note for hidden racers. Counts update when custom racers or set memberships change.
- Collection action buttons have equal spacing above and below.

- Custom racers have an optional **Power / flavour name** field, shown as a red heading above the power text. Official and custom power text appears directly on the details panel without an inset box.

- Editing a custom racer, track or set closes its card details and opens the editor immediately on mobile. Saving returns to the updated entry.

- **Import backup** uses the same button styling as Download backup and Request persistent storage.

- Version details are shown in the top-right button; the old gold banner has been removed.
- **Include custom content** starts off in Racers, Tracks, Sets and Twists. Turn it on to browse custom entries; this does not mark them as hidden.
- **Leaf's Fan Expansion** includes 18 editable custom racers with original card artwork, power text and additional rulebook notes.
- Custom racers, tracks, sets and twists support optional images and can be edited or deleted when unused.
- Racer statistics include recorded copied/selected powers, replacements and deliberate game-draft pick positions.

## Features

### Games

- Create games with saved or anonymous players, configurable legs, tracks and finishing awards.
- Assign teams manually, fill remaining spaces randomly, or use a snake draft.
- Follow a clear **Line-up → Race in progress → Finish & save** flow. Powers and collapsible team rosters remain available during play.
- Record extra points, transfers, control changes, replacements, eliminations and Twist reveals as they happen. Live team totals update without provisional finishing awards; changes cannot leave a team below zero.
- Save an unfinished race, resume it later, or correct a recorded result. Completed games show overall and leg-by-leg results.

Official points belong to the player/team that gained them. Changing control of a racer does not transfer earlier points. After a leg, the last-place finisher’s current team starts next, followed by clockwise player order.

### Leagues and seasons

- Choose **player redraft**, **fixed-team**, or **racer-only** leagues.
- Organise racer leagues as one table, divisions, or conferences containing divisions. Fixtures can stay within divisions, span a conference, or cover the league.
- Allocate racers manually, randomly, or through an allocation draw, with exchanges and reserved places. Compact table selectors let you view the standings you need.
- Rank by the configured score, first places, second places and fewer eliminations, with manual tie-breaking for unresolved ties. Optional league points support alternative scoring.
- Link racer leagues as upper/lower tiers or peers. Configure movement from overall or division tables, check shared-racer conflicts, and review planned allocations before creating successor seasons.
- Add championship, promotion or relegation playoffs. Championship winners are highlighted while regular-season standings remain fixed.
- Reorganise racer league structures before fixtures start. Add racers before play or during successor setup; withdraw racers while preserving recorded history and rebuilding untouched fixtures.

### Tournaments

- Create racer knockouts from a filtered pool or seed them from a completed racer league.
- Choose the number of seeds; empty seed slots must be filled before creation. Keep other entrants together in a compact unseeded list.
- Draw racers individually, fill a heat or round, or place them manually. Selecting an already placed racer exchanges the two slots.
- Use single-leg, complete-game or custom multi-leg heats, with configurable tracks and chip awards.
- View the bracket from the start, jump to the next unplayed heat, and revisit completed rounds. Corrections check their effect on later heats and require confirmation before affected results are cleared.

### Deck builder and draft tool

- Save named racer decks using search, set filters, selection tools and collapsible power text.
- Combine official sets, custom sources and multiple saved decks in event pools. Overlapping racers appear once. **Custom sources start unticked**; saved selections are preserved.
- Configure **Include custom twists** once inside racer deck/pool setup. Hidden twists are excluded.
- Run a standalone draft without adding results to statistics. Player slots start as **Anonymous 1–4**, with saved-player dropdowns and an option to enter a name.
- Draw offers and power cards through the app or record physical-deck choices. Track cards returned to the top, bottom or shuffled deck, discarded, or kept held.

### Collections and statistics

Browse **Racers, Tracks, Sets and Twists** using searchable lists and full-card details. **Include custom content** starts off in each collection view; turn it on to see your custom entries, including Leaf's Fan Expansion. This filter is separate from hiding or restoring entries. Official artwork and power/rules text are bundled for offline use. Create custom entries with an optional image, hide or restore cards, and filter for hidden entries. Unused custom entries can be deleted; referenced entries explain where they are used so saved history is protected.

Statistics use saved results. Filter by date, set, track, leg, player and event type.

- **Results and points:** finishes, finishing awards, non-finish points, eliminations and recorded events. Non-finish points are gains minus losses outside finishing awards. Racer totals include points unambiguously linked to that racer, excluding transfers and unlinked team points.
- **Track performance:** average track points gained per saved leg, plus gains, losses and net points from entries marked Track. Unlinked team points stay in the whole-leg track total. Racer statistics include track points gained per involvement and per-track performance.
- **Player scores:** total points, average score normalised to four legs (each completed game has equal weight), and average score per saved leg on each track. Racer track tables show average finishing awards plus attributable non-finish points per involvement. Zero-point results count in these averages.
- **Recorded powers and events:** counts and history for hog holdings, Twist triggers and other attributed events. Power details show which cards supplied copied or selected powers, how often they were recorded, and which cards replaced a racer. Event entries and chosen deck draws are shown separately to avoid counting an action twice. Unattributed records are excluded.
- **Draft order:** average overall and within-batch pick positions, a position breakdown and history for deliberate game-draft picks recorded from v0.49.0 onwards. Earlier picks and random team assignments are excluded. Standalone drafts do not affect game results or statistics.

## Install and use offline

Open the app online in your preferred browser. Use its **Install app** or **Add to home screen** option where available. Let the initial load finish before testing offline, then reopen from the installed shortcut.

An app update uses the same address and does not require reinstalling. After an update is published, open online, close and reopen, and check the version in the top-right button.

## Leaf's Fan Expansion

The app adds **Leaf's Fan Expansion** once to your custom collection: 18 racers with card artwork, power text and the supplied rulebook's additional notes. It has no set image. Existing records are kept. Enable **Include custom content** in a collection view to browse it. Select the expansion's checkbox when preparing a racer pool; custom sets remain unticked by default.

The set and racers are ordinary custom entries: edit their names, text, images and set membership, or delete unused entries. Edits and deletions are retained across reloads and backups. Deleting a custom set keeps its cards and removes their membership in that set. Entries referenced by saved games, competitions, decks or drafts cannot be deleted until those references are removed; hiding them preserves the history.

## Custom images

When adding or editing a custom racer, track, set or twist, use **Add image** or **Replace image** to choose a PNG, JPEG or WebP file, then save the entry. A preview appears before saving. **Remove image** clears the artwork when you save; Cancel keeps the previous entry.

Files may be up to 20 MB. The app resizes the whole image without cropping, preserves transparency, and keeps a compact copy for offline use. Custom racer and track images also appear in game and draft card views; custom Twist images appear with recorded reveals.

## Your data and backups

Data is stored locally in each browser/device. There is **no account, cloud synchronisation or automatic transfer between devices**.

Use **Data → Download backup** regularly and confirm that the JSON file was downloaded. Backups include custom entries, saved players, games, leagues, tournaments, drafts, decks and hidden-card choices. Uploaded custom images are included in backups. Official artwork is bundled with the app rather than copied into backups.

**Import replaces local data; it does not merge it.** Export any changes you want to keep before importing another device’s backup.

Storage retention depends on the browser. Refusal of persistent storage does not necessarily prevent normal saving, but browser cleanup, private browsing or cleared site data can remove records. Keep backups outside the browser.
